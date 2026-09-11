# Parallax Releases

Parallax installer downloads and signed update information.

## Install

1. Install pyRevit if it is not already available on your computer.
2. Download the latest `Parallax_Setup_vX.Y.Z.exe` from [Releases](https://github.com/Kratos141-MEP/Parallax-Releases/releases/latest).
3. Close AutoCAD, then run the installer. Revit can remain open; use pyRevit > Reload after a manual installation.
4. Enter the password supplied separately by the distributor for that version.

An existing Parallax installation is not required. From version 1.4.1, Parallax can check for newer versions and download a verified installer. The updated 1.4.3 client opens Setup automatically after you click Update and the download is verified. Enter the new release password to install; close AutoCAD only. Older clients require a manual EXE launch once to gain this flow.

`manifest.json` is signed update metadata used by Parallax. Do not run it. The project signature verifies the update; it is not a Windows publisher certificate.
