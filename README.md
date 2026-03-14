# YKZ的升级打怪之旅

个人技术博客，基于 Hexo + Butterfly 主题构建。

## 简介

这是一个个人技术博客网站，记录作者的学习之旅。主要分享以下内容：

- **AI** - 人工智能相关知识与实践
- **Algorithms** - 算法与数据结构
- **Projects** - 个人项目作品
- **Notes** - 学习笔记
- **Python / Java / C++** - 编程语言学习记录

## 技术栈

- **框架**: [Hexo](https://hexo.io/) 7.3.0
- **主题**: [Butterfly](https://github.com/jerryc127/hexo-theme-butterfly) 5.5.4
- **部署**: GitHub Pages

## 项目结构

```
.deploy_git/           # 部署目录（GitHub Pages）
├── index.html         # 博客首页
├── 2026/             # 博客文章（按年份归档）
├── archives/          # 归档页面
├── categories/       # 分类页面
├── tags/             # 标签页面
├── css/              # 样式文件
└── js/               # 脚本文件
```

## 本地运行

如果你想本地预览博客：

```bash
# 安装 Node.js 和 Git

# 克隆博客源码仓库（注意：这是博客源文件，非部署目录）
git clone https://github.com/ykz-sudo/your-blog-source.git
cd your-blog-source

# 安装依赖
npm install

# 本地预览
hexo server
```

然后访问 http://localhost:4000 查看博客。

## 部署

博客已配置自动部署到 GitHub Pages。每次推送更新后，GitHub Actions 会自动构建并部署。

## 联系

- GitHub: [ykz-sudo](https://github.com/ykz-sudo)
- 博客: [YKZ的升级打怪之旅](https://ykz-sudo.github.io)

---

© 2025 - 2026 ykz. All rights reserved.
