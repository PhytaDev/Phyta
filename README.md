
# Phyta

Open-Source 2D "Garden"-Defense Engine
_A fully moddable framework for building lane-based defense games._

Phyta is an open-source engine dedicated to creating Plants vs. Zombies style 2D garden defense games. Our vision is to provide a highly moddable, scriptable, and community-driven platform, completely free from proprietary assets or restrictions.

## Current Status

*   **Stage**: Planning & Prototyping
*   **Engine**: Not yet implemented
*   **Gameplay**: Not yet implemented
*   **Assets**: Prototyping

## Core Goals

*   **Open Foundation**: Establish a robust, adaptable engine for PvZ-style gameplay
*   **Moddability**: Support runtime modding for entities, projectiles, game rules, and more
*   **Lightweight & Extensible**: Maintain a clean, readable, and easily extensible codebase
*   **Community-Driven**: Foster a vibrant ecosystem for mods, forks, and collaborative development

## Technology Stack

### Engine: Rust
Chosen for its great **speed, memory safety, cross-platform**. Rust will help us to build a high-performance engine that's stable and easy to extend, running close to native C++ performance.

### Scripting & Modding: Lua (via `mlua` crate)
Lua offers a combination of **simplicity, speed, and modding familiarity**. Key features include hot reloadable mods, a sandboxed environment for security, and LuaJIT support for performance.

## Contributing

We are currently laying the groundwork for Phyta and welcome **ideas, design discussions, and feature suggestions**. Once the core prototype is stable, we'll open up for code contributions.

## License

Phyta is distributed under the **MIT License**
