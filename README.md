# 学习通自动答题

> 📱 **LSPosed 模块** | 自动捕获学习通题目并调用 AI 智能答题，支持单选题、多选题、填空题自动作答。

## 功能特性

| 功能 | 说明 |
|------|------|
| **自动捕获** | 监听学习通 WebView 页面加载，自动获取题目 |
| **AI 答题** | 调用 AI API 智能分析题目并自动选择答案 |
| **自动填空** | 识别填空题并自动填充答案 |

## ⚠️ 仅供学习

本项目仅供学习交流使用，请勿用于任何商业目的或违规行为。

## 环境要求

- LSPosed 框架
- Android 9.0+ (API 29+)

## 配置说明
适配了部分模型的openai格式deepseek和minimax，但是现在及将来都不会适配图片题

首次使用需配置 DeepSeek API：

1. 在学习通私有目录创建配置文件：
   ```
   /data/data/com.chaoxing.mobile/files/fxxk_config.txt
   ```

2. 配置内容格式：
   ```
   api_url=https://供应商api
   model=deepseek-chat
   api_key=sk-xxxxxxxxx
   ```

## 使用方法

1. 安装模块并激活
2. 打开学习通，进入作业/考试页面
3. 系统自动捕获题目并调用 AI 答题
4. AI 返回答案后自动点击选项或填充填空


## 注意事项

- 需要有效的 API Key
- AI 超时时间 3 分钟  答题仅取第一道题自动作答


---
**环境**: LSPosed (API 101)

## 💖 赞助

你的 Star 是对我最大的支持，赞助与否随心就好~

| 微信 | 支付宝 |
|:---:|:---:|
| ![微信](https://github.com/user-attachments/assets/df903b50-d5fb-4417-af6a-0f03df8f1967) | ![支付宝](https://github.com/user-attachments/assets/4acafcf4-9cbd-44ba-b827-7dbcb5c8cb2b) |

---
