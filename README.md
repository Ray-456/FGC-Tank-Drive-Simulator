# 🚗 FGC Tank Drive Levels

Welcome to **FGC Tank Drive Levels** — a robotics-inspired game where you control a tank-style robot through obstacles, walls, and goals.  
This repo only contains the **download link to the game**. The source code is not included.

---

## 📥 How to Download
1. Scroll up on this page and click on the **Releases** section (on the right side).  
   Or click here: [👉 Go to Releases](../../releases)  
2. Find the latest release (example: `v1.0.0`).  
3. Under **Assets**, download one of these:
   - `main.exe` → Run directly (Windows may warn you since it’s from the internet).  
   - `main.zip` → Safer option. Download, right-click → **Extract All**, then run `main.exe`.  

---

## 🎮 How to Play
- **Left Track** → `W` / `S` or Left Stick Y  
- **Right Track** → `↑` / `↓` or Right Stick Y  
- **Restart Level** → `R` (OPTIONS)  
- **Full Reset** → Hold `Shift + R` (R2 + OPTIONS)  
- **Toggle 2D ↔ 3D** → `T`  
- **Quit** → `Esc` or `X` (gamepad)  

---

## 🖥️ Requirements
- Windows 10 or newer (64-bit).  
- No need to install Python — the `.exe` runs standalone.  

---

## 🔒 Verify the Game
Each release includes a **SHA256 checksum**.  
To verify the file on Windows:
```powershell```

---

❓ Support

If the game doesn’t start, try running the unzipped version (main.zip).

If you find bugs or issues, open an Issue on this repo (top menu → Issues).
certutil -hashfile main.exe SHA256
