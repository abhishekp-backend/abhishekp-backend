<h1 align="center">Hi 👋, I'm Abhishek Patil</h1>
<h3 align="center">Software Engineer | Backend & Distributed Systems</h3>

<p align="center">
  Final-year Computer Science Engineering student focused on building fault-tolerant infrastructure, high-concurrency APIs, and resilient distributed systems where data consistency and transactional safety matter.
</p>

<p align="center">
  <a href="https://linkedin.com/in/abhishek-patil-9a4331197" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.leetcode.com/patilabhishek2005" target="_blank"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:patilabhishek2005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### 🛠️ Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Java 21, C++, Python, JavaScript, SQL |
| **Backend** | Spring Boot, Node.js, Express.js |
| **Databases & Messaging** | PostgreSQL, Redis, RabbitMQ, MongoDB, pgvector |
| **Systems & Infrastructure** | Concurrency, Multithreading, Docker, Kubernetes, AWS |
| **Observability** | Prometheus, Grafana, Spring Boot Actuator |
| **Testing & Performance** | JUnit 5, Mockito, Apache JMeter, Postman |

---

### 📌 Featured Projects

#### 🔹 [distributed-job-queue](https://github.com/abhishekp-backend/distributed-job-queue)
*Java 21 · Spring Boot · PostgreSQL · Kubernetes · Prometheus · Grafana*  
A distributed job-processing system designed around reliable database-backed job claiming and concurrent workers.
* Uses PostgreSQL `SELECT ... FOR UPDATE SKIP LOCKED` for concurrent job claiming.
* Supports retries, delayed jobs, priority-based processing, and recovery of stale `RUNNING` jobs.
* Uses concurrent worker execution for parallel job processing.
* Exposes application and worker metrics through Prometheus with Grafana dashboards for monitoring system behavior.
* Load-tested with Apache JMeter to evaluate throughput and latency under concurrent requests.

#### 🔹 [search-engine](https://github.com/abhishekp-backend/search-engine)
*Java 21 · Spring Boot · PostgreSQL · pgvector · Redis · RabbitMQ*  
A search platform combining traditional keyword retrieval with semantic vector search.
* Crawls and indexes thousands of web documents.
* Implements TF-IDF-based keyword retrieval and generates vector embeddings for semantic search using `pgvector`.
* Uses Redis for caching frequently accessed search results and RabbitMQ for asynchronous processing.
* Designed toward hybrid keyword + semantic ranking.

---

### 🧠 Currently Focused On
* Distributed systems and reliability
* Java concurrency and JVM internals
* PostgreSQL internals and query optimization
* Backend performance, scalability, and cloud infrastructure

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=abhishekp-backend&theme=transparent&hide_border=true" alt="GitHub Streak" />
</p>
