# 🦄 Nyxicorns RPG

A cozy 3D RPG game built with React, Three.js and TypeScript for the web. Explore a whimsical world filled with magical unicorn creatures called Nyxicorns.

## 🎮 About

Nyxicorns RPG is a browser-based 3D role-playing game focused on exploration, collection, and cozy gameplay mechanics. Built with modern web technologies to deliver a smooth, accessible experience directly in your browser.

## 🛠 Tech Stack

- **Framework**: React 18 (TypeScript / TSX)
- **Engine**: Three.js (WebGL)
- **State Management**: Zustand
- **Build Tool**: Vite
- **Package Manager**: npm

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

## 📁 Project Structure

```
Nyxicorns-rpg/
├── app/
│   ├── public/              # Static assets (icons, logo)
│   ├── src/
│   │   ├── engine/          # 3D engine (lighting, camera, scene, post-processing)
│   │   ├── game/
│   │   │   ├── data/        # Game data (NPCs, quests, recipes, species, world config)
│   │   │   ├── nyxicorns/    # Nyxicorn creatures (models, wild spawns, companion AI)
│   │   │   ├── player/      # Player controller, model, interaction system
│   │   │   ├── systems/     # Gameplay systems (build, cooking, farming, fishing, festivals, NPCs, resources)
│   │   │   ├── ui/          # UI screens (HUD, inventory, crafting, quests, dialogue, menus)
│   │   │   └── world/       # World generation (terrain, trees, water, sky, weather, clouds, particles)
│   │   ├── stores/          # Global state (Zustand stores for each game system)
│   │   ├── App.tsx          # Root component
│   │   ├── main.tsx         # Entry point
│   │   └── index.css        # Global styles
│   ├── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── vite.config.ts
├── .gitignore
└── README.md
```

## 📄 License

To be defined.

## 🔗 Links

- [Repository](https://github.com/noctyraluxa/Nyxicorns-rpg)
- [Play the game](https://nyxicorns-rpg.dls.so)

---

> Built by [Sacha Monier](https://github.com/noctyraluxa)