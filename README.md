# Guide: Make Windows 11 look very similar to Windows 7 without replacing or modifying system files
The contents and source codes contained within this repository are released under the terms and conditions set by the MIT License.

This is a comprehensive guide to recreate the classic Windows 7 aspect and functionality on Windows 11. On Windows 10, the process should be similar and with potentially expected better results in some areas. However, it is important to note that some parts may vary (for instance, the theme to use on Windows 10 is usually Aero10) but the same principles should apply. If there are problems, please refer to the author.

---

## Step 1 — Install SecureUxTheme

- https://github.com/namazso/SecureUxTheme

This software patches UxTheme in memory so third-party themes can be applied. After installing, **restart your PC**.

---

## Step 2 — Install ExplorerPatcher

- https://github.com/valinet/ExplorerPatcher/releases

⚠️ This is the only official source. On the release page, scroll down and download the installer — **ignore the "Source code" section**.

---

## Step 3 — Install Windhawk

- https://windhawk.net/

This software contains the mod marketplace that will be used to install most of the mods below.

---

## Step 4 — Install the Theme

1. Download a Windows 7-style theme, for example **Aero11**:
   - https://github.com/Sand216/Aero11
2. Extract the contents into `C:\Windows\Resources`.
3. Open Personalization with `WIN + R` → paste:
   ```text
   shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}
   ```
4. Select the native Windows theme first, then apply the one just installed.

If the theme fails to apply (blank/white screen), redo the SecureUxTheme steps or try a different theme.

---

## Step 5 — Configure OpenGlass

- https://github.com/ALTaleX531/OpenGlass/releases

This software enables the Aero Glass effect on modern Windows. Use the installer, it should auto-select the correct build for the system.

---

## Step 6 — Install Open-Shell with the Windows 7 Skin

1. Install **Open-Shell**:
   - https://github.com/Open-Shell/Open-Shell-Menu/releases
2. Download the **Windows 7 skin**:
   - https://github.com/EJSnow/Windows-7-skin
3. Go to C:\Program Files\Open-Shell\Skins and add the Windows 7 skin files, then go to the **Skin** tab and import the downloaded skin.

---

## Step 7 — Install the Windhawk Mods

Open Windhawk → **Explore** → search for and install the following mods:

### Taskbar / Start Menu / Core UI
- Aerexplorer (Windows 11 port, credits to aubymori for the original)
- Aero Flip 3D Recreation
- Aero Flyout Fix
- Aero Peek on Show desktop hover
- Classic Taskbar and Start Menu Properties
- Eradicate Immersive Menus
- Force thick frames
- Resource Redirect — open its settings, find **pane7**, and save
- Restore Button Pulse Animation
- Taskbar classic context menu
- Windows 7 Command Bar
- Windows 7 Window Animations Restorer

### Network / Action Center / System Flyouts
- Windows 7 Network Flyout Recreation
- Windows 7/8.1 Action Center Recreation

### Control Panel & Settings
- Classic Display Control Panel Restorer
- Control Panel Revival
- Performance Information and Tools Restorer
- Redirect Settings to Control Panel
- Windows 11 HomeGroup Page Restorer
- Windows 7 Legacy Applet Restorer
- Windows 7 Region and Language Restorer
- Windows 7/8.1 Language Switcher Restorer
- Windows Update Control Panel Page Restorer

### Dialogs & System Behavior
- Logon & Sleep Fade Restorer
- Logon, Logoff & Shutdown Sounds Restored
- Windows Vista/7 Open With Dialog Restorer
- Windows 7 Classic AutoPlay Dialog Restorer
- Windows 7/8.1 Please Wait Restorer

---

## Step 8 — Download and Run Win7Taskbar

- https://github.com/babamohammed2022/Win7Taskbar/releases

1. Extract everything into a folder.
2. Run `win7taskbar.exe`.
3. ⚠️ This is an **alpha** release, expect some minor bugs and limitations.
4. To refine it: right-click the taskbar → **Properties** → disable the custom search.

---

## Optional: Windows 8.1 interface

- Right-click the taskbar → **Properties** → choose the Windows 8 network flyout.
- Go to **Additional settings** → choose the Windows 8.1 theme.

---

## Quick Links

- SecureUxTheme: https://github.com/namazso/SecureUxTheme
- ExplorerPatcher: https://github.com/valinet/ExplorerPatcher/releases
- Windhawk: https://windhawk.net/
- Aero11: https://github.com/Sand216/Aero11
- OpenGlass: https://github.com/ALTaleX531/OpenGlass/releases
- Open-Shell: https://github.com/Open-Shell/Open-Shell-Menu/releases
- Windows 7 skin for Open-Shell: https://github.com/EJSnow/Windows-7-skin
- Win7Taskbar: https://github.com/babamohammed2022/Win7Taskbar/releases
