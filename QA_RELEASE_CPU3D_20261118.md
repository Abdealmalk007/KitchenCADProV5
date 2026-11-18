# Kitchen CAD Pro V5 — CPU3D Portable Beta (18 Nov 2026)

**Public preview / نسخة تجريبية للاختبار فقط — not a production release.**

This is the newer **Windows x64 portable build** of Kitchen CAD Pro V5 with a stable, static CPU-based 3D preview. It is published for voluntary testing and feedback.

## Installation / طريقة التشغيل

1. Download `KitchenCADProV5_CPU3D_QA_20261118_PORTABLE.zip`.
2. Extract **all** files to a folder (do not launch the EXE inside the ZIP).
3. Run `Launch_KitchenCAD_CPU3D_QA.cmd` from that extracted folder.
4. A sample kitchen, `Sample_4Walls_2Cabinets.ngcad`, is included. Open it to experiment with walls, cabinets, openings, appliances and 2D/CPU 3D previews. Work on copies of existing projects.

**Portable:** no installer or administrator privileges needed. App user data is isolated in `%LOCALAPPDATA%\KitchenCADProV5QA\CPU3DPortableData`.

## Tested behavior

- PyInstaller frozen EXE ran on Windows x64 and the real GUI 3D QAction was invoked; CPU fallback appeared, app exited 0.
- ZIP: 445 files, complete CRC verification and pinned SHA-256.
- Extracted portable EXE passed independent cold-start software selftest.
- E/F archives matched the published candidate SHA-256.
- Consolidated validation: **25/25 automated tests passed**.

## Important limitations / قيود مهمة

- **CPU 3D is a static software preview**, not the original interactive GPU/PBR rendering path. The native OpenGL 3D crash is not fixed.
- The catalog available in the interface is a QA subset; third-party vendor catalogs and rights have not all been verified.
- Actual CNC machine operation, Cut List/BOM and manufacturing outputs are **NOT approved**. Never use these outputs for fabrication, cutting or machine control without independent checking and a qualified machinist's approval.
- Production installation, in-place upgrade/rollback, full clean-Windows guest acceptance and historical R17H startup diagnostics remain open.
- **Unsigned** Windows executable; Windows SmartScreen may display an unverified publisher warning. Do not disable antivirus or Windows security protections to run it.
- Project V3 verification at publication: **86% complete / 14% outstanding**. This public Beta is for feedback only and does **not** pass the Production release gate.
- No warranty. Copyright © 2026 ProTech. All Rights Reserved for original ProTech materials, subject to applicable third-party licenses.

## Checksums

Portable ZIP SHA-256:
`95a30e852b9df0709c4730ddc11c3e6bbd31415c2ccf345f5be5a352ad773be6`

Frozen EXE SHA-256:
`3221a1d4f68beaf27e90e3b41f1c746fc4d99980b465a7e64fbe33e3ca129b1c`

## Feedback

Report observed errors and attach a description of the operation, Windows version, and reproduction steps. Do not share private client projects or confidential files.

Website: https://alghad.digital/programs/kitchen/
Support: protech.2025.2026@gmail.com
