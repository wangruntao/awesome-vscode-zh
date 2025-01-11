# 🔍 开发调试插件

本文档收集了提升调试效率的VSCode插件。

## Debug Visualizer

![Downloads](https://img.shields.io/visual-studio-marketplace/d/hediet.debug-visualizer)
![Rating](https://img.shields.io/visual-studio-marketplace/r/hediet.debug-visualizer)

### 📝 插件简介
可视化调试工具，支持多种数据结构的可视化展示。

### ✨ 主要特点
- 支持数组、树等数据结构可视化
- 实时更新视图
- 支持自定义可视化规则
- 多种展示方式

### 🔧 推荐配置
```json
{
  "debug.visualize.enableInlineValues": true,
  "debug.toolBarLocation": "docked",
  "debug.openDebug": "openOnDebugBreak"
}
```

## Chrome Debugger

![Downloads](https://img.shields.io/visual-studio-marketplace/d/msjsdiag.debugger-for-chrome)
![Rating](https://img.shields.io/visual-studio-marketplace/r/msjsdiag.debugger-for-chrome)

### 📝 插件简介
Chrome浏览器的调试工具，支持断点调试、变量查看等功能。

### ✨ 主要特点
- 支持断点调试
- 变量监视
- 控制台集成
- 源码映射

### 📖 配置示例
```json
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "chrome",
      "request": "launch",
      "name": "Launch Chrome",
      "url": "http://localhost:3000",
      "webRoot": "${workspaceFolder}"
    }
  ]
}
```

### 💡 使用技巧
- 善用条件断点
- 使用logpoint代替console.log
- 配合React/Vue开发工具使用
- 注意源码映射配置 