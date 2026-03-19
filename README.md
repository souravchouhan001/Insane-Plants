# 🌱 Insane-Plants - Easy 10-Channel Plant Watering

[![Download Insane-Plants](https://img.shields.io/badge/Download-Insane--Plants-brightgreen?style=for-the-badge)](https://github.com/souravchouhan001/Insane-Plants/releases)

---

## 📋 About Insane-Plants

Insane-Plants is a smart watering system made for plant lovers. It uses an ESP8266-based Wemos D1 Mini board. The system controls 10 watering channels and checks soil moisture with 10 capacitive sensors. It also measures temperature with a DS18B20 sensor. The setup includes strong pump drivers and safety features. This way, it waters your plants only when needed and keeps everything safe.

You don’t need to be an expert to use it. This guide will help you get it running step by step on a Windows PC.

---

## ⚙️ What You Need

- A Windows computer (Windows 7 or later)
- Internet access to download files
- USB cable (usually micro-USB) to connect to Wemos D1 Mini
- The Wemos D1 Mini board with the assembled Insane-Plants hardware

---

## 💾 Where to Download

To get the software, visit the release page:

[![Download Here](https://img.shields.io/badge/Download-Insane--Plants-blue?style=for-the-badge)](https://github.com/souravchouhan001/Insane-Plants/releases)

This page holds all the files you need. Look for the latest version marked as stable.

---

## 🚀 Getting Started: Download and Install

1. **Open the release page** linked above in your web browser.

2. **Find the latest release section.** You’ll see files listed under it.

3. **Download the Windows executable or installer file.** It usually ends with `.exe` or `.msi`.

4. **Once downloaded, locate the file** in your ‘Downloads’ folder using File Explorer.

5. **Double-click to run the file.** If Windows shows a security warning, click ‘Run’ or ‘Yes’ to continue.

6. **Follow the on-screen instructions.** Accept license terms and pick an install folder if asked.

7. **Finish the installer.** It creates a shortcut on your desktop or start menu.

---

## 🔌 Connect Your Devices

1. **Plug the Wemos D1 Mini into your computer** using the USB cable.

2. Windows may install drivers automatically. If not, you may need to install drivers for the USB-to-serial chip on the board.

3. Check Device Manager (press `Win + X` and select ‘Device Manager’) to ensure the board shows under ‘Ports (COM & LPT).’

4. Note the COM port number assigned to your device (e.g., COM3, COM4).

---

## 🖥️ Running the Software

1. **Open the installed Insane-Plants application** from your desktop or start menu.

2. The software will ask you to select the COM port. Choose the one that corresponds to your Wemos board.

3. Click ‘Connect’ or ‘Start’ to link the software with your hardware.

4. You will see sensor readings like soil moisture and temperature.

5. The software lets you control pumps for each plant channel.

6. Use the interface to start or stop watering as needed.

---

## ✔️ System Requirements

- Windows 7, 8, 10, or 11  
- At least 100 MB free disk space  
- USB 2.0 or higher port  
- Internet connection (for downloading updates)  
- Wemos D1 Mini board with Insane-Plants hardware assembled

---

## 🔧 Tips for Best Use

- Place sensors properly into the soil near roots for accurate moisture readings.

- Use good-quality USB cables to avoid connection issues.

- If pump control does not respond, verify the COM port and cable connection.

- Keep your system up to date by checking the release page regularly.

---

## 🛠️ Troubleshooting

- **App does not detect Wemos board:**  
  - Check USB cable connection.  
  - Install USB-to-serial drivers manually.  
  - Restart the app and reconnect.

- **Sensor readings stay constant or zero:**  
  - Make sure sensors are properly connected.  
  - Restart the device and app.  
  - Check wiring for damage.

- **Pumps do not activate:**  
  - Verify pump driver board is powered.  
  - Double-check software control settings.  
  - Try another USB port or cable.

---

## 📚 Additional Resources

- Visit the release page: https://github.com/souravchouhan001/Insane-Plants/releases  
- Look up ESP8266 and Wemos D1 Mini basics online for more hardware info.  
- Use forums and communities for assistance with IoT and DIY electronics.

---

## 🔗 More Downloads

You can always visit the releases page to get updates or alternative downloads:

[Download Insane-Plants from Releases](https://github.com/souravchouhan001/Insane-Plants/releases)