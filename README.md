# TextCard Pro v2.0

> 让长文更有力量。

**TextCard Pro** 是一款专为社交媒体（X/Twitter、小红书、Instagram 等）设计的长文转长图工具。它能够将枯燥的纯文本或 Markdown 文稿，一键转化为具有顶级杂志排版美学的高清图片，助你突破平台的字数限制，用设计感传递每一句话。

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Tech](https://img.shields.io/badge/tech-HTML5%20%2B%20Tailwind-orange.svg)

---

## ✨ 核心特性

- **🚀 极简工作流**：无需安装，双击即用。左侧编辑，中间预览，右侧导出。
- **📝 Markdown 全力驱动**：集成 `marked.js`，支持标题、列表、加粗、引用及代码块等排版语法。
- **🎨 大师级经典模板**：
  - **现代社论 (Modern Editorial)**：极致简约的黑白排版，张力十足。
  - **复古报刊 (Vintage News)**：羊皮纸质感搭配精美衬线字，叙事感拉满。
  - **瑞士平面 (Swiss Design)**：基于国际主义排版风格，几何美感的极致体现。
  - **典雅深邃 (Elegant Night)**：专为深度思考设计的深色模式，白金配色，锐利夺目。
- **📸 工业级导出标准**：
  - **3.0x 超采样**：生成的图片在 4K 屏幕或高清社交平台上依然纤毫毕现。
  - **一键复制**：支持直接生成图片流并写入剪贴板，无需保存文件即可快速发送。
- **🛠 动态排版控件**：实时调节页边距（Padding）、字号大小，并可自由开启/关闭品牌水印。

---

## 🛠 技术栈

本项目坚持 **“零编译、轻量化”** 的原则，使用以下技术构建：

- **Frontend**: HTML5, Tailwind CSS (高性能实用类优先框架)
- **Rendering**: [html-to-image](https://github.com/bubkoo/html-to-image) (将 DOM 节点转换为高清矢量位图)
- **Markdown**: [marked.js](https://github.com/markedjs/marked) (快速、轻量级的 MD 解析引擎)
- **Fonts**: Google Fonts (Noto Serif SC, Inter, JetBrains Mono)

---

## 🚀 快速开始

1. **下载项目**：
   ```bash
   git clone https://github.com/your-username/textcard-pro.git
   ```
2. **运行**：
   无需配置任何服务器或 Node.js 环境，直接双击根目录下的 `index.html` 即可在浏览器中开启创作。

---

## 📖 使用指南

1. **输入内容**：在左侧 Markdown 编辑区输入你的文字。你可以点击“导入示例”快速查看排版效果。
2. **选择模板**：在模板区点击切换四种不同的视觉风格。
3. **精细调节**：
   - 拖动 **Padding** 滑块调整呼吸感。
   - 调整 **Font Size** 适配不同长度的文案。
4. **导出分享**：
   - 点击 **生成高清图片**：下载 PNG 文件。
   - 点击 **复制到剪贴板**：直接在 X 或微信窗口 `Ctrl+V` 发送。

---

## 🔧 常见问题

**Q: 为什么导出的图片文字很模糊？**
A: 本项目默认开启了 3.0 倍率采样。如果依然模糊，请确保浏览器缩放比例为 100%，并使用最新版本的 Chrome 或 Edge。

**Q: 是否支持移动端使用？**
A: 本工具已针对响应式布局进行了优化，但在桌面端浏览器（Chrome/Edge/Safari）上能获得最精准的导出效果。

---

## 📄 开源协议

本项目基于 **MIT License** 开源。你可以自由地使用、修改和分发。

---

*“在这个注意力稀缺的时代，排版本身就是一种表达。” —— TextCard Pro 团队*
