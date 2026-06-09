# Starlet Libraries

**Starlet Libraries** is a long-term personal exploration of C++ engine architecture, graphics systems, and developer tooling. It prioritizes small, composable libraries over monolithic designs, with experimentation as a core principle.

The organization houses focused modules for rendering, scene management, math, serialization, and input, alongside engine samples, experimental sandboxes, and build automation. Everything is designed around mono-repo development via [`starlet-setup`](https://github.com/masonlet/starlet-setup).

> This is not intended to be a publicly released framework, production engine, or drop-in library. It's an experimental lab for personal C++ programming.

## Quick Start

- **Mono-repo development** -> [`starlet-setup`](https://github.com/masonlet/starlet-setup) Tooling for cloning, configuring, and building Starlet projects
- **See examples** -> [`starlet-samples`](https://github.com/masonlet/starlet-samples) Example scenes and experiments demonstrating rendering, scenes, and input.
- **Start a project** -> [`template-game`](https://github.com/starlet-libs/template-game) Project template wired to the engine and libraries.

## Repositories

### Games
- **[`starlet-noise-sandbox`](https://github.com/masonlet/starlet-noise-sandbox)** — Experimental noise algorithms
- **[`starlet-image-sandbox`](https://github.com/masonlet/starlet-image-sandbox)** — Image loading and format experiments
- **[`starlet-samples`](https://github.com/masonlet/starlet-samples)** — Example scenes demonstrating rendering, scene management, and input

### Core Libraries
- **[`engine`](https://github.com/starlet-libs/engine)** — Core engine and orchestration layer
- **[`graphics`](https://github.com/starlet-libs/graphics)** — Rendering, shaders, meshes, and textures
- **[`controls`](https://github.com/starlet-libs/controls)** — Input and control handling
- **[`scene`](https://github.com/starlet-libs/scene)** — ECS-based scene management
- **[`math`](https://github.com/starlet-libs/math)** — Lightweight header-only math utilities
- **[`logger`](https://github.com/starlet-libs/logger)** — Logging tooling
- **[`serializer`](https://github.com/starlet-libs/serializer)** — File and data serialization utilities
- **[`testing`](https://github.com/starlet-libs/testing)** — Future cross-library unit and integration testing

### Tooling
- **[`starlet-setup`](https://github.com/masonlet/starlet-setup)** — Python utility for cloning, configuring, and building Starlet projects for mono-repo development
- **[`.github`](https://github.com/starlet-libs/.github)** — Organization-level configuration and documentation


