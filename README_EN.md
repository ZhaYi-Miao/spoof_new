**English** | [简体中文](README.md)
# Parent Process Launcher

A GUI tool for Windows that lets you launch a program using an existing process as its "parent."  
Useful for testing or researching process behavior—and *maybe* it works with [this latest version](https://github.com/LiteLoaderQQNT/LiteLoaderQQNT) (no guarantees, just tossing out a repo ¯\\\_(ツ)\_/¯).

## ✨ Tips

- **Run as Administrator**  
  Right-click and choose "Run as administrator" to avoid permission-related launch failures.

- **Launch Flow**  
  First select the program you want to launch, then choose the launch method.

- **Earliest Process**  
  Typically: `C:\Windows\System32\svchost.exe`

- **NVOL = Nvidia Overlay.exe**  
  Abbreviated due to UI space limits. Full path usually:  
  `C:\Program Files\NVIDIA Corporation\NVIDIA App\CEF\NVIDIA Overlay.exe`

- **NVIDIA GPU Users**  
  Use the **Find NVOL Processes** button to quickly list all `Nvidia Overlay.exe` PIDs.  
  Especially helpful when running multiple instances of [this software](https://github.com/PRO-2684/qqnt-version-history)—tested and confirmed to be more stable and less crash-prone.

- **Log Output**  
  The tool launches your specified program and displays log information.

- **No Command Line Needed**  
  Fully graphical interface. Simple and intuitive to use.

---

Feel free to fork or contribute if you find it useful!
