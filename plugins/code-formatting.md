# 🎨 代码格式化插件

本文档收集了一些优秀的代码格式化相关插件。

## Prettier - Code formatter

![Prettier Downloads](https://img.shields.io/visual-studio-marketplace/d/esbenp.prettier-vscode)
![Prettier Rating](https://img.shields.io/visual-studio-marketplace/r/esbenp.prettier-vscode)

### 📝 插件简介
Prettier 是一个固执己见的代码格式化工具，支持多种语言，能够统一团队的代码风格。

### ✨ 主要特点
- 支持多种语言：JavaScript、TypeScript、CSS、JSON、HTML等
- 零配置开箱即用
- 可以集成到各种编辑器和CI流程中
- 有完整的中文文档支持

### 🔧 推荐配置
```json
{
  "prettier.semi": false,        // 是否使用分号
  "prettier.singleQuote": true,  // 使用单引号
  "prettier.printWidth": 100,    // 每行代码长度
  "prettier.tabWidth": 2,        // 缩进长度
  "editor.formatOnSave": true    // 保存时自动格式化
}
```

### 📖 使用教程
1. 安装插件
2. 在设置中开启`Format On Save`
3. 右键选择`Format Document with...`选择Prettier作为默认格式化工具

### 🎯 使用技巧
- 可以在项目根目录创建`.prettierrc`文件自定义配置
- 使用`.prettierignore`文件排除不需要格式化的文件
- 配合ESLint使用效果更佳

## ESLint

![ESLint Downloads](https://img.shields.io/visual-studio-marketplace/d/dbaeumer.vscode-eslint)
![ESLint Rating](https://img.shields.io/visual-studio-marketplace/r/dbaeumer.vscode-eslint)

### 📝 插件简介
ESLint 是一个可组装的JavaScript和JSX检查工具，不仅能检查代码格式，还能发现代码质量问题。

### ✨ 主要特点
- 支持JavaScript/TypeScript
- 可配置性强
- 支持自定义规则
- 有丰富的中文文档

### 🔧 推荐配置
```json
{
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```

### 💡 使用建议
- 建议与Prettier配合使用
- 可以使用流行的配置预设如`airbnb`的规则
- 团队开发建议统一ESLint配置
