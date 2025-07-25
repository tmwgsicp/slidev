---
title: Cursor × 开源项目实践
info: |
  使用 Cursor 进行开源项目实践的经验分享
class: bg-gradient-to-br from-gray-900 via-black to-gray-900 text-white text-center
mdc: true
theme: default
layout: cover
---

# `Cursor × 开源项目`

<div class="text-center">
  <h2 class="text-2xl font-mono font-bold mb-4 text-cyan-400">从零到一的开源实践之路</h2>
  <div class="mt-6 space-y-2">
    <p class="text-2xl font-mono text-gray-300">分享人：石子健</p>
    <p class="text-sm font-mono text-blue-400">Powered by Cursor</p>
  </div>
</div>

---

# `👋 关于我`

<div class="flex items-center gap-6">
  <div class="flex-1">
    <div class="bg-slate-800/50 p-4 rounded-lg border border-cyan-500/30 font-mono text-sm">
      <div class="space-y-2">
        <div class="text-gray-300"><span class="text-blue-400">主业：</span> 财务</div>
        <div class="text-gray-300"><span class="text-green-400">身份：</span> AI探索者 & 开源拥护者</div>
        <div class="text-gray-300"><span class="text-cyan-400">专长：</span> AI编程 | AI工作流 | 低代码开发</div>
        <div class="text-gray-300"><span class="text-purple-400">平台：</span> n8n | Dify | Coze</div>
        <div class="text-gray-300"><span class="text-yellow-400">经验：</span> AI工作流、智能体落地实战</div>
      </div>
    </div>
  </div>
  
  <div class="flex-1 text-center">
    <div class="w-40 h-40 bg-slate-800/50 rounded-xl mx-auto mb-2 flex items-center justify-center border border-cyan-500/30">
      <span class="text-5xl">👨‍💻</span>
    </div>
    <div class="font-mono text-xs text-gray-400">// 不务正业的财务</div>
  </div>
</div>

---

# `📋 分享内容`

<div class="grid grid-cols-2 gap-6 mt-6">
  <div class="bg-slate-800/30 p-5 rounded-xl border border-blue-500/30">
    <h3 class="text-xl font-mono font-bold mb-3 text-blue-400">⚡ 开源项目二次开发</h3>
    <ul class="text-base font-mono space-y-2">
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> 小白也能看懂复杂代码</li>
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> 不懂技术照样能改功能</li>
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> Cursor全自动编写代码</li>
    </ul>
  </div>
  
  <div class="bg-slate-800/30 p-5 rounded-xl border border-green-500/30">
    <h3 class="text-xl font-mono font-bold mb-3 text-green-400">🚀 落地首个开源项目</h3>
    <ul class="text-base font-mono space-y-2">
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> 从想法到实现</li>
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> 开发过程实录</li>
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> 项目成果展示</li>
    </ul>
  </div>
</div>

---

# `🎥 开源项目 StreamCap`

<div class="text-center mb-6">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <p class="text-xl font-mono font-bold text-cyan-400">开源直播监控 & 录制工具</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-6">
  <div class="space-y-4">
    <div class="bg-slate-800/30 p-4 rounded-xl border border-blue-500/30">
      <h3 class="text-lg font-mono font-bold mb-3 text-blue-400">📦 项目信息</h3>
      <div class="space-y-2 text-sm font-mono">
        <div class="text-gray-300"><span class="text-blue-400">类型：</span> 流媒体工具</div>
        <div class="text-gray-300"><span class="text-green-400">功能：</span> 监控 | 录制 | 推送</div>
        <div class="text-gray-300"><span class="text-cyan-400">平台：</span> 抖音 | YouTube | 全球平台</div>
      </div>
    </div>
  </div>

  <div class="space-y-4">
    <div class="bg-slate-800/30 p-4 rounded-xl border border-green-500/30">
      <h3 class="text-lg font-mono font-bold mb-3 text-green-400">⚡ 二开功能</h3>
      <div class="space-y-2 text-sm font-mono">
        <div class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">+</span> AI直播文案识别</div>
        <div class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">+</span> 飞书 & 企业微信推送</div>
        <div class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">+</span> UI界面重构优化</div>
      </div>
    </div>
  </div>
</div>

---

# `📊 二开成果展示`

<div class="text-center mb-6">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <p class="text-xl font-mono font-bold text-cyan-400">二开前后效果对比</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-6">
  <div class="bg-slate-800/30 p-4 rounded-xl border border-blue-500/30">
    <h3 class="text-lg font-mono font-bold mb-3 text-center text-blue-400">🔴 原版功能</h3>
    <div class="bg-black rounded-lg p-3">
      <video controls class="w-full rounded" style="max-height: 400px;">
        <source src="./assets/before-demo.mp4" type="video/mp4">
        <div class="text-gray-400 text-center py-4 text-sm font-mono">浏览器不支持视频</div>
      </video>
    </div>
  </div>
  
  <div class="bg-slate-800/30 p-4 rounded-xl border border-green-500/30">
    <h3 class="text-lg font-mono font-bold mb-3 text-center text-green-400">🟢 二开版本</h3>
    <div class="bg-black rounded-lg p-3">
      <video controls class="w-full rounded" style="max-height: 400px;">
        <source src="./assets/after-demo.mp4" type="video/mp4">
        <div class="text-gray-400 text-center py-4 text-sm font-mono">浏览器不支持视频</div>
      </video>
    </div>
  </div>
</div>

---

# `🛠️ Cursor 二开实录`

<div class="text-center mb-5">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <p class="text-xl font-mono font-bold text-cyan-400">开发过程展示</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-5">
  <div class="bg-slate-800/30 p-4 rounded-xl border border-blue-500/30">
    <h3 class="text-base font-mono font-bold mb-3 text-center text-blue-400">🔍 代码展示</h3>
    <div class="bg-black rounded-lg p-2">
      <img src="./assets/streamcap二开1.jpg" alt="streamcap二开1" class="w-full h-auto object-contain rounded" style="max-height: 300px;">
    </div>
  </div>

  <div class="bg-slate-800/30 p-4 rounded-xl border border-green-500/30">
    <h3 class="text-base font-mono font-bold mb-3 text-center text-green-400">⚡ 文件展示</h3>
    <div class="bg-black rounded-lg p-2">
      <img src="./assets/streamcap二开2.jpg" alt="streamcap二开2" class="w-full h-auto object-contain rounded" style="max-height: 300px;">
    </div>
  </div>
</div>

---

# `⚡ 开发方式对比`

<div class="text-center mb-5">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <p class="text-xl font-mono font-bold text-cyan-400">传统开发 vs Cursor驱动开发</p>
  </div>
</div>

<div class="space-y-5">
  <div class="bg-slate-800/30 p-5 rounded-xl border border-cyan-500/30">
    <h3 class="text-lg font-mono font-bold mb-3 text-center text-cyan-400">📊 方法论对比</h3>
    <div class="grid grid-cols-2 gap-5">
      <div class="bg-slate-800/50 p-3 rounded-lg border border-blue-500/30">
        <h4 class="font-mono font-bold text-blue-400 mb-2 text-sm text-center">❌ 传统方式</h4>
        <div class="space-y-1 text-xs font-mono">
          <div class="flex items-center text-gray-300"><span class="text-blue-400 mr-2">×</span> 学习框架语法</div>
          <div class="flex items-center text-gray-300"><span class="text-blue-400 mr-2">×</span> 理解整个架构</div>
          <div class="flex items-center text-gray-300"><span class="text-blue-400 mr-2">×</span> 环境配置调试</div>
          <div class="flex items-center text-gray-300"><span class="text-blue-400 mr-2">×</span> 数月学习周期</div>
        </div>
      </div>
      <div class="bg-slate-800/50 p-3 rounded-lg border border-green-500/30">
        <h4 class="font-mono font-bold text-green-400 mb-2 text-sm text-center">✅ Cursor方式</h4>
        <div class="space-y-1 text-xs font-mono">
          <div class="flex items-center text-gray-300"><span class="text-green-400 mr-2">✓</span> 直接描述需求</div>
          <div class="flex items-center text-gray-300"><span class="text-green-400 mr-2">✓</span> AI智能解释</div>
          <div class="flex items-center text-gray-300"><span class="text-green-400 mr-2">✓</span> 自动生成代码</div>
          <div class="flex items-center text-gray-300"><span class="text-green-400 mr-2">✓</span> 小时级完成</div>
        </div>
      </div>
    </div>
  </div>
  
  <div class="bg-slate-800/50 p-4 rounded-xl border border-cyan-500/30 text-center">
    <p class="text-lg font-mono font-bold text-cyan-400">🚀 人人都能成为开发者！</p>
  </div>
</div>

---

# `🚀 我的开源项目`

<div class="text-center mb-6">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <h2 class="text-2xl font-mono font-bold text-cyan-400">Dify-on-Qianniu</h2>
    <p class="text-base font-mono text-gray-300 mt-1">7x24小时 AI 客服自动化系统</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-6">
  <div class="space-y-4">
    <div class="bg-slate-800/30 p-4 rounded-xl border border-blue-500/30">
      <h3 class="text-lg font-mono font-bold mb-3 text-blue-400">🚀 核心功能</h3>
      <div class="space-y-2 text-sm font-mono">
        <div class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> 智能消息监测</div>
        <div class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> AI内容识别</div>
        <div class="flex items-center text-gray-300"><span class="text-cyan-400 mr-2">></span> 自动智能回复</div>
      </div>
    </div>
  </div>
  
  <div class="space-y-4">
    <div class="bg-slate-800/30 p-4 rounded-xl border border-green-500/30">
      <h3 class="text-lg font-mono font-bold mb-3 text-green-400">🛠️ 技术栈</h3>
      <div class="space-y-2 text-sm font-mono">
        <div class="text-gray-300"><span class="text-blue-400">语言：</span> Python</div>
        <div class="text-gray-300"><span class="text-green-400">RPA：</span> Clicknium</div>
        <div class="text-gray-300"><span class="text-cyan-400">AI：</span> Dify</div>
      </div>
    </div>   
  </div>
</div>

---

# `📈 开发历程`

<div class="text-center mb-5">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <p class="text-xl font-mono font-bold text-cyan-400">从想法到开源的完整历程</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-5">
  <div class="flex items-center gap-3">
    <div class="w-8 h-8 bg-blue-500 rounded-full flex items-center justify-center font-mono font-bold text-sm text-white border border-blue-400">1</div>
    <div class="flex-1 bg-slate-800/30 p-4 rounded-lg border border-blue-500/30">
      <h4 class="font-mono font-bold text-blue-400 text-sm">💡 需求分析</h4>
      <p class="text-gray-300 font-mono text-xs mt-1">Cursor主导需求分析与可行性评估</p>
    </div>
  </div>
  
  <div class="flex items-center gap-3">
    <div class="w-8 h-8 bg-green-500 rounded-full flex items-center justify-center font-mono font-bold text-sm text-white border border-green-400">2</div>
    <div class="flex-1 bg-slate-800/30 p-4 rounded-lg border border-green-500/30">
      <h4 class="font-mono font-bold text-green-400 text-sm">🏗️ 架构设计</h4>
      <p class="text-gray-300 font-mono text-xs mt-1">Cursor主导技术选型和架构规划</p>
    </div>
  </div>
  
  <div class="flex items-center gap-3">
    <div class="w-8 h-8 bg-cyan-500 rounded-full flex items-center justify-center font-mono font-bold text-sm text-white border border-cyan-400">3</div>
    <div class="flex-1 bg-slate-800/30 p-4 rounded-lg border border-cyan-500/30">
      <h4 class="font-mono font-bold text-cyan-400 text-sm">⚡ 快速开发</h4>
      <p class="text-gray-300 font-mono text-xs mt-1">Cursor全自动编写代码</p>
    </div>
  </div>
  
  <div class="flex items-center gap-3">
    <div class="w-8 h-8 bg-blue-500 rounded-full flex items-center justify-center font-mono font-bold text-sm text-white border border-blue-400">4</div>
    <div class="flex-1 bg-slate-800/30 p-4 rounded-lg border border-blue-500/30">
      <h4 class="font-mono font-bold text-blue-400 text-sm">🚀 发布上线</h4>
      <p class="text-gray-300 font-mono text-xs mt-1">Cursor指导GitHub开源发布</p>
    </div>
  </div>
</div>

---

# `💬 开发实录`

<div class="text-center mb-5">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <p class="text-xl font-mono font-bold text-cyan-400">Cursor驱动的对话式开发</p>
  </div>
</div>

<div class="grid grid-cols-2 gap-6">
  <div class="bg-slate-800/30 p-4 rounded-xl border border-blue-500/30">
    <h3 class="text-base font-mono font-bold mb-3 text-center text-blue-400">🎯 代码展示</h3>
    <div class="bg-black rounded-lg p-2">
      <img src="./assets/dify-on-qianniu2.jpg" alt="qianniu2" class="w-full h-auto object-contain rounded" style="max-height: 300px;">
    </div>
  </div>

  <div class="bg-slate-800/30 p-4 rounded-xl border border-green-500/30">
    <h3 class="text-base font-mono font-bold mb-3 text-center text-green-400">🔧 文件展示</h3>
    <div class="bg-black rounded-lg p-2">
      <img src="./assets/dify-on-qianniu3.jpg" alt="qianniu3" class="w-full h-auto object-contain rounded" style="max-height: 300px;">
    </div>
  </div>
</div>

---

# `🎯 项目成果展示`

<div class="grid grid-cols-2 gap-6">
  <div class="bg-slate-800/30 p-5 rounded-xl border border-blue-500/30">
    <h3 class="text-lg font-mono font-bold mb-3 text-center text-blue-400">📦 GitHub开源</h3>
    <div class="bg-black rounded-lg p-3">
      <img src="./assets/dify-on-qianniu1.jpg" alt="GitHub项目截图" class="w-full h-auto object-contain rounded">
    </div>
  </div>

  <div class="bg-slate-800/30 p-5 rounded-xl border border-green-500/30">
    <h3 class="text-lg font-mono font-bold mb-3 text-center text-green-400">📱 AI客服落地</h3>
    <div class="flex justify-center">
      <div class="bg-black rounded-xl p-3 border border-gray-600" style="width: 180px;">
        <img src="./assets/dify-on-qianniu淘宝客服效果.png" alt="AI客服效果截图" class="w-full h-auto object-contain rounded-lg">
      </div>
    </div>
  </div>
</div>

---

# `📝 总结与展望`

<div class="text-center mb-6">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <h2 class="text-xl font-mono font-bold text-cyan-400">从实践到思考的完整闭环</h2>
  </div>
</div>

<div class="grid grid-cols-2 gap-6 mb-6">
  <div class="bg-slate-800/30 p-6 rounded-xl border border-blue-500/30">
    <h3 class="text-xl font-mono font-bold mb-4 text-center text-blue-400">🎯 核心收获</h3>
    <ul class="space-y-3 text-base font-mono">
      <li class="flex items-center text-gray-300"><span class="text-blue-400 mr-3">🔓</span> <span class="text-blue-400 font-bold">破圈突破：</span> 财务人也能写代码</li>
      <li class="flex items-center text-gray-300"><span class="text-green-400 mr-3">⚡</span> <span class="text-green-400 font-bold">效率飞跃：</span> 从月级到小时级开发</li>
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-3">🌟</span> <span class="text-cyan-400 font-bold">价值创造：</span> 1个开源项目落地</li>
    </ul>
  </div>
  
  <div class="bg-slate-800/30 p-6 rounded-xl border border-green-500/30">
    <h3 class="text-xl font-mono font-bold mb-4 text-center text-green-400">🔮 未来规划</h3>
    <ul class="space-y-3 text-base font-mono">
      <li class="flex items-center text-gray-300"><span class="text-blue-400 mr-3">🤖</span> <span class="text-blue-400 font-bold">深度协同：</span> 探索与Cursor协同</li>
      <li class="flex items-center text-gray-300"><span class="text-cyan-400 mr-3">🔍</span> <span class="text-cyan-400 font-bold">开源挖掘：</span> 挖掘和参与开源项目</li>
      <li class="flex items-center text-gray-300"><span class="text-green-400 mr-3">💰</span> <span class="text-green-400 font-bold">商业探索：</span> 寻找商业化机会</li>
    </ul>
  </div>
</div>

---

# `🎬 结语`

<div class="text-center mb-6">
  <div class="bg-slate-800/50 p-3 rounded-xl border border-cyan-500/30">
    <h2 class="text-xl font-mono font-bold text-cyan-400">用Cursor重新定义开发</h2>
  </div>
</div>

<div class="text-center mb-6">
  <p class="text-lg font-mono text-gray-300 mb-2">感谢聆听，期待与你一起探索AI时代的无限可能</p>
  <p class="text-sm font-mono text-blue-400">// 让每个想法都有实现的机会</p>
</div>

<div class="bg-slate-800/30 p-6 rounded-xl border border-cyan-500/30">
  <h3 class="text-xl font-mono font-bold mb-4 text-center text-cyan-400">📱 联系方式</h3>
  <ul class="space-y-3 text-base font-mono">
    <li class="flex items-center text-gray-300"><span class="text-red-400 mr-3">📖</span> <span class="text-red-400 font-bold">小红书：</span> Excel办公不求人</li>
    <li class="flex items-center text-gray-300"><span class="text-gray-400 mr-3">🐙</span> <span class="text-gray-400 font-bold">GitHub：</span> tmwgsicp</li>
    <li class="flex items-center text-gray-300"><span class="text-blue-400 mr-3">📧</span> <span class="text-blue-400 font-bold">邮箱：</span> creator@waytomaster.com</li>
  </ul>
</div>