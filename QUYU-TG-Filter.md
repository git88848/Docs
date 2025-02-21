# 🚀 趋于飞机筛号工具 (QUYU-TG-Filter)

一个用于批量检测手机号是否注册 Telegram 账号的筛号工具。 ✨

## 🎮 使用教程

### 🛠️ 环境要求
- 🐍 Python 3.7+
- 📱 已登录的 Telegram 账号

### 📦 安装步骤
1. ⬇️ 安装依赖：
   ```bash
   pip install telethon
   ```

2. 📂 准备目录结构：
   ```
   ./
   ├── sessions/          # 存放 Telegram 会话文件
   ├── TelegramPhoneNumberRegisteredScript.py
   ├── start.bat         # 启动脚本 ▶️
   ├── phone_numbers.txt  # 待检测的号码列表 📝
   └── phone_register.txt # 已注册号码结果 ✅
   ```

3. 🔐 准备 Telegram 账号：
   - 将 session 文件放入 sessions 目录

### 📝 准备号码列表
1. 在 phone_numbers.txt 中添加要检测的号码
2. 支持的号码格式：
   ```
   +84915552193
   84915552193
   84 915552193
   ```
3. ✨ 支持一行多个号码（空格分隔）

### ▶️ 运行检测
1. 启动程序：
   - 🖱️ 双击 `start.bat` 运行程序
   - 💻 或使用命令行：
   ```bash
   python TelegramPhoneNumberRegisteredScript.py
   ```

2. 运行流程：
   - 🔄 加载 sessions 目录下的账号
   - 📊 实时显示检测进度
   - 💾 自动保存已注册号码

### 📊 检测结果
- ✅ 已注册号码保存在 phone_register.txt
- 🔄 自动跳过 phone_register.txt 中已有的号码

## ⚠️ 注意事项

### 💡 使用建议
- ⏱️ 合理设置检测间隔
- 🔍 定期检查账号是否正常

### 🔢 检测数量说明
单个Telegram协议号的检测能力：
- 📊 默认配置：
  - 批量大小：10个号码/批
  - 等待时间：3秒/批
  
- 🎯 理论最大值：
  - 每天批次：28800批 (86400秒 ÷ 3秒)
  - 每天号码：288000个 (28800批 × 10个)

- 💡 建议使用量：
  - 建议控制在理论最大值的30%左右
  - 每天约8-9万个号码
  - 可通过以下方式调整速度：
    1. 增加等待时间（建议5-10秒）
    2. 减少批量大小（建议5个）

- ⚡ 优化建议：
  1. 准备多个检测账号轮换使用
  2. 定期监控账号状态
  3. 出现限制时增加等待时间

### 🛡️ 异常处理
- ⚡ 程序会自动跳过无效的 session 文件
- 🔄 自动跳过 phone_register.txt 中已有的号码

## 📝 更新日志

### v1.0.0 (2025-02-22) 🎉
- 🌟 首次发布
- 📱 支持批量检测手机号
- 💾 自动保存已注册号码
- ⏱️ 支持设置检测间隔
- 🔄 自动跳过已有结果

## 📱 联系方式与社群

### 🌟 Telegram 社群
- 📢 官方频道：[@QUYUkjpd](https://t.me/QUYUkjpd)
- 👥 交流群：[@QUYUkjq](https://t.me/QUYUkjq)
- 👨‍💻 作者：[@Lawofforce](https://t.me/Lawofforce)

### 🎯 购买咨询
- 💫 如需购买请联系：[@Lawofforce](https://t.me/Lawofforce)

## 💝 赞助支持

如果觉得这个程序对你有帮助，欢迎赞助支持！ 🌟

### 💎 TRC20-USDT 钱包地址

```bash
TQ2gs6167orQSVWVNHWrKq9SZ8a5WRETZs
```

### 📲 TRC20-USDT 收款二维码

或扫描以下二维码进行转账：

![USDT收款二维码](https://quickchart.io/qr?text=TQ2gs6167orQSVWVNHWrKq9SZ8a5WRETZs&size=200)

您的支持是我们持续改进的动力！ ✨
