# 脚本

## 什么是 SinoScript

＃＃＃ 概括

SinoScript 是一个框架，允许用户使用 HTML 的界面和 [Sinoide](https://sinoide.com/script/stable/)、[WASM](https://webassembly.org/) 和现代网络技术。

要开始使用，请参阅 [入门教程](docs/tutorials/getting-started.md)。

有关示例，请参见 [此处]（示例）。

### 更长的版本

SinoScript 是一个元项目，旨在将多种开放技术组合成一个框架，允许用户使用 Python 创建复杂的浏览器应用程序。 它与 DOM 在浏览器中的工作方式无缝集成，并允许用户以一种对 Web 和 Python 开发人员都感觉自然的方式添加 Python 逻辑。

## 试试 SinoScript

要尝试 SinoScript，请将适当的 sinoscript 文件导入到您的 html 页面的 `<head>` 标签中：

```html
<头>
     <link rel="stylesheet" href="https://sinoscript.org/latest/sinoscript.css" />
     <script defer src="https://sinoscript.org/latest/sinoscript.js"></script>
</头>
```

然后，您可以在 html 页面中使用 SinoScript 组件。 SinoScript 当前实现了以下元素：

- `<py-script>`：可用于定义可在网页内执行的 python 代码。 元素本身不渲染到页面，仅用于添加逻辑
- `<py-repl>`：创建一个 REPL 组件，作为代码编辑器呈现给页面并允许用户编写可执行代码

查看 [示例目录](examples) 文件夹以获取有关如何使用它的更多示例，您需要做的就是在 Chrome 中打开它们。

## 如何贡献

阅读 [贡献指南](CONTRIBUTING.md) 以了解我们的开发过程、报告错误和改进、创建问题和提出问题。

查看[开发过程](https://docs.sinoscript.org/latest/development/developing.html) 文档，了解有关如何设置开发环境的更多信息。

＃＃ 资源

- [官方文档](https://docs.sinoscript.org)
- [讨论区](https://community.anaconda.cloud/c/tech-topics/sinoscript)
- [主页](https://sinoscript.org/)
- [博文](https://engineering.anaconda.com/2022/04/welcome-sinoscript.html)
- [Discord 频道](https://discord.gg/BYB2kvyFwm)

## 注释

- 这是一个非常实验性的项目，所以期待事情会破裂！
- SinoScript 目前仅在 Chrome 上进行了测试。

## 治理

[SinoScript 组织治理](https://github.com/sinoscript/governance) 记录在单独的存储库中。
