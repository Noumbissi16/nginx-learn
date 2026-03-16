# Node.js + Docker DevOps Project

> A minimal containerized Node.js application built as part of my DevOps learning journey.

---

## 📖 About Me

I'm **Noumbissi Stael**, a software developer currently learning **DevOps, Cloud Infrastructure and Distributed Systems**.

This project is a simple Node.js application that serves a static HTML file. The objective is to practice:

- Containerization and deployment using **Docker** and **nginx**
- Load balancing and automatic container scaling

This aligns with my DevOps learning path and my goal to build scalable systems through real-world projects.

---

## ⚙️ DevOps Stack

- **Node.js** — Backend runtime
- **Docker** — Containerization
- **nginx** — Reverse proxy & load balancing
- **Docker Compose** — Multi-container orchestration

---

## 🚀 Run the Application

### Run Locally

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the server:
   ```bash
   npm start
   ```

### Run with Docker

Build and start containers (replace `5` with your desired number of app instances):

```bash
docker compose up --build --scale app1=5
```

Then access the application at: [http://localhost](http://localhost)

---

## 🌐 Connect With Me

- **GitHub**: [github.com/Noumbissi16](https://github.com/Noumbissi16)
- **GitLab**: [gitlab.com/noumbissistael](https://gitlab.com/noumbissistael)
- **LinkedIn**: [Noumbissi Stael](https://www.linkedin.com/in/noumbissi-stael-910a48241/)
- **X / Twitter**: [@noumbissi_stael](https://x.com/noumbissi_stael)

---

© 2026 Noumbissi Stael — DevOps Learning Project