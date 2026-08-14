# Kalcite Engine

Kalcite is a predictable compiled language and a Rust 2D engine for constrained
platforms. It prioritizes explicit memory use: no virtual machine, no garbage
collector, and no implicit allocation in the runtime model.

## Projects

| Project | Description | Links |
| --- | --- | --- |
| [Kalcite](https://github.com/Kalcite-Engine/kalcite) | Language, compiler, runtime, 2D engine, CLI, and platform backends. | [Repository](https://github.com/Kalcite-Engine/kalcite) · [Issues](https://github.com/Kalcite-Engine/kalcite/issues) |
| [Kally](https://github.com/Kalcite-Engine/kally) | Package Manager, based on git | [Repository](https://github.com/Kalcite-Engine/kally) · [Issues](https://github.com/Kalcite-Engine/kally/issues) |
| [Kalcite LSP](https://github.com/Kalcite-Engine/kalcite-lsp) | Independent Language Server Protocol implementation for editor tooling. | [Repository](https://github.com/Kalcite-Engine/kalcite-lsp) · [Issues](https://github.com/Kalcite-Engine/kalcite-lsp/issues) |
| [Kalcite Editor](https://github.com/Kalcite-Engine/kalcite-editor) | Independent native graphical editor for Kalcite projects. | [Repository](https://github.com/Kalcite-Engine/kalcite-editor) · [Issues](https://github.com/Kalcite-Engine/kalcite-editor/issues) |
| [Documentation](https://github.com/Kalcite-Engine/kalcite-docs) | The versioned manual for users and contributors. | [Read the docs](https://kalcite-engine.github.io/kalcite-docs/) · [Repository](https://github.com/Kalcite-Engine/kalcite-docs) |
| [Website](https://github.com/Kalcite-Engine/kalcite-website) | Project overview, product direction, and platform information. | [Visit the site](https://kalcite-engine.github.io/kalcite-website/) · [Repository](https://github.com/Kalcite-Engine/kalcite-website) |

## Start here

```bash
git clone --recurse-submodules https://github.com/Kalcite-Engine/kalcite.git
cd kalcite
cargo test --workspace
```

Kalcite uses Rust 1.85.0. The NumWorks target additionally requires the
`thumbv7em-none-eabihf` Rust target; the complete setup is in the
[documentation](https://kalcite-engine.github.io/kalcite-docs/getting-started/installation/).

## Contributing

Contributions, issue reports, and documentation improvements are welcome. Read
the [contribution guide](https://github.com/Kalcite-Engine/kalcite/blob/main/CONTRIBUTING.md)
before opening a pull request.
