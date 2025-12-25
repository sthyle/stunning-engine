# stunning-engine

Project to build a high performance game engine in Rust.

Status
------
This repository is in the initial setup phase. The current branch `Init/structure` contains a basic Rust project skeleton and CI workflow.

Goals
-----
- Build a high-performance, modular game engine in Rust.
- Focus on safety, concurrency, and performance.
- Provide clear APIs for rendering, physics, audio, and scripting.

Roadmap (high level)
---------------------
1. Project scaffolding and tooling (this commit)
2. Core ECS (Entity-Component-System) and scheduler
3. Renderer (Vulkan/metal abstractions)
4. Physics and collision system
5. Asset pipeline and resource management
6. Scripting bindings (Lua/Rhai)
7. Examples and sample games

Getting started (local)
------------------------
Prerequisites:
- Rust toolchain (rustup) installed

Build and run the example:

cargo build --release
cargo run

Contributing
------------
Contributions are welcome. See CONTRIBUTING.md for details.

License
-------
This project is released under the MIT License. See LICENSE.
