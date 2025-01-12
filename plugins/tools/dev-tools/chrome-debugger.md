# Chrome Debugger

## 插件简介
Chrome Debugger是一个用于在VSCode中调试JavaScript和TypeScript代码的工具，支持Chrome浏览器和Node.js环境。

## 主要特性
- 断点调试
- 变量查看
- 调用栈追踪
- 条件断点
- 表达式求值
- 源码映射
- 热重载

## 安装方法
1. 打开VSCode
2. 按下`Ctrl+P`
3. 输入`ext install ms-vscode.js-debug`

## 使用方法
1. 配置调试
   - 创建launch.json
   - 设置调试配置
   - 选择调试目标

2. 开始调试
   - 设置断点
   - 启动调试会话
   - 使用调试工具栏

## 配置示例
```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "type": "chrome",
            "request": "launch",
            "name": "Launch Chrome",
            "url": "http://localhost:3000",
            "webRoot": "${workspaceFolder}/src",
            "sourceMapPathOverrides": {
                "webpack:///src/*": "${webRoot}/*"
            }
        }
    ]
}
```

## 常见问题
1. 断点不生效
   - 检查源码映射
   - 验证文件路径
   - 确认调试配置

2. 连接失败
   - 检查端口设置
   - 确认浏览器版本
   - 验证URL配置 