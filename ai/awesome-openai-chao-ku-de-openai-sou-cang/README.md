---
description: 關於 OpenAI 的所有精彩內容的精選列表 - ChatGPT 背後的研究公司
---

# Awesome OpenAI - 超酷的 OpenAI 蒐藏

#### OpenAI 通用資源

* [OpenAI 概述](https://beta.openai.com/)
* [OpenAI API 文檔](https://beta.openai.com/docs/introduction)
* [OpenAI 示例](https://beta.openai.com/examples)
* [​​OpenAI 遊樂場](https://beta.openai.com/playground)

#### 快速開始

* [OpenAI 快速入門](https://beta.openai.com/docs/quickstart)
* [OpenAI 快速入門應用](https://github.com/openai/openai-quickstart-node)

#### 楷模

* [GPT-3](https://beta.openai.com/docs/models/gpt-3)
* [法典](https://beta.openai.com/docs/models/codex)
* [內容過濾器](https://beta.openai.com/docs/models/content-filter)

#### 構建應用程序指南

* [文本完成](https://beta.openai.com/docs/guides/completion)
* [圖像生成](https://beta.openai.com/docs/guides/images)
* [代碼完成](https://beta.openai.com/docs/guides/code)
* [嵌入](https://beta.openai.com/docs/guides/embeddings)
* [微調](https://beta.openai.com/docs/guides/fine-tuning)

#### 熱門應用

* [ChatGPT - 官方應用](https://chat.openai.com/)
* [Dalle - 官方圖像生成應用](https://beta.openai.com/docs/guides/images)
* [Whisper - 官方語音識別應用](https://openai.com/blog/whisper/)
* [推特機器人](https://github.com/transitive-bullshit/chatgpt-twitter-bot)
* [無服務器電報機器人](https://github.com/franalgaba/chatgpt-telegram-bot-serverless)
* [Dalle 克隆 - Vue3](https://github.com/Jaykef/OpenAI-ImageGeneration-Vue3)
* [Mac 菜單欄 ChatGPT 應用](https://github.com/vincelwt/chatgpt-mac)
* [Google 文檔機器人 - ChatGPT 作為 Google 文檔中的插件](https://github.com/cesarhuret/docGPT)
* [Dicord 機器人 - ChatGPT for discord](https://github.com/m1guelpf/chatgpt-discord)
* [ChatGPT 逆向工程 api](https://github.com/acheong08/ChatGPT)
* [ChatGPT 非官方桌面應用](https://github.com/lencx/ChatGPT)
* [ChatGPT Web（vue3、express、chatgpt api）](https://github.com/Chanzhaoyu/chatgpt-web)

#### 熱門回購

* [很棒的 ChatGPT](https://github.com/humanloop/awesome-chatgpt)
* [OpenAI Cookbook - 使用 OpenAI API 的示例和指南](https://github.com/openai/openai-cookbook)

#### 最新消息

* [GPT-4 發布](https://openai.com/product/gpt-4)
* [GPT-4 加深了 Duolingo 上的對話](https://openai.com/customer-stories/duolingo)

#### 將 OpenAI API 與前端框架/庫結合使用的應用程序

* [OpenAI 快速入門 - React](https://github.com/openai/openai-quickstart-node)
* [Dalle Clone - Vue3、vite、pinia](https://github.com/Jaykef/OpenAI-ImageGeneration-Vue3)

#### 使用 OpenAI API 開發工具

* [Kubernetes 和 Prometheus ChatGPT Bot](https://github.com/robusta-dev/kubernetes-chatgpt-bot)

#### VSCode 擴展

* [OpenAI Helper - 幫助您在 Visual Studio Code 中使用 OpenAI 工具](https://marketplace.visualstudio.com/items?itemName=dogukanakkaya.chatgpt-code)
* [ChatGPT VScode 插件](https://marketplace.visualstudio.com/items?itemName=JayBarnes.chatgpt-vscode-plugin)
* [ChatGPT](https://marketplace.visualstudio.com/items?itemName=kiranshah.chatgpt-helper)

#### API 參考

要安裝官方 Python 綁定，請運行以下命令：

```
pip 安裝 openai
```

要安裝官方 Node.js 庫，請在 Node.js 項目目錄中運行以下命令：

```
npm 安裝 openai
```

**驗證**

OpenAI API 使用 API 密鑰進行身份驗證。訪問您的 [API 密鑰](https://beta.openai.com/account/api-keys) 頁面以檢索您將在請求中使用的 API 密鑰。

請記住，您的 API 密鑰是秘密的！不要與他人共享或在任何客戶端代碼（瀏覽器、應用程序）中公開它。生產請求必須通過您自己的後端服務器進行路由，您的 API 密鑰可以從環境變量或密鑰管理服務中安全加載。

所有 API 請求都應在 Authorization HTTP 標頭中包含您的 API 密鑰，如下所示：

```
授權：承載 YOUR_API_KEY
```
