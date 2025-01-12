# Prettier Extension

## 插件简介
Prettier是一个代码格式化工具，可以帮助团队保持一致的代码风格，支持多种语言和框架。

## 主要特性
- 自动代码格式化
- 多语言支持
- 与ESLint集成
- 保存时自动格式化
- 自定义配置选项
- 统一的代码风格
- 团队协作支持

## 安装方法
1. 打开VSCode
2. 按下`Ctrl+P`
3. 输入`ext install esbenp.prettier-vscode`

## 使用方法
1. 创建.prettierrc
```json
{
    "semi": true,
    "singleQuote": true,
    "tabWidth": 2,
    "printWidth": 80,
    "trailingComma": "es5"
}
```

2. 配置编辑器
   - 设置默认格式化工具
   - 启用保存时格式化

## 配置示例
```json
{
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "prettier.requireConfig": true,
    "prettier.useEditorConfig": true
}
```

## 常见问题
1. 格式化失败
   - 检查配置文件
   - 验证文件类型支持

2. 与ESLint冲突
   - 安装eslint-config-prettier
   - 调整规则优先级
