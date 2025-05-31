
# Explore UV Project

This project demonstrates how to create and set up a Python project using **UV**, a fast Python package manager and environment manager.

## 📦 Prerequisites

- Python installed
- [UV installed](https://github.com/astral-sh/uv)
- Visual Studio Code (VSCode)

## 🚀 Setup Instructions

### 1. Check UV Installation

```bash
uv --version
uv --help
```

### 2. Initialize a New Project

```bash
uv init --package explore-uv
```

This creates a new Python project structure with `src/` directory following best practices.

### 3. Open the Project in VSCode

```bash
cd explore-uv
code .
```

### 4. Create a Virtual Environment

```bash
uv venv
```

### 5. Activate the Virtual Environment

**Linux/macOS:**

```bash
source .venv/bin/activate
```

**Windows:**

```cmd
.venv\Scripts\activate
```

### 6. Select the Python Interpreter in VSCode

Choose the Python interpreter from `.venv/bin/python` to ensure VSCode uses the virtual environment.

### 7. Run the Project

```bash
uv run explore-uv
```

This command executes your main application file.

## 📁 Project Structure

```
explore-uv/
├── .venv/               # Virtual environment
├── pyproject.toml       # Project configuration
├── src/
│   └── explore_uv/      # Main source code package
│       └── __init__.py
└── README.md            # Project documentation
```

## 📚 References

- [UV Documentation](https://github.com/astral-sh/uv)
- [PEP 621 - Python packaging](https://peps.python.org/pep-0621/)
