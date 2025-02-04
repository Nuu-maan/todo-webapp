<div align="center">

# 🚀 Next.js Todo Pro

[![GitHub Stars](https://img.shields.io/github/stars/Nuu-maan/todo-webapp?style=flat-square&logo=github&color=5865F2)](https://github.com/Nuu-maan/todo-webapp/stargazers)
[![License](https://img.shields.io/badge/license-MIT-97CA00?style=flat-square)](LICENSE)
[![Next.js](https://img.shields.io/badge/Next.js-14.0+-000?style=flat-square&logo=next.js)](https://nextjs.org/)

![Todo App Preview](https://i.pinimg.com/736x/0f/ed/9c/0fed9c050dba713078325dfb028ceeb5.jpg)

</div>

## ✨ Features

<div align="center">

| Core Functionality | Collaboration | Security |
|--------------------|---------------|----------|
| ✅ Task Management | 👥 Shared Workspaces | 🔐 OAuth 2.0 |
| 📅 Due Dates | 💬 Comments | 🔑 RBAC |
| 🏷️ Labels & Filters | 📊 Activity Feed | 🔒 Encryption |
| 🔄 Sync Across Devices | 📁 File Attachments | 📝 Audit Logs |

</div>

## 🏗 Architecture

```mermaid
graph TD
    A[Client Layer] --> B[Next.js App Router]
    B --> C[API Layer]
    C --> D[Service Layer]
    D --> E[Data Layer]
    
    subgraph "Frontend"
    A --> F[Components]
    F --> G[Hooks]
    G --> H[State Management]
    end
    
    subgraph "Backend"
    C --> I[Auth Service]
    C --> J[Task Service]
    C --> K[User Service]
    end
    
    subgraph "Database"
    E --> L[PostgreSQL]
    E --> M[Redis Cache]
    end

    style A fill:#2ecc71,stroke:#fff,stroke-width:2px
    style B fill:#3498db,stroke:#fff,stroke-width:2px
    style C fill:#9b59b6,stroke:#fff,stroke-width:2px
    style D fill:#e74c3c,stroke:#fff,stroke-width:2px
    style E fill:#f1c40f,stroke:#fff,stroke-width:2px
```

## 🛠️ Tech Stack

**Frontend**
- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript 5.3
- **Styling**: Tailwind CSS + CSS Modules
- **State**: Zustand
- **Components**: Shadcn UI

**Backend**
- **Runtime**: Node.js 18 LTS
- **ORM**: Prisma
- **Database**: PostgreSQL
- **Cache**: Redis
- **Validation**: Zod

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/Nuu-maan/todo-webapp.git

# Install dependencies
pnpm install

# Configure environment
cp .env.example .env.local

# Run database migrations
pnpm db:push

# Start development server
pnpm dev
```

## 📄 License

MIT License © 2024 [Numan](https://github.com/Nuu-maan)  
See [LICENSE](LICENSE) for full text.

---

<div align="center">

**Need Help?**  
[Open an Issue](https://github.com/Nuu-maan/todo-webapp/issues)  
[View Documentation](/docs)

</div>

