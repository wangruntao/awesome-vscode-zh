# GitLens

## 插件简介

GitLens是一个强大的Git集成工具，它可以帮助你更好地理解代码，查看代码历史，以及进行版本控制。

## 主要特性

- 行内代码历史
- 文件历史和比较
- 分支管理和可视化
- 提交搜索和导航
- 代码责任追踪
- 仓库状态集成
- 交互式rebase

## 安装方法

1. 打开VSCode
2. 按下 `Ctrl+P`
3. 输入 `ext install eamodio.gitlens`

## 使用方法

1. 查看代码历史

   - 将鼠标悬停在代码行上
   - 查看最后修改信息
   - 点击查看详细历史
2. 文件历史

   - 在文件标签右键
   - 选择GitLens选项
   - 查看文件历史

## 配置示例

```json
{
    "gitlens.codeLens.enabled": true,
    "gitlens.currentLine.enabled": true,
    "gitlens.hovers.currentLine.over": "line",
    "gitlens.statusBar.enabled": true
}
```

## 常见问题

1. 性能问题

   - 禁用不需要的功能
   - 配置适当的缓存
2. 显示问题

   - 检查主题兼容性
   - 调整字体设置
