<div align="center">
  <h1>Setup Guide</h1>
  <p>Get your development environment ready in minutes</p>
</div>

## 📋 Prerequisites

- Node.js 18.17 or later
- npm or yarn
- Git

## 🚀 Installation

1. **Clone Repository**
   ```bash
   git clone https://github.com/yourusername/todo-app.git
   cd todo-app
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   ```bash
   cp .env.example .env.local
   ```

4. **Configure Variables**
   ```env
   DATABASE_URL="your-database-url"
   NEXTAUTH_SECRET="your-secret"
   NEXTAUTH_URL="http://localhost:3000"
   ```

5. **Database Setup**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

6. **Start Development**
   ```bash
   npm run dev
   ```

## 📝 Available Scripts

- `npm run dev` - Development server
- `npm run build` - Production build
- `npm start` - Start production
- `npm test` - Run tests
- `npm run lint` - Check code

## 🔧 Configuration

### Database

1. Setup your database
2. Update DATABASE_URL
3. Run migrations

### Authentication

1. Generate NEXTAUTH_SECRET
2. Configure providers
3. Update callback URLs

## 🆘 Need Help?

- Check [GitHub Issues](https://github.com/yourusername/todo-app/issues)
- Join our [Discord](your-discord-link)
- Read our [FAQ](docs/FAQ.md)

<div align="center">
  <p>Happy coding! 💻</p>
</div>