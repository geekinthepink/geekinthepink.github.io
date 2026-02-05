# 豆狸的博客

基于 Hugo 的静态博客，部署在 GitHub Pages。

🔗 **在线访问**: https://geekinthepink.github.io

## 本地开发

```bash
# 安装 Hugo (macOS)
brew install hugo

# 克隆仓库
git clone https://github.com/geekinthepink/geekinthepink.github.io.git
cd geekinthepink.github.io

# 添加主题
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

# 本地预览
hugo server -D
```

## 写作

```bash
# 创建新文章
hugo new content posts/文章标题.md
```

Front matter 示例：
```yaml
---
title: "文章标题"
date: 2024-02-05T10:00:00+08:00
draft: false
tags: ["标签1", "标签2"]
categories: ["分类"]
---
```

## 部署

推送到 main 分支即可自动部署：
```bash
git add .
git commit -m "更新博客"
git push origin main
```
