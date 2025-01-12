# Code Runner

## 插件简介

Code Runner是一个用于快速运行各种编程语言代码的工具，支持多种语言和自定义命令。

## 主要特性

- 多语言支持
- 快捷键运行
- 自定义执行命令
- 运行选中代码
- 外部终端支持
- 工作目录设置
- 运行结果输出

## 安装方法

1. 打开VSCode
2. 按下 `Ctrl+P`
3. 输入 `ext install formulahendry.code-runner`

## 使用方法

1. 运行整个文件

   - 按下 `Ctrl+Alt+N`
   - 或点击右上角播放按钮
2. 运行选中代码

   - 选中代码片段
   - 按下 `Ctrl+Alt+N`

## 配置示例

```json
{
    "code-runner.executorMap": {
        "javascript": "node",
        "python": "python -u",
        "java": "cd $dir && javac $fileName && java $fileNameWithoutExt"
    },
    "code-runner.runInTerminal": true,
    "code-runner.saveFileBeforeRun": true
}
```

## 常见问题

1. 命令未找到

   - 检查环境变量
   - 验证语言环境
2. 编码问题

   - 设置合适的文件编码
   - 配置终端编码
