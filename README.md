<h1 align="center">Jithin P R</h1>

<p align="center">
  Full-stack and backend developer · TypeScript · Python · AI-powered applications
</p>

<p align="center">
  <a href="mailto:jithinpr888@gmail.com"><img alt="Email" src="https://img.shields.io/badge/jithinpr888%40gmail.com-1f2937?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

---

I build applications end to end: database schema and access rules, typed server code, and the interface on top.
My recent work covers a multi-tenant engineering platform with database-enforced authorization, an AI desktop
automation assistant, a civic incident-response system, and an IoT anomaly detector running an autoencoder on live sensor data.

## Technical skills

| Area | Technologies |
| --- | --- |
| **Languages** | TypeScript, JavaScript, Python, SQL, C, C++, HTML, CSS |
| **Frontend** | React, Next.js (App Router), Vite, Tailwind CSS, React Router, GSAP, Framer Motion, Leaflet, Chart.js, Recharts |
| **Backend and APIs** | Node.js, Express, Next.js Server Actions, FastAPI, Flask, REST, WebSocket, Zod |
| **Databases and cloud** | PostgreSQL, Supabase (Auth, Row Level Security, Vault), Firebase (Auth, Realtime Database), SQLite, Render, Vercel |
| **AI/ML and automation** | Gemini API, TensorFlow / Keras, PyTorch / TorchVision, Whisper, Playwright, Gmail API, tree-sitter, voice-agent design (Retell AI) |
| **Embedded and IoT** | ESP32, Arduino, MPU6050, serial and HTTP device communication |
| **Tools** | Git, GitHub, npm, Supabase CLI, ESLint, Jasmine |

## Featured projects

### [OneForAll](https://github.com/Jpr-2311/OneForAll) — engineering intelligence platform
**Problem:** requirements, tasks and code live in separate tools, so teams lose track of which code delivers which work.
OneForAll links an organization's teams, projects, requirements and tasks to the exact repository commits they ship,
and turns each snapshot into a searchable code-structure graph. Final-year project; my focus is the backend.

- Organization → department → team → project hierarchy with OWNER / ADMIN / MEMBER roles, enforced by PostgreSQL Row Level Security and covered by 13 SQL test suites
- Repository ingestion from a ZIP upload or a GitHub commit, with HMAC-SHA256-signed file manifests and automatic exclusion of credential files
- Symbol and relationship extraction with tree-sitter for TypeScript, JavaScript, Python and Java, shown as an interactive graph
- GitHub and Jira Cloud integrations; stored tokens are encrypted with AES-256-GCM on the server

`Next.js 16` `React 19` `TypeScript` `Supabase` `PostgreSQL` `Zod` `tree-sitter` `Tailwind CSS`

### [ARC Remote](https://github.com/Jpr-2311/ARC-REMOTE-DA) — AI desktop automation assistant
**Problem:** acting on your own computer while away from it. A paired phone or browser sends a natural-language job
to a desktop daemon, which runs it locally and streams progress back, asking for clarification or confirmation when needed.

- Pairing with a one-time 6-digit code, bearer-token auth, a command allowlist and an audit log
- Job pipeline: acknowledge → clarify / confirm → execute → verify → result, persisted to SQLite and streamed over WebSocket
- My work: the Windows control layer, the mobile client, intent routing, agents, and Gmail and email automation

`Python` `FastAPI` `WebSocket` `SQLite` `Gemini` `Playwright` `Whisper` `React` `Vite`

### [MediThread](https://github.com/Jpr-2311/YODHA-HACK) — healthcare records and prescription assistant · [live demo](https://medithread.onrender.com/login)
**Problem:** patients' records are scattered and hard to understand, and doctors lose consultation time to note-taking.
Patients upload prescriptions and lab reports; the app extracts them, explains them in English and Malayalam, checks
for drug interactions and danger signs, and sends Telegram dose reminders. Doctors get a voice console that drafts SOAP notes.

- Team project for the YODHA hackathon (Team FullSleeve); my contribution was the frontend UI redesign

`React 19` `Vite` `FastAPI` `PostgreSQL` `Redis` `Gemini` `Groq` `Docker`

### [CrisisIQ](https://github.com/Jpr-2311/Emergency) — civic incident reporting and emergency response · [live demo](https://crisisiq-frontend-233w.onrender.com/)
**Problem:** road-damage reports and emergencies reach authorities slowly and without priority.
Citizens report incidents with photos; officers, administrators and an emergency control center handle them in
role-based portals.

- Three services: React frontend, Express API gateway, FastAPI AI service
- Live incident map, hospital capacity view, notifications and a citizen leaderboard
- Operator copilot that answers questions over live Firebase data with Gemini

`React` `Vite` `Tailwind CSS` `Express` `FastAPI` `Firebase` `Gemini` `PyTorch` `Leaflet`

### [Edge Vibration Anomaly Detection](https://github.com/Jpr-2311/miniProjectNew)
**Problem:** abnormal vibration needs to be caught as it happens, not found in a log later.
An ESP32 with an MPU6050 accelerometer streams 3-axis data to a Flask service, where a Keras autoencoder scores each
100-sample window by reconstruction error.

- Live worker and supervisor dashboards with an audible alarm; the ESP32 drives a buzzer on alerts
- Full pipeline: baseline collection, training, and real-time detection

`ESP32` `Arduino C++` `Python` `Flask` `TensorFlow / Keras` `React` `Chart.js`

### [Loan-against-property voice agent](https://github.com/Jpr-2311/SalesAgents-AI-Assignment)
**Problem:** a qualification call must verify the customer, ask seven checks in order, and route every outcome correctly.
This project holds the system prompt, requirements, a state-machine design, seven test scenarios (including interruptions,
out-of-order answers and adversarial input) and the test results on Retell AI.

`Voice AI` `Prompt engineering` `State machines` `Retell AI`

## More projects

| Project | Description | Stack |
| --- | --- | --- |
| [ARC](https://github.com/Jpr-2311/ARC) | Landing page for the ARC assistant, with GSAP animations | React, Vite, GSAP, Framer Motion |
| [ssmp](https://github.com/Jpr-2311/ssmp) | SIC two-pass assembler, absolute loader and relocating loader | C |
| [Chinmaya-Hackthon](https://github.com/Jpr-2311/Chinmaya-Hackthon) | Hackathon prototype for citizen pothole reporting | React, Express, FastAPI |
| [momo](https://github.com/Jpr-2311/momo) · [demo](https://momo-wdl3.onrender.com/) | Chat app backed by the Gemini API | Express, Gemini, JavaScript |
| [finance](https://github.com/Jpr-2311/finance) | Finance dashboard: transactions, income and expenses, charts | React, Vite, Tailwind CSS, Chart.js |
| [Amazon_Clone](https://github.com/Jpr-2311/Amazon_Clone) · [demo](https://amazon-clone-lovat-eta.vercel.app) | Storefront with cart, checkout and order tracking, with Jasmine tests | JavaScript, HTML, CSS |
| [miniproject](https://github.com/Jpr-2311/miniproject) | First version of the anomaly-detection ML scripts | Python |
| [Cpp_practise](https://github.com/Jpr-2311/Cpp_practise) | C++ practice programs | C++ |
| [random-joke-generator](https://github.com/Jpr-2311/random-joke-generator) · [demo](https://random-joke-generator-plum.vercel.app) | Fetches jokes from a public REST API | JavaScript |
| [Movie_review](https://github.com/Jpr-2311/Movie_review) · [demo](https://movie-review-nine-black.vercel.app), [Time-Converter](https://github.com/Jpr-2311/Time-Converter) · [demo](https://time-converter-murex.vercel.app), [hotel-front-end](https://github.com/Jpr-2311/hotel-front-end), [rock-paper-scissors](https://github.com/Jpr-2311/rock-paper-scissors), [stone-paper-scissor](https://github.com/Jpr-2311/stone-paper-scissor) | Early front-end exercises | HTML, CSS, JavaScript |

## Hackathons

- **YODHA hackathon** — MediThread, with Team FullSleeve
- **Chinmaya hackathon** — idea-phase prototype for citizen pothole reporting

---

<p align="center">Open to software engineering roles and collaboration on full-stack or AI projects: <a href="mailto:jithinpr888@gmail.com">jithinpr888@gmail.com</a></p>
