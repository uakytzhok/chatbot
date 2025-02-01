# ChatGPT Telegram Bot
![python-version](https://img.shields.io/badge/python-3.9-blue.svg)
[![openai-version](https://img.shields.io/badge/openai-1.58.1-orange.svg)](https://openai.com/)
[![license](https://img.shields.io/badge/License-GPL%202.0-brightgreen.svg)](LICENSE)
[![Publish Docker image](https://github.com/n3d1117/chatgpt-telegram-bot/actions/workflows/publish.yaml/badge.svg)](https://github.com/n3d1117/chatgpt-telegram-bot/actions/workflows/publish.yaml)

A [Telegram bot](https://core.telegram.org/bots/api) that integrates with OpenAI's _official_ [ChatGPT](https://openai.com/blog/chatgpt/), [DALL·E](https://openai.com/product/dall-e-2) and [Whisper](https://openai.com/research/whisper) APIs to provide answers. Ready to use with minimal configuration required.

## Screenshots

### Demo
![demo](https://user-images.githubusercontent.com/11541888/225114786-0d639854-b3e1-4214-b49a-e51ce8c40387.png)

### Plugins
![plugins](https://github.com/n3d1117/chatgpt-telegram-bot/assets/11541888/83d5e0cd-e09a-463d-a292-722f919e929f)

## Features
- [x] Support markdown in answers
- [x] Reset conversation with the `/reset` command
- [x] Typing indicator while generating a response
- [x] Access can be restricted by specifying a list of allowed users
- [x] Docker and Proxy support
- [x] Image generation using DALL·E via the `/image` command
- [x] Transcribe audio and video messages using Whisper (may require [ffmpeg](https://ffmpeg.org))
- [x] Automatic conversation summary to avoid excessive token usage
- [x] Track token usage per user - by [@AlexHTW](https://github.com/AlexHTW)
- [x] Get personal token usage statistics via the `/stats` command - by [@AlexHTW](https://github.com/AlexHTW)
- [x] User budgets and guest budgets - by [@AlexHTW](https://github.com/AlexHTW)
- [x] Stream support
- [x] GPT-4 support
  - If you have access to the GPT-4 API, simply change the `OPENAI_MODEL` parameter to `gpt-4`
- [x] Localized bot language
  - Available languages :brazil: :cn: :finland: :de: :indonesia: :iran: :it: :malaysia: :netherlands: :poland: :ru: :saudi_arabia: :es: :taiwan: :tr: :ukraine: :gb: :uzbekistan: :vietnam: :israel:
- [x] Improved inline queries support for group and private chats - by [@bugfloyd](https://github.com/bugfloyd)
  - To use this feature, enable inline queries for your bot in BotFather via the `/setinline` [command](https://core.telegram.org/bots/inline)
- [x] Support *new models* [announced on June 13, 2023](https://openai.com/blog/function-calling-and-other-api-updates)
- [x] Support *functions* (plugins) to extend the bot's functionality with 3rd party services
  - Weather, Spotify, Web search, text-to-speech and more. See [here](#available-plugins) for a list of available plugins
- [x] Support unofficial OpenAI-compatible APIs - by [@kristaller486](https://github.com/kristaller486)
- [x] (NEW!) Support GPT-4 Turbo and DALL·E 3 [announced on November 6, 2023](https://openai.com/blog/new-models-and-developer-products-announced-at-devday) - by [@AlexHTW](https://github.com/AlexHTW)
- [x] (NEW!) Text-to-speech support [announced on November 6, 2023](https://platform.openai.com/docs/guides/text-to-speech) - by [@gilcu3](https://github.com/gilcu3)
- [x] (NEW!) Vision support [announced on November 6, 2023](https://platform.openai.com/docs/guides/vision) - by [@gilcu3](https://github.com/gilcu3)
- [x] (NEW!) GPT-4o model support [announced on May 12, 2024](https://openai.com/index/hello-gpt-4o/) - by [@err09r](https://github.com/err09r)
- [x] (NEW!) o1 and o1-mini model preliminary support

## Additional features - help needed!
If you'd like to help, check out the [issues](https://github.com/n3d1117/chatgpt-telegram-bot/issues) section and contribute!  
If you want to help with translations, check out the [Translations Manual](https://github.com/n3d1117/chatgpt-telegram-bot/discussions/219)


