# Python Lab

This is a Python development environment set up with Dev Containers.

## Getting Started

1. Open this repository in VS Code
2. Install the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension
3. Run the command `Remote-Containers: Reopen in Container`
4. The development container will build and launch automatically

## Features

- Python 3.14 environment
- Pre-installed Python extensions for VS Code
- Docker-in-Docker support
- GitHub CLI integration
- Automatic dependency installation from `requirements.txt`

## Customization

To customize the Python version or add additional tools:
1. Modify the `devcontainer.json` file
2. Update the `Dockerfile` for system-level changes
3. Add Python dependencies to `requirements.txt`

## Development Tips

- All Python extensions and linters are pre-configured
- The container automatically installs dependencies listed in `requirements.txt`
- Use the integrated terminal for running Python scripts
- Debugging support is included with the Python extension