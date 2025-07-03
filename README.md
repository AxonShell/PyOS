# PyOS – AxonShell Terminal Operating System

**Developer**: KunilArch  
**Current Version**: PyOS 2.0.1 Beta 
**Stable current version**: PyOS 1.0.3
**License**: Open Source up until 1.0.3 
**Platform**: Windows, Android (via Pydroid), Linux-compatible (terminal-based)

---

## Overview

PyOS is a lightweight Python-based terminal-style operating system simulator. Built for educational, creative, and experimental use, PyOS offers a modular command-line environment that simulates various OS-like behaviors through apps.

---

## Version History

### PyOS 0.1 (Initial Build)
- Basic UI and terminal introduction
- Simple launch logic and password system
- No persistent storage

### PyOS 0.2
- Introduction of "user_info.txt" to store username and password data
- Factory reset feature
- Text editor added (basic, writes to ".txt" files)
- Numbered app launch menu

### PyOS 1.0.3
- More apps: System Info, Terminal, Memory Game, Calculator
- Code Editor supports ".py", ".html", ".js", and more, any extension can be used.
- GPU info added using "wmic"
- ASCII Paint added
- Improved game and editor stability
- Social links and "cmd" app (with version, password, and reset)

### PyOS Lite
- No external libraries: psutil, platform, and others removed
- Reduced feature set for ultra-compatibility
- Preserved only essential apps: Text Editor, Calculator, File Explorer

- No Builds for PyOS Lite will be made after this one.


### PyOS 2.0.1 Beta
- Apps upgraded to display version numbers, Beta feature Builds only
- System Info improved with better formatting
- ASCII Paint added as a creative app
- Added: Shoutouts, Changelog apps
- Terminal and Text Editor optimized
- Hidden `cmd` app with extra features (MRT scan, factory reset)
- Fully structured version with major stability updates
- MRT (Malicious Software Removal Tool) Windows specific scan feature sub process
- More  accurate results for system details: OS, CPU, GPU, RAM, Disk
- Auto-detects OS type (Windows, Linux, Android)
- user_info.txt auto-updates missing values
  - advanced features: true/false
- All major apps retained and enhanced to be better
- Cleaner code organization

---

## File Structure

- Main.py: Main launcher script
- user_info.txt: Stores user preferences and settings
- No external dependencies required (except optional modules like psutil)



## Disclaimer

This project is for educational and entertainment purposes. It does not replace a real OS but simulates one through Python scripting.
