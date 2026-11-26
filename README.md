# 全景视界 360° / Panorama 360°

A zero-dependency, 100% client-side **360° equirectangular panorama viewer** and **multi-scene single-file HTML packager**, built with a custom tiled WebGL shader engine.

纯静态零依赖的 **360° 全景查看与多场景单文件打包工具**，内置多瓦片 WebGL 渲染引擎，所有图像处理与打包均在本地浏览器完成，无需后端服务器。

🔗 **Live Demo / 在线体验**: `[https://your-username.github.io/pano360/](https://cgpiece.github.io/pano360/)`

---

## ✨ Features / 核心特性

- **Ultra-HD Tiled WebGL Engine / 超清多瓦片渲染**
  - Automatically slices high-resolution panoramas (7560×3780, 8K, 12K+) into GPU-safe `≤2048px` texture tiles (up to `4×2`), preventing WebGL black screens on any device.
  - 自动将高分辨率全景图切分为不超过显卡纹理上限的瓦片网格无缝渲染，彻底告别大图黑屏。
- **Multi-Scene Management / 多场景管理**
  - Batch drag-and-drop import (JPG / PNG / WebP), drag cards to reorder, customize scene titles, set default camera views, and calibrate True North (`0°`).
  - 支持批量拖拽导入、卡片拖拽排序、编辑标题/备注、设定场景默认视角及正北方向矫正。
- **VR Split-Screen & 3DOF Gyro / VR 分屏与体感**
  - One-click side-by-side stereo view (`V`) with automatic 3DOF gyroscope head tracking (works in both portrait and landscape VR headsets over HTTPS).
  - 一键开启左右双目分屏并自动启用 3DOF 空间姿态陀螺仪，支持手机横屏放入 VR 眼镜浏览。
- **Single-File HTML Export / 多场景单文件导出**
  - Package all scenes into one standalone offline `.html` file with resolution presets, custom **Logo Watermark** (image or text, opacity & scale), custom theme, and optional compass/language toggles.
  - 一键将多个场景打包为独立离线 `.html` 文件，支持画质预设、自定义图片/文字水印、主题同步及视角信息开关。
- **Theme & Bilingual UI / 主题与双语支持**
  - Customizable accent color, panel color, opacity, and backdrop blur; auto-detects browser language (`简体中文` / `English`) with one-click switching.
  - 支持自定义主题配色、透明度与毛玻璃模糊度，默认自适应浏览器语言并支持一键切换中英文。
- **Immersive Experience / 沉浸式浏览**
  - Auto-hiding scene dock (`1.5s`), global idle UI auto-hide (`3s`), manual Pure Mode (`H`), and translucent zoom feedback bar.
  - 托盘 1.5 秒自动收起、3 秒无操作自动隐藏所有悬浮控件，支持纯净模式与缩放视觉反馈条。

---

## ⌨️ Keyboard Shortcuts / 快捷键

| Key / 按键 | Action / 功能 |
| :--- | :--- |
| `W` `A` `S` `D` | Look around / 上下左右旋转视口 |
| `↑` / `↓` | Zoom in / out (FOV) / 放大与缩小视角 |
| `←` `→` or `PgUp` `PgDn` | Switch scene / 切换上/下一场景 |
| `V` | Toggle VR split-screen + gyro / 开启或退出 VR 分屏 |
| `Space` | Pause / resume auto-rotation / 暂停或开启自动旋转 |
| `R` | Reset to scene default view / 重置为默认视角 |
| `F` or Double-Click | Toggle fullscreen / 全屏切换 |
| `H` | Toggle immersive pure mode / 沉浸纯净模式 |
| `K` or `?` | Toggle shortcuts panel / 打开快捷键面板 |
| `Esc` | Exit modal, VR mode, or pure mode / 退出弹窗、VR 或沉浸模式 |

---

## 🚀 Usage / 使用方式

1. **Online**: Open the GitHub Pages link directly in your desktop or mobile browser.
2. **Offline**: Download `index.html` and double-click it to open locally (note: mobile gyroscope requires HTTPS hosting such as GitHub Pages).
3. Drag & drop your 360° equirectangular images onto the page, arrange them, and click **Export HTML** to share.

---

## 🔒 Privacy / 隐私说明

All images are processed **100% locally in your browser**. Nothing is uploaded to any server.

所有全景图片与导出文件均在你的**本地浏览器内存中完成处理**，不会上传至任何服务器。

---

## ☕ Support / 请我喝杯咖啡

If you find this tool helpful, feel free to support the development!  
如果这个工具对你有帮助，欢迎请我喝杯咖啡支持后续更新：

- **PayPal**: [paypal.me/cgpiece](https://paypal.me/cgpiece)
- **Ko-fi**: [ko-fi.com/cgpiece](https://ko-fi.com/cgpiece)
<!-- - **Buy Me a Coffee**: [buymeacoffee.com/cgpiece](https://www.buymeacoffee.com/cgpiece) -->
<!-- - **Gumroad**: [cgpiece.gumroad.com](https://cgpiece.gumroad.com) -->

| 微信赞赏 / WeChat Pay | 支付宝 / Alipay |
| :---: | :---: |
| <img src="assets/wechat-pay.svg" width="160" alt="WeChat Pay" /> | <img src="assets/alipay.svg" width="160" alt="Alipay" /> |

---

## 👤 Author / 作者

- **Author**: cgpiece
- **Version**: 1.0
