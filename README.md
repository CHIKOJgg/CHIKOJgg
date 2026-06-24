<div align="center">

# Miroslau · Backend Engineer

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Java+%2F+Spring+Boot+Backend+Developer;AI-Augmented+Polyglot+Shipper;REST+APIs+%7C+PostgreSQL+%7C+Redis+%7C+Docker;Building+Production-Ready+Systems)](https://github.com/CHIKOJgg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miroslav-pisaryk-953490261)
[![Profile views](https://komarev.com/ghpvc/?username=CHIKOJgg&style=flat-square&color=58A6FF)](https://github.com/CHIKOJgg)
[![GitHub followers](https://img.shields.io/github/followers/CHIKOJgg?style=flat-square&color=58A6FF)](https://github.com/CHIKOJgg?tab=followers)

</div>

---

## 👨‍💻 About Me

Backend engineer with a focus on **Java / Spring Boot** and a habit of shipping complete systems. I don't stop at the API — I wire up auth, migrations, caching, CI/CD, and observability before calling a feature done.

Across projects I work in Python, JavaScript, and React when the problem calls for it. I lean heavily on AI-assisted workflows (Anthropic API, OpenRouter, local LLMs, MCP tooling) to move faster across the full stack without sacrificing quality on the backend side that matters most.

- 🏛 Student @ BSUIR (Belarusian State University of Informatics and Radioelectronics)
- 🔭 Currently building: **Klawa AI Assistant** — Spring Boot + Anthropic API + Telegram
- ⚡ I ship with AI, but architect like I have to maintain it for years

---

## 🛠 Core Stack

### Java Ecosystem
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)

### Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_7-DD0031?style=for-the-badge&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

### Infrastructure & Testing
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Also Ship In
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

---

## 🤖 AI & Tooling

> I treat AI as infrastructure, not a shortcut. Here's what's in the stack:

| Layer | Tool |
|---|---|
| **LLM APIs** | Anthropic Claude API · OpenRouter (Gemini, GPT) |
| **Local Inference** | LM Studio · Qwen3-Coder 80B on RTX 3060 12GB |
| **Agent Tooling** | MCP stack: filesystem, Git, PostgreSQL, Playwright, shell, Qdrant |
| **Editor** | Zed + MCP integration — AI-native dev environment |
| **AI in prod** | Klawa (Claude) · PMTS (Claude regime classification) · java-interwiew-tinder (OpenRouter) |

---

## 📌 Featured Projects

### 🧠 [Klawa AI Assistant](https://github.com/CHIKOJgg/klawa)
> Spring Boot · Anthropic Claude API · Telegram · PostgreSQL · JWT · Spring Modulith

Personal AI assistant with a production-grade backend. JWT auth with refresh-token rotation, conversation history persistence, Flyway migrations, Spring Modulith architecture. Fully Dockerized with GitHub Actions CI.

---

### 📈 [PMTS — Prediction Market Trading System](https://github.com/CHIKOJgg/pmts)
> Python · aiohttp · PostgreSQL · Redis · Anthropic Claude API · Docker

Automated trading system for binary prediction markets (Polymarket + Opinion Markets). Runs two concurrent strategies: **cross-venue arbitrage** (locks spread when the same event is mispriced across two exchanges) and **Stoikov delta-neutral market making** (earns the bid-ask spread while managing inventory skew). Built-in **AI signal enricher** uses Claude to classify market regime — stable / trending / volatile / thin — and adjusts edge thresholds in real time with a 200ms timeout fallback to heuristics. Ships with a 12-check synchronous risk gate (drawdown kill switch, per-market exposure caps, delta limits) and a realistic backtest engine with Beta fill distributions and sqrt-impact slippage.

---

### 🃏 [Java Interview Tinder](https://github.com/CHIKOJgg/java-interwiew-tinder) · [↗ Live](https://java-interwiew-tinder.vercel.app)
> React 18 · Vite · Node.js · Express · PostgreSQL · OpenRouter API · Telegram Mini App

Tinder-style Telegram Mini App for Java interview prep. Swipe right — you know it, swipe left — get an AI explanation via OpenRouter. Progress is tracked per user, AI answers are cached in PostgreSQL to save tokens. Features flip-card animations, category color coding, and a Zustand state store. Deployed on Vercel with a Railway backend.

---

### 📊 [Markowitz Crypto Portfolio Optimizer](https://github.com/CHIKOJgg/MarkowitzModel-java-crypto-analysis-)
> Java 21 · JavaFX · Maven · ojalgo · Material Design 3

Desktop application that fetches real crypto market data and calculates efficient portfolios using the Markowitz model. Features a full statistical forecast engine with confidence intervals, portfolio weight normalization, and a Material Design 3 UI.

---

### 💱 [Trading Platform](https://github.com/CHIKOJgg/spring-boot-trading)
> Spring Boot 3.2 · Java 21 · PostgreSQL · Redis · WebSocket (STOMP) · JWT · Flyway

Full-stack trading system for banking operations and exchange transactions. Real-time order flow over WebSocket, JWT + refresh-token auth, Redis caching, Flyway migrations. One `docker compose up --build` to run.

---

### 🎰 [Ultra Casino](https://github.com/CHIKOJgg/Ultra-casino) · ⭐ 3
> Python · JavaScript · Telegram WebApp · WebSocket

Fully functional crypto casino as a Telegram WebApp. 5 games (Crash, Mines, Dice, Coinflip, Roulette), Provably Fair system, real-time WebSocket chat, VIP tier with rakeback, progressive jackpot, and admin panel.

---

### ⚙️ [Matching Engine](https://github.com/CHIKOJgg/matching-engine)
> Spring Boot · Spring Data JPA · PostgreSQL · JUnit 5

Clean REST API with full CRUD, DTO mapping, validation, pagination, and layered architecture. Solid integration test coverage.

---

## 📊 GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=CHIKOJgg&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&count_private=true" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CHIKOJgg&layout=compact&theme=github_dark&hide_border=true" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=CHIKOJgg&theme=github-dark-blue&hide_border=true)](https://github.com/CHIKOJgg)

</div>

---

## 🏆 Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=CHIKOJgg&theme=onestar&no-frame=true&row=1&column=7)](https://github.com/CHIKOJgg)

</div>

---

## 📈 Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=CHIKOJgg&theme=github-compact&hide_border=true)](https://github.com/CHIKOJgg)

</div>

---

<div align="center">

*Open to backend roles · Minsk / Remote*  
**[LinkedIn](https://www.linkedin.com/in/miroslav-pisaryk-953490261) · [GitHub](https://github.com/CHIKOJgg)**

</div>
