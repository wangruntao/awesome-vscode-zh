# SonarLint

## 插件简介
SonarLint是一个代码质量检查工具，可以帮助开发者在编码时发现和修复质量问题。

## 主要特性
- 实时代码分析
- 多语言支持
- 代码气味检测
- 安全漏洞检查
- 自动修复建议
- 与SonarQube集成
- 详细的问题说明

## 安装方法
1. 打开VSCode
2. 按下`Ctrl+P`
3. 输入`ext install sonarsource.sonarlint-vscode`

## 使用方法
1. 打开任意代码文件
2. SonarLint会自动开始分析
3. 查看问题列表和建议

## 配置示例
```json
{
    "sonarlint.rules": {
        "javascript:S1854": false,
        "python:S107": {
            "level": "off"
        }
    },
    "sonarlint.output.showAnalyzerLogs": false,
    "sonarlint.output.showVerboseLogs": false
}
```

## 常见问题
1. 规则太严格
   - 可以在设置中禁用特定规则
   - 调整规则的严重程度

2. 分析性能问题
   - 配置文件排除
   - 减少同时分析的文件数 