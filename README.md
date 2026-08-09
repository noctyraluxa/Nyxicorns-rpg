# Nyxicorns RPG

> A beautiful 3D cozy fantasy RPG built with React, Three.js, and TypeScript.

## Tech Stack

- **React** — UI framework (all components are `.tsx`)
- **Three.js** — 3D rendering engine
- **TypeScript** — type safety across the project
- **Vite** — build tool and dev server
- **Zustand** — global state management

## Project Structure

```
app/
├── src/
│   ├── engine/     # 3D engine (lighting, camera, scene, post-processing)
│   ├── game/       # Gameplay systems
│   │   ├── data/       # Game data (recipes, quests, nyxicorn species)
│   │   ├── nyxicorns/  # Nyxicorn creatures
│   │   ├── player/     # Player controller
│   │   ├── systems/   # Gameplay systems (inventory, crafting, fishing, etc.)
│   │   ├── ui/        # In-game UI
│   │   └── world/      # World generation, terrain, vegetation
│   └── stores/     # Zustand stores (gameStore, inventoryStore, nyxicornStore)
├── package.json
└── vite.config.ts
```

## Getting Started

```bash
cd app
npm install
npm run dev
```

## Build

```bash
cd app
npm run build
```

## License

All rights reserved.