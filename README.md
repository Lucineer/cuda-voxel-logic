# cuda-voxel-logic

3D voxel spatial reasoning — occupancy grids, A* pathfinding, raycasting, CSG operations (Rust)

Part of the Cocapn spatial layer — how agents perceive and navigate physical space.

## What It Does

### Key Types

- `Pos` — core data structure
- `VoxelGrid` — core data structure

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-voxel-logic.git
cd cuda-voxel-logic

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_voxel_logic::*;

// See src/lib.rs for full API
// 15 unit tests included
```

### Available Implementations

- `Pos` — see source for methods
- `VoxelGrid` — see source for methods
- `Ord for Node` — see source for methods
- `PartialOrd for Node` — see source for methods

## Testing

```bash
cargo test
```

15 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: spatial
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates

- [cuda-sensor-agent](https://github.com/Lucineer/cuda-sensor-agent)
- [cuda-resolve-agent](https://github.com/Lucineer/cuda-resolve-agent)
- [cuda-world-model](https://github.com/Lucineer/cuda-world-model)
- [cuda-weather](https://github.com/Lucineer/cuda-weather)

## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
