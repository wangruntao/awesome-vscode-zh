# File Utils

## 插件简介
File Utils是一个文件管理增强工具，提供了多种文件操作功能，让文件管理更加便捷。

## 主要特性
- 快速复制文件路径
- 新建文件和文件夹
- 文件重命名
- 文件移动
- 复制/粘贴文件
- 文件对比
- 批量操作

## 安装方法
1. 打开VSCode
2. 按下`Ctrl+P`
3. 输入`ext install sleistner.vscode-fileutils`

## 使用方法
1. 文件操作
   - 右键文件选择操作
   - 使用命令面板
   - 快捷键操作

2. 路径操作
   - 复制相对路径
   - 复制绝对路径
   - 复制文件名

## 配置示例
```json
{
    "fileutils.typeahead.enabled": true,
    "fileutils.typeahead.exclude": {
        "**/.git": true,
        "**/node_modules": true
    },
    "fileutils.delete.useTrash": true
}
```

## 常见问题
1. 权限问题
   - 检查文件权限
   - 验证工作区权限

2. 操作失败
   - 确认文件未被占用
   - 检查路径是否有效 