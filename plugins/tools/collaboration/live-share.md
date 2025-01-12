# Live Share

## 插件简介

Live Share是一个实时协作开发工具，允许开发者共享工作区并进行实时协作编辑和调试。

## 主要特性

- 实时代码编辑
- 共享调试会话
- 共享终端
- 语音通话
- 共享服务器
- 跟随和聚焦
- 安全共享

## 安装方法

1. 打开VSCode
2. 按下 `Ctrl+P`
3. 输入 `ext install ms-vsliveshare.vsliveshare`

## 使用方法

1. 开始共享

   - 点击状态栏的Live Share按钮
   - 或按下 `Ctrl+Shift+P`输入 `Live Share: Start Share Session`
   - 复制生成的链接分享给他人
2. 加入会话

   - 打开收到的链接
   - 或在VSCode中选择 `Join Session`
   - 输入共享链接

## 配置示例

```json
{
    "liveshare.audio.startCallOnShare": true,
    "liveshare.guestApprovalRequired": true,
    "liveshare.nameTagVisibility": "Activity",
    "liveshare.showInStatusBar": "whileCollaborating"
}
```

## 常见问题

1. 连接问题

   - 检查网络连接
   - 验证防火墙设置
2. 权限问题

   - 确认登录状态
   - 检查共享权限设置
