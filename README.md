# Linux Bar / Taskbar Solutions

This project aims to build a flexible bar/taskbar for Linux that supports both X11 and Wayland.

## Comprehensive Linux Rice Taskbar/Status Bar Solutions

### Wayland-Only Solutions

| Project | Git Repository | Language | Description |
|---------|---------------|----------|-------------|
| **Waybar** | https://github.com/Alexays/Waybar | C++ | Highly customizable, feature-rich status bar with extensive module system |
| **Swaybar** | https://github.com/swaywm/sway (built-in) | C | Minimalist status bar, part of Sway compositor |
| **Hyprbar** | https://github.com/hyprwm/hyprbar | C | Lightweight bar specifically for Hyprland compositor |
| **Nwg-panel** | https://github.com/nwg-piotr/nwg-panel | Python | GTK-based panel for Sway and Hyprland, supports widgets/plugins |
| **Ironbar** | https://github.com/JakeStanger/ironbar | Rust | GTK4-based bar with CSS styling support |
| **Yambar** | https://gitlab.com/dnkl/yambar | C | Modular status bar with plugin-based architecture |
| **Ags** | https://github.com/Aylur/ags | TypeScript/GJS | GTK Shell framework, can be used as status bar |
| **Eww** | https://github.com/elkowar/eww | Rust | Widget system, configurable as status bar on Wayland |
| **Quickshell** | https://github.com/quickshell-mirror/quickshell | C++ | QtQuick-based desktop shell toolkit |
| **Sysbar** | https://github.com/System64fumo/sysbar | C++ | Modular status bar for Wayland |
| **Bar-rs** | https://github.com/faervan/bar-rs | Rust | Status bar using iced-rs for Hyprland/niri/wayfire |
| **Heliumbar** | https://github.com/metis-os/heliumbar | Rust | Aesthetic bar for wlroots-based compositors |
| **Husky-Panel** | https://github.com/CharOfString/Husky-Panel | C++ | Monolithic bar for Linux desktop |
| **Wayle** | https://github.com/wayle-rs/wayle | Rust | Compositor agnostic shell with extensive customization |
| **GBar** | https://github.com/scorpion-26/gBar | C++ | Blazingly fast status bar written with GTK |
| **Fabric** | https://github.com/Fabric-Development/fabric | Python | GTK-based widget framework for desktop widgets |

### X11-Only Solutions

| Project | Git Repository | Language | Description |
|---------|---------------|----------|-------------|
| **Polybar** | https://github.com/polybar/polybar | C++ | Feature-rich, highly customizable bar with 50+ modules |
| **i3bar** | https://github.com/i3/i3 (built-in) | C | Native status bar for i3wm, JSON protocol |
| **Lemonbar** | https://github.com/LemonBoy/bar | C | Minimalist, ultra-fast X11 bar (~3KB binary) |
| **Dzen2** | https://github.com/dzen2/dzen2 | C | Simple, flexible X11 bar with text-based output |
| **Xmobar** | https://github.com/jaor/xmobar | Haskell | Status bar for Xmonad, written in Haskell |
| **Slstatus** | https://github.com/stilor/slstatus | C | Suckless status monitor, minimal and fast |
| **Tint2** | https://gitlab.com/o9000/tint2 | C | Lightweight panel/taskbar with system tray |
| **Fbpanel** | https://github.com/fbpanel/fbpanel | C | Lightweight X11 panel with taskbar/launchers |
| **Bmpanel2** | https://github.com/nicm/bmpanel2 | C | Simple, minimal X11 panel |
| **Wbar** | https://github.com/nicm/wbar | C | Dock-like bar for X11, minimal and fast |
| **Dwmblocks** | https://github.com/lukesmith-xyz/dwmblocks | C | Block-based status bar for dwm |
| **i3blocks** | https://github.com/vivien/i3blocks | C | Block-based status bar for i3wm |
| **Conky** | https://github.com/brndnmtthws/conky | C++ | System monitor, can output to root window/panel |
| **Yabar** | https://github.com/geommer/yabar | C | Modern status bar for X11 |
| **Py3status** | https://github.com/ultrabug/py3status | Python | i3bar compatible status bar writer |
| **Spectrwm bar** | https://github.com/conformal/spectrwm (built-in) | C | Built-in status bar for spectrwm |
| **Herbstluftwm panel** | https://github.com/herbstluftwm/herbstluftwm (built-in) | C | Built-in panel for herbstluftwm |
| **Dwm status** | https://dwm.suckless.org/patches/status2d (via dwm) | C | Status text built into dwm |
| **Xmonad** | https://github.com/xmonad/xmonad | Haskell | Can display status via XMonad.Hooks.Statusbar |
| **Bmpanel** | https://github.com/nicm/bmpanel | C | Simple panel for X11 |

### Dual-Support (X11 and Wayland)

| Project | Git Repository | Language | Description |
|---------|---------------|----------|-------------|
| **Eww** | https://github.com/elkowar/eww | Rust | Widget system, works on both X11 and Wayland |
| **Ags** | https://github.com/Aylur/ags | TypeScript/GJS | GTK Shell framework, works on both |
| **Conky** | https://github.com/brndnmtthws/conky | C++ | System monitor, outputs to both X11 and Wayland |
| **Quickshell** | https://github.com/quickshell-mirror/quickshell | C++ | QtQuick-based shell for both |
| **Fabric** | https://github.com/Fabric-Development/fabric | Python | GTK widget framework for both |

### Desktop Environment Panels (Standalone-able)

| Project | Git Repository | Language | Description |
|---------|---------------|----------|-------------|
| **Plasma Panel** | https://invent.kde.org/plasma/plasma-desktop | C++/QML | KDE Plasma's feature-rich panel with widgets |
| **Xfce Panel** | https://gitlab.xfce.org/xfce/xfce4-panel | C | Lightweight panel with plugin support |
| **Budgie Panel** | https://github.com/BuddiesOfBudgie/budgie-desktop | C/Vala | Modern panel from Budgie desktop |
| **Cinnamon Panel** | https://github.com/linuxmint/cinnamon | JavaScript/C | Panel from Cinnamon desktop with applets |
| **MATE Panel** | https://github.com/mate-desktop/mate-panel | C | Traditional panel from MATE desktop |
| **LXDE Panel** | https://github.com/lxqt/lxpanel | C | Lightweight panel from LXDE/LXQt |
| **GNOME Topbar** | https://gitlab.gnome.org/GNOME/gnome-shell (built-in) | JavaScript | Minimal top bar from GNOME |
| **Pantheon Panel** | https://github.com/elementary/pantheon-shell | Vala | Panel from elementary OS Pantheon |
| **Enlightenment Shelf** | https://github.com/nicm/enlightenment | C | Panel/shelf from Enlightenment |
| **AfterStep Wharf** | http://www.afterstep.org/ | C | Dock/wharf from AfterStep |

### Dock-like Solutions

| Project | Git Repository | Language | Description |
|---------|---------------|----------|-------------|
| **Crystal Dock** | https://github.com/dangvd/crystal-dock | C++ | Dock with smooth parabolic zooming, translucent effects, and cross-desktop support |
| **Plank** | https://github.com/ricotz/plank | Vala | Lightweight dock with themes |
| **DockbarX** | https://github.com/xuzhen/dockbarx | Python | Dock-like taskbar with grouping/thumbnails |
| **AWN** | https://github.com/pdelagrave/awn | Python/C | Avant Window Navigator with applets |
| **Cairo-Dock** | https://github.com/Cairo-Dock/Cairo-Dock | C | OpenGL-based dock with plugins |
| **Wingpanel** | https://github.com/elementary/wingpanel | Vala | Top panel from elementary OS |
| **Tint2 (dock mode)** | https://gitlab.com/o9000/tint2 | C | Can be configured as dock |

### Crystal Dock Technical Details

Crystal Dock is a modern dock-like application for Linux with advanced visual effects and cross-desktop compatibility.

**Key Features:**
- Smooth parabolic zooming with translucent effects
- Four visual styles: Glass 3D, Glass 2D, Flat 2D, Metal 2D
- Application Menu, Launcher/Task Manager, Trash, Wi-Fi Manager, Volume Control
- Battery Indicator, Keyboard Layout, Version Checker, Clock, Pager
- Multiple docks support
- Integration with Budgie, Hyprland, KDE Plasma 6, Labwc, LXQt, Niri, Sway, Wayfire (Wayland)
- Cross-platform: Version 1 (X11) and Version 2 (Wayland)

**Technical Specifications:**

| Aspect | Details |
|--------|---------|
| **Language** | C++ (81.2%) | C (17.6%) |
| **Build System** | CMake |
| **License** | GPL-3.0 |
| **Stars** | 356 |
| **Forks** | 26 |
| **Last Release** | Crystal Dock v2.16 (2025-12-22) |

**Dependencies:**
- Qt6 (GUI framework)
- LayerShellQt6 (Wayland Layer Shell integration)
- Wayland (display protocol)

**Installation Examples:**

```bash
# Ubuntu/Debian (if package available)
sudo apt install crystal-dock

# Build from source
cd crystal-dock
git clone https://github.com/dangvd/crystal-dock.git
cd crystal-dock
src
mkdir build
cmake -S . -B build -DCMAKE_INSTALL_PREFIX=/usr
cmake --build build --parallel
sudo cmake --install build

# Launch
crystal-dock
```

**Visual Comparison:**

| Feature | Crystal Dock | Plank | Wingpanel | Tint2 |
|---------|--------------|-------|-----------|-------|
| **Visual Style** | Modern, animated | Classic GTK | Elementary OS theme | Minimal |
| **Animations** | Parabolic zoom | Subtle slide | Minimal | None |
| **Transparency** | Translucent effects | Semi-transparent | Glass-like | Minimal |
| **Integration** | Cross-DE | GNOME/Budgie | Elementary OS | Generic |
| **Memory Usage** | Medium-high | Low | Medium | Low |

**Desktop Environment Support:**

| Desktop Environment | Support | Notes |
|-------------------|---------|-------|
| **Budgie** | ✓ | Native integration |
| **Hyprland** | ✓ | Wayland support |
| **KDE Plasma 6** | ✓ | Native integration |
| **Labwc** | ✓ | Wayland support |
| **LXQt** | ✓ | Native integration |
| **Niri** | ✓ | Wayland support |
| **Sway** | ✓ | Wayland support |
| **Wayfire** | ✓ | Wayland support |

**Crystal Dock vs Polybar comparison:**

| Aspect | Crystal Dock | Polybar |
|--------|--------------|---------|
| **Type** | Dock/Panel | Status Bar |
| **Primary Use** | Application launching, system controls | System monitoring, panels |
| **Visual Style** | Modern, animated 3D | Minimal text-based |
| **Language** | C++/C | C++ |
| **Memory Usage** | Higher (Qt6-based) | Lower (custom C++) |
| **Integration** | Native DE integration | Bar-focused, system-wide |
| **Use Case** | Dock functionality | Status monitoring |

**Crystal Dock Applications:**

Crystal Dock is particularly useful for users who want:
- **Modern aesthetics** with visual effects and animations
- **System control** from a centralized dock (volume, wifi, battery)
- **Cross-desktop compatibility** without switching applications
- **Professional appearance** with glass-like effects

**GitHub References:**
- Repository: https://github.com/dangvd/crystal-dock
- Documentation: https://github.com/dangvd/crystal-dock/wiki/Documentation
- Releases: https://github.com/dangvd/crystal-dock/releases
- Issues: https://github.com/dangvd/crystal-dock/issues

**Download/Clone Commands:**

```bash
# Clone Crystal Dock
git clone --depth=1 https://github.com/dangvd/crystal-dock.git crystal-dock

# Alternative with submodules
git clone --recursive --depth=1 https://github.com/dangvd/crystal-dock.git crystal-dock
```

### Widget Frameworks (Bar-Capable)

| Project | Git Repository | Language | Description |
|---------|---------------|----------|-------------|
| **Eww** | https://github.com/elkowar/eww | Rust | ElKowars Wacky Widgets, configurable as bar |
| **Ags** | https://github.com/Aylur/ags | TypeScript/GJS | Aylurs GTK Shell, bar-capable |
| **Fabric** | https://github.com/Fabric-Development/fabric | Python | Next-gen desktop widget framework |
| **Quickshell** | https://github.com/quickshell-mirror/quickshell | C++ | QtQuick desktop shell toolkit |
| **Conky** | https://github.com/brndnmtthws/conky | C++ | System monitor with desktop output |

### WM Built-in Status/Taskbars

| WM | Git Repository | Built-in Bar | Description |
|----|---------------|--------------|-------------|
| **Sway** | https://github.com/swaywm/sway | Swaybar | Built-in status bar |
| **i3** | https://github.com/i3/i3 | i3bar | Built-in status bar |
| **dwm** | https://dwm.suckless.org/ | Status text | Status in window title |
| **xmonad** | https://github.com/xmonad/xmonad | Via xmobar | Uses xmobar/generic bar |
| **bspwm** | https://github.com/baskerville/bspwm | External | Uses polybar/lemonbar/eww |
| **herbstluftwm** | https://github.com/herbstluftwm/herbstluftwm | Herbstclient panel | Built-in panel |
| **spectrwm** | https://github.com/conformal/spectrwm | Built-in | Built-in status bar |
| **awesome** | https://github.com/awesomeWM/awesome | wibar | Built-in widget bar |
| **Qtile** | https://github.com/qtile/qtile | Bar widget | Python-based widget bar |
| **LeftWM** | https://github.com/leftwm/leftwm | External | Uses polybar/lemonbar |

### Legacy/Abandoned Projects

| Project | Git Repository | Language | Description |
|---------|---------------|----------|-------------|
| **Bmpanel** | https://github.com/nicm/bmpanel | C | Simple X11 panel (unmaintained) |
| **Fbpanel** | https://github.com/fbpanel/fbpanel | C | Lightweight panel (inactive) |
| **Wbar** | https://github.com/nicm/wbar | C | Dock-like bar (inactive) |
| **Dzen2** | https://github.com/dzen2/dzen2 | C | Simple bar (stable/unmaintained) |
| **Lemonbar** | https://github.com/LemonBoy/bar | C | Minimalist bar (stable) |

### Language Distribution Summary

| Language | Count | Notable Projects |
|----------|-------|------------------|
| **C** | ~20 | Polybar, Lemonbar, Dzen2, Tint2, Dwmblocks, i3blocks, Yambar |
| **C++** | ~8 | Quickshell, Sysbar, Husky-Panel, GBar, Conky |
| **Rust** | ~6 | Waybar, Eww, Ironbar, Bar-rs, Wayle, Heliumbar |
| **Python** | ~5 | Nwg-panel, Ags, Fabric, Py3status, DockbarX |
| **Haskell** | ~2 | Xmobar, Xmonad |
| **TypeScript** | ~1 | Ags |
| **Vala** | ~3 | Plank, Wingpanel, Budgie |
| **JavaScript** | ~1 | Cinnamon |

### Display Server Support Matrix

| Solution | X11 | Wayland | Both |
|----------|-----|---------|------|
| Waybar | | ✓ | |
| Polybar | ✓ | | |
| Lemonbar | ✓ | | |
| Dzen2 | ✓ | | |
| Xmobar | ✓ | | |
| Slstatus | ✓ | | |
| Tint2 | ✓ | | |
| i3bar | ✓ | | |
| Dwmblocks | ✓ | | |
| i3blocks | ✓ | | |
| Yambar | | ✓ | |
| Nwg-panel | | ✓ | |
| Ironbar | | ✓ | |
| GBar | | ✓ | |
| Hyprbar | | ✓ | |
| Eww | | | ✓ |
| Ags | | | ✓ |
| Conky | | | ✓ |
| Quickshell | | | ✓ |
| Fabric | | | ✓ |


