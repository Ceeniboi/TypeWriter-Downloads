# TypeWriter

**TypeWriter v1.0** – A small Windows tool that simulates human typing from your clipboard, with per-device activation.

---

## Download

👉 [Go to the Releases page](../../releases) and download the latest ZIP.  
Unzip it, then run `TypeWriter.exe`.

---

## Hotkeys

- **Start**: Ctrl + Alt + Q  
- **Quit**:  Ctrl + Alt + A  
- **Emergency abort (while typing)**: Move mouse to the **top-left corner** of the screen  

*(There is no manual Stop hotkey — the emergency abort is the only way to interrupt typing mid-flow.)*

---

## Activation (offline, one-time)

1. Run `TypeWriter.exe`. It will show your **Device ID**.  
2. Give your Device ID to the seller to receive an **Activation Code**.  
3. Paste the code when prompted. You should see “License saved.”  
4. On later runs, the app will start licensed without asking again.  

License file is stored at:  
`%APPDATA%\TypeWriter\license.key`

---

## Integrity

A SHA-256 checksum file is included in every release.  
To verify on Windows:

```bash
certutil -hashfile TypeWriter.exe SHA256
