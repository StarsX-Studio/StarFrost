# Starfrost CSS 框架

## 简介

Starforst 是一个现代化、轻量级的 CSS 框架，专为快速构建响应式网站和 Web 应用而设计。它提供了超过 40 个精心设计的 UI 组件和实用工具类，同时保持极小的文件体积（仅 36KB）。Starforst 采用 CSS 变量实现主题定制，支持一键切换深色/浅色模式，让开发者可以轻松创建美观且一致的界面。

## 主要特性

- 🚀 **轻量高效**：JS与CSS核心文件共仅有 42KB
- 🎨 **主题系统**：基于 CSS 变量的主题系统，支持深色/浅色模式一键切换
- 📱 **响应式设计**：完美适配移动设备到桌面设备
- 🧩 **组件丰富**：提供 40+ 开箱即用的 UI 组件
- 🛠️ **实用工具**：包含大量实用工具类，加速开发流程

## 组件列表

### 基础组件
1. 布局系统（网格、容器、响应式工具）
2. 按钮（多种样式和尺寸）
3. 卡片（带悬停效果）
4. 表单控件（输入框、选择框、复选框等）
5. 表格（条纹、边框等样式）
6. 图像（响应式、圆形等样式）

### 导航组件
7. 导航栏（固定顶部）
8. 侧边栏（响应式）
9. 面包屑导航
10. 分页组件
11. 标签页
12. 下拉菜单

### 信息展示
13. 警告框
14. 工具提示
15. 弹出框（Popover）
16. 徽章
17. 标签
18. 时间线
19. 步骤条
20. 模态框

### 进度与状态
21. 进度条
22. 加载动画
23. 骨架屏（内容加载占位）
24. 折叠面板
25. 手风琴

### 其他组件
26. 轮播图
27. 列表组
28. 分割线
29. 信息提示（Toast）
30. 页脚

### 实用工具类
31. 阴影工具
32. 圆角工具
33. 间距工具
34. 边框工具
35. 浮动工具
36. 文本工具（对齐、截断等）
37. 背景工具
38. 显示工具（display）
39. 位置工具
40. 溢出工具

## 快速开始

### 安装方法

下载本地使用：
```
<link rel="stylesheet" href="starfrost.min.css">
<link rel="stylesheet" href="starfrost.min.js">
```

### 基本模板

```
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starforst 示例</title>
    <link rel="stylesheet" href="starfrost.css">
</head>
<body>
    <nav class="sf-navbar">
        <!-- 导航内容 -->
    </nav>
    
    <div class="sf-container">
        <!-- 页面内容 -->
    </div>
</body>
</html>
```

## 主题切换

Starforst 支持深色/浅色主题一键切换：

```
<button class="sf-btn sf-theme-toggle" id="themeToggle">
    <i class="fas fa-moon"></i>
</button>

<script>
    document.getElementById('themeToggle').addEventListener('click', () => {
        document.documentElement.classList.toggle('sf-theme-dark');
    });
</script>
```

### 手动应用深色主题
在 <html> 标签添加类名：
```<html class="sf-theme-dark">```

## 核心设计理念

1. **简单设计**：通过组合简单工具类创建复杂界面
2. **移动优先**：所有组件从移动端开始设计，逐步增强到大屏幕
3. **主题定制**：通过覆盖 CSS 变量轻松自定义主题
4. **一致性**：所有组件共享相同设计和间距系统

## 浏览器支持

支持所有现代浏览器：
- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

不支持 IE11 及更旧版本
(毕竟IE太难适配了 —— 新雨)
## 许可证

Starforst 基于 MIT 许可证发布，可免费用于个人和商业项目。

## 贡献与支持

欢迎贡献代码或报告问题：
[GitHub 仓库](https://github.com/StarsX-Studio/starfrost)
