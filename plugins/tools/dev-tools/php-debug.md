# PHP Debug

## 插件简介
PHP Debug是一个用于调试PHP应用程序的工具，支持XDebug集成和断点调试。

## 主要特性
- XDebug集成
- 断点调试
- 变量查看
- 调用栈
- 步进执行
- 条件断点
- 日志点

## 安装方法
1. 打开VSCode
2. 按下`Ctrl+P`
3. 输入`ext install xdebug.php-debug`

## 使用方法
1. 配置XDebug
   - 安装XDebug扩展
   - 配置php.ini
   - 设置调试端口

2. 开始调试
   - 设置断点
   - 启动调试会话
   - 使用调试控制台

## 配置示例
```json
{
    "php.debug.ideKey": "VSCODE",
    "php.validate.executablePath": "/usr/local/bin/php",
    "php.debug.executablePath": "/usr/local/bin/php",
    "php.debug.port": 9003
}
```

## 常见问题
1. XDebug未连接
   - 检查XDebug配置
   - 验证端口设置
   - 确认PHP版本

2. 断点未触发
   - 检查路径映射
   - 验证XDebug日志
   - 确认请求参数 