# 🎨 YunuWallEngine V1.0

<img width="1359" height="767" alt="image" src="https://github.com/user-attachments/assets/6da1c973-2e22-4f1b-accc-7f2162442ac5" />

<img width="1366" height="768" alt="gambar" src="https://github.com/user-attachments/assets/5dd57f0c-f5e8-419d-8d1d-bd70e13c2bd0" />

## What is YunuWallEngine?

A **ultra-lightweight video wallpaper engine** optimized for low-spec computers (2GB RAM). Run smooth animated wallpapers without lag, stuttering, or excessive CPU/GPU usage—even on decade-old laptops.

**Perfect for:**
- Old laptops / budget PCs
- Office computers with strict spec limits
- Users who want beautiful wallpapers without performance cost
- Anyone tired of static wallpapers

---

## 🔥 What's New in Latest Release

### 🪟 Windows Build *(OFFICIAL RELEASE V1.2.1 🎉)*

<img width="496" height="550" alt="gambar" src="https://github.com/user-attachments/assets/f2f32f44-e28d-4b98-ae15-3ed88b9b19c6" />

* 🎯 **Code Refactoring & Core Efficiency:** Stripped down and refactored bloated code into an ultra-lean structure. Drastically reduced unnecessary variables to minimize overhead and maximize execution efficiency.
* ⚡ **Enhanced Wallpaper Optimization:** Upgraded the wallpaper optimization algorithm for lightning-fast speeds. Re-engineered the process to be as lightweight and efficient as possible on system resources.
* 🖼️ **Asynchronous UI Thumbnail:** Fixed preview rendering lags by offloading the task entirely to the background. Runs fully asynchronously to guarantee a smooth, freeze-free GUI experience during thumbnail loads.

### 🪟 Windows Build *(NEW RELEASE V1.2.0 🎉)*

* 🎯 **Smart Aspect Ratio (Bangkit Scale Ported):** The core feature from Linux is now on Windows! Automatically detects video resolution via background FFmpeg, applying perfect scaling/cropping to fit 1:1 or 21:9 videos flawlessly without distortion.
* ⚡ **Dynamic Turbo Compression:** Goodbye rigid 960x540. Turbo Compression now uses smart proportional scaling (`960:-2`) to shrink file size while perfectly locking the original aspect ratio.
* 🧠 **Smart CPU Threading:** The engine now reads your PC specs, automatically detecting total CPU cores/threads and reserving **1 exclusive thread** for the OS to prevent freezes during heavy compression.
* 🖼️ **Asynchronous UI Thumbnail:** Added an instant 320x180 thumbnail preview with black padding to prevent stretched images. Runs asynchronously so the GUI never freezes during loads!
* 📝 **Automated System Logging:** Introduced `engine_log.txt` for real-time activity tracking, bug detection, and physical verification of video files and Windows Startup Shortcuts.
* 🛠️ **Crucial Bug Fixes:** Fixed persistent video scaling issues, resolved locked optimize buttons, patched `$CmdLineRaw` parsing for folders with spaces, and stabilized MPV forced shutdowns during resets.

---

### 🐧 Linux Build *(OFFICIAL RELEASE V1.1.0 🎉)*
* 🎯 **Smart Auto-Scale Monitor:** Automatically stretches 1:1 square videos and seamlessly crops/fits 20:9 or 21:9 ultra-wide wallpapers to match 16:9 displays.
* 🛠️ **Crucial Bug Fixes:** Resolved X11 aspect ratio lock issues, improved watchdog loop, and fixed binary thread execution.
* 🪶 **Ultra-Lightweight Footprint:** Engine binaries optimized to the absolute smallest footprint possible with minimal RAM and CPU overhead.
* 📊 **Real-time Progress Indicator:** Smooth compression progress bar integration powered by YAD.

> 🛠️ **Note for Linux Users:**  
> The Linux build is currently under active development and continuous optimization. We are actively refining the core scripts to deliver the best performance possible for low-spec hardware. Stay tuned for further updates!

---
    
## ✨ Key Features

<img width="572" height="388" alt="image" src="https://github.com/user-attachments/assets/b2c8bd4b-cbba-4d1e-aeb8-af0041e73b80" />

- **🎯 Balanced CPU/GPU Usage** - Smart optimization prevents thermal throttling and maintains system stability
- **💾 Ultra-Low RAM Usage** - Runs smoothly on 2GB RAM systems (yes, really)
- **⚡ Fast Startup** - Lightweight codebase means instant launch
- **🎬 Automatic Wallpaper Optimization** - No matter how heavy your video is, it gets optimized automatically
- **🚀 Auto-start on Boot** - Wallpaper runs automatically every time you start Windows
- **📦 Portable Format** - No installation needed. Extract and run. Can even run from USB.
- **🗜️ Compressed Size** - Entire engine fits in a small file

---

## 🆚 YunuWallEngine Overview

<img width="557" height="149" alt="image" src="https://github.com/user-attachments/assets/a159a412-5add-4067-b721-ea6d2d836511" />

| Feature | YunuWallEngine |
|---------|---|
| File Size | ~70MB |
| RAM Usage | 3-30MB |
| CPU Usage | 2-5% |
| GPU Usage | Adaptive |
| System Requirement | 2GB RAM minimum |
| Portable (No Install) | ✅ Yes |
| Video Support | MP4, AVI, WebM |
| Customization | Good |
| Price | 🆓 Free |

**Bottom Line:** YunuWallEngine is for users with older PCs who want animated wallpapers **without the performance cost**.

---

## 💻 System Requirements

### Minimum (Tested & Works)
- **CPU:** Dual Core 2.0 GHz (Intel i3 2nd Gen or equivalent)
- **RAM:** 2GB
- **GPU:** Integrated graphics
- **OS:** Windows 7, 8, 10, 11

### Recommended
- **CPU:** Intel i3 3rd Gen or higher
- **RAM:** 4GB+
- **GPU:** Dedicated graphics (optional)

---

## 🚀 Quick Start

### 🖥️ Windows Installation 
1. Download `YunuWallEngine_V1.0.rar` from [**Releases**](https://github.com/YunuP-Dev/YunuWallEngine/releases)
2. Extract using **WinRAR**, **7-Zip**, or Windows built-in extractor
3. Open the extracted folder and run `YunuWallEngine.exe`
4. Select your video wallpaper (.mp4) and click **Apply**

### 🐧 Linux Installation 
1. Download `YunuWallEngine_Linux_V1.0.zip` from [**Releases**](https://github.com/YunuP-Dev/YunuWallEngine/releases)
2. Extract the archive inside your File Manager (Thunar, Nemo, or Nautilus)
3. Open the extracted folder, right-click on the `YunuWallEngine` file (the executable binary), and select **Execute** or **Run**
4. Select your video wallpaper (.mp4) and click **Apply**

> 💡 **Tip for First-Time Users:**  
> If the "Execute" option doesn't appear on your first launch, open a terminal in that folder once and type: `chmod +x YunuWallEngine` to grant executable permission. After that, you can close the terminal and just double-click the file forever!


### Supported Video Formats
- `.mp4` (Recommended)
- `.avi`
- `.mkv`
- `.webm`
- `.mov`

### Tips for Best Performance
- Use **HD (1080p) or lower** resolution videos
- Videos between **30-60 seconds** work best
- Keep videos under **100MB** for smooth playback
- Reduce GPU usage: Go to Settings → GPU Mode → "Balanced"

---

## ⚙️ Features Explained

### Auto-Optimization
- Automatically converts heavy wallpapers to optimized format
- Reduces frame rate if system can't handle it smoothly
- No manual tweaking needed

### Balanced CPU/GPU
- Smart switching between CPU and GPU rendering
- Prevents thermal throttling
- System stays cool even during summer

### Auto-Start on Boot
- Once enabled, wallpaper loads automatically on startup
- Zero manual intervention

---

## 📊 Performance Comparison (Real-world Test)

Testing on **Intel i3 2330m + 4GB RAM:**

| Tool | RAM | CPU | Temp |
|------|-----|-----|------|
| YunuWallEngine | 45MB | 3% | 45°C |
| Wallpaper Engine | 180MB | 12% | 55°C |

*YunuWallEngine is 4x lighter than Wallpaper Engine!*

---

## 🛠️ Troubleshooting

**Q: Wallpaper not showing?**
- A: Restart Windows or run the app again. Wallpaper needs to be in supported format.

**Q: High CPU usage?**
- A: Enable "Auto-Optimization" in settings. Reduce video resolution.

**Q: Crashes on startup?**
- A: Update your GPU drivers or disable GPU mode (use CPU instead).

**Q: Can I use videos from YouTube?**
- A: Download them first using tools like yt-dlp, then convert to MP4.

---

## 💬 Community & Support

- **Report a Bug:** Open an [Issue](https://github.com/YunuP-Dev/YunuWallEngine/issues)
- **Ask Questions:** Use [Discussions](https://github.com/YunuP-Dev/YunuWallEngine/discussions/1)
- **Share Wallpapers:** Check out community shared wallpapers in Discussions!

---

## 📝 License

Other

---

## 👤 Author

**YunuP-Dev**

*Built for people with old computers who still want pretty things.*

---

**Keywords:** video wallpaper 2GB RAM • lightweight wallpaper engine • low-spec PC • PC kentang • MPV wallpaper • free wallpaper engine • Windows 7/10/11 wallpaper • Linux live wallpaper • Linux Mint video wallpaper • X11 wallpaper engine • low resource wallpaper • potato PC live wallpaper • YunuWallEngine
