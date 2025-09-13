# AI & Software Projects

[日本語はこちら](#日本語版)

Welcome. This site showcases a collection of software I’ve built, ranging from AI-driven apps to other creative and technical projects.

## Table of Contents

- [AI Agent Thriller Game](#-ai-agent-thriller-game)
- [Twitch ChatGPT Bot](#-chatgpt-powered-twitch-bot-with-logging)
- Seasonal Ramen Chef AI Agent (Ruby + OpenAI) - Pending
- LangChain AI Agent orchestration - Pending
- Dockerized Node.js + React.js App (with optional Rust service) - Pending
- Cookie Persistence Utility - Pending
- OpenGL Scene - Pending

---

## 🎮 AI Agent Thriller Game

### Description

An interactive text adventure game called Eternal Hunt where an AI agent plays the role of the game narrator.
<br/><br/>
Using the OpenAI Agents SDK, this game features two AI agents that help tell a story. One agent is the narrator that interacts with the player. The other agent is a web researcher with access to the internet. The web researcher can only be contacted by the narrator agent when it needs access to real time information. The narrator agent is trained with the story background, has custom function tools, can save updates in the story log, and can conduct inventory management.
<br/><br/>
There is a Jupyter Notebook version of the game that walks through the game's main processes. The main Python application comes with both a Gradio and Streamlit UI.

### Code

[GitHub Repo](https://github.com/swallace100/thriller-game-ai-agent)

### Tech Stack

- Python
- Jupyter Notebook
- OpenAI Agents SDK
- Gradio
- Streamlit

### Screenshots

#### Gradio UI Screenshot

![Screenshot 1](images/Gradio_Eternal_Hunt.jpg)
<br/><br/>

---

## 🤖 ChatGPT Powered Twitch Bot with Logging

### Description

A Twitch chatbot that integrates with OpenAI’s GPT models to keep offline chat entertaining.
It generates jokes, trivia, nicknames, micro-stories, and AI-generated images using custom prompts, while logging all chat messages by channel and date.
<br/><br/>
The bot was originally built with TwitchIO 2.x (IRC-based) and has now been fully updated to use Twitch’s modern EventSub WebSocket system, making it future-proof and aligned with Twitch’s recommended architecture.
<br/><br/>
This project demonstrates how to blend AI creativity with Twitch interactivity, offering a lively companion when streams are offline.

### Code

[GitHub Repo](https://github.com/swallace100/ChatGPT-Powered-Twitch-Bot-With-Logging)

### Tech Stack

- Python
- OpenAI API (Chat + Images)
- Twitch EventSub WebSockets
- dotenv
- Requests
- Web Sockets

### **Screenshots:**

#### Chat Responses

<img src="images/Twitch_Chat_Bot.jpg" alt="Twitch Chat Bot" width="400"/>

<br/><br/>

---

## 🍜 Seasonal Ramen Generator (Ruby + OpenAI)

**Description:** Suggests ramen recipes based on the current season and seasonal Japanese ingredients.  
**Code:** Coming soon!

---

# 日本語版

[English version](#ai--software-projects)

ようこそ。このサイトでは、私が開発したソフトウェアを紹介する。AI を活用したアプリから、その他のクリエイティブや技術的なプロジェクトまで幅広く取り上げている。

## 目次

- [AI Agent のスリラーのゲーム](#-ai-agentのスリラーのゲーム)
- [Twitch ChatGPT ボット](#-chatgpt-搭載-twitch-ボットチャットログ付き)
- [季節のラーメンジェネレーター](#-季節のラーメンジェネレーター-ruby--openai)
- 季節限定ラーメンシェフ AI エージェント（Ruby + OpenAI） - 準備中
- LangChain AI エージェントオーケストレーション - 準備中
- Docker 化された Node.js + React.js アプリ（Rust サービスを追加可能） - 準備中
- クッキー永続化ユーティリティ - 準備中
- OpenGL シーン - 準備中

## 🎮 AI Agent のスリラーのゲーム

### 概要

『永遠の狩り』はインタラクティブなテキストアドベンチャーゲームで、AI エージェントがナレーターとして登場する。
<br/><br/>
このゲームは OpenAI の Agents SDK を活用し、二つの AI エージェントがストーリーを伝える。一つのエージェントはナレーターとなりプレイヤーとやり取りし、もう一つのエージェントはインターネットにアクセスして情報を調べる研究者の役割を果たす。研究者エージェントには、ナレーターエージェントがリアルタイムの情報を必要とする時だけ連携できる。ナレーターエージェントはストーリーに基づいて学習されており、カスタム機能を備えている。さらに、ストーリーの変更をログに保存したり、在庫管理を行ったりすることも行える。
<br/><br/>
Jupyter Notebook 版では、ゲームの主な処理の流れを示している。メインの Python アプリケーションは、Gradio と Streamlit の UI を備えている。

### コード

[GitHub Repo](https://github.com/swallace100/thriller-game-ai-agent)

### 技術スタック

- Python
- Jupyter Notebook
- OpenAI Agents SDK
- Gradio
- Streamlit

### スクリーンショット

#### Gradio UI のスクリーンショット

![Screenshot 1](images/Gradio_Eternal_Hunt_jp.jpg)

---

## 🤖 ChatGPT 搭載 Twitch ボット（チャットログ付き）

### 概要

OpenAI の GPT モデルを活用し、ジョーク、トリビア、ニックネーム、マイクロストーリー、AI 画像生成 を行う Twitch チャットボット。
チャットメッセージはチャンネルごと・日付ごとにログファイルとして保存され、オフライン時でも配信の場を盛り上げる存在となる。
<br/><br/>
当初は TwitchIO 2.x（IRC ベース）を用いて構築されたが、現在は Twitch の最新システム EventSub WebSocket を利用するよう完全に更新済み。これにより、将来的にも安定して利用できる設計となっている。
<br/><br/>
AI の創造性と Twitch のインタラクティブ性を融合させ、オフライン時でも視聴者を楽しませるコンパニオンとして機能する。

### コード

[GitHub リポジトリ](https://github.com/swallace100/ChatGPT-Powered-Twitch-Bot-With-Logging)

### 技術スタック

- Python
- OpenAI API
- Twitch EventSub WebSocket
- dotenv
- Requests
- WebSockets

### ステータス

#### チャット応答例

<img src="images/Twitch_Chat_Bot.jpg" alt="Twitch Chat Bot" width="400"/>
<br/><br/>

---

## 🍜 季節のラーメンジェネレーター (Ruby + OpenAI)

**概要:** 季節に応じた食材を使ったラーメンレシピを提案します。  
**コード:** 近日公開！
