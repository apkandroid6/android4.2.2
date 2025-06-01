# Android 4.2.2 + Limbo PC Emulator

> ⚠️ This `.iso` file is actually a **ZIP archive** containing:
> - An **Android 4.2.2 ISO** (bootable)
> - An **APK for Limbo PC Emulator** (for Android)

## 📦 Contents

After extracting, you’ll find:
- `android-4.2.2.iso` – Bootable Android 4.2.2 image for emulators or VMs
- `Limbo.apk` – Android app for emulating x86 systems (based on QEMU)

---

## ✅ How to Use

### 1. Rename the File
This file is **not a real ISO**. First, rename it to a `.zip`:

```bash
mv android422.iso > android422.zip
```

### 2. Extract the ZIP Archive

#### On Android:
- Use **ZArchiver**, **RAR**, or **Files by Google**
- Locate `android422.zip`, tap it, and choose **Extract**

#### On Windows:
- Right-click the file > **Extract All…**
- Or use tools like **7-Zip** or **WinRAR**

#### On macOS / Linux:
Use the Terminal:
```bash
unzip android422.zip -d android422

### 3. Install and Use the Files

#### 📲 On Android:
1. **Install Limbo Emulator**:
   - Open the extracted folder and tap `Limbo.apk`
   - If prompted, allow installation from unknown sources
   - Follow the on-screen steps to complete installation

2. **Run Android 4.2.2 in Limbo**:
   - Open **Limbo PC Emulator**
   - Create a new VM profile
   - Under **Load ISO**, select `android-4.2.2.iso`
   - Set:
     - Architecture: `x86`
     - RAM: at least `512 MB` (more if available)
     - CPU Model: `Default` or `qemu32`
     - Storage: No hard disk needed
   - Tap **Start** to boot into Android 4.2.2

#### 💻 On PC (optional):
You can also boot `android-4.2.2.iso` in a PC virtual machine:
- Use **VirtualBox**, **VMware**, or **QEMU**
- Create a VM and attach `android-4.2.2.iso` as the boot ISO

---

### 4. (Optional) Create a Shortcut or Save the VM Settings

#### 📲 On Android:
To make it easier to boot Android 4.2.2 later:

- After setting up your VM in Limbo, tap **Save** to store the configuration.
- You can name it something like `Android422`.
- Next time you open Limbo, just select `Android422` from the list and tap **Start**.

#### 💡 Tip:
If your device supports it, you can also:
- Create a home screen shortcut to Limbo for quick access.
- Keep the extracted folder in an easy-to-access location like `Downloads` or `Documents`.

---

You're now ready to run Android 4.2.2 on your device using Limbo Emulator!