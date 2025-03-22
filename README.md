# Getting Started with Python in Robotics

This is the repository for **Getting Started with Python in Robotics**. It contains a single notebook covering Python basics up to object-oriented programming (OOP):

- **[Python Basics](notebooks/python_basics.ipynb)**

The notebook is designed to help you learn Python for robotics applications.

---

## 🛠 Installation Guide

You can install Python using `pyenv` (recommended) or without it. Follow the instructions below for your operating system.

### Using Pyenv (Recommended)

**1. Install pyenv:**

- **macOS**:
  ```bash
  brew install pyenv
  ```
- **Linux**:
  ```bash
  curl https://pyenv.run | bash
  ```
- **Windows**:
  Use [pyenv-win](https://github.com/pyenv-win/pyenv-win) with the following command:
  ```powershell
  winget install pyenv-win
  ```

**2. Install Python**

- Install a specific Python version using `pyenv install`:

  ```bash
  pyenv install 3.x.x
  ```

  This downloads and compiles the specified Python version.

- Set the installed version as the global default with `pyenv global`:
  ```bash
  pyenv global 3.x.x
  ```
  This makes it the default Python version across your system.

**3. Verify Installation**

- Confirm Python is installed and accessible:
  ```bash
  python --version
  ```
  This should display the installed version.

**Additional Pyenv Commands:**

- `pyenv versions` - Lists all installed Python versions.
- `pyenv local <version>` - Sets a Python version for the current directory.
- `pyenv uninstall <version>` - Uninstalls a specified Python version.

---

### Without Pyenv

**1. macOS and Linux:**

- Install using your package manager.
  - macOS: `brew install python`
  - Ubuntu: `sudo apt install python3 python3-pip`

**2. Windows:**

- Download from the [official Python website](https://www.python.org/downloads/).
- Ensure "Add Python to PATH" is checked during installation.

**3. Verify Installation:**

- Check the installed version of Python and Pip:
  ```bash
  python --version
  pip --version
  ```

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Getting-Started-with-Python-in-Robotics.git
   cd Getting-Started-with-Python-in-Robotics
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

Open `notebooks/python_basics.ipynb` and follow along to learn Python.

---

## 📧 Support

If you have any issues, feel free to create an issue in the repository or reach out via GitHub Discussions.

---

## 📜 License

This project is licensed under the GPLv3 License.
