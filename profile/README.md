# Starlet Libraries

**Starlet Libraries** is a long-term personal exploration of C++ engine architecture, graphics systems, and developer tooling. It prioritizes small, composable libraries over monolithic designs, with experimentation as a core principle.

[![License](https://img.shields.io/github/license/starlet-libs/.github)](https://github.com/starlet-libs/.github/blob/main/LICENSE)

> This is not intended to be a publicly released framework, production engine, or drop-in library. It's an experimental lab for personal C++ programming.

The organization houses focused modules for rendering, scene management, math, serialization, and input, alongside engine samples, experimental sandboxes, and build automation. Everything is designed around mono-repo development via [`star-setup`](https://github.com/star-setup).

## Quick Start

- **Mono-repo development** -> [`star-setup`](https://github.com/star-setup/core) Tooling for cloning, configuring, and building Starlet projects
- **See examples** -> [`starlet-samples`](https://github.com/masonlet/starlet-samples) Example scenes and experiments demonstrating rendering, scenes, and input.
- **Start a project** -> [`template-game`](https://github.com/starlet-libs/template-game) Project template wired to the engine and libraries.

## Repositories

| Name/Category | URL(s) | Description |
| ------------- | ------ | ----------- |
| Games                                |
| Noise Sandbox | [GitHub](https://github.com/masonlet/starlet-noise-sandbox) | Experimental noise algorithms |
| Image Sandbox | [GitHub](https://github.com/masonlet/starlet-image-sandbox) | Image loading and format experiments |
| Samples       | [GitHub](https://github.com/masonlet/starlet-samples) | Example scenes demonstrating rendering, scene management, and input |
| Libraries                            |
| Engine        | [GitHub](https://github.com/starlet-libs/engine) | Core engine and orchestration layer |
| Graphics      | [GitHub](https://github.com/starlet-libs/graphics) | Rendering, shaders, meshes, and textures |
| Controls      | [GitHub](https://github.com/starlet-libs/controls) | Input and control handling |
| Scene         | [GitHub](https://github.com/starlet-libs/scene) | ECS-based scene management |
| Math          | [GitHub](https://github.com/starlet-libs/math) | Lightweight header-only math utilities |
| Logger        | [GitHub](https://github.com/starlet-libs/logger) | Logging tooling |
| Serializer    | [GitHub](https://github.com/starlet-libs/serializer) | File and data serialization utilities |
| Testing       | [GitHub](https://github.com/starlet-libs/testing) | Future cross-library unit and integration testing |
| Tooling                              |
| Star Setup    | [GitHub](https://github.com/star-setup), [npm](https://www.npmjs.com/package/@star-setup/star-setup) | Tool for cloning, configuring, and building Starlet projects for single and mono-repo development |
| .github       | [GitHub](https://github.com/starlet-libs/.github) | Organization-level configuration and documentation |
