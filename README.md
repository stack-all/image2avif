<h1 align="center">image2avif</h1>

<div align="center">

Convert images(`.jpg`, `.png`, `.jpeg`) to AVIF format.

![GitHub repo size](https://img.shields.io/github/repo-size/stack-all/image2avif) <a title="hits" target="_blank" href="https://github.com/stack-all/image2avif"><img src="https://hits.b3log.org/stack-all/image2avif.svg" ></a> ![GitHub contributors](https://img.shields.io/github/contributors/stack-all/image2avif) ![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/stack-all/image2avif/main.yml) ![GitHub License](https://img.shields.io/github/license/stack-all/image2avif)

English &nbsp;&nbsp;|&nbsp;&nbsp; [简体中文](README_ZH.md)

</div>

## ✨Features

- 🚪 Easy to get start. Just upload your images and wait for results!
- 🚀 AVIF format is the next-generation for image. It could reduce file sizes by 20-90%.
- ☁️ Use [`Github Action`](https://github.com/stack-all/image2avif/actions) to process images so that the client doesn't have to bear the heavy conversion.

## 🔧Usage

Just upload pictures(`.jpg`, `.png`, `.jpeg`) to the root of `main` branch. Action would automatically convert them to AVIF format and put them under `output` folder in `main` branch and the root of `output` branch

## 🛡jsDelivr URL

You could use [`jsDelivr`](https://www.jsdelivr.com/) as CDN for converted images and the URLs would be like this

- [`Gcore`](https://gcore.com/)

```text
https://gcore.jsdelivr.net/gh/[username]/[repo]@[branch]/[path]
```

- [`Cloudflare`](https://cloudflare.com/)

```text
https://testingcf.jsdelivr.net/gh/[username]/[repo]@[branch]/[path]
```

For example, if you would like to use `new-folder-1.avif` in [`stack-all/image2avif`](https://github.com/stack-all/image2avif) repository, you could use

```text
https://testingcf.jsdelivr.net/gh/stack-all/image2avif@main/output/new-folder-1.avif
```

as [`Cloudflare`](https://cloudflare.com/) CDN URL or

```text
https://gcore.jsdelivr.net/gh/stack-all/image2avif@main/output/new-folder-1.avif
```

as [`Gcore`](https://gcore.com/) CDN URL.
