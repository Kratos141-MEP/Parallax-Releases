# Parallax Releases

Parallax installer downloads and signed update information.

## Install

The 1.5.4 installer was replaced again on 15 October 2026 to fix Setup stopping on an unsupported XML encoding label in an unrelated Revit add-in registration, including older registrations that use ClientId. This includes the reported ReviToDWG registration. Existing add-in files are preserved, and a valid existing pyRevit installation is reused. If you downloaded 1.5.4 before this latest replacement, download the EXE again and run it manually; the version and installer password are unchanged.

1. Download the latest `Parallax_Setup_vX.Y.Z.exe` from [Releases](https://github.com/Kratos141-MEP/Parallax-Releases/releases/latest).
2. Run Setup and enter the password supplied separately by the distributor. Installation is per Windows user.
3. From 1.5.4, Setup includes pyRevit for machines without it and preserves a valid existing pyRevit environment. A new pyRevit installation requires restarting Revit. Otherwise follow Setup's Reload/restart instructions.
4. Revit may remain open during installation. Close AutoCAD if Setup requests it to replace or repair CadBridge; matching bundles can remain in use.
5. Chat includes its own runtime and PDF readers. Sign in with ChatGPT through Codex Setup.

Version 1.5.4 is offered for direct user testing. Clean-machine installation and new Revit workflows have not completed live acceptance. See the installed Patch Notes for changes and scope.

pyRevit is distributed under GPL v3 with upstream notices and [the exact corresponding source](https://codeload.github.com/pyrevitlabs/pyRevit/zip/refs/tags/v6.4.0.26100%2B0515). Parallax installation restrictions do not restrict rights to that component.

`manifest.json` is signed update metadata used by Parallax. Do not run it. The project signature authenticates the package; it does not provide a Windows publisher certificate. Older clients that cannot read the new update information must download and run the latest installer manually.

Users on 1.5.3: download and run the 1.5.4 EXE manually once. Its bundled runtime and pyRevit exceed the old client update-size limit.
