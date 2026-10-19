# 🖐️ Hi, I'm Daria Yatsenko
**Python Backend Engineer | Fundamental CS & Math Background**

I am a software engineer specializing in **System Design, database optimization, and high-throughput asynchronous architectures**. With a strong foundation in Applied Mathematics and low-level software R&D (C++, Assembly), I possess a deep understanding of memory management, concurrency, and system performance. 

I take full ownership across the entire **SDLC** — from business requirements analysis and algorithmic design to bare-metal production deployment, security tuning, and automated infrastructure management.

<div align="center">
  <br>
  <img style="width: 200px; max-width: 90%;" alt="scheme-git" src="https://github.com/user-attachments/assets/44e0e7c0-6ced-454c-8283-c46c57235d42" />

  <br><i>Featured Project: Cost-Effective High-Performance Monolithic Architecture</i>
</div>

---

## 🛠️ Technical Stack

* **Backend & API:** Python (FastAPI, Flask, Asyncio, HTTPX), REST APIs, SQLAlchemy, Alembic, Pytest.
* **Databases & Caching:** PostgreSQL (Advanced relational modeling, complex M2M, Self-referencing tables, Indexing optimization), SQLite (WAL-mode local caching), Redis, Raw SQL.
* **Infrastructure & DevOps:** Linux (Bare-Metal, Bash scripting), Nginx Proxy, Gunicorn, Docker & Docker Compose, Kubernetes, CI/CD, SSL/TLS, Automated Backups.
* **CS Core & Low-Level:** Algorithms & Data Structures, Multithreading, C++, Assembly, Discrete Mathematics.
* **Frontend Integration:** Vanilla JS (ES6+), HTML5/CSS3 (BEM, Mobile-First), Performance & SEO optimization.

---

## 🔥 Featured Production Projects

### 🛒 1. High-Performance E-Commerce Platform | [Live Demo](https://oakaffection.ru) • [Repository](https://github.com/dashdash27/OakAffection)
*A conversion-centric, production-ready online store with a custom CMS and optimized automated logistics, deployed end-to-end as a cost-effective monolith.*
* **Engineering Challenges:** 
  * Designed a local geo-caching engine via **SQLite (WAL mode)** to map and store 80k+ delivery pickup points (ПВЗ) fetched dynamically via **DaData API**, reducing network latency to sub-millisecond local lookup speeds.
  * Injected localized async orchestration using `asyncio.gather` and **HTTPX** inside a synchronous framework, polling multiple external carrier APIs concurrently and cutting checkout response times by **300%**.
  * Shifted state management to `Local Storage` and synced cart data reactively across browser tabs using the **Broadcast Channel API**, slashing redundant backend traffic by **70%**.
* **Infrastructure:** Bare-metal deployment on Linux VPS with `Nginx` (reverse proxy & rate limiting), `Gunicorn`, and automated systemd/cron services.
* **Stack:** Flask, Asyncio, HTTPX, PostgreSQL, SQLite, Vanilla JS, Mobile-First CSS.

### 🧠 2. Knowledge Management System (Zettelkasten) | [Repository](https://github.com/dashdash27/Linkify)
*A specialized knowledge management application designed for complex non-linear data structuring and recursive data visualization.*
* **Engineering Challenges:** Developed a highly scalable relational data model featuring advanced **Many-to-Many** and **Self-Referencing (Self-Join)** database structures to represent infinite recursive note linking. Built an optimized interactive dashboard for graph-based knowledge analytics.
* **Stack:** Flask, PostgreSQL, SQLAlchemy, Jinja2 (Advanced Macros), JS / AJAX.

### 🏗️ 3. Real-Time Exchange Rate Monitor | [Repository](https://github.com/dashdash27/rate-tracking-system)
*A resilient, microservice-based financial data tracking application engineered for continuous high-frequency data ingestion.*
* **Engineering Challenges:** Implemented a containerized architecture with a strict fault-tolerance layer, custom error handling, and transactional state management to prevent data gaps during external financial API failures.
* **Stack:** Python, Docker & Docker Compose, PostgreSQL, Raw SQL integrations.

---

## 🎓 Education & Research Background

* **B.S. in Software Engineering & Math Administration (Honors Degree)**
* Deep understanding of low-level programming concepts (C++, Assembly), concurrency models, and complex algorithm optimization.

---

## 📫 Connect with me:
[LinkedIn](https://www.linkedin.com/in/daria-yatsenko-7819003b1/) • [Telegram](https://t.me/dasya_y) • dasshh27@gmail.com
