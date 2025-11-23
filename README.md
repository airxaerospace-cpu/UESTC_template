# 🎉 UESTC_template - Quickly Format Your Academic Papers

[![Download UESTC_template](https://img.shields.io/badge/Download-UESTC_template-brightgreen)](https://github.com/airxaerospace-cpu/UESTC_template/releases)

## 📚 目录
- [项目简介](#项目简介)
- [安装与运行](#安装与运行)
- [文件介绍](#文件介绍)
- [个性化设计](#个性化设计)
- [注意事项](#注意事项)
- [特别感谢](#特别感谢)
- [在线 PDF 转 docx 网站](#在线网站)

## 📖 项目简介
本项目基于 `pandoc` 和 `Latex` 构建。使用该模板可以快速排版符合 UESTC 要求的论文，包括课程论文、综设报告和学位论文。模板源自王稳师兄的改良版本，方便用户快速上手。

## 🚀 安装与运行

### 1. 安装
个人推荐在 `Windows` 环境中使用，因为 `Latex` 完整安装包大的确需要约 7GB 的空间。

### 📥 [Pandoc](https://pandoc.org/installing.html)

> **注意**: 请访问以下链接以获取最新版本。

#### For Windows
* [安装包地址](https://github.com/jgm/pandoc/releases/tag/3.8.2.1) (选择与您电脑版本相符的安装包)

#### For Linux
使用终端命令来安装 Pandoc：
```bash
sudo apt update
wget https://github.com/jgm/pandoc/releases/download/3.8.2.1/pandoc-3.8.2.1-1-amd64.deb
sudo dpkg -i pandoc-3.8.2.1-1-amd64.deb
pandoc --version 
```
如果您看到以下类似的输出，说明 Pandoc 安装成功。
```bash
pandoc 3.8.2.1
Compiled with pandoc-types 1.22, texmath 0.12.0.1, skylighting 0.11.0.1
```

### 📦 [Latex](https://www.latex-project.org/get/)
#### For Windows
* [下载安装包](https://mirror.ctan.org/systems/texlive/tlnet/install)

### 2. 下载和安装
请访问 [此页面下载](https://github.com/airxaerospace-cpu/UESTC_template/releases) 以获取所需文件并执行安装。

## 📂 文件介绍
模板包含以下文件：
- **主文件**: `main.tex` - 这是您将在其基础上编写论文的主要文件。
- **样例文件**: `example.tex` - 提供了一个示例，帮助您了解如何使用模板。
- **样式文件**: `uestc.sty` - 包含了所有排版样式设置。

用户可以直接在 `main.tex` 中修改内容以开始撰写自己的论文。

## 🎨 个性化设计
您可以根据需要调整样式文件，以满足个人审美或特定要求。修改 `uestc.sty` 文件中的参数可以轻松改变文档的外观。具体配置可以参考模板的注释部分。

## ⚠️ 注意事项
- 确保 `pandoc` 和 `Latex` 已正确安装，以避免编译错误。
- 使用符合 UESTC 要求的格式进行排版，确保论文符合学校标准。
- 避免同时使用多个版本的 `Latex`，这可能导致冲突和安装问题。

## 🙏 特别感谢
感谢王稳师兄对此模板的改良，以及社区中所有为此项目做出贡献的人。

## 🌐 在线 PDF 转 docx 网站
如需将 PDF 文件转换为 docx 格式，可以使用在线转换工具。[点击这里访问转换网站](https://smallpdf.com/pdf-to-word)。

[![Download UESTC_template](https://img.shields.io/badge/Download-UESTC_template-brightgreen)](https://github.com/airxaerospace-cpu/UESTC_template/releases)