# Third-Party Notices

Stream Copy Remuxer and Transcoder is packaged with Python 3.11, Tcl/Tk, TkinterDnD2/TkDND, and the PyInstaller bootloader. License texts are embedded in the EXE and copied to `data/documentation/licenses` on first launch.

## FFmpeg and FFprobe

FFmpeg and FFprobe are not included in this executable or its ZIP. The app requires FFmpeg 9 or newer and a working, matching FFprobe. It checks its FFmpeg subfolders, manually copied tools beside the EXE, and then the system PATH. If needed, it offers to download FFmpeg Full directly from gyan.dev into the app's `ffmpeg` subfolder. The provider's builds are licensed under GPLv3; the downloaded package's license and readme are retained beside the tools.

Downloads require confirmation, are verified against the provider's SHA-256 and are installed in a versioned `ffmpeg` subfolder beside the app. Existing system installations are read without being modified. No graphics driver or Vulkan SDK is redistributed or installed by the app.

FFmpeg project information: https://ffmpeg.org/

Windows build provider: https://www.gyan.dev/ffmpeg/builds/

## TkinterDnD2 and TkDND

TkinterDnD2 0.6.2 is an MIT-licensed Python wrapper and packaged Tk extension for native OLE2 drag-and-drop on Windows. See `licenses/TkinterDnD2-MIT-LICENSE.txt`.

Project information: https://github.com/Eliav2/tkinterdnd2

## Python

Python Software Foundation License. See `licenses/Python-3.11-LICENSE.txt`.

## Pillow

Pillow 11.3.0 provides image support. Its license and bundled-library notices are included in `licenses/Pillow-LICENSE.txt`.

## Tcl/Tk

BSD-style Tcl/Tk license. See `licenses/Tcl-Tk-license.terms`.

## PyInstaller

GPL license with the PyInstaller bootloader exception. See `licenses/PyInstaller-COPYING.txt`.

The PyInstaller 6.16.0 Windows bootloader was modified on 2026-10-15 to place extraction in `data/temp` beside the executable, handle literal percent characters in its path, and keep temporary work there. Upstream per-instance access restrictions and normal-exit cleanup are retained. The matching third-party source and changes are available in the repository’s [licensing folder](licenses/PyInstaller-6.16.0-portable-launcher-source.zip). These materials are not needed to run the app. This archive contains PyInstaller source, not the application's source.

Project and license: https://pyinstaller.org/en/v6.16.0/license.html
