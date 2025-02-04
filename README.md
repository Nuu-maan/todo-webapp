
<div align="center">

# 🚀 Next.js Todo Pro

[![GitHub Stars](https://img.shields.io/github/stars/Nuu-maan/todo-webapp?style=for-the-badge&logo=github&color=5865F2&labelColor=000000)](https://github.com/Nuu-maan/todo-webapp/stargazers)
[![Open Issues](https://img.shields.io/github/issues/Nuu-maan/todo-webapp?style=for-the-badge&logo=git&color=FFA500&labelColor=000000)](https://github.com/Nuu-maan/todo-webapp/issues)
[![License](https://img.shields.io/badge/license-MIT-97CA00?style=for-the-badge&logo=open-source-initiative&labelColor=000000)](LICENSE)

![Star History Chart](https://api.star-history.com/svg?repos=Nu-maan/todo-webapp&type=Date&theme=dark)

</div>

## 🌟 Key Features

<div align="center">

| 🛠 Core Functionality    | 🌐 Collaboration       | 🔒 Security         |
|-------------------------|-----------------------|--------------------|
| 📝 Rich Text Tasks      | 👥 Shared Workspaces  | 🔐 OAuth 2.0       |
| 🗓 Smart Due Dates       | 💬 Threaded Comments  | 🔑 RBAC            |
| 🏷 Custom Labels         | 📊 Activity Analytics | 🔒 E2E Encryption  |

</div>

## 🧑💻 Core Team

<div align="center">

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Nuu-maan">
        <img src="https://avatars.githubusercontent.com/Nuu-maan" width="150" style="border-radius:50%">
        <br/>
        <strong>Numan</strong>
      </a>
      <br/>
      <a href="https://github.com/Nuu-maan?tab=followers">
        <img src="https://img.shields.io/github/followers/Nuu-maan?style=social&logo=github">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/anisvsc">
        <img src="https://avatars.githubusercontent.com/anisvsc" width="150" style="border-radius:50%">
        <br/>
        <strong>Anish Gupta</strong>
      </a>
      <br/>
      <a href="https://github.com/anisvsc?tab=followers">
        <img src="https://img.shields.io/github/followers/anisvsc?style=social&logo=github">
      </a>
    </td>
  </tr>
</table>

</div>

## 🏗 Architecture Overview

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

## 🛠 Technology Stack

<div align="center">

| Layer       | Technologies                                                                                  |
|-------------|-----------------------------------------------------------------------------------------------|
| **Frontend**| Next.js 14, TypeScript 5, Tailwind CSS, React Aria, Zustand                                    |
| **Backend** | Node.js 18, Prisma, PostgreSQL, Redis,                                                     |
| **DevOps**  | Docker, GitHub Actions, Vercel, ,                                            |
| **Tools**   | ESLint, Prettier, Husky, Commitlint                                                       |

</div>

## 🚀 Getting Started

```bash
# Clone repository
git clone https://github.com/Nuu-maan/todo-webapp.git

# Install dependencies
npm install

# Configure environment
cp .env.example .env.local

# Run migrations
npx prisma migrate dev

# Start development server
npm run dev
```

## 📜 License 

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for full text.

---

<div align="center">

[![GitHub Contributors](https://img.shields.io/github/contributors/Nuu-maan/todo-webapp?style=for-the-badge&logo=github&color=2BAF2B&labelColor=000000)](https://github.com/Nuu-maan/todo-webapp/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/Nuu-maan/todo-webapp?style=for-the-badge&logo=github&color=9B59B6&labelColor=000000)](https://github.com/Nuu-maan/todo-webapp/commits/main)

</div>


**Copyright © 2024 Numan & Anish Gupta** - [View License](LICENSE)