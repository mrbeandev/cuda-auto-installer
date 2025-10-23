# CUDA Auto Installer Project

The aim of this project is to build a Python script that can automatically install the NVIDIA driver's CUDA toolkit compatible with the system's GPU and PyTorch.

## Features

- Detect NVIDIA GPU presence
- Auto-detect CUDA version requirements
- Ask user about virtual environment creation
- Install CUDA toolkit (if not present)
- Install PyTorch with CUDA support
- Verify installation

## Usage

After installing the package:

```bash
ai-gpu-pkgs setup
```

## Project Structure

- `cuda_installer.py`: Main script with installation logic
- `pyproject.toml`: Package configuration for PyPI
- `README.md`: Package documentation
- `.gitignore`: Git ignore file

## Development

1. Clone the repository
2. Create virtual environment: `python -m venv .venv`
3. Activate: `.venv\Scripts\activate` (Windows)
4. Install in dev mode: `pip install -e .`
5. Test: `ai-gpu-pkgs --help`
