# 🚀 Cursor Slidev 项目部署指南

## 📦 方案一：Vercel部署（推荐）

### ✅ 优势
- 完全免费
- 自动HTTPS证书
- 全球CDN加速
- Git集成自动部署
- 零配置，开箱即用

### 📋 部署步骤

1. **推送代码到GitHub**
```bash
git add .
git commit -m "准备部署"
git push origin main
```

2. **Vercel部署**
- 访问 [vercel.com](https://vercel.com)
- GitHub账号登录
- 点击 "New Project"
- 选择 `cursor-slidev` 仓库
- 自动检测配置，点击 "Deploy"

3. **完成**
- 获得部署地址：`https://cursor-slidev.vercel.app`
- 以后推送代码自动重新部署

---

## 🖥️ 方案二：云服务器部署

### 📋 服务器要求
- Ubuntu/CentOS Linux
- Node.js 18+ 
- Nginx
- 至少1GB内存

### 🔧 部署步骤

#### 1. 服务器环境准备
```bash
# 更新系统
sudo apt update && sudo apt upgrade -y

# 安装Node.js 18+
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt-get install -y nodejs

# 安装Nginx
sudo apt install nginx -y

# 安装PM2（进程管理）
sudo npm install -g pm2
```

#### 2. 上传项目文件
```bash
# 方法一：直接上传dist目录
scp -r ./dist/* user@your-server:/var/www/cursor-slidev/

# 方法二：完整项目+服务器构建
scp -r ./ user@your-server:/var/www/cursor-slidev/
ssh user@your-server
cd /var/www/cursor-slidev
npm install
npm run build
```

#### 3. Nginx配置
```bash
# 创建配置文件
sudo nano /etc/nginx/sites-available/cursor-slidev
```

```nginx
server {
    listen 80;
    server_name your-domain.com;  # 替换为你的域名或IP
    
    root /var/www/cursor-slidev/dist;
    index index.html;
    
    # 支持SPA路由
    location / {
        try_files $uri $uri/ /index.html;
    }
    
    # 静态资源缓存
    location ~* \.(js|css|png|jpg|jpeg|gif|ico|svg|woff|woff2)$ {
        expires 1y;
        add_header Cache-Control "public, immutable";
    }
    
    # Gzip压缩
    gzip on;
    gzip_types text/plain text/css application/json application/javascript text/xml application/xml text/javascript;
}
```

```bash
# 启用配置
sudo ln -s /etc/nginx/sites-available/cursor-slidev /etc/nginx/sites-enabled/
sudo nginx -t
sudo systemctl reload nginx
```

#### 4. HTTPS配置（可选）
```bash
# 安装Certbot
sudo apt install certbot python3-certbot-nginx -y

# 申请SSL证书
sudo certbot --nginx -d your-domain.com
```

---

## 🎯 推荐选择

### 🥇 **首选：Vercel**
- 适合：快速展示、分享PPT
- 优点：零配置、自动化、免费
- 用途：技术分享、演示

### 🥈 **备选：云服务器**
- 适合：企业使用、自定义需求
- 优点：完全控制、可扩展
- 用途：商业演示、内部培训

---

## 🔍 部署验证

部署完成后访问以下URL检查：
- `/` - 首页
- `/presenter` - 演讲者模式
- `/overview` - 概览模式
- `/assets/` - 静态资源加载

---

## 🛠️ 故障排除

### Vercel常见问题
- **构建失败**：检查 `package.json` 中的Node.js版本
- **路由404**：确认 `vercel.json` 重写规则正确

### 云服务器常见问题
- **访问403**：检查文件权限 `chmod -R 755 /var/www/cursor-slidev`
- **Nginx错误**：查看日志 `sudo tail -f /var/log/nginx/error.log`
- **端口占用**：检查防火墙和安全组设置

---

## 📞 技术支持

如遇到部署问题，可以提供：
1. 错误日志截图
2. 服务器配置信息
3. 部署步骤描述

祝部署顺利！🎉 