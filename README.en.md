<p align="center">
  <a href="https://shader-hub.ru">
    <img src="https://shader-hub.ru/og-image.png" alt="Shader Hub" width="640" />
  </a>
</p>

<h1 align="center">Shader Hub</h1>

<p align="center">
  <strong>GLSL/WebGPU editor · explore · learn</strong>
</p>

<p align="center">
  <a href="https://shader-hub.ru"><img src="https://img.shields.io/badge/website-shader--hub.ru-8b5cf6?style=for-the-badge" alt="Website" /></a>
  <a href="https://github.com/likeavenus/shader-hub/stargazers"><img src="https://img.shields.io/github/stars/likeavenus/shader-hub?style=for-the-badge&logo=github&label=Stars" alt="GitHub stars" /></a>
  <a href="https://github.com/likeavenus/shader-hub/issues"><img src="https://img.shields.io/github/issues/likeavenus/shader-hub?style=for-the-badge&logo=github&label=Issues" alt="Issues" /></a>
</p>

<p align="center">
  <a href="./README.md">Русская версия</a>
</p>

---

**Shader Hub** is a browser portal for creative coders: write **GLSL** (and experiment with **WebGPU**), see live previews, publish to a community feed, and follow **Shader School** — a hands-on course with automatic grading and XP leaderboard.

> **This repository is the public home of the project** (README, feedback, stars).  
> Application source code is maintained in a **private** repository during active development.

## Live

**[https://shader-hub.ru](https://shader-hub.ru)** — free, no install.

| Area | URL |
|------|-----|
| Editor | [/editor](https://shader-hub.ru/editor) |
| Learn (Shader School) | [/learn](https://shader-hub.ru/learn) |
| Feed | [/](https://shader-hub.ru/) |

## Features

- **Live shader editor** — Monaco, instant preview, compare with reference
- **Community feed** — publish works, likes, profiles
- **Shader School** — 15 lessons, stages, hints, pixel-based grading
- **Leaderboard** — XP and streaks
- **RU / EN** — learning content and UI

## Tech stack

| Layer | Technologies |
|-------|----------------|
| **Frontend** | React 19, TypeScript, Vite 6, Tailwind CSS 4, React Router 7, TanStack Query, Zustand, Monaco Editor |
| **Shaders** | WebGL 2 (GLSL), WebGPU / WGSL (where supported) |
| **API** | Node.js (Express), PostgREST, PostgreSQL 16 |
| **Auth** | JWT (Supabase-style flow) |
| **Deploy** | Docker Compose, nginx, Selectel VPS |

## Support the project

If Shader Hub is useful to you:

1. **[⭐ Star this repo](https://github.com/likeavenus/shader-hub)** — helps others discover it  
2. **[Open an issue](https://github.com/likeavenus/shader-hub/issues)** — bugs, ideas, lesson feedback  
3. **Try the site** and share the link

## Contact

**[@likeavenus](https://github.com/likeavenus)** · [Telegram](https://t.me/likeavenus) · [gulievrafael94@gmail.com](mailto:gulievrafael94@gmail.com)

---

<p align="center">
  <a href="https://github.com/likeavenus/shader-hub">
    <img src="https://img.shields.io/github/stars/likeavenus/shader-hub?style=social" alt="Star Shader Hub on GitHub" />
  </a>
</p>
