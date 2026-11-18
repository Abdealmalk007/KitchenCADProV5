# Kitchen CAD Pro V5 - RC6 Beta

## New — CPU3D Portable Beta (18 November 2026)

**[Download Kitchen CAD Pro V5 CPU3D Portable ZIP](https://github.com/Abdealmalk007/KitchenCADProV5/releases/download/v5.0.0-beta-cpu3d-20261118/KitchenCADProV5_CPU3D_QA_20261118_PORTABLE.zip)** — 102,002,435 bytes, Windows 10/11 x64.

Extract the entire archive and run `Launch_KitchenCAD_CPU3D_QA.cmd`. A four-wall sample scene is included. This build uses a **static CPU 3D preview** to avoid an unresolved native OpenGL shutdown fault. This is voluntary QA testing only, **not** a production/CNC-certified application.

SHA-256: `95a30e852b9df0709c4730ddc11c3e6bbd31415c2ccf345f5be5a352ad773be6`.

[Full Beta release notes](https://github.com/Abdealmalk007/KitchenCADProV5/releases/tag/v5.0.0-beta-cpu3d-20261118) | [Checksum](SHA256SUMS_CPU3D_20261118.txt) | [Arabic instructions](README_AR.md)

**Do not use unverified CNC, BOM, cutting or cost outputs for fabrication.** Keep project backups; no Production installer/rollback or final clean Windows acceptance is claimed. EXE is unsigned and Windows SmartScreen may display a warning; never disable security software for testing.

---

### Previous release (RC6 Beta Setup)

**Status: Beta / نسخة تجريبية. Not stable or production certified.**

## Download
**[Download Kitchen CAD Pro V5 RC6 BETA for Windows](https://github.com/Abdealmalk007/KitchenCADProV5/releases/download/v5.0.0-rc6-beta/KitchenCADProV5_RC6_BETA_Setup.exe)**

- Installer: KitchenCADProV5_RC6_BETA_Setup.exe
- Size: 94,506,899 bytes (about 90.13 MiB)
- SHA256: E65571E8D840C6E0EAB7FE5B5B899EC81DA172B9AD7FC2088C88C35ACE731E25
- [Checksums](SHA256SUMS.txt) | [Arabic README](README_AR.md) | [Known limitations](RELEASE_NOTES.md) | [License](LICENSE)

### About this installer
This is the RC6 BETA installer for voluntary Windows evaluation. It installs side-by-side per user in Local AppData and does not replace previous installations. The different RC6 QA_Setup file is restricted to Windows Sandbox, cannot install normally, and is NOT published here.

### Planned/preview features
Room design, door and window openings, cabinet catalog, countertops, appliances, accessories, lighting and materials; 2D and 3D previews; saving/export and manufacturing drafts. The complete interactive workflow and all production deliverables have NOT received final acceptance.

### Honest test status
- Frozen RC6 EXE passed 3/3 GPU smoke runs and 2/2 GPU/CPU fallback checks.
- A distinct Sandbox-only QA installer passed 18/18 clean-install, runtime and uninstall stages. It is NOT the publicly downloadable Beta installer.
- The distributed BETA installer has NOT completed normal-host install/upgrade/rollback acceptance tests.
- At packaging time, V3 project acceptance was 86% verified and 14% pending.
- Historical startup-hang root cause, full UI workflow and actual CNC output approval are unresolved.
- The Beta installer is UNSIGNED (Authenticode NotSigned). Windows SmartScreen may warn.

**Safety:** Back up projects, evaluate on non-production systems. Never use CNC, cut lists, estimates, BOM or measurements for fabrication without independent review and approval from a qualified workshop technician for the actual machine, materials and postprocessor.

Copyright (c) 2026 ProTech. All Rights Reserved for original ProTech code and materials. Third-party licenses remain in effect. Beta is provided as-is without warranty.

Official website: https://alghad.digital/programs/kitchen/
Support: protech.2025.2026@gmail.com

Proprietary source code is not distributed in this public repository.
