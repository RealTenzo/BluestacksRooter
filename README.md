# 🔧 Bluestacks_Rooter_By_Tenzo

A sleek and modern tool to **enable or disable root access** in **BlueStacks 5** and **MSI App Player** by directly modifying the file from the Windows Registry path.


---

## ✨ Features

- ✅ Modern WinForms UI (rounded corners, animations)
- 🔄 One-click **Root / Unroot**
- 🔍 Auto-detects BlueStacks configuration path
- 💡 Built-in notifications and feedback
- 🧠 No need for adb or external scripts
- 🖥️ Supports **BlueStacks 5**, **MSI Player**, and similar

---

## 📁 How It Works

This tool reads the path to `Bluestacks_nxt` from the Windows Registry and toggles the `bst.root` value:

```ini
bst.root=1   --> Root enabled 
bst.root=0   --> Root disabled
