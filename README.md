<h1 align="center">Roshan Prabhu</h1>

<p align="center">
  <b>Applied AI agentic systems, and the robots I want to put them in next.</b>
</p>

<p align="center">
  <img alt="MComp Computer Science (AI), Sheffield" src="https://img.shields.io/badge/MComp_Computer_Science_(AI)-Sheffield-9B816B?style=for-the-badge">
  <img alt="Available June 2027" src="https://img.shields.io/badge/Placement-Available_June_2027-6DB33F?style=for-the-badge">
</p>

This summer I gave an agent 28 tools over a video editor, then made sure it could not put one frame into your video without you clicking.

What I actually want is one AI that knows enough about me to run the whole job. Nobody has built that yet, so I keep building pieces of it.

---

## What I build

### Deskmate

**The agent works the same editor you do, and the accept button is the one thing it cannot reach.**

`WebMCP` `React` `no backend` · [**Try it**](https://deskmate-cc.vercel.app) · [Code](https://github.com/Powahm/webmcp2026)

A creator's workstation in a browser tab: script, teleprompter, camera, editor. Seventeen tools read the page, eleven propose changes. I built the WebMCP layer and worked across the whole app, with one teammate.

<details>
<summary><b>The consent boundary, which is the part I would want to talk about</b></summary>

Every accept path refuses anything that is not a trusted user event, the same test the browser uses to tell a click from a script. So the agent can compose an animated title card, put a sound under it, reframe to 9:16 and list every hesitation in the take, in four calls, and still cannot put one frame into your video.

Nothing is uploaded and there is no backend, because the state that makes an agent useful here never leaves the page: which teleprompter line you are on mid-take, whether the camera is rolling, which words sit under the playhead.

</details>

### AI Star Arena

**You write a Python function to fly a spaceship, and then you are not allowed to touch it. Fly into the storm and that is your code's fault, not your reflexes.**

`Godot` `IBM Granite` `Ollama` `RAG` · [**Play it**](https://olbailey.itch.io/ai-star-arena) · [Demo](https://www.youtube.com/watch?v=BjCdVldTSDg)

Built for IBM. Your ship moves, fires and allocates its own power across engines, shields, scanners and weapons while a nebula storm closes in around the map. I was scrum lead and engineering lead for seven of us over three months, 200+ hours each. **IBM asked to reuse it for hackathons across universities.**

<details>
<summary><b>The assistant I built into the in-game editor</b></summary>

IBM Granite running locally through Ollama, RAG over our own ship API, guardrails on top. It answers from the real API surface instead of inventing methods that do not exist, and nothing leaves the machine. The game will even fetch Ollama and pull the model for you from its own settings page, so you never have to go and set anything up yourself.

</details>

### TrendSwipe

**The same swipe you already know, except instead of dates you get clothes, and at the end of it your cart is full.**

`Gemini` `Supabase` `Grafana` · [Code](https://github.com/Rifat-R/hacksheffield10)

Built in 24 hours at HackSheffield with a team of four, which I led. **It won the Grafana Labs Prize, top among 50 teams.** The dashboards the judges watched during our demo were fed live by the same Supabase stream the app was writing to.

### Ikiru

**A raccoon guards your screen time, and you have to negotiate with him for more.**

`Android` `co-founded`

Per-app guards, a global social block, a timer, app stats, widgets and a 3D raccoon. Five weeks from nothing to a working app in testers' hands.

### My second brain

**Every model I open reads the same file about me first.**

`Python` `React` `Notion` `Google Calendar`

The most complex thing I have built, made with Claude's help. It holds my live tasks and calendar, and an evidence bank that every factual claim has to trace back to before it can be written down.

<details>
<summary><b>Why there is an evidence bank in it</b></summary>

The problem I kept running into was models writing confident, wrong things about me. So nothing can be claimed in here unless it points at a sourced entry, and anything I have not backed up comes back flagged instead of quietly smoothed over.

Every claim on this page traces to one of those entries.

</details>

---

## A few other things

- I led seven people on a Java Spring Boot codebase, with role based access control, a full testing pyramid and PR review on everything.
- I got a model reading word-search puzzles out of photographs to 98.7% letter accuracy on clean data, using PCA and a weighted KNN at K=13. I benchmarked a CNN against it and did not use it, because PCA and KNN held up better under noise and ran in real time.
- 40+ postgraduates turned up to CompSoc's icebreaker, which I ran in second year. I made it a mini hackathon instead of the usual name badges and people actually talked to each other.
- Awards so far: the Grafana Labs Prize, and Most Innovative Committee Member at Sheff Tech, which I was not expecting.

---

## What I'm into

Applied agentic systems are the job I want. Give a model real tools over real software and see how much of the work it can take off you. Robotics is where I want to go next. Everything I build stops at the edge of a screen right now, and I would like it to stop doing that.

The longer version is a personal AI that knows your context, your deadlines and how you write, so you are not re-explaining yourself to a fresh chat window every morning. The second brain above is my first proper attempt at it. Ikiru comes from the same place, software that gives you your attention back instead of farming it. Long term I think the interesting version is a companion, something that sticks around for years and gets better at you.

I also take photographs.

---

## Away from the keyboard

President of the Computer Science Society at Sheffield. Before that, technical events coordinator, where I ran five workshops on prompt engineering, GitHub, Docker, R and hackathon prep, with every exercise written from scratch rather than borrowed. Currently rebuilding the society site around a resource repository that future cohorts contribute to.

---

## Stack

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)
[![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB)](#)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=fff)](#)
[![Flask](https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff)](#)
[![SQL](https://img.shields.io/badge/SQL-%2307405e.svg?logo=postgresql&logoColor=white)](#)
[![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=fff)](#)

[![Ollama](https://img.shields.io/badge/Ollama-000?logo=ollama&logoColor=fff)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)](#)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=fff)](#)
[![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=fff)](#)
[![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=fff)](#)
[![Godot](https://img.shields.io/badge/Godot-%23FFFFFF.svg?logo=godot-engine)](#)

---

<p align="center">
  <a href="https://www.linkedin.com/in/roshan-prabhu/"><img alt="LinkedIn" src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff"></a>
  <a href="https://rosh.prabz.org"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-000?logo=vercel&logoColor=fff"></a>
  <a href="https://www.instagram.com/_powah_/"><img alt="Photography" src="https://img.shields.io/badge/Photography-%23E4405F.svg?logo=Instagram&logoColor=white"></a>
</p>

<p align="center">
  Looking for a 2027 placement year, available from June 2027.<br>
  If you are building agent tooling and want someone who has shipped it, get in touch.
</p>
