<!-- Animated Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=220&section=header&text=Yashwant%20Badhe&fontSize=45&fontAlignY=35&animation=fadeIn" />
</p>

<h3 align="center">🚀 Backend Engineer | FastAPI | System Design Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=22&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&width=650&lines=Building+Scalable+Backend+Systems;FastAPI+%7C+Python+%7C+SQLAlchemy;Kafka+%7C+Redis+%7C+Microservices;Turning+Legacy+Code+into+Clean+Architecture" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yashwant-badhe-a34788235"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:yashwantbadhe68@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://instagram.com/yashwant_badhe_patil"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Yashwantbadhe2401&label=Profile+Views&color=36BCF7&style=flat" />
  <img src="https://img.shields.io/github/followers/Yashwantbadhe2401?label=Followers&style=social" />
</p>

---

## 💫 About Me

```yaml
currently_working_on: "Scalable backend systems for rider operations & analytics platforms"
tech_stack: "Python · FastAPI · SQLAlchemy"
learning: "System Design · Kafka · Redis · Microservices Architecture"
open_to_collaborate: "Backend APIs · Distributed systems · Open-source Python/FastAPI"
ask_me_about: "Python · FastAPI · REST APIs · SQL · Kafka basics · .NET → Python migrations"
fun_fact: "I love turning tangled legacy systems into clean, modern architectures 🚀"
```

---

## 🧠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,mysql,redis,kafka,docker,kubernetes,aws,nginx,git,github,linux,react,nodejs,javascript" />
</p>

<details>
<summary><b>✨ Full Tech Arsenal (click to expand)</b></summary>
<br>

| Category | Stack |
|---|---|
| **Languages** | Python, Java, C, C++, JavaScript |
| **Backend** | FastAPI, Express, Node.js |
| **Databases** | MySQL, PostgreSQL, MongoDB, SQL Server, Redis |
| **DevOps & Cloud** | Docker, Kubernetes, AWS, Jenkins, Nginx |
| **Frontend** | React, Angular, Next.js, HTML, CSS, Bootstrap |
| **Data & AI** | Pandas, NumPy, Matplotlib, TensorFlow, scikit-learn |
| **Tools** | Postman, Swagger, Jira, GitHub Actions, GitLab CI |

</details>

---

## 🚀 Featured Projects

<p align="center">
  <a href="https://github.com/Yashwantbadhe2401/FarmFusion">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Yashwantbadhe2401&repo=FarmFusion&theme=radical" />
  </a>
  <a href="https://github.com/Yashwantbadhe2401/mern-chat-app-master">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Yashwantbadhe2401&repo=mern-chat-app-master&theme=radical" />
  </a>
</p>

<p align="center"><i>More projects focus on scalable APIs, FastAPI microservices, SQL optimization & real-time systems</i></p>

<details>
<summary><b>🚖 Rider Operations & Analytics Platform</b></summary>
<br>

**Role:** Backend Engineer (Python / FastAPI)

**Problem:** Legacy synchronous APIs caused slow rider onboarding, tight coupling, and poor analytics scalability.

**Solution:**
- Designed FastAPI-based async APIs
- Introduced Kafka event-driven architecture
- Implemented Redis caching to reduce DB load
- Migrated legacy .NET components to Python

**Impact:**
- ⬆️ API response time improved by **~40%**
- ⬇️ DB read load reduced by **~50%** via caching
- 📊 Enabled real-time analytics & event replay

**Tech:** `Python` `FastAPI` `Kafka` `Redis` `SQL Server` `PostgreSQL` `Docker`

</details>

<details>
<summary><b>💬 Real-Time Chat & Notification System</b></summary>
<br>

**Role:** Backend Developer

- Built async WebSocket-based chat using Tornado / FastAPI
- Implemented background notifications via Kafka
- Designed scalable message persistence layer

**Key Skills:** Async IO, event streaming, real-time systems

</details>

<details>
<summary><b>🛒 Full-Stack E-Commerce Backend</b></summary>
<br>

**Role:** Backend & API Engineer

- Secure JWT-based authentication
- Cart, order, and payment workflows
- Role-based access (Admin / User / Vendor)

**Key Skills:** REST APIs, SQL optimization, authentication

</details>

---

## 🧩 System Design — Rider Operations (Event-Driven Architecture)

```text
┌──────────────┐
│ Rider / Web  │
│  Mobile App  │
└──────┬───────┘
       │ REST / JWT
┌──────▼───────┐
│  FastAPI     │  Async APIs
│  API Layer   │  Validation
└──────┬───────┘
       │ Events
┌──────▼───────┐
│    Kafka     │  Topics
│ Event Stream │  (rider, order,
└──────┬───────┘   analytics)
       │
┌──────▼──────────────┐
│  Consumer Services  │
│  (Async Workers)    │
└───┬───────────┬─────┘
    │           │
┌───▼───┐   ┌───▼─────────┐
│ Redis │   │  SQL DBs     │
│ Cache │   │ Ops + Reports│
└───────┘   └──────────────┘
       │
┌──────▼────────┐
│ Analytics &   │
│ Monitoring    │
│ (Dashboards)  │
└───────────────┘
```

<details>
<summary><b>🔍 What this diagram demonstrates</b></summary>
<br>

- Clear **request → event → processing → analytics** flow
- Non-blocking APIs using **FastAPI async**
- Loose coupling via **Kafka topics**
- **Redis** for hot data & performance
- **SQL databases** for transactional + reporting workloads

</details>

---

## ⚡ Performance & Scalability Snapshot

<details>
<summary><b>📊 Click to expand production-oriented metrics</b></summary>
<br>

> *Representative metrics based on real backend workloads & best practices*

**🚀 API Layer (FastAPI)**
| Metric | Value |
|---|---|
| Throughput | ~1,200–2,000 req/min per instance |
| Latency (P95) | 80–120 ms |
| Concurrency | Async endpoints with background tasks |
| Workers | Uvicorn + Gunicorn (4–8 workers/instance) |

**🧵 Kafka Event Processing**
| Metric | Value |
|---|---|
| Topics | rider-registration, order-status, delivery-events, analytics-events |
| Consumers | 3–6 per topic (horizontal scaling) |
| Processing Rate | ~5k–10k events/min |
| Failure Handling | Retry + DLQ pattern |
| Event Replay | Supported for analytics rebuilds |

**⚡ Redis Caching**
| Metric | Value |
|---|---|
| Use Cases | Hot rider data, order lookups, rate limiting |
| Cache Hit Ratio | ~85–92% |
| Latency | <5 ms |
| TTL Strategy | Dynamic (30s–5 min) |

**🗄️ Databases (SQL)**
| Metric | Value |
|---|---|
| Transactional DB | SQL Server / PostgreSQL |
| Query Optimization | Indexed queries + stored procedures |
| Avg Query Time | 10–40 ms |
| Analytics Queries | Async / read replicas |

**📈 Reliability & Scale**
- Uptime target: **99.9%**
- Observability: logs + metrics + dashboards
- Backpressure handling via Kafka consumer lag monitoring
- Stateless FastAPI services, horizontal scaling via containers
- Kubernetes-ready deployment

</details>

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Yashwantbadhe2401&show_icons=true&theme=radical" height="180"/>
  <img src="https://nirzak-streak-stats.vercel.app/?user=Yashwantbadhe2401&theme=radical" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yashwantbadhe2401&layout=compact&theme=radical" height="160"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Yashwantbadhe2401&theme=redical&hide_border=true" />
</p>

---

## 🏆 Achievements

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Yashwantbadhe2401&theme=radical&margin-w=12" />
</p>

---

## ✍️ Developer Wisdom

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" />
</p>

---

## 🎯 What I Bring to a Team

- Strong **system design & scalability thinking**
- Clean, maintainable backend architectures
- Experience modernizing legacy systems
- Ownership mindset from API → DB → deployment

> 📬 **Open to backend roles, freelance projects & system design challenges**

---

<p align="center">
  <img src="https://visitcount.itsvg.in/api?id=Yashwantbadhe2401&icon=2&color=12" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" />
</p>
