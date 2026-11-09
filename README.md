# PD-OS Official Software Package Repository (ARM32 S905L)

Official software distribution repository for **PD-OS ARM32bit** running on the **Amlogic Meson GXL S905L** (Quad Cortex-A53).

## Package Architecture & Standard
In accordance with the official PD-OS application specification:
Each package directory `/opt/<appName>/` contains:
1. `<appName>.pda`: Standalone PD-OS GUI Application C source code utilizing the `<app.h>` native userspace windowing and graphics API.
2. `<appName>.pdj`: Package manifest defining application name, tooltip, and icon configuration:
   ```ini
   appName = "AppName"
   toolTip = ""
   iconImage = ""
   ```

## Packages in this Repository
- **pd-calc**: Desktop Calculator (`calc.pda`, `calc.pdj`)
- **pd-paint**: Paint Studio (`paint.pda`, `paint.pdj`)
- **pd-clock**: World Clock & Stopwatch (`clock.pda`, `clock.pdj`)
- **pd-notes**: Desktop Scratchpad & Notes (`notes.pda`, `notes.pdj`)
- **pd-sysmon**: System & Hardware Resource Monitor (`sysmon.pda`, `sysmon.pdj`)
- **pd-terminal**: Terminal Shell (`terminal.pda`, `terminal.pdj`)
- **pd-nettools**: Network Diagnostics (`nettools.pda`, `nettools.pdj`)

## Installation via PD-OS Package Manager
```bash
elev pdpm install pd-calc
elev pdpm install pd-paint
elev pdpm install pd-clock
elev pdpm install pd-notes
elev pdpm install pd-sysmon
elev pdpm install pd-terminal
elev pdpm install pd-nettools
```
