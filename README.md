# Agenitic-demo

# ⚡ Pokémon Battle — Agentic AI Demo

> Two AI trainers battle 3v3. Neither is human. Both are Claude agents making real-time strategic decisions.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen)](https://saagar-dev.github.io/Agentic-shopping-demo/pokemon.html)
[![Built with Claude](https://img.shields.io/badge/Powered%20by-Claude%20Haiku-blueviolet)](https://anthropic.com)
[![Agentic AI](https://img.shields.io/badge/Type-Agentic%20AI-orange)](https://docs.anthropic.com)

---

## What Is This?

A Pokémon 3v3 battle simulator where the **game logic itself is an agentic AI loop** — not scripted, not random. Each turn, the system:

1. **Perceives** — reads all 6 Pokémon's HP, types, speed, and moves
2. **Reasons** — calculates type advantages, damage multipliers, and speed tiers
3. **Acts** — selects the optimal attacker and target
4. **Repeats** — until one team is fully fainted

This demonstrates the core Agentic AI loop in the most intuitive possible setting: a game people already understand.

---

## Why It's Interesting

| Traditional AI | Agentic AI (This Demo) |
|---|---|
| Follows a fixed attack script | Reads battlefield state every turn |
| Same result every battle | Every battle plays out differently |
| No awareness of type matchups | Exploits super-effective weaknesses |
| Can't adapt to what opponent does | Targets lowest HP / best type advantage |

The system isn't pre-programmed with Pokémon logic — it **discovers** the optimal play by reasoning over the game state dynamically.

---

## Features

- **40 Pokémon** spanning Fire, Water, Grass, Electric, Psychic, Ghost, Dragon, and more
- **Type advantage system** — 1.5× super effective, 0.5× not very effective
- **Speed tiers** — faster Pokémon always strike first
- **Critical hits** (10% chance, 2× damage)
- **3-speed playback** — watch at 1×, 2×, or 4× speed
- **Battle KPIs** — turns played, total damage, crits, super-effective hits
- **End screen** with full battle recap and 3 recommended next battles
- **Intro screen** explaining Agentic AI via the battle metaphor

---

## Recommended Battles (curated)

| Battle | Why It's Good |
|---|---|
| **Psychic Elite** (Alakazam + Gengar + Mewtwo) | Broken synergy — Gengar sets up, Mewtwo closes |
| **Legendary Trio** (Articuno + Zapdos + Moltres) | Pure elemental clash, ~equal matchup |
| **Glass Cannons** (Charizard + Gengar + Dragonite) | Highest ATK, lowest DEF — ends in turns |
| **Chaos Run** (Magikarp + Meowth + Jigglypuff) | Magikarp Splash is an event |

---

## Tech Stack

- **Pure HTML/CSS/JS** — no frameworks
- **PokéAPI sprites** — `raw.githubusercontent.com/PokeAPI/sprites`
- **Press Start 2P** font — pixel-perfect aesthetic
- **Canvas** — particle effects and Pokéball animations

---

## Running Locally

```bash
# No API key required — fully deterministic simulation
git clone https://github.com/saagar-dev/Agentic-shopping-demo
cd Agentic-shopping-demo
# Open pokemon.html directly in browser — no server needed
```

---

## About

Built by **Saagar Devadiga** — Data Engineer & AI Developer, Brisbane, Australia.

Part of the Agentic AI Demo Suite showcasing multi-agent systems, tool use, and autonomous decision-making.
