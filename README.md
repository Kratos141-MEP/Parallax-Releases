# Parallax Releases

Parallax installer downloads and signed update information.

## Install

User 1.5.5 improves ParaLink Category/Family values, Profile workflows, Chat and native operation results. **The installer does not include the Routix tab.**

1. Download `Parallax_Setup_v1.5.5.exe` from [Release 1.5.5](https://github.com/Kratos141-MEP/Parallax-Releases/releases/tag/v1.5.5).
2. Run Setup and enter the password supplied separately by the distributor. Installation is per Windows user.
3. Setup includes pyRevit for machines without it and preserves a valid existing pyRevit environment. A new pyRevit installation requires restarting Revit. Otherwise follow Setup's Reload/restart instructions.
4. Revit may remain open during installation. Close AutoCAD if Setup requests it to replace or repair CadBridge; matching bundles can remain in use.
5. Chat includes its own runtime and PDF readers. Sign in with ChatGPT through Codex Setup.

Tag Master, Drawing Register, Duct Report and Pipe Report remain disabled. Version 1.5.5 is released for direct user testing at the owner's request. Outstanding clean-machine and live Revit acceptance cases remain tracked separately; automatic checks do not imply live acceptance. See the installed VI/EN Patch Notes for changes and scope.

pyRevit is distributed under GPL v3 with upstream notices and [the exact corresponding source](https://codeload.github.com/pyrevitlabs/pyRevit/zip/refs/tags/v6.4.0.26100%2B0515). Parallax installation restrictions do not restrict rights to that component.

`manifest.json` is signed update metadata used by Parallax. Do not run it. The project signature authenticates the package; it does not provide a Windows publisher certificate.

Users on 1.5.3 or earlier: download and run the latest EXE manually once. Its bundled runtime and pyRevit exceed the old client update-size limit. Older clients whose update check fails must also download and run the installer manually.
