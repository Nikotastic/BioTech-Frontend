<div align="center">

# 🧬 BioTech Frontend

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)


</div>

## 📋 Table of Contents

- [📌 Initial Project Guidelines](#-initial-project-guidelines--frontend)
- [🌳 Git Flow – Branch Convention](#-git-flow--branch-convention)
- [🧩 Commit Convention](#-commit-convention-conventional-commits)
- [📘 Important](#-important)

---

## 📌 Initial Project Guidelines – Frontend

This repository contains the **frontend** of the BioTech project.

> ⚠️ **The entire team must follow these branch and commit conventions in a mandatory way.**

---

## 🌳 Git Flow – Branch Convention

### 🎯 Main Branches

| Branch    | Purpose                     |
| --------- | --------------------------- |
| `main`    | Stable version / Production |
| `develop` | Integration of new features |

---

### 🔀 Working Branches

| Prefix     | Use                        |
| ---------- | -------------------------- |
| `feature/` | New frontend features      |
| `hotfix/`  | Urgent fixes in production |
| `release/` | Version preparation        |

#### 📝 Branch Name Examples

```bash
 feature/login
 feature/navigation
 feature/dashboard
 hotfix/error-css
 release/v1.0.0
```

---

### ⚡ Git Flow Rules

<table>
<tr>
<td>

**📌 Rule 1**

> Each sprint task must have its own `feature/` branch

</td>
</tr>
<tr>
<td>

**🔥 Rule 2**

> `hotfix/` branches fix directly on `main` and then sync with `develop`

</td>
</tr>
<tr>
<td>

**📦 Rule 3**

> `release/` branches come from `develop` and go back to `main` and `develop`

</td>
</tr>
</table>

---

## 🧩 Commit Convention (Conventional Commits)

### 📐 Mandatory Format

```
<type>(<scope>): <brief description>
```

**Example**: `feat(auth): add OAuth login`

---

### 🏷️ Allowed Commit Types

| Type       | Use                                      | Example                                       |
| ---------- | ---------------------------------------- | --------------------------------------------- |
| `feat`     | New feature                              | `feat(ui): add navbar component`              |
| `fix`      | Bug fix                                  | `fix(auth): fix token validation error`       |
| `docs`     | Documentation                            | `docs(readme): update installation steps`     |
| `style`    | Visual changes or CSS formatting         | `style(button): improve styles with Tailwind` |
| `refactor` | Code restructuring without logic changes | `refactor(hooks): optimize custom hooks`      |
| `test`     | Tests                                    | `test(login): add unit tests`                 |
| `chore`    | Dependencies, configurations, builds     | `chore(deps): update React to v18`            |
| `revert`   | Revert a commit                          | `revert: revert navbar changes`               |

---

### 📚 Complete Examples

```bash
# New feature
feat(ui): add navbar component

# Bug fix
fix(auth): fix token validation error

# Documentation
docs(readme): update installation steps

# Styles
style(dashboard): apply dark theme with Tailwind

# Refactoring
refactor(components): reorganize folder structure

# Testing
test(services): add coverage for AuthService

# Configuration
chore(vite): update build configuration
```

---

## 📘 Important

> 🔴 **These rules are MANDATORY for all team members.**

### 📞 Contact

- 💬 Any questions should be consulted with the **Scrum Master**
- 📢 Report blockers in the daily standup
- 📝 Document important decisions in the project

---

<div align="center">

### 🌟 Thank you for contributing to the BioTech project!

**Made with ❤️ by the development team**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com)

---

© 2025 BioTech. All rights reserved.

</div>
