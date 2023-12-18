<h1 align="center">image2avif</h1>

<div align="center">

将图片（`.jpg`、 `.png`、 `.jpeg`） 转换为 AVIF 格式.

![GitHub repo size](https://img.shields.io/github/repo-size/stack-all/image2avif) <a title="hits" target="_blank" href="https://github.com/stack-all/image2avif"><img src="https://hits.b3log.org/stack-all/image2avif.svg" ></a> ![GitHub contributors](https://img.shields.io/github/contributors/stack-all/image2avif) ![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/stack-all/image2avif/main.yml) ![GitHub License](https://img.shields.io/github/license/stack-all/image2avif)

[English](README.md) &nbsp;&nbsp;|&nbsp;&nbsp; 简体中文

</div>

## ✨特性

- 🚪 易于上手！只需将图片上传，等待转换结果即可。
- 🚀 作为下一代图片格式的 AVIF 可将图片压缩至原图的 20-90% 。
- ☁️ 使用 [`Github Action`](https://github.com/stack-all/image2avif/actions) 来运行，用户端无须承担沉重的转换负载。

## 🔧使用

只需将图片（`.jpg`、 `.png`、 `.jpeg`）推送至 `main` 分支的根路径. `Github Action` 将自动将图片转换为 AVIF 格式并将其放置于 `main` 分支的 `output` 文件夹以及 `output` 分支的根路径。

## 🛡jsDelivr URL

你可以使用 [`jsDelivr`](https://www.jsdelivr.com/) 作为转换后的图片的 CDN 加速。网址格式如下：

- [`Gcore`](https://gcore.com/)

```text
https://gcore.jsdelivr.net/gh/[username]/[repo]@[branch]/[path]
```

- [`Cloudflare`](https://cloudflare.com/)

```text
https://testingcf.jsdelivr.net/gh/[username]/[repo]@[branch]/[path]
```

例如，假设你想获取 [`stack-all/image2avif`](https://github.com/stack-all/image2avif) 库中的 `new-folder-1.avif` 的加速网址，你可以使用：

```text
https://testingcf.jsdelivr.net/gh/stack-all/image2avif@main/output/new-folder-1.avif
```

这是使用 [`Cloudflare`](https://cloudflare.com/) 作为 CDN 加速，或者你也可以：

```text
https://gcore.jsdelivr.net/gh/stack-all/image2avif@main/output/new-folder-1.avif
```

这是使用 [`Gcore`](https://gcore.com/) 作为 CDN 加速。

## 🙏 致谢

- [`ImageMagick`](https://github.com/ImageMagick/ImageMagick)，强大的开源图像处理工具。
- [`VSCodium`](https://github.com/VSCodium/vscodium)，社区驱动的自由 VSCode 发行版。
- [`jsDelivr`](https://www.jsdelivr.com/)，为免费的开源项目提供 CDN 加速。
- [`Github Action`](https://github.com/features/actions)，它为该项目提供了计算资源以及 CI/CD 平台。
