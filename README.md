[update-readmes]   Mode: rewrite — migrating to template structure...
# penguins-kernel-manager

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/penguins-kernel-manager)

<!-- AI:start:what-it-does -->
This project provides a tool for building, installing, and managing Linux kernels across various distributions and architectures. It is designed for developers and system administrators who need a unified interface for handling custom kernels, with support for integration into the Penguins ecosystem tools like Penguins Eggs and Penguins Recovery. The project includes both CLI and GUI options and supports extensibility through plugins.
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
The project is structured as a Python package with CLI and GUI entry points for managing Linux kernels across distributions and architectures. The main components include:

1. **CLI (`penguins_kernel_manager/cli`)**: Implements command-line functionality for kernel management tasks.
2. **GUI (`penguins_kernel_manager/gui`)**: Provides a graphical interface using PySide6 or PyQt6 for kernel management.
3. **Integration scripts (`integration`)**: Contains plugins for Penguins Eggs and Penguins Powerwash tools, enabling seamless integration with related projects.
4. **Tests (`tests`)**: Includes unit tests for verifying functionality.
5. **Profiles (`profiles`)**: Stores configuration files and templates for supported distributions and kernel variants.
6. **Scripts (`scripts`)**: Utility scripts for development and deployment tasks.

The directory structure is as follows:

```plaintext
.
├── .github/                # GitHub workflows
├── integration/            # Integration scripts for related tools
│   ├── eggs-plugin/
│   └── recovery-plugin/
├── penguins_kernel_manager/ # Main Python package
│   ├── cli/
│   ├── gui/
│   ├── core/
│   └── utils/
├── profiles/               # Kernel and distro profiles
├── scripts/                # Development and deployment scripts
├── tests/                  # Unit tests
├── Makefile                # Build and integration targets
├── pyproject.toml          # Python project configuration
├── README.md               # Project documentation
└── LICENSE                 # License file
```
<!-- AI:end:architecture -->

## Install


```bash
# CLI only
pip install penguins-kernel-manager

# GUI (PySide6 — recommended, LGPL)
pip install "penguins-kernel-manager[pyside6]"

# GUI (PyQt6 — alternative, GPL)
pip install "penguins-kernel-manager[pyqt6]"
```

---

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/penguins-kernel-manager`](https://github.com/Interested-Deving-1896/penguins-kernel-manager) and mirrored through:

```
Interested-Deving-1896/penguins-kernel-manager  ──►  OpenOS-Project-OSP/penguins-kernel-manager  ──►  OpenOS-Project-Ecosystem-OOC/penguins-kernel-manager
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[GPL-3.0](https://github.com/Interested-Deving-1896/penguins-kernel-manager/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
