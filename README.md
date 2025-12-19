# 个人博客网站

这是一个使用HTML、CSS和JavaScript构建的个人博客网站。该项目具有现代化的设计风格，支持Markdown格式的文章展示，并提供良好的用户体验。

## 项目概述

本项目是一个响应式的个人博客网站，具有以下特点：

- 现代化的深色主题设计，带有蓝色渐变效果
- 响应式布局，适配不同屏幕尺寸
- 支持Markdown格式的文章展示
- 整块文章点击跳转功能
- 优雅的动画效果和视觉反馈

## 主要功能模块

### 1. 首页 (index.html)
- 展示博客文章列表
- 导航栏和网站标题
- 每个文章块都可以整块点击跳转到详情页

### 2. 文章详情页 (articles/test-article.html)
- 展示完整的文章内容
- 支持Markdown格式的各种元素（标题、列表、代码块、引用等）
- 返回首页的导航按钮

### 3. 样式文件
- `style.css`: 主样式文件，定义了网站的整体外观
- `articles/markdown.css`: 专门用于Markdown内容渲染的样式

## 使用说明

1. 直接在浏览器中打开 `index.html` 文件即可浏览博客首页
2. 点击任意文章块可跳转到文章详情页
3. 在文章详情页可以通过"返回首页"按钮回到主页

## 添加新文章

如果您在`art`文件夹中添加了新的Markdown文件，需要手动将其转换为HTML格式并保存到`articles`文件夹中：

1. 复制`articles/model.html`文件作为模板
2. 将Markdown内容转换为HTML格式
3. 将新文件保存到`articles`文件夹中
4. 在`index.html`中添加新文章的链接

## 文件结构

```
.
├── index.html              # 博客首页
├── art/                   # 原始Markdown文章文件夹
│   ├── Java配置.md         # Java环境配置指南
│   ├── XSS-Labs通关笔记.md  # XSS-Labs靶场通关笔记
│   ├── c.md               # C语言学习笔记
│   ├── docker笔记.md        # Docker学习笔记
│   ├── docker笔记简化版.md   # Docker学习笔记简化版
│   ├── ensp.md            # eNSP网络设备配置
│   ├── font.md            # 前端学习笔记
│   ├── mysql.md           # MySQL数据库学习笔记
│   ├── php.md             # PHP基础教程
│   ├── python.md          # Python编程笔记
│   ├── sqli注入总结.md       # SQL注入总结
│   ├── tkinter.md         # Tkinter GUI编程指南
│   └── vscode.md          # VSCode使用技巧
├── articles/              # 转换后的HTML文章文件夹
│   ├── c.html             # C语言学习笔记
│   ├── docker-simple.html  # Docker学习笔记简化版
│   ├── docker.html         # Docker学习笔记
│   ├── ensp.html          # eNSP网络设备配置
│   ├── font.html          # 前端学习笔记
│   ├── java.html          # Java环境配置指南
│   ├── model.html          # Markdown语法示例模板
│   ├── mysql.html          # MySQL数据库学习笔记
│   ├── php.html            # PHP基础教程
│   ├── python.html         # Python编程笔记
│   ├── sqli.html           # SQL注入总结
│   ├── test-article.html   # Markdown格式测试文章
│   ├── tkinter.html        # Tkinter GUI编程指南
│   ├── vscode-config.html  # VSCode配置指南
│   ├── vscode.html         # VSCode使用技巧
│   └── xss-labs.html       # XSS-Labs靶场通关笔记
└── css/                   # 样式文件夹
    ├── style.css           # 主样式文件
    └── markdown.css        # Markdown样式文件
```