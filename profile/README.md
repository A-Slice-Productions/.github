# 🚀 A-Slice Productions

**An HRK's Redux Engine fork bringing massive performance boosts for extreme note counts and low-end hardware.**

Original engine architecture credit belongs to **HRK.EXEX** for creating **H-Slice**—the foundation for making a P-Slice fork truly powerful!

---

## 📌 About A-Slice

**A-Slice** is a high-performance, low-level Haxe/C++ engine fork designed to bypass memory allocation bottlenecks, eliminate garbage collection hitching, and render extreme, high-NPS charts smoothly across both PC and mobile platforms.

Whether you are stress-testing billions of notes, charting heavy spam files, or playing on low-end Android hardware, A-Slice is engineered to keep your framerates stable and memory usage capped.

---

## ⚡ Core Features & Optimizations

* 🚀 **Extreme Note Performance:** Custom C++ note culling and rendering logic designed to process multi-million and billion-note charts without lagging out.
* 📱 **Low-End & Mobile Optimization:** Dynamic memory management and stability fixes to prevent heap allocation crashes on low-spec Android/iOS hardware.
* 🛠️ **Native Andres HUD:** Integrated PlayState HUD built directly into C++/Haxe for zero LUA overhead.
* 📊 **Safe Chart Editor Mode:** Lightweight editor loading profiles designed to open massive JSON files without crashing.
* ⚡ **Botplay & Input Decoupling:** Separated botplay evaluation threads to ensure hit-registration stays smooth during high-density streams.

---

## 📂 Release Architecture & Supported Platforms

A-Slice Releases are compiled and deployed across multiple platforms:

| Platform | File Target | Optimization Target |
| :--- | :--- | :--- |
| **Windows** | `A-Slice_Windows.zip` | x64 High-FPS & Extreme NPS Benchmarking |
| **Linux** | `A-Slice_Linux.zip` | Native x64 Low-Overhead Builds |
| **Android** | `A-Slice_Android.zip` | Low-RAM Allocation & Touch-Optimized UI |
| **iOS** | `A-Slice_ios.zip` | Mobile ARM Performance |
| **macOS** | `A-Slice_MacOS.zip` | Universal macOS Performance |

---

## 🛠️ Building From Source

### Prerequisites
* [Haxe 4.3.0+](https://haxe.org/)
* [Lime & OpenFL](https://lime.software/)
* [HaxeFlixel](https://haxeflixel.com/)

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone [https://github.com/A-Slice-Productions/A-Slice.git](https://github.com/A-Slice-Productions/A-Slice.git)
   cd A-Slice
