# 别踩白块 · 钢琴挑战 🎹

一个纯 HTML5 Canvas 实现的经典节奏反应游戏，无任何外部依赖，打开即玩。

## 🎮 玩法

- 4 列钢琴键布局，黑块从上往下滚动
- **点击黑块** → 得分 + 粒子特效
- **点击白块** → 游戏结束
- **漏掉黑块** → 游戏结束

## ✨ 特性

- 🎯 **连击系统**：650ms 内连续命中触发 Combo（x3 蓝 / x6 金 / x10 红）
- ⚡ **速度递增**：每得 8 分自动加速
- 💥 **粒子特效**：命中时彩色粒子爆发
- 🔊 **音效反馈**：Web Audio API 实时音效（可静音）
- ⚠️ **危险预警**：黑块接近底部红色闪烁
- 📱 **移动端优化**：支持手指滑动横扫，响应式布局
- 🏆 **最高记录**：localStorage 持久化存储

## 🚀 快速开始

直接用浏览器打开 `index.html` 即可。

或一键部署到 GitHub Pages：

1. Fork 本仓库
2. Settings → Pages → Source 选择 `main` 分支
3. 访问 `https://你的用户名.github.io/piano-game/`

## 🛠 技术栈

- HTML5 Canvas
- 原生 JavaScript
- Web Audio API
- 零依赖，单文件

## 📄 License

MIT
