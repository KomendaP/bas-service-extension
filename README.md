# BAS Service Extension Releases

This repository contains official release builds (.vsix files) of the BAS Service Extension for Visual Studio Code.

## Release History

| Version                    | Release Date | Changes         | Download Link                                       |
| -------------------------- | ------------ | --------------- | --------------------------------------------------- |
| [0.0.1](CHANGELOG.md#v001) | 2025-02-04   | Initial release | [Download](releases/archive/bas-service-0.0.1.vsix) |

## Repository Structure

```

/releases
├── bas-service-x.x.x.vsix # Latest version
└── archive/ # Previous versions
└── bas-service-x.x.x.vsix

```

## Installation Instructions

### Manual Installation

1. Download the desired `.vsix` file from this repository
2. Open VS Code
3. Press `Ctrl+Shift+P` to open command palette
4. Type "Install from VSIX" and select the command
5. Navigate to the downloaded `.vsix` file and select it

### Command Line Installation

```bash
code --install-extension path/to/bas-service-x.x.x.vsix
```

## Version Naming Convention

Versions follow semantic versioning (MAJOR.MINOR.PATCH):

- MAJOR: Breaking changes
- MINOR: New features, backwards compatible
- PATCH: Bug fixes, backwards compatible

## Notes

- Only official releases are stored in this repository
- Each release is tested and verified before publishing
- Previous versions are maintained in the `/archive` folder
