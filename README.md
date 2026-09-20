# Guide: Turning Windows 11 into Windows 7

A complete guide to recreate the classic Windows 7 look and functionality on Windows 10/11.

---

## Step 1 — Install SecureUxTheme

- https://github.com/namazso/SecureUxTheme

Patches UxTheme in memory so third-party themes can be applied. After installing, **restart your PC**.

---

## Step 2 — Install ExplorerPatcher

- https://github.com/valinet/ExplorerPatcher/releases

⚠️ This is the only official source. On the release page, scroll down and download the installer — **ignore the "Source code" section**.

---

## Step 3 — Install Windhawk

- https://windhawk.net/

The mod marketplace you'll use to install most of the mods below.

---

## Step 4 — Install the theme

1. Download a Windows 7-style theme, for example **Aero11**:
   - https://github.com/Sand216/Aero11
2. Extract the contents into `C:\Windows\Resources`.
3. Open Personalization with `WIN+R` → paste:
   ```
   shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}
   ```
4. Select the native Windows theme first, then apply the one you just installed.

If the theme fails to apply (blank/white screen), redo the SecureUxTheme steps or try a different theme.

---

## Step 5 — Configure OpenGlass

- https://github.com/ALTaleX531/OpenGlass/releases

Enables the Aero Glass effect on modern Windows. Use the installer — it auto-selects the correct build for your system.

---

## Step 6 — Install Open-Shell with the Windows 7 skin

1. Install **Open-Shell**:
   - https://github.com/Open-Shell/Open-Shell-Menu/releases
2. Download the **Windows 7 skin**:
   - https://github.com/EJSnow/Windows-7-skin
3. In Open-Shell settings, go to the **Skin** tab and import the downloaded skin.

---

## Step 7 — Install the Windhawk mods

Open Windhawk → **Explore** → search for author **babamohammed** → install the mods below.

**Taskbar / Start Menu / core UI**
- Classic Taskbar and Start Menu Properties
- Aero Flyout Fix
- Aero Flip 3D Recreation
- Windows 7 Window Animations Restorer
- Windows 7 Command Bar
- Taskbar classic context menu
- Restore Button Pulse Animation
- Resource Redirect — open its settings, find **pane7**, and save

**Network / Action Center**
- Windows 7 Network Flyout Recreation
- Windows 7/8.1 Action Center Recreation

**Control Panel**
- Control Panel Revival
- Redirect Settings to Control Panel
- Windows 7 Legacy Applet Restorer
- Classic Display Control Panel Restorer
- Performance Information and Tools Restorer
- Windows Update Control Panel Page Restorer
- Windows 7 Region and Language Restorer
- Windows 7/8.1 Language Switcher Restorer
- Windows 11 HomeGroup Page Restorer

**Dialogs / system behavior**
- Windows Vista/7 Open With Dialog Restorer
- Windows 7 Classic AutoPlay Dialog Restorer
- Windows 7/8.1 "Please Wait" Restorer
- Legacy File Copy
- Logon, Logoff & Shutdown Sounds Restored
- Classic Windows Photo Viewer Redirect

---

## Step 8 — Download and run Win7Taskbar

- https://github.com/babamohammed2022/Win7Taskbar/releases

1. Extract everything into a folder.
2. Run `win7taskbar.exe`.
3. ⚠️ This is an **alpha** release — expect bugs.
4. To refine it: right-click the taskbar → **Properties** → disable the custom search.

---

## Optional: Windows 8.1 touches

- Right-click the taskbar → **Properties** → choose the Windows 8 network flyout.
- Go to **Additional settings** → choose the Windows 8.1 theme.

---

## Quick links

- SecureUxTheme: https://github.com/namazso/SecureUxTheme
- ExplorerPatcher: https://github.com/valinet/ExplorerPatcher/releases
- Windhawk: https://windhawk.net/
- Aero11: https://github.com/Sand216/Aero11
- OpenGlass: https://github.com/ALTaleX531/OpenGlass/releases
- Open-Shell: https://github.com/Open-Shell/Open-Shell-Menu/releases
- Windows 7 skin for Open-Shell: https://github.com/EJSnow/Windows-7-skin
- Win7Taskbar: https://github.com/babamohammed2022/Win7Taskbar/releases
