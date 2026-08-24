<h1 align="center">Jaewon Choi &nbsp;·&nbsp; 최재원</h1>

<p align="center">
  <b>AI Native Product Manager</b><br/>
  I move the work people do by hand (marketing, GTM, reporting) into AI agents<br/>
  and prove it with products that ship.
</p>

<p align="center">
  <a href="https://jaewon-choi.vercel.app"><img src="https://img.shields.io/badge/Portfolio-%E2%86%92-0A0A0B?style=for-the-badge" alt="Portfolio"/></a>
  <a href="https://t.me/cobling"><img src="https://img.shields.io/badge/Telegram-%40cobling-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dune-FF6B4A?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Metabase-509EE3?style=for-the-badge&logo=metabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
</p>

---

### 👋 In short

Five years in Web3 as a BD / PM, running global go-to-market end to end. The questions that mattered most in that job kept coming back without a tool behind them. Is anyone finding us when they ask an AI? What does this market actually look like this week? Did the content land? Every time, the answer arrived as a deck somebody had assembled by hand the night before.

So I started building the answers instead. I'm not an engineer. I build a working version and put it in front of the people who have to decide, so we find out early instead of three months in.

Below: what came out of the GTM side of that, and what came out of the product side.

---

### 📈 Marketing & GTM

**🟢 [geo-probe](https://github.com/choiaewoooon/geo-probe)** &nbsp;·&nbsp; [live dashboard ↗](https://ai-visibility-monitor-psi.vercel.app)
Measures how discoverable a brand is *inside AI answers*, the GEO problem. Asks the category question your customer would ask, **never naming the brand**, repeats it n≥5 across ChatGPT · Gemini · Claude, then reports a mention rate and median rank instead of one lucky screenshot. Zero dependencies. &nbsp;`Node` `GEO` `measurement`

**[signal-to-story](https://github.com/choiaewoooon/signal-to-story)**
Market signal → short-form content pipeline. Script generation, capital-markets compliance review, and a human approval gate wired into one flow. Runs keyless through the local Claude CLI. &nbsp;`Python` `Claude` `HITL`

**[canton-telegram-bot](https://github.com/choiaewoooon/canton-telegram-bot)** &nbsp;·&nbsp; **[kospi-morning-bot](https://github.com/choiaewoooon/kospi-morning-bot)**
Daily community/report bots running unattended on launchd. The KOSPI bot grades its own morning calls against actual closing prices, every trading day, so I can see how often it was right. &nbsp;`Python` `LLM ops`

---

### 🛠 Products — public & live

**🟢 MarketMarket** &nbsp;·&nbsp; [live in production ↗](https://marketmarket.io/prediction/surebet)
A prediction-market arbitrage view. I wrote the feature spec and built the data tab on my own; the engineering team integrated it into the production service, where it runs today. &nbsp;`spec` `data` `0→1`

**🟢 [canton-hub](https://github.com/choiaewoooon/canton-hub)** &nbsp;·&nbsp; [live ↗](https://canton-hub.vercel.app)
Real-time dashboard for Canton Network. Collects scattered external sources on a schedule, serves them to the frontend over REST + SSE. &nbsp;`FastAPI` `Next.js`

**🟢 [polymarket-community-calendar](https://github.com/choiaewoooon/polymarket-community-calendar)** &nbsp;·&nbsp; [live ↗](https://polymarket-calender.vercel.app)
Polymarket prediction-market data, visualized as a calendar and timeline. &nbsp;`React` `TypeScript`

**🟢 Rock'n'Dead** &nbsp;·&nbsp; [play it ↗](https://rock-and-dead.vercel.app)
A pixel-art rhythm action game where you play guitar to cut down autotuned zombies. Three chapters, 23 charted songs, six bosses, every track original. I scoped it, designed the systems, directed the art, wrote the charts, and rebuilt them against friends' playtest notes. &nbsp;`TypeScript` `Canvas 2D` `Web Audio`

**[live-korean-subtitles](https://github.com/choiaewoooon/live-korean-subtitles)**
Chrome extension that turns English audio in any tab into live Korean subtitles: transcribe, translate, summarize, save as Markdown. Bring your own Gemini key. &nbsp;`JavaScript` `Gemini`

**[pasta-timer](https://github.com/choiaewoooon/pasta-timer)**
A pasta timer that shows you the sauce recipe while you wait. Ten noodle types, al dente presets, alerts at T-1 minute and at zero. I scoped it, designed it, and built it over a couple of weekends. &nbsp;`TypeScript` `PWA`

---

### 🤖 Agents & harness

**[claude-code-harness](https://github.com/choiaewoooon/claude-code-harness)**
A non-engineer's Claude Code harness, public edition: the docs → plugin → automation onboarding framework, a 3-model judge-panel scorer, and ops notes from running daily LLM bots. &nbsp;`Claude Code` `Python`

**[krx-ai-bot](https://github.com/choiaewoooon/krx-ai-bot)**
Event-driven autonomous trading daemon for KRX. Claude reads the market regime; rule-based risk limits do the gatekeeping. Paper-trading by default. &nbsp;`Python` `asyncio`

---

### 🧰 How I work

- Built **13 MarketMarket automation plugins on my own**, plus **19 skills and 11 agents**, inside my team's shared Claude Code harness. I ran the onboarding for it too. The public half lives in [claude-code-harness](https://github.com/choiaewoooon/claude-code-harness).
- Turn scattered data into **live dashboards**, not slide decks.
- Treat a marketing claim as a **measurement problem**. Run it enough times to be sure, write down the method, and report the zeros when there are zeros.
- Ship LLM and agentic workflows myself with **Claude Code**, far enough that someone else can use them.

---

<p align="center">
  No streak counters or commit graphs here — the live products above are the metric.
</p>
