
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

## 🛠 Core Features

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; margin: 3rem 0">
  <!-- Auth Card -->
  <div style="padding: 2rem; background: #f8f9fa; border-radius: 16px">
    <div style="display: flex; align-items: center; gap: 1rem; margin-bottom: 1rem">
      <img src="https://assets.website-files.com/6450b31696e25f8aa6cdd7b0/6450b31696e25f1d9dcdd8c7_Kindelogo.svg" 
           width="120" 
           alt="Kinde Logo"
           style="display: block; height: auto; max-width: 100%">
      <h3 style="margin: 0">Enterprise Auth</h3>
    </div>
    <p>Secure authentication with Kinde including SSO, RBAC, and audit logs</p>
  </div>

  <!-- Sync Card -->
  <div style="padding: 2rem; background: #f8f9fa; border-radius: 16px">
    <div style="display: flex; align-items: center; gap: 1rem; margin-bottom: 1rem">
      <img src="https://en.wikipedia.org/wiki/File:SWR_Logo_Orange.svg" 
           width="60" 
           alt="SWR Logo"
           style="display: block; height: auto; max-width: 100%">
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

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; margin: 3rem 0">
  <div style="text-align: center; padding: 1.5rem; background: #f8f9fa; border-radius: 12px; transition: transform 0.2s">
    <div style="margin: 0 auto; width: 120px; height: 120px; border-radius: 50%; overflow: hidden; border: 3px solid #0070f3">
      <img src="https://github.com/Nuu-maan.png" width="120" alt="Numan's Profile">
    </div>
    <h3 style="margin: 1rem 0">Numan</h3>
    <div style="display: flex; gap: 1rem; justify-content: center">
      <a href="https://github.com/Nuu-maan">
        <img src="https://img.shields.io/badge/Profile-181717?style=flat-square&logo=github">
      </a>
    </div>
  </div>

  <div style="text-align: center; padding: 1.5rem; background: #f8f9fa; border-radius: 12px; transition: transform 0.2s">
    <div style="margin: 0 auto; width: 120px; height: 120px; border-radius: 50%; overflow: hidden; border: 3px solid #00c7ff">
      <img src="https://github.com/anisvsc.png" width="120" alt="Anish's Profile">
    </div>
    <h3 style="margin: 1rem 0">Anish Gupta</h3>
    <div style="display: flex; gap: 1rem; justify-content: center">
      <a href="https://github.com/anisvsc">
        <img src="https://img.shields.io/badge/Profile-181717?style=flat-square&logo=github">
      </a>
    </div>
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
