## OMNIDEX
Transformation-Based Multi-World Battle Game

## Overview
**OMNIDEX** is a transformation-driven action game that combines dynamic hero selection with progressive combat mechanics. Players select heroes from an intuitive DNA carousel interface, unlock unique abilities and costumes, and engage in real-time battles across multiple themed environments with adaptive difficulty.

Designed for both web and mobile platforms, OMNIDEX leverages modern scalable technologies to support future expansion into multiplayer features, competitive leaderboards, and monetization systems.

---

## Features

### 1. Hero Selection Interface

- **Dynamic Hero Carousel**: Horizontally scrollable DNA-inspired interface with smooth animations
- **Real-Time Stat Visualization**: Display character stats (Strength, Speed, Intelligence)
- **Interactive Hero Preview**: Animated character previews with detailed information panels
- **Responsive Design**: Seamless experience across desktop and mobile devices


### 2. Transformation System

Each selected hero unlocks:
- Unique abilities
- Custom costume
- Modified stats
- Specialized attack style
- Powers dynamically apply in-game

### 3. Multi-World Combat Environment

| World | Description | Difficulty |
|-------|-------------|-----------|
| **Garden Realm** | Entry-level combat zone with basic enemies | Easy |
| **Ice Frontier** | Advanced physics mechanics with tactical AI | Medium |
| **Volcano Core** | Environmental hazards and lava mechanics | Hard |
| **Desert Storm** | Visibility reduction with boss encounters | Advanced |

### 4. Battle Mechanics

- **Real-Time Combat System**: Active player engagement with dynamic enemy AI
- **Energy Management**: Health bar system with resource management
- **Reward System**: Coins earned per successful hit, with progressive scaling
- **Level Progression**: Monster defeats trigger level-ups with increased difficulty
- **Environmental Hazards**: World-specific mechanics affecting combat strategy

### 5. Progression System

- Monster defeat → Level Up
- Higher levels → Stronger enemies
- Increasing spawn rate
- Enhanced AI behavior
- Unlockable worlds

---

# Tech Stack

### Frontend
- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Game Engine**: Phaser.js (2D)

### Backend (Planned)
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB

### Mobile Deployment
- **Platform**: React Native (Expo)

---

## Project Structure
```bash
OMNIDEX/
│
├── public/
│   ├── assets/
│   │   ├── characters/
│   │   ├── monsters/
│   │   ├── worlds/
│   │   └── sounds/
│
├── src/
│   ├── app/
│   │   ├── page.tsx
│   │   ├── game/
│   │   │   └── page.tsx
│   │   └── layout.tsx
│   │
│   ├── components/
│   │   ├── HeroCarousel.tsx
│   │   ├── HeroDetails.tsx
│   │   ├── GameCanvas.tsx
│   │   └── Footer.tsx
│   │
│   ├── data/
│   │   └── characters.ts
│   │
│   ├── game/
│   │   ├── scenes/
│   │   │   ├── GardenScene.ts
│   │   │   ├── IceScene.ts
│   │   │   ├── VolcanoScene.ts
│   │   │   └── DesertScene.ts
│   │   │
│   │   └── config.ts
│   │
│   ├── store/
│   │   └── useGameStore.ts
│   │
│   └── styles/
│       └── globals.css
│
├── package.json
├── tailwind.config.ts
└── README.md
```

# Getting Started
1. Clone the Repository
```bash
git clone https://github.com/TahiraNawab123/OMNIDEX.git
```
2. Install Dependencies
```npm install```

3. Run Development Server
```npm run dev```


The app will run locally at:
```bash
http://localhost:3000
```

# UI Design Philosophy

- Futuristic sci-fi interface
- Neon holographic visual theme
- Smooth animated transitions
- Responsive mobile-first design
- Modular component architecture

# Future Enhancements

- Multiplayer mode
- Online leaderboard system
- User authentication
- Cloud save system
- In-game marketplace
- Boss battle events
- Sound effects & background music system
