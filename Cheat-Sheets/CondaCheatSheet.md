# Conda Command Cheat Sheet

Here's a handy **Conda Command Cheat Sheet** 🐍 to help you manage environments, packages, and configurations efficiently.

---

## 🧪 Environment Management

| Command                                | Description                             |
| -------------------------------------- | --------------------------------------- |
| `conda create -n env_name`             | Create a new environment                |
| `conda create -n env_name python=3.10` | Create env with specific Python version |
| `conda activate env_name`              | Activate an environment                 |
| `conda deactivate`                     | Deactivate current environment          |
| `conda env list`                       | List all environments                   |
| `conda remove -n env_name --all`       | Delete an environment                   |

---

## 📦 Package Management

| Command                                  | Description                     |
| ---------------------------------------- | ------------------------------- |
| `conda install package_name`             | Install a package               |
| `conda install package_name=version`     | Install specific version        |
| `conda install -n env_name package_name` | Install in specific environment |
| `conda update package_name`              | Update a package                |
| `conda remove package_name`              | Remove a package                |
| `conda list`                             | List installed packages         |
| `conda search package_name`              | Search for available versions   |

---

## 📁 Environment Export & Rebuild

| Command                                        | Description                |
| ---------------------------------------------- | -------------------------- |
| `conda env export > environment.yml`           | Export current environment |
| `conda env create -f environment.yml`          | Create env from YAML file  |
| `conda list --explicit > spec.txt`             | Export exact package specs |
| `conda create --name env_name --file spec.txt` | Rebuild env from spec file |

---

## 🔧 Configuration & Info

| Command                                       | Description                  |
| --------------------------------------------- | ---------------------------- |
| `conda info`                                  | Show Conda info              |
| `conda config --show`                         | Show config settings         |
| `conda config --add channels channel_name`    | Add a new channel            |
| `conda config --set auto_activate_base false` | Disable auto base activation |

---

## 🧼 Cleanup & Maintenance

| Command              | Description                       |
| -------------------- | --------------------------------- |
| `conda clean --all`  | Remove unused packages and caches |
| `conda update conda` | Update Conda itself               |

---
