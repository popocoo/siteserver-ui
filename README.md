# SiteServer.UI 用户界面UI库

SiteServer CMS 响应式用户交互组件库，建立在 Bootstrap 最新版本 v4.0之上，采用Sass编写，基于HTML5以及CSS3，完全响应式。

## 介绍

SiteServer.UI 是一个功能齐全的主题样式，包括各种实用组件，这些组件在任何页面上都可以很容易地使用，主题是完全响应和可定制的。

## 代码结构

我们在开发 SiteServer.UI 时遵循现在Web标准和模块化结构，以下部分是 SiteServer.UI 的代码组织结构说明。

### 代码组织

```
├── html files
Src/assets/
├── scss/
│   └── All SCSS files
├── css/
│   └── All css files.
├── fonts/
├── pages/
│   └── All the pages related scripts
├── images/
│   └── All images
├── plugins/
│   └── The plugins files - which are not available through bower
└── js/
    └── All common Javascripts files
```

### CSS & Sass

Sass是一种CSS预处理器，它扩展了CSS语言，添加了允许变量、函数和许多其他技术的特性，这些技术允许您使CSS更容易维护、更易于管理和可扩展。

文件解释如下:

| 文件          | 说明                                           |
| ------------- | :--------------------------------------------- |
| bootstrap.css | Bootstrap v4.0.0，所有页面都使用了此核心文件。 |
| style.scss    | sass版本样式文件                               |
| style.css     | css版本样式文件                                |
| style.min.css | css压缩版本样式文件，生产环境使用              |