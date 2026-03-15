

# 生日祝福网页项目

一个精美的生日祝福静态网页项目，包含多种展示页面和动画效果。

## 项目简介

本项目是一个基于 HTML、CSS 和 JavaScript 的生日祝福网页应用，提供了丰富的视觉展示效果，包括生日蛋糕动画、回忆时间线、祝福页面等多种形式。

## 页面功能

### 1. 生日蛋糕页面 (BirthdayCake.html)
- 动态生日蛋糕动画
- 蜡烛火焰效果
- 生日祝福文字
- 互动按钮

### 2. 回忆时间线 (Memories.html)
- 使用 fullPage.js 实现的整屏滚动效果
- 时间线形式展示回忆
- 图片和文字结合的展示方式
- 气泡背景动画

### 3. 登录页面 (login.html)
- 表单登录界面
- 动态气泡背景效果
- 输入框动画

### 4. 彩蛋页面 (EasterEgg.html)
- 隐藏的惊喜内容

### 5. 首页 (index1.html)
- 标签页切换功能
- 命令菜单界面

## 技术栈

- **前端框架**: jQuery
- **页面滚动**: fullPage.js
- **样式**: CSS3 动画、Flexbox 布局
- **响应式设计**: 支持不同屏幕尺寸

## 目录结构

```
├── css/                    # 样式文件
│   ├── jquery.fullPage.css
│   ├── normalize.css
│   ├── style.css
│   ├── stylel.css
│   ├── styles.css
│   └── styless.css
├── html/                   # HTML 页面
│   ├── BirthdayCake.html
│   ├── EasterEgg.html
│   ├── Memories.html
│   ├── index1.html
│   └── login.html
├── img/                    # 图片资源
├── js/                     # JavaScript 文件
├── music/                  # 背景音乐
└── vercel.json            # Vercel 配置文件
```

## 使用说明

1. 直接在浏览器中打开 `html/BirthdayCake.html` 即可查看生日蛋糕效果
2. 打开 `html/Memories.html` 查看回忆时间线
3. 打开 `html/login.html` 查看登录页面效果

## 自定义修改

- 修改 `img/` 目录下的图片替换为对应内容
- 修改 `music/` 目录下的音乐文件
- 在 HTML 文件中修改祝福文字内容

## 浏览器支持

- Chrome
- Firefox
- Safari
- Edge

## 部署

项目已配置 `vercel.json`，可直接部署到 Vercel 平台。

## 许可证

MIT License