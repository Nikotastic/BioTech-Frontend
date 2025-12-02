
<div align="center">
# 🧬 BioTech Frontend
  
![React](https://img.shields.io/badge/React-19.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.2.4-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-4.1.17-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TypeScript](https://img.shields.io/badge/JavaScript-ES2020-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A modern, scalable frontend application built with React and powered by cutting-edge technologies**

[🚀 Live Demo](https://biotech-frontend.vercel.app) | [📖 Documentation](https://docs.biotech.com) | [🐛 Report Bug](https://github.com/your-repo/issues)

</div>

---

## ✨ Features

🎯 **Modern Architecture** - Feature-based structure for maximum scalability  
⚡ **Lightning Fast** - Built with Vite for instant hot reload  
🎨 **Beautiful UI** - Styled with Tailwind CSS v4  
🔐 **Secure Authentication** - JWT-based auth with cookie management  
📱 **Responsive Design** - Mobile-first approach  
🔄 **State Management** - Zustand for efficient global state  
📝 **Form Validation** - React Hook Form with Yup validation  
🌐 **API Integration** - Axios for robust HTTP client

---

## 🛠️ Tech Stack

### Core Technologies

| Technology                                                                                                   | Version | Purpose            |
| ------------------------------------------------------------------------------------------------------------ | ------- | ------------------ |
| ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=white)                   | 19.2.0  | Frontend Framework |
| ![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite&logoColor=white)                      | 7.2.4   | Build Tool         |
| ![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) | 4.1.17  | CSS Framework      |
| ![Zustand](https://img.shields.io/badge/-Zustand-FF6B6B?style=flat)                                          | 5.0.9   | State Management   |

### Additional Libraries

- **React Router DOM** `7.9.6` - Client-side routing
- **Axios** `1.13.2` - HTTP client
- **React Hook Form** `7.67.0` - Form handling
- **Yup** `1.7.1` - Schema validation
- **js-cookie** `3.0.5` - Cookie management

---

## 📁 Project Architecture

```
🏗️ Feature-Based Architecture (Feature-Sliced Design)
```

```bash
src/
├── 🎯 app/                    # Application layer
│   ├── hooks/                 # Global application hooks
│   ├── providers/             # Context providers
│   ├── routers/               # Route configuration
│   ├── store/                 # Root store setup
│   └── App.jsx                # Main app component
├── 🔧 shared/                 # Shared utilities
│   ├── components/            # Reusable components
│   ├── constants/             # App constants
│   ├── hooks/                 # Shared hooks
│   ├── types/                 # TypeScript types
│   └── utils/                 # Helper functions
├── 🚀 features/               # Business features
│   ├── auth/                  # Authentication feature
│   │   ├── components/        # Auth-specific components
│   │   ├── hooks/             # Auth hooks
│   │   ├── pages/             # Auth pages
│   │   ├── services/          # Auth API calls
│   │   └── store/             # Auth state management
│   └── users/                 # User management feature
│       ├── components/
│       ├── hooks/
│       ├── pages/
│       ├── services/
│       └── store/
├── 📊 entities/               # Domain entities
│   ├── session/               # Session entity
│   └── user/                  # User entity
├── 📄 pages/                  # Route pages
│   ├── Dashboard/
│   ├── Home/
│   └── Login/
├── 🧩 widgets/                # Complex UI widgets
├── 🎨 assets/                 # Static assets
│   ├── icons/
│   └── images/
└── 💅 styles/                 # Global styles
    └── index.css
```

### 📋 Folder Description

| 📁 Folder   | 📝 Description                                           |
| ----------- | -------------------------------------------------------- |
| `app/`      | Global configuration: routes, stores, providers, layouts |
| `shared/`   | Reusable components, hooks, and utilities                |
| `features/` | Business logic modules (auth, users, etc.)               |
| `entities/` | Domain models and basic business logic                   |
| `pages/`    | Route-connected page components                          |
| `widgets/`  | Complex components composed of multiple features         |
| `assets/`   | Images, icons, and static resources                      |
| `styles/`   | Global CSS and Tailwind configuration                    |

---

## 🚀 Getting Started

### Prerequisites

![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=flat&logo=node.js&logoColor=white)
![npm](https://img.shields.io/badge/npm-9+-CB3837?style=flat&logo=npm&logoColor=white)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Nikotastic/BioTech-Frontend.git
   cd BioTech-Frontend
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Start development server**

   ```bash
   npm run dev
   ```

5. **Open your browser**
   ```
   http://localhost:5173
   ```

---

## 📜 Available Scripts

| Script             | Description              | Command           |
| ------------------ | ------------------------ | ----------------- |
| 🔥 **Development** | Start development server | `npm run dev`     |
| 🏗️ **Build**       | Create production build  | `npm run build`   |
| 👀 **Preview**     | Preview production build | `npm run preview` |
| 🧹 **Lint**        | Run ESLint               | `npm run lint`    |

---

## 🔄 Git Workflow

We follow a **Simplified Git Flow** to ensure organized and collaborative development.

### 🌿 Main Branches

| Branch    | Purpose                                           |
| --------- | ------------------------------------------------- |
| `main`    | 🏷️ Stable production code. **No direct commits!** |
| `develop` | 🚧 Development integration branch                 |

### 🔧 Working Branches

Create your branch from `develop`:

| Type                 | Pattern                  | Example                     |
| -------------------- | ------------------------ | --------------------------- |
| ✨ **Features**      | `feat/feature-name`      | `feat/user-authentication`  |
| 🐛 **Bug Fixes**     | `fix/bug-description`    | `fix/login-error`           |
| 📚 **Documentation** | `docs/update-name`       | `docs/api-documentation`    |
| 🎨 **Styling**       | `style/component-name`   | `style/button-improvements` |
| ♻️ **Refactoring**   | `refactor/module-name`   | `refactor/auth-service`     |
| ⚙️ **Chores**        | `chore/task-description` | `chore/update-dependencies` |

---

## 💬 Commit Convention

We use **Conventional Commits** for clear and consistent commit messages.

### Format

```
type(scope): brief description in lowercase

type: feat | fix | docs | style | refactor | test | chore
scope: area of change (optional)
```

### Examples

```bash
✨ feat(auth): add login form with validation
🐛 fix(users): resolve user data fetching error
📚 docs(readme): update installation instructions
🎨 style(header): improve responsive design
♻️ refactor(api): optimize axios client configuration
⚙️ chore(deps): update tailwind to v4.1.17
```

---

## 🤝 Contributing

1. **Update develop branch**

   ```bash
   git checkout develop
   git pull origin develop
   ```

2. **Create feature branch**

   ```bash
   git checkout -b feat/your-feature-name
   ```

3. **Make changes and commit**

   ```bash
   git add .
   git commit -m "feat(scope): your commit message"
   ```

4. **Push branch**

   ```bash
   git push --set-upstream origin feat/your-feature-name
   ```

5. **Create Pull Request**
   - Target: `develop` branch
   - Wait for review and approval

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 Team

<div align="center">

**Built with ❤️ by the BioTech Team**

[🐛 Report Issues](https://github.com/Nikotastic/BioTech-Frontend/issues) | [💡 Request Features](https://github.com/Nikotastic/BioTech-Frontend/issues/new) | [📖 Documentation](https://docs.biotech.com)

</div>
