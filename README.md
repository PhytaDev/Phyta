# Phyta
A fully moddable 2D garden-defense engine

Phyta is an open-source framework for building lane-based defense games. Inspired by classic titles like Plants vs. Zombies, Phyta is designed to be mod-friendly and scriptable from the ground up. Completely free from proprietary assets or restrictions.

## Current Status

- **Stage**: Planning & prototyping

**Engine**: Not yet implemented

**Gameplay**: None

**Assets**: None/Prototyping

## Goals

- Provide an open foundation for PvZ-style gameplay.
- Support runtime modding (define entities, projectiles, rules)
- Keep the engine lightweight, readable, and extensible
- Encourage a community-driven ecosystem of mods and forks

## Contributing

We’re still laying the groundwork.
Ideas, design discussions, and feature suggestions are very welcome.
Code contributions will open once the prototype core is ready.

## Language

Engine language: Rust. But why?

Rust offers speed, safety, and cross-platform reliability — perfect for an open-source engine meant to be extended and modded. Its strong type system and memory safety make it easier to build complex systems without crashes or leaks, while still running close to native C++ performance.

In short: Rust lets Phyta stay fast, safe, and hackable.

Scripting & Modding Language: LUA specifically mlua crate. 
Lua was chosen for its speed, simplicity, and modding familiarity.

- Hot-reloadable mods
- Sandboxed
- LuaJIT support
- Simple structure


## License

MIT License
