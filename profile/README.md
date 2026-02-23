# Starlet Engine

**Starlet Engine** is a long-term personal exploration of C++ engine architecture, graphics systems, and developer tooling. It prioritizes small, composable libraries over monolithic designs, with experimentation as a core principle.

The organization houses focused modules for rendering, scene management, math, serialization, and input, alongside engine samples, experimental sandboxes, and build automation. Everything is designed around mono-repo development via [`starlet-setup`](https://github.com/starlet-engine/starlet-setup).

> This is not intended to be a publicly released framework, production engine, or drop-in library. It's an experimental lab for personal C++ programming.

## Quick Start

- **Start a project** -> [`starter`](https://github.com/starlet-engine/starter) Project template wired to the engine and libraries.
- **See examples** -> [`samples`](https://github.com/starlet-engine/samples) Example scenes and experiments demonstrating rendering, scenes, and input.
- **Mono-repo development** -> [`starlet-setup`](https://github.com/starlet-engine/starlet-setup) Tooling for cloning, configuring, and building Starlet projects

## Repositories

### Experiments
- **[`noise-sandbox`](https://github.com/starlet-engine/noise-sandbox)** — Experimental noise algorithms
- **[`image-sandbox`](https://github.com/starlet-engine/image-sandbox)** — Image loading and format experiments

### Core Libraries
- **[`engine`](https://github.com/starlet-engine/engine)** — Core engine and orchestration layer
- **[`graphics`](https://github.com/starlet-engine/graphics)** — Rendering, shaders, meshes, and textures
- **[`controls`](https://github.com/starlet-engine/controls)** — Input and control handling
- **[`scene`](https://github.com/starlet-engine/scene)** — ECS-based scene management
- **[`math`](https://github.com/starlet-engine/math)** — Lightweight header-only math utilities
- **[`logger`](https://github.com/starlet-engine/logger)** — Logging tooling
- **[`serializer`](https://github.com/starlet-engine/serializer)** — File and data serialization utilities
- **[`testing`](https://github.com/starlet-engine/testing)** — Future cross-library unit and integration testing

### Tooling
- **[`starlet-setup`](https://github.com/starlet-engine/starlet-setup)** — Python utility for cloning, configuring, and building Starlet projects for mono-repo development
- **[`.github`](https://github.com/starlet-engine/.github)** — Organization-level configuration and documentation


