# Oxide

Oxide is an independent, from-the-ground-up reimplementation of Minecraft written in Rust.

## Overview

The project aims to recreate the core Minecraft experience with a modern Rust-based architecture, while putting a strong emphasis on performance, memory efficiency, and clean systems design.

### Goals

- Reimplement the client and server in Rust.
- Reduce memory usage through careful data structures, allocation strategies, and resource management.
- Improve frame rates and rendering performance through optimized rendering and world processing.
- Build efficient world, chunk, entity, networking, and gameplay systems.
- Keep the codebase modular so individual systems can be optimized without rewriting the entire engine.

## Performance Focus

Oxide is being designed with optimization as a first-class concern. Planned and ongoing work includes techniques for reducing unnecessary allocations, limiting redundant work, improving data locality, batching expensive operations, and keeping rendering and world updates efficient.

Performance will be measured against real workloads rather than assumed from implementation details.

## Project Status

Oxide is an active development project. Features, architecture, compatibility, and performance are expected to change substantially as development continues.

## Building

The project uses Rust and Cargo.

```bash
cargo build
```

For an optimized build:

```bash
cargo build --release
```

## Name and Relationship to Minecraft

Oxide is an independent project and is not affiliated with, endorsed by, or sponsored by Mojang Studios or Microsoft. Minecraft is a trademark of Mojang Studios/Microsoft.

This repository is intended for original implementation and development work; it does not imply ownership of Minecraft or its proprietary source code or assets.

## Attribution

Projects that redistribute or contain substantial portions of Oxide must credit **CynTheSolveroftheabsolutefabric** and link to the original repository:

**Oxide by CynTheSolveroftheabsolutefabric**  
https://github.com/CynTheSolveroftheabsolutefabric/Oxide

See [NOTICE](NOTICE) for the project's attribution and independence notice, and [LICENSE](LICENSE) for the license terms.

## License

Oxide is released under a modified MIT-style license with an attribution requirement. See [LICENSE](LICENSE) for the full license text.
