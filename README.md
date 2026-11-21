# DarkCipher-OS

**DarkCipher-OS** is an all-in-one, menu-driven Termux customization and optimization tool crafted by **DarkCipherBPBD**. Easily personalize your Termux terminal with custom ASCII welcome banners, shell usernames, Zsh/Fish/Bash themes, Nerd Fonts, 11+ color schemes, extra keyboard layouts, and session lock security.

---

## Features
- **Custom Welcome Banner & Shell Username:** Set your own ASCII banner text (with `ANSI Shadow` and multiple FIGlet fonts + Rainbow `lolcat` support) and custom shell prompt username (`DarkCipher@termux`).
- **Multi-Shell Support:** Full automated setup & customization for **Bash** (`ble.sh`), **Zsh** (`Oh My Zsh` + autosuggestions & syntax highlighting), and **Fish**.
- **11+ Built-in Color Themes:** Default (Gunmetal), Dracula, Nord, Monokai, Solarized Dark, Gruvbox, Tokyo Night, Catppuccin, Ayu Dark, Cobalt2, and One Half Dark.
- **Nerd Fonts Gallery:** One-click installation for Fira Code, JetBrains Mono, Hack, Caskaydia Cove, Source Code Pro, Ubuntu, and Meslo Nerd Fonts.
- **Termux Behavior & Extra Keys:** Configure cursor style, blinking, extra keys rows, bell sound/vibrate, fullscreen mode, and back-key behavior.
- **Cyber Lock Security:** Add or remove password lock protection on terminal startup.

---

## Installation & Usage

1. **Update Termux & install Git:**
   ```bash
   pkg update -y && pkg install git -y
   ```

2. **Clone this repository & enter the folder:**
   ```bash
   git clone https://github.com/DarkCipherBPBD/DarkCipher-OS.git
   cd DarkCipher-OS
   ```

3. **Give permission and run the tool:**
   ```bash
   chmod +x os.sh
   bash os.sh
   ```

4. **First-time Setup:**
   - Select **`01` (Necessary Setup)** from the main menu to automatically install required packages (`zsh`, `fish`, `figlet`, `toilet`, `ruby`, `lolcat`, `eza`, `bat`, etc.) and fonts.
   - Then choose **`02` (Zsh)**, **`03` (Fish)**, or **`04` (Bash)** -> **`03` (Customize Prompt & Welcome Banner)** to set your custom banner name and shell username!

---

## Author
- **Name:** DarkCipherBPBD (Dark Cipher)
- **GitHub:** [github.com/DarkCipherBPBD](https://github.com/DarkCipherBPBD)
