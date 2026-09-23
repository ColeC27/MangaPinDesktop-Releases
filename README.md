# MangaPin Desktop Releases (BETA)
App auto-updates, no need to redownload.

#### DISCLAIMER: 
The app is unsigned, as that would mean paying hundreds each year. Due to this, MangaPin Desktop may be more difficult to open than other apps you are used to. Read the bottom of this document for instructions if needed.

## Download Latest Release:

| Platform | Download |
|----------|----------|
| **Windows** | [Download for Windows](https://github.com/ColeC27/MangaPinDesktop-Releases/releases/latest/download/MangaPin-Windows-Setup.exe) |
| **Mac** (Apple Silicon) | [Download for Mac](https://github.com/ColeC27/MangaPinDesktop-Releases/releases/latest/download/MangaPin-Mac-arm64.dmg) |
| **Linux** | [Download for Linux](https://github.com/ColeC27/MangaPinDesktop-Releases/releases/latest/download/MangaPin-Linux.AppImage) |

Or browse [all releases](https://github.com/ColeC27/MangaPinDesktop-Releases/releases/).

### Opening on Windows:
1. If **Windows protected your PC** (SmartScreen) appears:
   - Click **More info**
   - Click **Run anyway**
2. If the `.exe` still will not start: right-click it → **Properties** → check **Unblock** → **Apply** → **OK**, then run it again.

After the first **Run anyway**, Windows usually stops asking.  
If **Smart App Control** is on (some Windows 11 PCs), it can block unsigned apps entirely. You'll have to turn it off.

### Opening on Mac:
1. Open the `.dmg` and drag **MangaPin** to **Applications**.
2. Do **not** double-click it the first time (Gatekeeper will refuse).
3. In **Applications**, **Control-click** (or right-click) **MangaPin** → **Open** → **Open**.

**If macOS still blocks it:**
1. **System Settings** → **Privacy & Security**
2. Scroll to the message that MangaPin was blocked
3. Click **Open Anyway**
4. Confirm **Open**

You only need to do this once per install.

### Opening on Linux:
1. Right-click the file → **Properties** → **Permissions** → enable **Allow executing file as program**.
2. Double-click it.
If double-click does nothing, in a terminal:
```bash
chmod +x MangaPin-Linux.AppImage
./MangaPin-Linux.AppImage
```
On some Ubuntu versions, AppImages also need FUSE (`libfuse2`).


<sub>All rights reserved. Subject to MangaPin license.</sub>   
