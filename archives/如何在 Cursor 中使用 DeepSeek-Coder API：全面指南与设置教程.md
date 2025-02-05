# 如何在 Cursor 中使用 DeepSeek-Coder API：全面指南与设置教程

![Cursor 编辑器界面](https://bbtdd.com/img/0067508191.webp)

## Cursor 简介

Cursor 是一款以 AI 为核心的代码编辑器，具备智能自动完成、多行编辑、智能重写等功能，能够显著提升软件开发效率。此外，Cursor 还提供了与 AI 对话的能力，帮助开发者更好地理解和操作代码库。

## Cursor 的核心特性

- **多行编辑**：支持多行编辑，不仅能生成代码，还能基于现有代码自动提示可能需要修改的地方，体验非常顺滑，很多时候只需按下 Tab 键即可完成多行代码的编辑。
- **AI 对话**：可以与 AI 对话，帮助开发者理解和操作代码库。值得一提的是，对话背后是一个多模态模型，可以输入图片、代码、文本等，然后生成对应的代码。

## Cursor 的订阅计划

- **Hobby**：免费计划，包括两周 Pro 试用期、每月 2000 个代码补全、50 个慢速优先的高级请求和 200 次 Cursor-small 模型的使用。Cursor-small 是一个更快的模型，适用于快速编辑任务。
- **Pro**：每月 $20，包括所有 Hobby 计划内容，并提供无限制的代码补全、每月 500 个快速优先的高级请求、无限制的慢速高级请求、无限制的 Cursor-small 使用以及每天 10 次 Claude Opus 使用。高级模型包括 GPT-4、GPT-4o 和 Claude 3.5 Sonnet。
- **Business**：每用户每月 $40，包括 Pro 计划内容，并增加了集中式账单、管理员使用情况仪表板、强制隐私模式和 OpenAI/Anthropic 零数据保留政策。隐私模式确保代码仅存储在用户的设备上，不会用于训练。

## 切换到 DeepSeek-Coder API 的方法

DeepSeek-Coder 是一个代码能力接近 GPT-4 的模型，价格非常便宜，输入 1 元/ 1 百万 tokens（命中缓存 0.1元百万 tokens），输出 2 元/ 1 百万 tokens。

### 设置步骤

1. 在 Cursor 设置界面，添加模型名称 `deepseek-coder`。
2. 在设置 OpenAI API 的地方输入 DeepSeek 的 API 密钥。
3. 点击 Overwrite OpenAI Base URL，输入 `https://api.deepseek.com/beta`。

![DeepSeek-Coder API 设置界面](https://bbtdd.com/img/311501553595.webp)

### 硅基流动开源版 DeepSeek-Coder-V2-Instruct API 设置方法

1. 在 Cursor 设置界面，添加模型名称 `deepseek-ai/DeepSeek-Coder-V2-Instruct`。
2. 在设置 OpenAI API 的地方输入硅基流动的 API 密钥。
3. 点击 Overwrite OpenAI Base URL，输入 `https://api.siliconflow.cn/v1`。

硅基流动提供的 DeepSeek-Coder-V2-Instruct API 价格为 1.33 元/ 1 百万 tokens，输入输出同价。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

![DeepSeek-Coder-V2-Instruct API 设置界面](https://bbtdd.com/img/631006653703.webp)