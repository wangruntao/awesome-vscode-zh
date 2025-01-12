# Search Everywhere

## 插件简介
Search Everywhere是一个全局搜索工具，可以快速搜索工作区中的任何内容，包括文件、符号和命令。

## 主要特性
- 全局搜索
- 实时搜索结果
- 模糊匹配
- 文件内容搜索
- 符号搜索
- 命令搜索
- 历史记录

## 安装方法
1. 打开VSCode
2. 按下`Ctrl+P`
3. 输入`ext install search-everywhere`

## 使用方法
1. 快速搜索
   - 按下`Ctrl+Shift+F`
   - 输入搜索关键词
   - 实时查看结果

2. 高级搜索
   - 使用正则表达式
   - 设置搜索范围
   - 过滤文件类型

## 配置示例
```json
{
    "search-everywhere.exclude": {
        "**/.git": true,
        "**/node_modules": true,
        "**/*.map": true
    },
    "search-everywhere.maxResults": 100,
    "search-everywhere.quickOpen": true
}
```

## 常见问题
1. 搜索速度慢
   - 配置排除目录
   - 限制搜索范围

2. 结果不准确
   - 调整搜索设置
   - 使用精确匹配 