# Akiii-v-1.9 推文回复器
Akiii 回复器是一款专为 X / Twitter KOL 打造的 AI 回复辅助 Chrome 扩展，支持在推文旁一键生成自然、有观点、无 AI 味的中英文评论，并可先编辑草稿后再填入回复框，适合 Web3 / Crypto 内容创作者、社区运营和增长人员提升日常互动效率。

# Akiii 回复器

Akiii 回复器是一款专为 X / Twitter KOL 打造的 AI 回复辅助 Chrome 扩展。

它可以在 X 推文旁边生成快捷按钮，帮助用户根据当前推文内容，一键生成自然、有观点、无 AI 味的中英文评论回复。

生成后的内容不会自动发送，而是先进入可编辑草稿窗口。用户可以自行修改、润色，确认满意后再填入 X 回复框。

<img width="1690" height="1443" alt="image" src="https://github.com/user-attachments/assets/0328e04f-61b6-43e5-b49a-d71012d10fa6" />

---

## 项目简介

Akiii 回复器的核心目标是：

> 让 X / Twitter 回复更自然、更高效、更像真人表达。

它不是一个简单的 AI 自动回复工具，而是针对 Crypto / Web3 KOL 日常互动场景设计的回复助手。

插件内置了专门优化过的提示词，会尽量避免常见 AI 味表达，例如：

- 值得关注
- 未来可期
- 赋能生态
- 持续看好
- 多维度
- 深度解析
- 感谢分享
- 确实如此

回复风格默认追求：

- 短而有力
- 有观点
- 有棱角
- 不端着
- 不油腻
- 不像机器人
- 更像真实 KOL 随手发出的评论

---

## 核心功能

### 1. 推文旁一键生成回复

在 X / Twitter 时间线或推文详情页中，插件会在推文操作区域加入 `AI回` 按钮。

<img width="650" height="241" alt="image" src="https://github.com/user-attachments/assets/5a4a3d46-ef09-4c8c-bc30-aa1e171128d0" />


点击后，插件会自动识别当前推文内容，并生成一条适合直接回复的评论。

---

### 2. 回复框内一键生成

当用户打开 X 回复窗口后，插件会在回复框附近显示 `AI填入` 按钮。

用户可以直接基于当前推文生成回复内容。

---

### 3. 可编辑草稿窗口

为了解决 X 输入框自动填入后不方便修改的问题，Akiii 回复器不会直接强行写入内容。

生成后的回复会先进入独立的可编辑草稿窗口。
<img width="443" height="284" alt="image" src="https://github.com/user-attachments/assets/55749570-46c7-4973-8d3e-7e15400185f7" />


用户可以：

- 手动修改回复
- 删除不满意的部分
- 调整语气
- 确认满意后再点击 `填入 X`

插件只负责辅助生成和填入，不会自动发布内容。

---

### 4. 中英文自动识别

插件会自动判断原推文语言。

规则如下：

- 中文推文生成中文短评
- 英文推文生成英文回复
- 中英混合推文根据主要语言自动选择

<img width="509" height="642" alt="image" src="https://github.com/user-attachments/assets/6be22880-b1b4-474a-8a95-6fdbb568f7ed" />


英文回复会尽量保持自然、简洁，像真实 Web3 / Crypto KOL 的评论，而不是中式英语或翻译腔。

---

### 5. 去 AI 味提示词

Akiii 回复器内置了专门优化过的 KOL 回复提示词。

默认要求：

- 回复自然、有灵魂
- 不写空话、套话、官话
- 不写营销味太重的内容
- 不写新闻稿式总结
- 不滥用 emoji
- 不输出解释
- 只输出最终回复结果

---

### 6. 禁用词设置

用户可以在设置页自定义禁用词。

例如：

```text
我觉得,值得关注,未来可期,赋能,生态,感谢分享
```

插件会尽量避免在生成结果中出现这些词，让回复更接近真人表达。

---

### 7. 项目方 @ 账号识别

如果推文中出现项目方账号，插件可以在合适的位置自然带上项目方 `@handle`。

如果原推文没有明确项目方账号，插件不会乱编账号。

---

### 8. 支持多种 API 接口

当前支持以下接口类型：

- OpenAI Responses API
- 兼容 Chat Completions 的接口
- API2D / 中转接口

<img width="503" height="509" alt="image" src="https://github.com/user-attachments/assets/9c65effb-8239-4d6a-8145-f1bcd06dc13c" />


如果 API Key 是 `fk` 开头，插件会自动识别为 API2D / 中转 Key，避免误走 OpenAI 官方接口导致报错。

---

### 9. 本地保存配置

插件配置和 API Key 仅保存在浏览器本地扩展存储中。

不会上传到任何第三方服务器。

请注意：不要把自己的 API Key 上传到 GitHub，也不要写进公开代码里。

<img width="498" height="513" alt="image" src="https://github.com/user-attachments/assets/66b10c36-d47e-4bc3-b26e-aecf0e88d8e4" />


---

### 10. 二次元高端 UI

Akiii 回复器 v1.9 加入了二次元初音风格底图，并采用半透明玻璃拟态 UI 设计。

整体风格偏：

- 可爱
- 高端
- 半透明
- 赛博感
- 二次元
- 轻量化

适合长期作为浏览器插件使用。

---

## 使用场景

Akiii 回复器适合以下用户：

- X / Twitter KOL
- Crypto / Web3 内容创作者
- 项目方社区运营
- BD / Growth 人员
- 英文推文互动用户
- 中文 Crypto 社区创作者
- 高频评论区互动用户

适合用于：

- 快速回复推文
- 提高评论效率
- 增加互动频率
- 生成英文评论
- 避免 AI 味模板回复
- 日常社区运营互动

---

## 安装方式

### 方式一：Chrome 开发者模式安装

1. 下载本项目代码。
2. 解压插件文件夹。
3. 打开 Chrome 浏览器。
4. 进入：

```text
chrome://extensions/
```

5. 打开右上角「开发者模式」。
6. 点击「加载已解压的扩展程序」。
7. 选择插件文件夹。
8. 点击插件图标，填写 API Key 并保存。
9. 打开 X / Twitter 页面，刷新后即可使用。

---

## 使用方式

### 1. 设置 API Key

点击浏览器右上角插件图标，进入设置页。

填写 API Key 后点击保存。

支持：

```text
OpenAI 官方 Key：sk- / sk-proj- 开头
API2D / 中转 Key：fk 开头
```

---

### 2. 在 X 页面使用

打开 X / Twitter 后，推文旁边会出现：

```text
AI回
```

点击后，插件会自动识别推文内容并生成回复草稿。

---

### 3. 编辑草稿

生成后的内容会出现在 Akiii 可编辑草稿窗口。

你可以自由修改。

确认满意后点击：

```text
填入 X
```

内容会被填入 X 回复框。

---

## 文件结构

```text
akiii-reply-extension/
├── manifest.json
├── background.js
├── content.js
├── content.css
├── options.html
├── options.js
├── README.md
└── img/
    ├── i_16.png
    ├── i_32.png
    ├── i_48.png
    ├── i_128.png
    ├── i_256.png
    └── miku_ui_bg.webp
```

---

## 版本信息

当前版本：

```text
v1.9
```

主要更新：

- 升级半透明玻璃拟态 UI
- 融入二次元初音风格底图
- 移除默认风格选择模块
- 支持中英文自动回复
- 修复中文乱码问题
- 修复重复插入问题
- 增加可编辑草稿窗口
- 支持 API2D / 中转 Key 自动识别
- 回复内容只填入，不自动发送

---

## 注意事项

1. 插件不会自动发布内容。
2. 所有生成内容建议用户自行检查后再发布。
3. 请勿将 API Key 上传到 GitHub。
4. 如果 X 页面结构更新，部分按钮位置可能需要后续适配。
5. 本插件仅用于提升内容创作和社区互动效率。

---

## 作者信息

作者：Akiii  

X：[@Guomin184935](https://x.com/Guomin184935)

Telegram 社群：https://t.me/ZzWzryZz

<img width="635" height="811" alt="image" src="https://github.com/user-attachments/assets/b4f747be-9c73-4ecf-a457-08d305467137" />


---

## Pairing: GetXAPI MCP server (optional alternative backend)

Users who already adopt this project sometimes ask about routing read-heavy operations (tweet search, profile lookup, follower lists) to a different X/Twitter backend during testing or for specific workflows. The [GetXAPI MCP server](https://github.com/getxapi/getxapi-mcp) (MIT licensed, open source) implements the same read tools and can be paired with this project without changing existing behavior.

Two integration patterns:

1. **Side-by-side in your AI client.** Keep this project for its primary workflow and add the GetXAPI MCP server when you need a different backend for read operations. Each tool name maps to whichever backend the user has configured.

2. **Code-level toggle.** For a worked reference of an optional alternative backend behind a single env variable, see the [pattern merged into GenAIwithMS/twitter-mcp](https://github.com/GenAIwithMS/twitter-mcp/pull/3).

Tool compatibility (subset that pairs cleanly with this project's read path):

- `search_tweets`
- `get_user_profile`
- `get_user_followers`
- `get_tweet_by_id`

Repository: https://github.com/getxapi/getxapi-mcp

This pairing is fully optional. No behavior change for existing users of this project.

## License

MIT License
