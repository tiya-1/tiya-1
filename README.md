<!-- Paste this whole file into README.md of your public repo named exactly: tiya-1 -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:3b3fd8,100:7a3bd8&height=230&section=header&text=Tiya%20Jain&fontSize=64&fontColor=ffffff&fontAlignY=42&animation=twinkling&desc=I%20build%20backends%2C%20real-time%20systems%20and%20AI-powered%20apps&descSize=18&descAlignY=66" alt="Tiya Jain" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=2600&pause=1000&color=FFB86B&center=true&vCenter=true&width=640&height=30&lines=%2F%2F+30%2B+REST+APIs+shipped+with+NestJS+%2B+PostgreSQL;%2F%2F+SyncRoom%3A+video+rooms+kept+in+sync+over+WebSockets;%2F%2F+LLM+APIs+wired+into+real+products;%2F%2F+open+to+software+development+roles" alt="What I'm working on" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-Live_site-8B9BFF?style=for-the-badge&logo=vercel&logoColor=black)](https://tiya-portfolio-flame.vercel.app/)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tiya-jain-435467362)

**Jump to:** [About](#about) · [Projects](#projects) · [Skills](#skills) · [Internship](#internship) · [Contact](https://tiya-portfolio-e8ojm7pis-tiya-1s-projects.vercel.app/#contact)

</div>

> [!TIP]
> **Open to software development roles.** On [my portfolio](https://tiya-portfolio-e8ojm7pis-tiya-1s-projects.vercel.app/), press **Ctrl K** (⌘K on Mac) to jump anywhere, or drag the 3D tech sphere around.

---

<a name="about"></a>
## 👩‍💻 About me

```ts
// profile.ts
export const tiya = {
  role:       "Software Developer",
  studying:   "B.Tech CSE · IMS Engineering College · 2023–2027 · CGPA 8.5/10",
  shipped:    "30+ production REST APIs during a backend internship",
  building:   "SyncRoom, real-time synchronized watch rooms",
  hackathons: ["Hacknovate 7.0 finalist", "NexGen Hack finalist"],
  caresAbout: ["clean architecture", "secure APIs (JWT + RBAC)", "products that feel good to use"],
  status:     "open to software development roles",
} as const;
```

I'm a final-year Computer Science student who likes building software end to end: MERN products, NestJS and PostgreSQL backends, and applications powered by LLM APIs.

---

<a name="projects"></a>
## 🚀 Projects

*Click a project to open it.*

<details open>
<summary><b>🎬 SyncRoom</b> &nbsp;·&nbsp; watch YouTube together, perfectly in sync</summary>
<br/>

Create or join a room and watch together in real time. Play, pause, seek and the current video stay synchronized for everyone, and **every protected action is validated on the server before it is broadcast**.

`MongoDB` `Express` `React` `Node.js` `JavaScript` `WebSockets` `YouTube IFrame API`

**How it works**

```text
  Host or Moderator
        │  play · pause · seek · change video
        ▼
  ┌──────────────────┐   role not allowed
  │ WebSocket server │ ─────────────────────▶ rejected, nothing broadcast
  └──────────────────┘
        │ role allowed
        ▼ broadcast to the room
  ┌─────────┬─────────┬─────────┐
  │ User A  │ User B  │ User C  │  ──▶  every player syncs
  └─────────┴─────────┴─────────┘
```

- ✅ Room-based watching
- ✅ Real-time play / pause / seek / video sync
- ✅ Host, Moderator and Participant roles
- ✅ Permissions enforced by the backend, not just hidden in the UI

[![Code](https://img.shields.io/badge/View_code-181717?style=for-the-badge&logo=github)](https://github.com/tiya-1/watch-party)

</details>

<details>
<summary><b>🤖 AI Spend Audit Platform</b> &nbsp;·&nbsp; find where software and cloud money is wasted</summary>
<br/>

An AI-powered platform that analyses cloud and software spend and generates cost-optimization recommendations. It uses LLM APIs with fallback mechanisms, responsive dashboards and a CI/CD pipeline.

`Next.js` `React` `TypeScript` `Tailwind CSS` `LLM APIs` `GitHub Actions` `Vercel`

**How it works**

```text
  Spend data ──▶ LLM analysis ──▶ Recommendations ──▶ Dashboard
                      │
                      └── if the model call fails ──▶ fallback mechanism
```

[![Live demo](https://img.shields.io/badge/Live_demo-8B9BFF?style=for-the-badge&logo=vercel&logoColor=black)](https://ai-spend-audit-rho-one.vercel.app/)
&nbsp;
[![Code](https://img.shields.io/badge/View_code-181717?style=for-the-badge&logo=github)](https://github.com/tiya-1/ai-spend-audit)

</details>

<details>
<summary><b>🧭 Path Finder</b> &nbsp;·&nbsp; a career learning platform</summary>
<br/>

A full-stack platform with secure JWT authentication, protected routes, course management and learning-progress tracking. It runs as separate frontend, backend and database services with **Docker Compose**.

`MongoDB` `Express` `React` `Node.js` `JWT` `Docker Compose`

**How it works**

```text
  ┌────────────┐      ┌────────────┐      ┌────────────┐
  │  Frontend  │ ───▶ │  Backend   │ ───▶ │  MongoDB   │
  │ container  │      │ container  │      │ container  │
  └────────────┘      └────────────┘      └────────────┘
              all three run with Docker Compose
```

[![Code](https://img.shields.io/badge/View_code-181717?style=for-the-badge&logo=github)](https://github.com/tiya-1/Career-Reality-Engine)

</details>

---

<a name="skills"></a>
## 🛠️ Tech skills

| Layer | Tools |
| :-- | :-- |
| **Languages** | <img src="https://skillicons.dev/icons?i=js,ts,java" alt="JavaScript, TypeScript, Java" align="center" /> &nbsp;+ SQL |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css" alt="React, Next.js, Tailwind CSS, HTML, CSS" align="center" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express,nestjs" alt="Node.js, Express, NestJS" align="center" /> &nbsp;+ REST APIs, JWT, RBAC, WebSockets |
| **Databases** | <img src="https://skillicons.dev/icons?i=mongodb,postgres,firebase" alt="MongoDB, PostgreSQL, Firebase" align="center" /> |
| **DevOps and tools** | <img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,postman,vercel" alt="Docker, Git, GitHub, GitHub Actions, Postman, Vercel" align="center" /> |
| **AI** | LLM API integration · Prompt engineering · AI application development |
| **Core CS** | Data structures and algorithms · OOP · DBMS · Operating systems · Computer networks |

---

<a name="internship"></a>
## 💼 Internship

<details open>
<summary><b>Backend Development Intern</b> &nbsp;·&nbsp; Digixito Media Pvt. Ltd., Noida &nbsp;·&nbsp; June–July 2026</summary>
<br/>

**IAIRE Community Platform**, a multi-school platform connecting students to innovation, research and patent-support resources.

- Built **30+ production-grade REST APIs**
- Implemented **JWT authentication** and **role-based access control (RBAC)** across multiple user roles
- Optimized PostgreSQL queries and a modular backend architecture using **TypeORM**
- Worked in Git-based workflows on a **monorepo**

`NestJS` `TypeScript` `PostgreSQL` `TypeORM` `JWT` `RBAC` `Monorepo`

**How a request flows**

```text
  Client ──▶ Controller ──▶ Service ──▶ TypeORM ──▶ PostgreSQL
```

</details>

---

<div align="center">

**Want to see how it all fits together?**

[**Open the portfolio →**](https://tiya-portfolio-e8ojm7pis-tiya-1s-projects.vercel.app/)

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:3b3fd8,100:7a3bd8&height=90&section=footer" alt="" />

</div>
