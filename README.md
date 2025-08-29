# ✨ SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES ✨

<p align="center">
  <a href="https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" alt="License: GPL v3">
  </a>
  <a href="https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/issues">
    <img src="https://img.shields.io/github/issues/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES?color=brightgreen" alt="GitHub issues">
  </a>
  <a href="https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/pulls">
    <img src="https://img.shields.io/github/issues-pr/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES?color=informational" alt="GitHub pull requests">
  </a>
  <a href="https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/stargazers">
    <img src="https://img.shields.io/github/stars/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES?style=social" alt="GitHub stars">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/repo-size/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES" alt="Repo size">
  <img src="https://img.shields.io/github/last-commit/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES" alt="GitHub last commit">
  <img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg" alt="Made with Bash">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux compatible">
</p>

A simple yet effective Bash script to display the active and available I/O schedulers for all block devices on your Linux system. It provides a quick, colorful, and easy-to-read overview of your system's I/O configuration.

---

## 🚀 Features

-   **Comprehensive View**: Lists I/O schedulers for all detected block devices (`/dev/sda`, `/dev/nvme0n1`, etc.).
-   **Clear Highlighting**: The active scheduler is clearly marked with `[]` brackets.
-   **Colorful Output**: Uses `tput` for colored terminal output to enhance readability.
-   **Minimalist & Fast**: A lightweight script with minimal dependencies.

## 🖥️ Compatibility

This script is designed for Linux and is compatible with most modern distributions, including:

-   ✅ Debian
-   ✅ Ubuntu
-   ✅ Linux Mint
-   ✅ Other Debian/APT-based derivatives

## 🛠️ Dependencies

The script relies on a few common command-line utilities. Before running, please ensure they are installed. The script does not currently install dependencies automatically.

-   **`tput`**: Part of the `ncurses-bin` package. It's used for terminal coloring and is almost always pre-installed.
-   **`grep`**: A standard utility, available on all Linux systems.

You can typically install `ncurses-bin` on Debian-based systems with:
```bash
sudo apt-get update && sudo apt-get install -y ncurses-bin
```

### Optional Dependency

-   **`lolcat`**: For a fun, rainbow-colored output! The script contains commented-out lines that use `lolcat`. If you'd like to try it, install `lolcat` and uncomment those lines in the script.
    ```bash
    sudo apt-get install -y lolcat
    ```

## ⚙️ Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES.git
    cd SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES
    ```

2.  **Make the script executable:**
    ```bash
    chmod +x custom-SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES.sh
    ```

3.  **Run the script:**
    ```bash
    ./custom-SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES.sh
    ```

## 💬 Contributing

[Pull requests, issues, and suggestions are warmly welcomed!](https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/blob/main/CONTRIBUTING.md)
See [CONTRIBUTING.md](https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/blob/main/CONTRIBUTING.md) for guidelines.

## 🌐 Links

-   [**Issues**](https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/issues)
-   [**Pull Requests**](https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/pulls)
-   [**Releases**](https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/releases)
-   [**Wiki**](https://github.com/LINUX-OASIS/SHOW-IOSCHEDULER-FOR-ALL-BLOCK-DEVICES/wiki)

## 🧙‍♂️ Maintainer

This project is maintained by [**LINUX-OASIS**](https://github.com/LINUX-OASIS).

## 📄 License

This project is licensed under the GNU General Public License v3.0. See the `LICENSE` file for details.
