**简体中文** | [English](README_EN.md)
## 父进程启动器

这是一个运行在 `Windows` 系统下的gui工具，可以选择一个已有的进程作为“父进程”启动另一个程序。主要用于测试或研究进程行为，或许可能用在 [这里的最新版](https://github.com/LiteLoaderQQNT/LiteLoaderQQNT)  ~我不知道啊 我真的不知道行不行 我随便写的github仓库（~

✨ 提示
- 建议右键选择管理员权限启动，避免因权限不足导致进程启动失败
- 先选择需要启动的程序，再选择启动方式
- `最早启动的进程` 一般是 `C:\Windows\System32\svchost.exe`
- 程序中的 `NVOL` 是 `Nvidia Overlay.exe` ，因为写不下了故用缩写，程序路径一般是 `C:\Program Files\NVIDIA Corporation\NVIDIA App\CEF\NVIDIA Overlay.exe`
- N卡用户可以考虑使用 `查找NVOL进程` 按钮来快速获取所有 `Nvidia Overlay.exe` 进程的pid，多开 [这个软件（github链接）](https://github.com/PRO-2684/qqnt-version-history) 可以用到，亲测更加稳定不易炸
- 启动你指定的程序，并显示log信息
- 包含图形界面，不需要命令行，很简单易懂
