# Kitchen CAD Pro V5 RC6 BETA release notes

Release date: 2026-11-12
Channel: BETA PRE-RELEASE, not production certified.
Binary: KitchenCADProV5_RC6_BETA_Setup.exe
Operating system: Windows desktop, unvalidated across all supported Windows versions.

Verified in recorded QA:
- Frozen RC6 application smoke tests: 3/3 passed, each under 60s on GeForce GT 730.
- GPU/CPU fallback tests: 2/2 passed.
- Sandbox-only QA installer clean-install/selftest/uninstall: 18/18 passed; this is not a test of the BETA installer.

Not yet verified:
- Actual install/upgrade/rollback of BETA setup on a normal host or clean representative VM.
- Historical R17H startup hang root cause.
- Full interactive 10-step kitchen workflow acceptance.
- CNC machine data/postprocessor and production fabrication authorization.
- Authenticode certificate signing. SmartScreen warnings may occur.

At packaging, V3 criteria: 86% verified and 14% still pending.
All CNC/cut-list/manufacturing drafts require independent verification before physical production.
