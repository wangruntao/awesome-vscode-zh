# ESLint Extension

## 插件简介
ESLint是一个用于查找和修复JavaScript代码问题的工具，可以帮助开发者保持代码质量和一致性。

## 主要特性
- 代码风格检查
- 潜在错误检测
- 最佳实践建议
- 自动修复功能
- 自定义规则支持
- TypeScript支持
- React/Vue规则支持

## 安装方法
1. 打开VSCode
2. 按下`Ctrl+P`
3. 输入`ext install dbaeumer.vscode-eslint`

## 使用方法
1. 初始化ESLint配置
```bash
npm init @eslint/config
```

2. 创建.eslintrc.json
```json
{
    "env": {
        "browser": true,
        "es2021": true
    },
    "extends": [
        "eslint:recommended",
        "plugin:@typescript-eslint/recommended"
    ],
    "parser": "@typescript-eslint/parser",
    "plugins": [
        "@typescript-eslint"
    ]
}
```

## 配置示例
```json
{
    "eslint.validate": [
        "javascript",
        "typescript",
        "javascriptreact",
        "typescriptreact"
    ],
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    }
}
```

## 常见问题
1. 规则冲突
   - 检查extends配置
   - 调整规则优先级

2. 性能问题
   - 配置适当的文件忽略
   - 减少不必要的规则
