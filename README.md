# 浏览器端 PDF 分割工具

这是一个完全在浏览器中运行的 PDF 文件分割工具。它允许用户通过多种方式分割 PDF 文件，而无需将文件上传到任何服务器，从而确保了用户的隐私和数据安全。

## ✨ 功能特性

- **多种分割模式**:
  - **按页码范围**: 提取并合并指定的页面（例如，提取第 1-5 页和第 8 页）。
  - **按固定页数**: 将 PDF 按指定的页数（例如，每 20 页）分割成多个文件。
  - **按文件大小**: 将 PDF 分割成指定大小（例如，每个文件约 50MB）的多个块。
- **纯客户端处理**: 所有操作都在您的浏览器中完成，PDF 文件不会离开您的电脑。
- **支持拖放**: 直接将 PDF 文件拖拽到窗口即可开始操作。
- **打包下载**: 如果分割后产生多个文件，会自动打包成一个 `.zip` 文件方便下载。

## 🚀 如何使用

无需安装或复杂的配置，只需：

1.  下载本项目。
2.  用现代浏览器（如 Chrome, Firefox, Edge）打开 `index.html` 文件。
3.  选择或拖拽您的 PDF 文件，然后按照界面提示操作。

## 部署

本项目是一个纯静态的单页面应用，不包含任何后端代码。因此，您可以轻松地将 `index.html` 文件部署到任何静态网站托管服务上，例如：

- [Cloudflare Pages](https://pages.cloudflare.com/)
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)

部署时，您不需要任何“构建命令”，只需将 `index.html` 作为站点的根文件即可。

## 🛠️ 技术栈

- **HTML / CSS / JavaScript**: 构建应用的基础。
- **[pdf-lib](https://github.com/Hopding/pdf-lib)**: 用于在 JavaScript 中创建和修改 PDF 文档的核心库。
- **[JSZip](https://github.com/Stuk/jszip)**: 用于在浏览器中创建 `.zip` 文件。
- **[FileSaver.js](https://github.com/eligrey/FileSaver.js/)**: 用于在浏览器中触发文件保存操作。
