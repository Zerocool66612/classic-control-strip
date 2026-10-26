# Classic Control Strip

**A classic Mac OS 9-inspired Control Strip for Linux, created by Drew Owen as part of the MacaqueOS project.**

Classic Control Strip brings a customizable retro desktop toolbar to KDE Plasma on Wayland, built with C++ and Qt 6 / LayerShellQt.

## Features

- Classic Platinum, Light, Dark and additional preset themes
- Theme creator with custom colors, backgrounds and textures
- Custom per-module icons and a visual icon editor
- Import/export of portable themes
- Movable and edge-attached Control Strip
- Volume, display, storage, memory, network and other Linux controls
- Startup settings and multi-monitor selection

## Build

On a Linux system with Qt 6 Widgets, LayerShellQt, CMake and a C++ compiler installed:

```bash
cmake -S . -B build
cmake --build build -j$(nproc)
./build/classic-control-strip
```

Some controls use external Linux utilities and may require additional packages or appropriate permissions.

## Status

**Version 2.0.1 — early public source release.** Developed and tested interactively on Kubuntu/KDE Wayland. This project is still under development; compatibility with other desktop environments is not guaranteed.

## Creator

**Drew Owen** — creator and project lead, MacaqueOS.

GitHub: [@Zerocool66612](https://github.com/Zerocool66612)

## License

License selection pending. Please do not assume the source is open-source licensed until a license file is added.

## Acknowledgment

Built with AI-assisted development and iterative testing.
