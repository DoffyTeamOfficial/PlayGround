# AQUARIA

A playable 2D block-based fishing sandbox for desktop and mobile browsers.

## Features

- Deterministic 240×60-tile world
- Crimson, Emerald, Crystal, and Turquoise biomes with transition zones
- Walking, jumping, platform collision, camera follow, zoom, and mobile joystick controls
- Fishing with biome-specific species and local catch records
- Eight-slot hotbar, inventory, dropped items, and block placement/destruction
- Persistent world modifications and player state
- Tidebound vending machines and local gacha spins
- Four independent local save slots
- Transparent water tiles and responsive canvas rendering

## Saves

Progress is saved only in browser `localStorage` under:

- `aquaria_save_0`
- `aquaria_save_1`
- `aquaria_save_2`
- `aquaria_save_3`

Each save stores the player position, inventory, settings, fishing records, and `worldMods` tile changes.

## Unsupported

- Multiplayer and networking
- Cloud saves and account synchronization
- Real-money purchases or server-backed prizes

## Run locally

Serve this directory with any static HTTP server, for example:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.
