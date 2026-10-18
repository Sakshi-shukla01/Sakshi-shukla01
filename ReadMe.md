<div align="center" id="top">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,100:A855F7&height=160&section=header&text=Sakshi%20Shukla&fontSize=46&fontColor=ffffff&fontAlignY=35&desc=Full-Stack%20%26%20AI%20Engineer&descAlignY=58&descSize=18"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Final-Year+CS+Undergrad+%40+Bharati+Vidyapeeth%2C+Pune;Research+Intern+%40+ARDE%2C+DRDO;Open+to+2027+SDE+%2F+AI+Engineer+roles" alt="Typing SVG"/>

<p>
<a href="https://linkedin.com/in/sakshishukla1008"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:sakshishukla1008@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://x.com/sakshi_shukla80"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=Sakshi-shukla01&style=flat-square&color=6366f1&label=Profile+views"/>
</p>

</div>

## 👋 About Me

- 🎓 B.Tech CSE at **Bharati Vidyapeeth COE, Pune** (2023 – 2027) · CGPA **9.67**
- 🔬 Research Intern at **ARDE, DRDO**
- 🌱 **GSSoC** contributor · 4 PRs merged
- 📚 Currently exploring **LLMs, LangChain & RAG**
- 📩 Open to **2027 SDE / AI Engineer** roles — [sakshishukla1008@gmail.com](mailto:sakshishukla1008@gmail.com)

## 💼 Experience

<details>
<summary>🔬 <b>Research Intern (CSE)</b> · ARDE, DRDO · <code>Jul 2026 – Present</code></summary>
<br/>

Paid research internship supporting technical research problems in a mentorship-driven government research program.

</details>

<details>
<summary>💻 <b>Full Stack Developer Intern</b> · Uptoskill · <code>Mar 2026 – May 2026</code></summary>
<br/>

- Built REST APIs (**Node.js, Express, PostgreSQL**) for an AI-powered LMS.
- Contributed to a **FastAPI** microservice with **JWT** and **Firebase OAuth**.

</details>

<details>
<summary>🌱 <b>Open Source Contributor</b> · GirlScript Summer of Code · <code>Apr 2026 – Jun 2026</code></summary>
<br/>

- Merged **4 PRs**, including a **Docker startup race-condition fix** and a `BackToTop` component.
- [View merged PRs →](https://github.com/pulls?q=is%3Apr+author%3ASakshi-shukla01+is%3Amerged)

</details>

## 📌 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| 🎧 [**SoundGuard**](https://github.com/Sakshi-shukla01/soundguard) | Detects and classifies machine faults from live audio in real time | PyTorch · FastAPI · WebSocket · React |
| ⚡ [**Grid Fault RCA Agent**](https://github.com/Sakshi-shukla01/grid-fault-agent) | RL environment + agent that localizes power-grid faults · [Live API](https://sakshi898-grid-fault-agent1.hf.space/docs) | FastAPI · MongoDB · Docker · K8s |
| 🎬 [**QuickShow**](https://github.com/Sakshi-shukla01/ticket-movie) | Movie ticket booking with race-free seat reservation and payments | React · Node.js · Redis · Stripe |

<details>
<summary><b>🔍 How they work (click to expand)</b></summary>
<br/>

**🎧 SoundGuard** — Audio is converted to mel-spectrograms; an autoencoder trained on normal sounds flags anomalies, and a CNN classifies the fault type. Streams live from the mic over WebSocket to a React dashboard.

**⚡ Grid Fault RCA Agent** — An OpenEnv-style `reset` / `step` environment with 3 difficulty tiers, deployed on Docker + Kubernetes and monitored with Prometheus + Grafana.

**🎬 QuickShow** — Seat holds use atomic Redis operations so two users can never book the same seat. Covered by 11 Jest/Supertest tests, with Stripe webhooks, Inngest jobs and Clerk auth.

</details>

## 🐞 Quick Challenge

**Two users click the last seat at the exact same millisecond. Both see it as free. What breaks?**

<details>
<summary><b>💡 Reveal answer</b></summary>
<br/>

A **check-then-act race condition** — the check and the booking are separate steps, so both slip through and the seat is sold twice. The fix: make the seat hold a single **atomic Redis operation**, so only one request wins. That's exactly what I did in [QuickShow](https://github.com/Sakshi-shukla01/ticket-movie).

</details>

## 🛠️ Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=py,java,js,ts,fastapi,nodejs,express,react,nextjs,tailwind,postgres,mongodb,redis,docker,kubernetes,aws,pytorch,jest&perline=9"/>
</p>

## 🏆 Achievements & Certifications

- 🥇 **Smart India Hackathon** — heritage tourism platform · [certificate](https://drive.google.com/file/d/1pmrNRFLxXOyRUCfudqhxgn7WI4o8a4of/view)
- 🧠 **Tata Crucible Quiz** — cleared national prelims · [certificate](https://drive.google.com/file/d/1uqCCD4jPy9BTCFwUJeuC7b8tD_nbx5en/view)
- 🚀 **Young Turks, Naukri** — talent recognition · [certificate](https://drive.google.com/file/d/1Wv5oQ2gnqLdabfNOnjmlh2j9IUnkUdYj/view)
- 📜 Oracle **OCI Gen AI Professional** · OCI Foundations · NPTEL Cloud Computing & DBMS

## 📊 GitHub Activity

<div align="center">
<img src="https://streak-stats.demolab.com/?user=Sakshi-shukla01&theme=tokyonight&hide_border=true&background=0D1117&ring=6366F1&fire=A855F7&currStreakLabel=6366F1" width="70%"/>
</div>

---

<div align="center">

<a href="https://github.com/Sakshi-shukla01/Sakshi-shukla01/issues/new?title=%F0%9F%91%8B%20Hello%20from%20...&labels=guestbook"><img src="https://img.shields.io/badge/✍️_Sign_the_guestbook-6366F1?style=for-the-badge"/></a>
<a href="mailto:sakshishukla1008@gmail.com?subject=Opportunity%20for%20Sakshi%20Shukla"><img src="https://img.shields.io/badge/📩_Hiring%3F_Email_me-A855F7?style=for-the-badge"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:A855F7,100:6366F1&height=90&section=footer"/>
