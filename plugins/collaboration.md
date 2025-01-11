# 🤝 协作效率插件

本文档收集了提升团队协作效率的VSCode插件。

## GitLens

![Downloads](https://img.shields.io/visual-studio-marketplace/d/eamodio.gitlens)
![Rating](https://img.shields.io/visual-studio-marketplace/r/eamodio.gitlens)

### 📝 插件简介
强大的Git源代码管理增强工具，提供了丰富的Git功能扩展。

### ✨ 主要特点
- 行内代码作者标注
- 文件历史记录查看
- 分支管理可视化
- 提交记录搜索
- 支持中文界面

### 🔧 推荐配置
```json
{
  "gitlens.currentLine.enabled": true,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.enabled": true,
  "gitlens.statusBar.enabled": true,
  "gitlens.hovers.enabled": true
}
```

### 💡 使用技巧
- 使用 `Alt + B` 查看行历史
- 在状态栏查看当前分支信息
- 使用交互式rebase简化合并操作
- 善用blame功能追踪代码变更

## Live Share

![Downloads](https://img.shields.io/visual-studio-marketplace/d/MS-vsliveshare.vsliveshare)
![Rating](https://img.shields.io/visual-studio-marketplace/r/MS-vsliveshare.vsliveshare)

### 📝 插件简介
微软官方的实时协作工具，支持多人同时编辑和调试代码。

### ✨ 主要特点
- 实时协作编辑
- 共享调试会话
- 语音通话集成
- 终端共享
- 安全可靠

### 📖 使用教程
1. 安装插件并登录
2. 点击状态栏的Live Share按钮
3. 复制链接分享给团队成员
4. 开始实时协作

### ⚠️ 注意事项
- 需要微软或GitHub账号
- 注意网络连接质量
- 建议在协作时使用语音通话
- 谨慎使用终端共享功能

## Git Graph

![Downloads](https://img.shields.io/visual-studio-marketplace/d/mhutchie.git-graph)
![Rating](https://img.shields.io/visual-studio-marketplace/r/mhutchie.git-graph)

### 📝 插件简介
可视化的Git提交历史查看工具，支持图形化显示分支结构。

### ✨ 主要特点
- 图形化显示提交历史
- 支持常用Git操作
- 分支管理便捷
- 性能优秀

### 💡 使用建议
- 结合GitLens使用效果更佳
- 使用图形界面进行分支合并
- 善用右键菜单的快捷操作
- 建议开启自动刷新功能 