# root_termux

`root_termux` is a Bash-based script that allows you to simulate root access inside Termux by installing and running an Ubuntu environment with root privileges (within Ubuntu only). It provides a safe testing environment without requiring real root access on your Android device.

---

## 🚀 Features

- Runs Ubuntu inside Termux
- Enables simulated root access inside Ubuntu
- No real root required on the Android device
- Lightweight and easy to set up

---

## 📱 Requirements

- Android device
- Termux installed
- Stable internet connection
- At least 3 GB of free storage

---

## ⚙️ Installation & Usage

Open Termux and run the following commands:

```bash
pkg update && pkg upgrade -y
git clone https://github.com/YourUsername/root-termux.git
cd root-termux
chmod +x *
bash install.sh
bash start.sh
