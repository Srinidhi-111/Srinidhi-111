<div align="center">

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/command-center.svg" width="100%" alt="Srinidhi R — deep space developer command center" />

<br/>

<a href="https://www.linkedin.com/in/srinidhi-rajesh-kanna-b39150339/">
  <img src="https://img.shields.io/badge/LINKEDIN-OPEN%20CHANNEL-06152B?style=for-the-badge&logo=linkedin&logoColor=22D3EE&labelColor=030712&color=0B2545" alt="LinkedIn" />
</a>
<a href="mailto:srinidhir.cs24@bitsathy.ac.in">
  <img src="https://img.shields.io/badge/EMAIL-SEND%20SIGNAL-06152B?style=for-the-badge&logo=gmail&logoColor=F472B6&labelColor=030712&color=0B2545" alt="Email" />
</a>
<a href="https://github.com/Srinidhi-111">
  <img src="https://img.shields.io/badge/GITHUB-ENTER%20PROFILE-06152B?style=for-the-badge&logo=github&logoColor=EAF7FF&labelColor=030712&color=0B2545" alt="GitHub" />
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=21&duration=2400&pause=800&color=22D3EE&center=true&vCenter=true&width=900&lines=INITIALIZING+DEVELOPER+PROFILE...;FULL-STACK+SYSTEMS+%7C+REAL-TIME+ANALYTICS+%7C+APPLIED+AI;I+BUILD+SOFTWARE+THAT+OBSERVES%2C+UNDERSTANDS%2C+AND+RESPONDS.;WELCOME+TO+THE+SRINIDHI+R+COMMAND+CENTER." alt="Animated developer introduction" />

</div>

<br/>

```text
┌──────────────────────────────────────────────────────────────────────────────┐
│  SIGNAL RECEIVED                                                              │
│  Identity      : Srinidhi R                                                   │
│  Coordinates   : Coimbatore, Tamil Nadu, India                                │
│  Program       : B.E. Computer Science and Engineering                        │
│  Specialization: Full-Stack Systems -  Backend Engineering -  Applied AI        │
│  Status        : Building systems that turn human behavior into useful data   │
└──────────────────────────────────────────────────────────────────────────────┘
```

I am a Computer Science and Engineering student building **full-stack, real-time, AI-enabled software systems**. I enjoy the complete engineering journey: identifying a real problem, designing an experience, building the backend, modeling data, integrating APIs, deploying the system, and documenting it clearly.

My current orbit includes **React, TypeScript, FastAPI, Python, PostgreSQL, WebSockets, cloud deployment, analytics platforms, NLP, and AI-assisted products**.

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/orbit-divider.svg" width="100%" alt="Cosmic orbit divider" />

## Mission control

<div align="center">

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/mission-map.svg" width="100%" alt="Constellation map of Srinidhi's engineering focus areas" />

</div>

<br/>

| System | Mission | Core Signal |
|---|---|---|
| **Full-Stack Engineering** | Build responsive interfaces connected to reliable backend systems | React, TypeScript, FastAPI, REST APIs |
| **Real-Time Analytics** | Transform raw interaction events into live, actionable product insight | WebSockets, PostgreSQL, Event Pipelines |
| **Applied AI** | Use AI where it adds practical value—not just as a label | NLP, LLM APIs, scikit-learn |
| **Cloud and Deployment** | Ship systems that are accessible, observable, and usable | Vercel, Render, Firebase, Cloud Platforms |
| **Human-Centered Design** | Build for real people, real constraints, and real outcomes | UX Analytics, UI/UX, Product Thinking |

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/orbit-divider.svg" width="100%" alt="Cosmic orbit divider" />

## Featured missions

### `MISSION_01` — UX Session Replay Analytics

> **A real-time UX intelligence platform that reveals not only what users do, but where they struggle and why.**

**Mission capabilities**

- Records and replays user interaction sessions using `rrweb`
- Detects rage clicks in real time with a sliding-window algorithm
- Streams live updates to the dashboard through `WebSockets`
- Provides replay timelines, click-density heatmaps, session health, alerts, and core metrics
- Uses a scalable event pipeline: client SDK → FastAPI ingestion → PostgreSQL → real-time analytics portal
- Uses `navigator.sendBeacon` for resilient event delivery, list virtualization for scale, and a Web Worker to protect UI responsiveness

**System stack**

```text
React -  TypeScript -  Vite -  Tailwind CSS -  FastAPI -  PostgreSQL - 
WebSockets -  rrweb -  rrweb-player -  Vitest -  Vercel -  Render
```

<div align="center">

[ LIVE PORTAL ](https://ux-session-replay-analytics.vercel.app) &nbsp;•&nbsp;
[ BACKEND API ](https://ux-portal-backend.onrender.com/docs) &nbsp;•&nbsp;
[ SOURCE CODE ](https://github.com/Srinidhi-111/UX-Session-Replay-Analytics)

</div>

---

### `MISSION_02` — StreetGuard

> **A parametric income-protection prototype for gig delivery workers affected by weather and city-level disruptions.**

**Mission capabilities**

- Models zone-based disruption triggers for weather, heat, air quality, and operational downtime
- Designs automated policy, eligibility, claim-initiation, and payout workflows
- Uses worker personas and local disruption patterns to shape product requirements
- Integrates a full-stack architecture using React, FastAPI, Firebase, external data APIs, and sandbox payment workflows
- Explores transparent premium calculation and claim-risk checks for a parametric-insurance model

**System stack**

```text
React -  Tailwind CSS -  FastAPI -  Python -  Firebase -  OpenWeatherMap - 
WAQI -  Razorpay Test Mode -  scikit-learn -  Vercel -  Railway
```

> **Prototype notice:** StreetGuard was created as a hackathon MVP. Production insurance underwriting, regulated policy issuance, and real payouts are outside the prototype scope. Test/simulated integrations are clearly separated from production claims and payments.

<div align="center">

[ SOURCE CODE ](https://github.com/Srinidhi-111/streetguard) &nbsp;•&nbsp;
[ PITCH DECK ](https://docs.google.com/presentation/d/1v2v14qv_H5xEEdcNhWL0Ht9p7J6llaco/edit?usp=sharing&ouid=118022404412997280067&rtpof=true&sd=true)

</div>

---

### `MISSION_03` — Meiyaa

> **A code-mixed Tamil-English scam and misinformation detector designed for the way people actually communicate.**

**Mission capabilities**

- Evaluates Tamil script, Tanglish, and English WhatsApp/SMS-style messages
- Produces a risk score, flagged signals, and a human-readable explanation
- Focuses on explainable outputs rather than an unexplained classification label
- Covers job scams, fake loans, OTP phishing, health misinformation, and lottery fraud
- Uses privacy-conscious curated examples derived from public advisories—not private messages

**System stack**

```text
Python -  FastAPI -  React -  Vite -  sentence-transformers -  NLP -  JSON
```

<div align="center">

[ SOURCE CODE ](https://github.com/Srinidhi-111/OpenHack26)

</div>

---

### `MISSION_04` — AI Stock Market Bot

> **A Python dashboard for market-data exploration and AI-assisted analysis.**

**Mission capabilities**

- Retrieves historical market data and displays interactive trends
- Computes market metrics using Pandas
- Visualizes price movements with Plotly
- Uses a Groq-powered LLM workflow for AI-assisted market summaries
- Includes validation and error handling for unavailable data or invalid symbols

**System stack**

```text
Python -  Streamlit -  Groq API -  yfinance -  Pandas -  Plotly
```

> Educational analysis project only. It does not provide financial advice.

<div align="center">

[ SOURCE CODE — COMING SOON ](#)

</div>

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/orbit-divider.svg" width="100%" alt="Cosmic orbit divider" />

## Systems I work with

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,c,js,ts,html,css,sql&theme=dark&perline=8" alt="Programming languages" />
<br/><br/>
<img src="https://skillicons.dev/icons?i=react,fastapi,firebase,postgres,git,github,tailwind,vite&theme=dark&perline=8" alt="Full stack and backend tools" />
<br/><br/>
<img src="https://skillicons.dev/icons?i=azure,gcp,vercel,figma,vscode&theme=dark&perline=8" alt="Cloud deployment and design tools" />

</div>

<br/>

```yaml
primary_stack:
  frontend: [React, TypeScript, Tailwind_CSS, Vite]
  backend: [FastAPI, Python, REST_APIs, WebSockets]
  data: [PostgreSQL, Firebase, Event_Analytics]
  ai: [NLP, sentence-transformers, Groq_API, scikit-learn]
  deployment: [Vercel, Render, Railway, Azure, GCP]

operating_principles:
  - Build real systems, not only prototypes
  - Make technical decisions explainable
  - Respect privacy and security by design
  - Ship, test, measure, improve
```

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/orbit-divider.svg" width="100%" alt="Cosmic orbit divider" />

## Current trajectory

```text
[████████████████████░░] Full-stack architecture
[█████████████████░░░░░] Backend engineering and API design
[███████████████░░░░░░░] Data structures and algorithms
[████████████████░░░░░░] Cloud deployment and observability
[█████████████████░░░░░] Applied AI and NLP systems
[██████████████░░░░░░░░] Privacy-aware analytics engineering
```

```text
NEXT_TRANSMISSION:
→ Build more production-minded backend systems
→ Strengthen testing, observability, and deployment pipelines
→ Explore AI agents that solve measurable product problems
→ Collaborate on engineering teams that build for real users
```

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/transmission.svg" width="100%" alt="Animated final space transmission" />

## Contribution telemetry

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Srinidhi-111&show_icons=true&hide_border=true&bg_color=030712&title_color=22D3EE&icon_color=F472B6&text_color=EAF7FF&ring_color=7C3AED" alt="GitHub statistics" />

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Srinidhi-111&layout=compact&hide_border=true&bg_color=030712&title_color=22D3EE&text_color=EAF7FF" alt="Top languages" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Srinidhi-111&bg_color=030712&color=EAF7FF&line=7C3AED&point=22D3EE&area=true&hide_border=true" width="100%" alt="Contribution activity graph" />

</div>

## Final transmission

<div align="center">

```text
I do not just study technology.
I build with it, test it, document it, and turn it into systems people can use.
```

<img src="https://raw.githubusercontent.com/Srinidhi-111/Srinidhi-111/main/assets/command-center.svg" width="100%" alt="Srinidhi R command center footer" />

</div>
