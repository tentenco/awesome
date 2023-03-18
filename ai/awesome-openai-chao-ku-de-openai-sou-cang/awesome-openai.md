---
description: >-
  A curated list of all things awesome about OpenAI - the research company
  behind ChatGPT
---

# Awesome-openAI

#### OpenAI General Resources

* [OpenAI Overview](https://beta.openai.com/)
* [OpenAI API Documentation](https://beta.openai.com/docs/introduction)
* [OpenAI Examples](https://beta.openai.com/examples)
* [OpenAI Playground](https://beta.openai.com/playground)

#### Quick Start

* [OpenAI Quick Start](https://beta.openai.com/docs/quickstart)
* [OpenAI Quick Start app](https://github.com/openai/openai-quickstart-node)

#### Models

* [GPT-3](https://beta.openai.com/docs/models/gpt-3)
* [Codex](https://beta.openai.com/docs/models/codex)
* [Content filter](https://beta.openai.com/docs/models/content-filter)

#### Guides on building applications

* [Text completioan](https://beta.openai.com/docs/guides/completion)
* [Image generation](https://beta.openai.com/docs/guides/images)
* [Code completioan](https://beta.openai.com/docs/guides/code)
* [Embeddings](https://beta.openai.com/docs/guides/embeddings)
* [Fine-tuning](https://beta.openai.com/docs/guides/fine-tuning)

#### Popular Applications

* [ChatGPT - Official app](https://chat.openai.com/)
* [Dalle - Official Image generation app](https://beta.openai.com/docs/guides/images)
* [Whisper - Oficial speech recognition app](https://openai.com/blog/whisper/)
* [Twitter bot](https://github.com/transitive-bullshit/chatgpt-twitter-bot)
* [Serverless Telegram bot](https://github.com/franalgaba/chatgpt-telegram-bot-serverless)
* [Dalle clone - Vue3](https://github.com/Jaykef/OpenAI-ImageGeneration-Vue3)
* [Mac menubar ChatGPT App](https://github.com/vincelwt/chatgpt-mac)
* [Google docs bot - ChatGPT as Addon in Google docs](https://github.com/cesarhuret/docGPT)
* [Dicord bot - ChatGPT for discord](https://github.com/m1guelpf/chatgpt-discord)
* [ChatGPT Reversed Engineered api](https://github.com/acheong08/ChatGPT)
* [ChatGPT unofficial desktop app](https://github.com/lencx/ChatGPT)
* [ChatGPT Web (vue3, express, chatgpt api)](https://github.com/Chanzhaoyu/chatgpt-web)

#### Popular Repos

* [Awesome ChatGPT](https://github.com/humanloop/awesome-chatgpt)
* [OpenAI Cookbook - examples and guides for using the OpenAI API](https://github.com/openai/openai-cookbook)

#### Latest News

* [GPT-4 release](https://openai.com/product/gpt-4)
* [GPT-4 deepens the conversation on Duolingo](https://openai.com/customer-stories/duolingo)

#### Apps Utilizing OpenAI API with Frontend Frameworks/Libraries

* [OpenAI Quick Start - React](https://github.com/openai/openai-quickstart-node)
* [Dalle Clone - Vue3, vite, pinia](https://github.com/Jaykef/OpenAI-ImageGeneration-Vue3)

#### Devops Tools using OpenAI APIs

* [Kubernetes and Prometheus ChatGPT Bot](https://github.com/robusta-dev/kubernetes-chatgpt-bot)

#### VSCode Extensions

* [OpenAI Helper - helps you use OpenAI tools in Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=dogukanakkaya.chatgpt-code)
* [ChatGPT VScode Plugin](https://marketplace.visualstudio.com/items?itemName=JayBarnes.chatgpt-vscode-plugin)
* [ChatGPT](https://marketplace.visualstudio.com/items?itemName=kiranshah.chatgpt-helper)

#### API References

To install the official Python bindings, run the following command:

```
pip install openai
```

To install the official Node.js library, run the following command in your Node.js project directory:

```
npm install openai
```

**Authentication**

The OpenAI API uses API keys for authentication. Visit your [API Keys](https://beta.openai.com/account/api-keys) page to retrieve the API key you'll use in your requests.

Remember that your API key is a secret! Do not share it with others or expose it in any client-side code (browsers, apps). Production requests must be routed through your own backend server where your API key can be securely loaded from an environment variable or key management service.

All API requests should include your API key in an Authorization HTTP header as follows:

```
Authorization: Bearer YOUR_API_KEY
```
