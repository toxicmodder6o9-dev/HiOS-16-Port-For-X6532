# 📱 HiOS 16 Custom ROM 

An ultra-light, highly optimized port tailored for performance and stability, explicitly tweaked to breathe new life into 3GB RAM devices. 

---

## 🚀 Changelog

* **Debloated & Cleaned:** Completely removed unnecessary bloatware and all AI features for a significantly cleaner, lighter system.
* **Essential Features Added:** Integrated Floating-Windows, Split-Screen, and Double-Tap to Wake (D2W).
* **Memory Management:** Added custom LMK (Low Memory Killer) and highly optimized 3GB zRAM tweaks for superior multitasking.
* **Kernel Upgraded:** Shipped with Grey-Raven Zenithed v7 Kernel, compiled with Clang 19 (Non-Root).
* **UI & Aesthetics:** Enabled minimal UI blur for a sleek look.
* **Performance Tweaks:** Applied system-wide tweaks to aggressively minimize lag and enhance overall responsiveness.
* **Bug Fixes:**
  * 🛡️ Resolved multiple SELinux denials for better stability.
  * 🛑 Fixed Launcher and SystemUI crashing unexpectedly.
  * 🐛 Fixed lockscreen notifications overlapping with the clock.
  * 🎨 Fixed background blur glitches on the Lockscreen Control Center and Power/Shut-Down interface.

---

## ⚠️ Known Bugs

* **Bright Flashlight:** The "Bright" flashlight toggle is currently bugged. *(Note: Standard flashlight functions work perfectly).*
* **Memfusion:** Disabled/Unavailable. *(Note: You do not need to flash a module for this; the built-in zRAM is already set to 3GB and is vastly superior).*

---

## 📌 Important Notes

1. **Let it Settle:** After the first boot, please give the ROM a good **5 to 10 minutes** to fully optimize itself before heavy use.
2. **RAM Expectations:** Minor lags during high-intensity usage are normal. HiOS 16 is a naturally RAM-hungry interface, though this build is heavily optimized to mitigate that.
3. **Wallpapers:** Due to the removal of the core AI features, only *System Depth*, *Vogue*, and *AI Wallpapers* are functional.
4. **Kernels:** Please **do not** report bugs if you decide to flash a different custom GKI kernel over this setup. 

---

## 💖 Special Thanks

A massive shoutout to the following developers for making this possible:
* **[@Opek_Furina](t.me/Opek_Furina)** – For the invaluable porting lessons.
* **[@idunnobree](t.me/idunnobree)** – For providing the stable base vendor.
