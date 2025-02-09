---
title: Hexo：基础用法
date: 2025-02-07 10:00:38
tags:
  - Hexo
categories: 博客开发
keywords: [基础用法, Hexo]
---


Welcome to [Hexo](https://hexo.io/)!  Check the [documentation](https://hexo.io/docs/) for more info. If you encounter any problems when using Hexo, you can find the answer in the [troubleshooting guide](https://hexo.io/docs/troubleshooting.html) or you can ask on [GitHub](https://github.com/hexojs/hexo/issues).

欢迎使用 [Hexo](https://hexo.io/)! 更多信息请查看[文档](https://hexo.io/docs/)。如果您在使用 Hexo 时遇到任何问题，可以在[故障排除指南](https://hexo.io/docs/troubleshooting.html)中找到答案，或者在 [GitHub](https://github.com/hexojs/hexo/issues) 上提问。

## Quick Start 快速开始


**Hexo 常用命令**

1. **初始化博客**

   在目标文件夹中初始化一个新的 Hexo 博客：

   ```bash
   hexo init
   ```

2. **生成静态文件**

   生成博客的静态文件：

   ```bash
   hexo generate
   ```

   该命令也可以简写为：

   ```bash
   hexo g
   ```

3. **启动本地服务器**

   启动本地服务器以预览博客：

   ```bash
   hexo server
   ```

   简写为：

   ```bash
   hexo s
   ```

   默认情况下，您可以在浏览器中访问 `http://localhost:4000` 查看您的博客。

4. **清除缓存**

   在生成或部署博客之前，建议先清除缓存和已生成的静态文件：

   ```bash
   hexo clean
   ```

   简写为：

   ```bash
   hexo cl
   ```

   这有助于避免由于缓存导致的问题。

5. **部署博客**

   将生成的静态文件部署到您的托管平台：

   ```bash
   hexo deploy
   ```

   简写为：

   ```bash
   hexo d
   ```

   请确保您已在 `_config.yml` 中正确配置了部署信息。

6. **创建新文章**

   创建一篇新文章：

   ```bash
   hexo new "文章标题"
   ```

   简写为：

   ```bash
   hexo n "文章标题"
   ```

   这将在 `source/_posts` 目录下生成一个新的 Markdown 文件，您可以在其中撰写您的文章。

**使用建议**

- **命令组合**：在本地撰写和预览文章时，您可以组合使用以下命令：

  ```bash
  hexo clean; hexo generate; hexo server
  ```

    如果您希望在前一个命令成功时才执行下一个命令，可以使用以下方法：

    ```powershell
    hexo clean; if ($?) {hexo generate; if ($?) {hexo server}}
    ```

  这将清除缓存，生成静态文件，并启动本地服务器供预览。

- **简化命令**：Hexo 提供了命令的简写形式，使用这些简写可以提高工作效率。例如，使用 `hexo g` 代替 `hexo generate`。

- **查看帮助**：如果您对某个命令有疑问，可以使用以下命令查看帮助信息：

  ```bash
  hexo help
  ```

  简写为：

  ```bash
  hexo h
  ```

通过熟练掌握以上命令，您可以更加高效地管理和维护您的 Hexo 博客。 

