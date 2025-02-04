<div align="center">
  <h1 style="margin: 2rem 0; font-size: 3rem; background: linear-gradient(45deg, #0070f3, #00c7ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
    🚀 Next.js Todo Enterprise
  </h1>
  
  <div style="display: flex; gap: 1rem; justify-content: center; margin-bottom: 3rem">
    <img src="https://img.shields.io/github/stars/Nuu-maan/todo-webapp?style=for-the-badge&logo=starship&color=gold&labelColor=000">
    <img src="https://img.shields.io/github/repo-size/Nuu-maan/todo-webapp?style=for-the-badge&logo=github&color=blue&labelColor=000">
    <img src="https://img.shields.io/github/license/Nuu-maan/todo-webapp?style=for-the-badge&logo=open-source-initiative&color=green&labelColor=000">
  </div>
</div>

---

## 🎯 Core Features

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; margin: 3rem 0">
  <div style="padding: 2rem; background: #1a1a1a; border-radius: 16px; border: 1px solid #2a2a2a">
    <div style="display: flex; align-items: center; gap: 1rem; margin-bottom: 1rem">
      <img src="https://www.kinde.com/static/logo-507d3a1f4e9e7c2a7d0d0a3e4e3a3d3a.svg" width="40">
      <h3 style="margin: 0">Enterprise Auth</h3>
    </div>
    <p>Secure authentication with Kinde including SSO, RBAC, and audit logs</p>
  </div>
  
  <div style="padding: 2rem; background: #1a1a1a; border-radius: 16px; border: 1px solid #2a2a2a">
    <div style="display: flex; align-items: center; gap: 1rem; margin-bottom: 1rem">
      <img src="https://swr.vercel.app/logo.svg" width="40">
      <h3 style="margin: 0">Real-time Sync</h3>
    </div>
    <p>Instant cross-device synchronization using SWR's stale-while-revalidate</p>
  </div>
</div>

---

## 🛠️ Installation Guide

### Requirements
- Node.js v18+
- PostgreSQL v15+
- Kinde Account

```bash
# Clone repository (SSH)
git clone git@github.com:Nuu-maan/todo-webapp.git

# Install dependencies
npm install

# Configure environment
cp .env.example .env.local

# Database setup
npx prisma migrate dev --name init

# Start development server
npm run dev
```

---

## 📈 System Architecture

```mermaid
graph TD
  A[Next.js Frontend] --> B[App Router]
  B --> C[API Routes]
  C --> D[Prisma ORM]
  D --> E[PostgreSQL]
  A --> F[Kinde Auth]
  F --> G[SSO/RBAC]
  A --> H[SWR]
  H --> I[Real-time Updates]
```

---

## 🌍 Live Demo

<div align="center" style="margin: 3rem 0">
  <a href="https://todo-webapp-demo.vercel.app">
    <img src="https://img.shields.io/badge/Explore_Live_Demo-FF6F00?style=for-the-badge&logo=vercel&logoColor=white">
  </a>
</div>

---

## 🤝 Contributors

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; margin: 3rem 0">
  <div style="text-align: center">
    <a href="https://github.com/Nuu-maan">
      <img src="https://avatars.githubusercontent.com/u/46296754?v=4" width="120" style="border-radius: 50%; border: 3px solid #0070f3">
      <h3>Numan</h3>
      <p>Core Architect</p>
    </a>
  </div>
  
  <div style="text-align: center">
    <a href="https://github.com/anisvsc">
      <img src="https://avatars.githubusercontent.com/u/47601396?v=4" width="120" style="border-radius: 50%; border: 3px solid #00c7ff">
      <h3>Anish Gupta</h3>
      <p>Fullstack Developer</p>
    </a>
  </div>
</div>

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

<div align="center" style="margin-top: 4rem; padding: 2rem; background: linear-gradient(45deg, #1a1a1a, #2a2a2a); border-radius: 16px">
  <h3>Support the Project</h3>
  <a href="https://github.com/Nuu-maan/todo-webapp">
    <img src="https://img.shields.io/badge/🌟_Star_Repository-FFD700?style=for-the-badge&logo=github&logoColor=black">
  </a>
</div>
