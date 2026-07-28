
<p align="center">
  <img src="https://imgs.search.brave.com/pHd_gnYopa1ibeeTSnDw8pQbnnfL5qKZqvs3MXefK_c/rs:fit:0:180:1:0/g:ce/aHR0cHM6Ly9hZ3Jp/bm92YS1wcm9qZWN0/LmV1L3dwLWNvbnRl/bnQvdXBsb2Fkcy8y/MDI2LzAyL0xPR08t/QUdSSU5PVkEtd2hp/dGUtZTE3NzA4ODIx/NTg4MTMucG5n" width="100%" alt="Agrinova Banner">
</p>

<h1 align="center">🌿 Agrinova</h1>

<p align="center"><b>AI‑Powered Precision Agriculture Platform</b></p>

<p align="center">
<img src="https://img.shields.io/github/license/YOUR_USERNAME/Agrinova?style=for-the-badge">
<img src="https://img.shields.io/github/stars/YOUR_USERNAME/Agrinova?style=for-the-badge">
<img src="https://img.shields.io/github/issues/YOUR_USERNAME/Agrinova?style=for-the-badge">
</p>

<p align="center">
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,nodejs,python,tensorflow,pytorch,opencv,supabase,postgres,docker,git,github,vscode&perline=8">
</p>

---

# Overview
Agrinova is an AI platform for crop disease detection, satellite crop monitoring, weather insights, analytics, and yield prediction.

## Features

| Icon | Feature |
|---|---|
| <img src="https://cdn.simpleicons.org/tensorflow" width="20"> | AI Disease Detection |
| <img src="https://cdn.simpleicons.org/opencv" width="20"> | Computer Vision |
| <img src="https://cdn.simpleicons.org/googlemaps" width="20"> | GPS Mapping |
| <img src="https://cdn.simpleicons.org/postgresql" width="20"> | PostgreSQL |
| <img src="https://cdn.simpleicons.org/supabase" width="20"> | Supabase Backend |
| <img src="https://cdn.simpleicons.org/docker" width="20"> | Docker |

# Screenshots

Replace these placeholders:

```text
assets/screenshots/dashboard.png
assets/screenshots/detection.png
assets/screenshots/mobile.png
```

# Architecture

```mermaid
flowchart TD
Farmer-->Web
Farmer-->Mobile
Web-->API
Mobile-->API
API-->AI
API-->DB[(PostgreSQL)]
AI-->Prediction
```

# AI Pipeline

```mermaid
flowchart LR
Image-->Preprocess-->Model-->Prediction-->Recommendation
```

# Tech Stack

### Frontend
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind"/>

### Backend
<img src="https://skillicons.dev/icons?i=nodejs,python,fastapi"/>

### AI
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv"/>

### Database
<img src="https://skillicons.dev/icons?i=supabase,postgres"/>

### DevOps
<img src="https://skillicons.dev/icons?i=docker,git,github,vercel"/>

# Project Structure

```text
Agrinova/
├── app/
├── components/
├── ai/
├── backend/
├── assets/
├── docs/
├── public/
├── package.json
└── README.md
```

# Installation

```bash
git clone https://github.com/maneziezra/Agrinova.git
cd Agrinova
npm install
npm run dev
```

# Environment

```env
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
DATABASE_URL=
OPENWEATHER_API_KEY=
```

# Roadmap
- [x] Dashboard
- [x] AI Detection
- [x] Authentication
- [ ] Mobile App
- [ ] IoT
- [ ] Drone Integration
- [ ] AI Assistant

# Contributing
Fork → Branch → Commit → Push → Pull Request.

# License
MIT

---
<p align="center">
Built with ❤️ for the future of African Agriculture.
</p>
