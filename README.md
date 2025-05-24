
[![Runner gif](https://github.com/hackesofice/Z/blob/main/all-in-one-tool/all_in_one_runner.gif)](https://github.com/hackesofice)

# All-in-One Runner Tool

**Automate your Termux workflow with ease!**  
This tool streamlines the startup process for commonly used servers and utilities, such as `acodex_server` and Live Server, making your development environment setup effortless.

---

## ⚠️ Disclaimer

- **Designed for Termux**: This tool is specifically built for the default `sh` shell in the Termux app on Android.  
- **Compatibility**: It may not work as intended on other terminals or shells.  
- **Beginner-Friendly**: If you’re new to Termux or unsure about shells, don’t worry—this tool is made for you!

---

## 🚀 Quick Start Guide

Follow these simple steps to set up the All-in-One Runner Tool:

### 1. Install Termux

- [Download Termux APK](https://f-droid.org/repo/com.termux_1000.apk) from F-Droid.  
- Install and open the Termux app on your Android device.

### 2. Install the Tool

Copy and paste the following commands into your Termux terminal, then press Enter:

```
rm -rf all-in-one-starter
pkg update && pkg upgrade
pkg install jq -y
termux-setup-storage
pkg install git -y
git clone https://github.com/hackesofice/all-in-one-runner.git
cd all-in-one-runner
mv main.sh .bashrc
mv .bashrc ~/
```

> **Note:**  
> This setup is required only once. The tool can automatically update itself to provide the latest features and improvements.

---

## ✨ Features

1. **Automatic Updates**  
   Stay up-to-date effortlessly. The tool checks for new versions and upgrades itself automatically.

2. **Automatic Dependency Installation**  
   No more manual installs! The tool detects and installs any required packages for the selected services.

3. **Autostart Acodex Server (AXS)**  
   Instantly set up and launch the [Acodex Server (Rust version)](https://github.com/hackesofice/acodex_server) for terminal access within the Acode app.

4. **Autostart Live Server**  
   Quickly spin up the backend server for Acode’s live preview feature with minimal prompts.

---

## 💡 Why Use This Tool?

- **Saves Time:** Automates repetitive setup tasks.  
- **Beginner-Friendly:** Minimal commands to remember.  
- **Always Updated:** Get the latest features without manual intervention.  
- **Seamless Integration:** Designed specifically for the Termux environment.

---

## 🛠️ Contribution & Support

- **Found a bug or have a suggestion?**  
  [Open an issue](https://github.com/hackesofice/all-in-one-runner/issues) on GitHub.  
- **Want to contribute?**  
  Pull requests are welcome! We appreciate all forms of contributions.

---

**Explore more projects and connect with the developer:**  
[GitHub: hackesofice](https://github.com/hackesofice)


