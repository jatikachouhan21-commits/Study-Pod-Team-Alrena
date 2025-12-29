# Python & pip Command Cheat Sheet

Here’s a practical **Python & pip Command Cheat Sheet** 🐍📦 — perfect for quick reference while coding, managing packages, or setting up environments.

---

## 🐍 Python CLI Essentials

| Command                           | Description                 |
| --------------------------------- | --------------------------- |
| `python` or `python3`             | Start Python REPL           |
| `python script.py`                | Run a Python script         |
| `python -m module_name`           | Run a module as a script    |
| `python -V` or `python --version` | Show Python version         |
| `python -m venv env_name`         | Create virtual environment  |
| `source env_name/bin/activate`    | Activate venv (Linux/macOS) |
| `env_name\Scripts\activate`       | Activate venv (Windows)     |
| `deactivate`                      | Exit virtual environment    |

---

## 📦 pip Package Management

| Command                              | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| `pip install package_name`           | Install a package                                |
| `pip install package==version`       | Install specific version                         |
| `pip install -r requirements.txt`    | Install from requirements file                   |
| `pip uninstall package_name`         | Uninstall a package                              |
| `pip list`                           | List installed packages                          |
| `pip freeze`                         | Output installed packages (for requirements.txt) |
| `pip show package_name`              | Show package details                             |
| `pip search keyword`                 | Search PyPI (deprecated in newer versions)       |
| `pip install --upgrade package_name` | Upgrade a package                                |
| `pip check`                          | Check for broken dependencies                    |

---

## 🧪 Virtual Environment Workflow

```bash
# Create and activate venv
python -m venv venv_name
source venv_name/bin/activate  # macOS/Linux
venv_name\Scripts\activate     # Windows

# Install packages
pip install flask numpy pandas

# Save environment
pip freeze > requirements.txt

# Rebuild environment
pip install -r requirements.txt
```

---
