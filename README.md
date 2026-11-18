# 3D Space Portfolio — Starter Project

The planning documents behind **Nebula Drift**, a 3D portfolio you play. You fly a ship through a neon nebula and dock at floating stations, one per project, each modelled to show what that project is.

There is **no code here**. These are the docs the original was built from, plus its 3D models, so you can build your own version with your own ship, stations and content.

## What's inside

| File | What it is |
|---|---|
| [`CONTRACT.md`](CONTRACT.md) | The idea, and what the experience must always do: audience promises, flight, docking, navigation, the gateway and asteroid game, non-goals |
| [`CLAUDE.md`](CLAUDE.md) | The working guide for an AI coding agent: stack, intended project structure, and the rules that kept the build healthy |
| [`REFERENCE.md`](REFERENCE.md) | The original project's README: a full tour of the finished experience, controls, tech and model credits. Use it as a reference for scope and feel |
| [`CONTENT.md`](CONTENT.md) | The portfolio content: projects, about and contact. **Replace this with your own** |
| [`public/models/`](public/models) | The 3D models: the ship and satellite, plus the station, dish and cargo models the finished build swapped for procedural geometry |

## How to use it

1. Use this template (or clone it) to start a new repo.
2. Rewrite `CONTENT.md` with your own projects, bio and contact channels.
3. Edit `CONTRACT.md` to match your own idea. It's the checklist the build is held to.
4. Open the folder in Claude Code (or another agent) and build it up: flight first, then stations and docking, then navigation, then the extras.

Stack the docs assume: React, Vite, TypeScript, react-three-fiber with drei and postprocessing, and Zustand.

## 3D model credits

The models in `public/models/` are not mine. They keep their original licences, and CC-BY means you must credit the author if you use them.

| File | Model | Author | License |
|---|---|---|---|
| `ship.glb` | Spitfire, from the [Ultimate Spaceships Pack](https://quaternius.com) | Quaternius | CC0 |
| `station.glb` | Wikiplanet Space Station, via [poly.pizza](https://poly.pizza) | Alan Zimmerman | CC-BY |
| `satellite.glb` | Satellite, via [poly.pizza](https://poly.pizza) | Poly by Google | CC-BY |
| `dish.glb` | Comms dish, via [poly.pizza](https://poly.pizza) | Not recorded. Check before reuse | Unknown |
| `cargo.glb` | Cargo depot, via [poly.pizza](https://poly.pizza) | Kay Lousberg | CC0 |
