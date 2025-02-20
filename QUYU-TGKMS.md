# 🚀 趋于飞机关键词监听推送系统 (QUYU-TGKMS)

一个功能强大的Telegram关键词监听推送系统，支持多账号监听，关键词触发通知。

## ✨ 功能特点

- 🔰 多账号监听支持
- 🎯 自定义关键词监听
- 🛡️ 多重消息过滤机制
- ⚡ 即时消息推送
- 🔐 安全的账号管理
- 🔄 实时消息捕获
- 📌 精准的消息定位

## 💻 环境要求

- 🪟 Windows 7/10/11
- 🐍 Python 3.7+
- 🌐 网络环境(需要能访问Telegram)

## 📥 部署教程

### 1️⃣ 安装Python环境

1. 访问Python官网：https://www.python.org/downloads/
2. 下载Python 3.7或更高版本
3. 运行安装程序，**重要：安装时勾选"Add Python to PATH"**
4. 打开命令提示符(cmd)，输入 `python --version` 验证安装

### 2️⃣ 安装依赖包

打开命令提示符(cmd)，依次执行以下命令：

```bash
pip install telethon
pip install emoji
pip install requests
```

### 3️⃣ 配置文件说明
1. 编辑 `TgMLis.py` 文件中的配置项：
   - `notify_target_id` ：替换为接收通知的目标聊天ID
   - `bot_token` ：替换为你的通知机器人Token

## 📖 使用教程

### 1️⃣ 首次使用

1. 双击运行 `start.bat`
2. 根据提示输入 `y` 开始登录账号
3. 输入手机号码（格式：+国际区号手机号，如：+8613800138000）
4. 输入Telegram发送的验证码
5. 如果开启了两步验证，还需要输入密码
6. 可以选择继续添加其他账号或完成登录，不需要继续添加就点击输入 `n`

### 2️⃣ 日常使用

- 🚀 直接运行 `start.bat` 输入 `n`
- 🔄 程序会自动加载已登录的账号开始监听
- 📬 当检测到关键词时，会自动推送通知到设定的Telegram目标聊天ID中

### 3️⃣ 自定义配置

在 `system_config` 中可以修改以下设置：
- 👤 `need_username` ：是否需要用户名
- 😊 `has_emoji` ：是否允许包含表情
- 📏 `message_length` ：消息最大长度
- 🔍 `keywords` ：监听的关键词列表
- 🚫 `nickname` ：需要屏蔽的昵称关键词
- ❌ `talk` ：需要屏蔽的话术关键词

## 📱 联系方式与社群

### Telegram 社群
- 📢 官方频道：[@QUYUkjpd](https://t.me/QUYUkjpd)
- 👥 交流群：[@QUYUkjq](https://t.me/QUYUkjq)
- 👨‍💻 作者：[@Lawofforce](https://t.me/Lawofforce)

### 💫 购买咨询
- 🛍️ 如需购买请联系：[@Lawofforce](https://t.me/Lawofforce)
- 🎯 演示群：[@QUYUfjgjcjt](https://t.me/QUYUfjgjcjt)

## 💝 赞助支持

如果觉得这个程序对你有帮助，欢迎赞助支持！

### 💎 TRC20-USDT 钱包地址

请复制以下地址进行转账：

```
TQ2gs6167orQSVWVNHWrKq9SZ8a5WRETZs
```

### 📲 TRC20-USDT 收款二维码

或扫描以下二维码进行转账：

![USDT收款二维码](https://quickchart.io/qr?text=TQ2gs6167orQSVWVNHWrKq9SZ8a5WRETZs&size=200)

您的支持是我们持续改进的动力！

## 📝 更新日志

### ✨ v1.0.0 (2025-02-19)
- 🎉 首次发布
- 🔰 支持多账号监听
- 🎯 支持自定义关键词
- ⚡ 支持即时消息推送
- 🛡️ 支持多重消息过滤
- 🔄 支持定时强制更新
- 🚀 优化性能和稳定性

## ⚠️ 注意事项

1. 🔒 建议使用小号进行监听，避免主号被限制
2. 📜 遵守Telegram使用规范，避免滥用
3. 🌐 如遇到登录失败，请检查网络环境

## ⚖️ 免责声明

本项目仅供学习交流使用，请勿用于非法用途。使用本项目所产生的一切后果由使用者自行承担。
