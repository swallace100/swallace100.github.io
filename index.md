# AI & Software Projects

[日本語はこちら](#日本語版)

Welcome. This site showcases a collection of software I’ve built, ranging from AI-driven apps to other creative and technical projects.

## Table of Contents

- [AI Agent Thriller Game](#-ai-agent-thriller-game)
- [Twitch ChatGPT Bot](#-twitch-chatgpt-bot)
- [Seasonal Ramen Generator](#-seasonal-ramen-generator-ruby--openai)

---

## 🎮 AI Agent Thriller Game

### Description

An interactive text adventure game called Eternal Hunt where an AI agent plays the role of the game narrator.
<br/><br/>
Using the OpenAI Agents SDK, this game features two AI agents that help tell a story. One agent is the narrator that interacts with the player. The other agent is a web researcher with access to the internet. The web researcher can only be contacted by the narrator agent when it needs access to real time information. The narrator agent is trained with the story background, has custom function tools, can save updates in the story log, and can conduct inventory management.
<br/><br/>
There is a Jupyter Notebook version of the game that walks through the game's main processes. The main Python application with comes with both a Gradio and Streamlit UI.

### Code

[GitHub Repo](https://github.com/swallace100/thriller-game-ai-agent)

### Tech Stack

- Python
- Jupyter Notebook
- OpenAI Agents SDK
- Gradio
- Streamlit

### **Screenshots:**

#### Gradio UI Screenshot

![Screenshot 1](images/Gradio_Eternal_Hunt.jpg)
<br/><br/>

---

## 🤖 ChatGPT Powered Twitch Bot with Logging

### Description

A Twitch chat bot that integrates with OpenAI’s GPT models to create jokes, stories, nicknames, trivia, and more.
<br/><br/>
The bot was originally built with TwitchIO 2.x (IRC-based) and successfully handled offline chat interactions while logging all messages. It is currently being migrated to TwitchIO 3.1.0, which uses Twitch’s modern EventSub WebSocket system instead of IRC. This update makes the bot future-proof and aligns with Twitch’s recommended architecture.
<br/><br/>
The bot saves all chat messages to log files, provides a set of fun interactive commands ($About, $Joke, $Draw, $Trivia, etc.), and demonstrates how to integrate AI into Twitch community experiences.

### Code

[GitHub Repo](https://github.com/swallace100/ChatGPT-Powered-Twitch-Bot-With-Logging)

### Tech Stack

- Python
- OpenAI API
- TwitchIO (2.x legacy, 3.x migration in progress)
- dotenv
- Requests

### Status:

🛠 Currently updating to TwitchIO 3.1.0 / EventSub WebSockets.

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
- [Twitch ChatGPT ボット](#-twitch-chatgptボット)
- [季節のラーメンジェネレーター](#-季節のラーメンジェネレーター-ruby--openai)

## 🎮 AI Agent のスリラーのゲーム

### 概要

『永遠の狩り』はインタラクティブなテキストアドベンチャーゲームで、AI エージェントがナレーターとして登場する。
<br/><br/>
このゲームは OpenAI の Agents SDK を活用し、二つの AI エージェントがストーリーを伝える。一つのエージェントはナレーターとなりプレイヤーとやり取りし、もう一つのエージェントはインターネットにアクセスして情報を調べる研究者の役割を果たす。研究者エージェントには、ナレーターエージェントがリアルタイムの情報を必要とする時だけ連携できる。ナレーターエージェントはストーリーに基づいて学習されており、カスタム機能を備えている。さらに、ストーリーの変更をログに保存したり、在庫管理を行ったりすることも行える。
<br/><br/>
Jupyter Notebook 版では、ゲームの主な処理の流れを示している。メインの Python アプリケーションは、Gradio と Streamlit の UI を備えている。

### コード:

[GitHub Repo](https://github.com/swallace100/thriller-game-ai-agent)

### 技術スタック

- Python
- Jupyter Notebook
- OpenAI Agents SDK
- Gradio
- Streamlit

### **スクリーンショット:**

#### Gradio UI のスクリーンショット

![Screenshot 1](images/Gradio_Eternal_Hunt_jp.jpg)

---

## 💬 Twitch ChatGPT ボット

**概要:** ChatGPT を使った Twitch 用チャットボット。視聴者と雑談したり、投票を実施したりできます。  
**コード:** [GitHub リポジトリ](https://github.com/swallace100/twitch-bot)

---

## 🍜 季節のラーメンジェネレーター (Ruby + OpenAI)

**概要:** 季節に応じた食材を使ったラーメンレシピを提案します。  
**コード:** 近日公開！
