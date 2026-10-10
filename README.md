# Trapdoor Dash 3 — PAUL'S DEVIL RUN 😈

A polished, mobile-first trap platformer inspired by Level Devil: 30 hand-designed levels across 3 worlds, surprise traps, 5 lives per run, star currency, hints, and a photo-inspired Gloria character.

**Play:** https://paulatawadrous5-beep.github.io/trapdoor-dash-3/

## Features

- **3 worlds × 10 levels** — 🌿 The Red Beginning, 🏭 The Trickster's Domain, 🔥 The Devil's Playground
- **Horizontal zigzag world map** with door nodes, locked/unlocked/completed states, star ratings
- **5 lives per run** + dramatic Game Over screen (progress is never lost)
- **Star currency** — earn stars by completing levels, spend on hints (5 → 10 → 15 ⭐)
- **Level-specific hints** that actually describe each level's traps
- **Traps** — pop-up spikes, falling spikes, saws, chasers (devils), crumbling & fake platforms, moving walls, fake doors
- **Sound effects only** — footsteps, jump, land, fall, trap warnings, star pickup, door, win, world-complete devil, game-over growl (no background music)
- **Gloria** — cartoon character inspired by her real photo (long dark hair, navy top, yellow flower)
- **PAUL split animation** after each world + special finale after level 30
- **PWA** — installable on mobile (Add to Home Screen), fullscreen, works offline via service worker
- **Progress saved** in localStorage (unlocked levels, stars, balance, sound setting)

## Controls

- Mobile: touch buttons (◀ ▶ JUMP)
- Desktop: Arrow keys / WASD / Space

## Files

- `index.html` — menus, map, HUD, overlays, PWA tags
- `style.css` — red/black devil theme, map, animations
- `game.js` — engine, 30 levels, audio, persistence
- `manifest.json`, `sw.js`, `icon-*.png` — PWA
- `gloria-avatar.png` — Gloria's portrait
