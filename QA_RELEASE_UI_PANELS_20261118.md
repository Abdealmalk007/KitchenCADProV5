# Kitchen CAD Pro V5 — UI Panels Beta (18 November 2026)

**Public Beta / نسخة تجريبية محدّثة** — Windows 10/11 x64, Portable ZIP, unsigned.

This release addresses user feedback that the catalog and property side panels occupied most of the design canvas in the earlier `v5.0.0-beta-cpu3d-20261118` Beta.

## What's fixed / الإصلاحات

- **More drawing space:** real Windows QA at 1593×829 produced **1031px canvas**, up from approximately 560px in the submitted screenshot, while keeping the panels accessible.
- **Focus Canvas (F9):** hides all side panels and expands to **1589px drawing area** at 1593px width, then restores the panels without changing the kitchen model.
- **Tabbed workflow and catalog:** Workflow and Catalog Studio share one dock area instead of each occupying separate large blocks.
- **Panels menu:** explicitly show or hide Workflow (`Ctrl+Shift+1`), Inspector/Properties (`Ctrl+Shift+2`), or Catalog (`Ctrl+Shift+3`).
- **Organized catalog:** item search and results remain visible; template editing/administration is under a collapsible **Advanced** section. The original commands and tooltips remain accessible.
- **Readable properties:** long bilingual Inspector labels wrap rather than squeezing numeric dimension controls.
- **Responsive Windows layout:** measured **842px canvas at 1366px window**, and **616px at 1100px**. Arabic/English toggles and layout reset keep the scene intact.

## Download and run

Download `KitchenCADProV5_UI_PANELS_BETA_20261118_PORTABLE.zip`, extract **ALL** files into one folder, and run:

`Launch_KitchenCAD_UI_PANELS_QA.cmd`

The ZIP contains the compiled `KitchenCADProV5_UI_PANEL_QA_PREVIEW_20261118.exe` plus a sample kitchen with four walls and two cabinets. It installs nothing and uses isolated QA data in `%LOCALAPPDATA%\KitchenCADProV5QA\UIPanelsBeta`.

## Verification

- **13/13 Python/Qt regression tests PASS**; Ruff critical checks PASS.
- Actual Windows Qt full-resolution UI acceptance PASS, project sample unchanged.
- Standalone frozen EXE Windows UI Automation PASS (5 required controls, two Focus toggles).
- Full ZIP CRC and SHA256; **445 files**; successful cold extraction into a separate folder followed by another real Windows UIAutomation PASS.
- Matching archive backups on **E:** and **F:**.
- ZIP SHA-256: `2a7fc416db1417c0dd42e4e0bb1cf7f0aeb1868bde75320be1e9067b31183791`
- EXE SHA-256: `0fa89472ca7c9eb6d41bb5b0886aac73198e0a2df6122825f2e41c95b1d996e3`

## Important QA limitations

This release is intended for **voluntary UI/design evaluation only**. It is not a production-certified kitchen manufacturing application. The 3D CPU preview is **static**, not a full GPU renderer; the native OpenGL shutdown crash, historical startup investigation, production in-place installer/rollback and physical CNC machine/operator signoff remain unresolved. Never use CNC, Cut List, BOM, measurements or estimates for fabrication without independent verification by a qualified workshop technician.

The executable is **UNSIGNED**; Windows SmartScreen may show an unverified-publisher warning. Do not disable security software to launch it. Work on copies and back up client projects.

Copyright © 2026 ProTech. Original code All Rights Reserved, subject to applicable third-party licenses. Feedback: protech.2025.2026@gmail.com.

**This is a NEW prerelease.** The prior CPU3D Beta tag and files remain unchanged.
