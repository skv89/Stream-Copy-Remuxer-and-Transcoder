# Third-party notices

Stream Copy Remuxer and Transcoder includes the Python 3.11 runtime, Tcl/Tk, TkinterDnD2/TkDND and the PyInstaller bootloader. The runtime license texts are provided in this repository:

- [Python 3.11 license](licenses/Python-3.11-LICENSE.txt)
- [Tcl/Tk license](licenses/Tcl-Tk-license.terms)
- [TkinterDnD2 MIT license](licenses/TkinterDnD2-MIT-LICENSE.txt)
- [PyInstaller license and bootloader exception](licenses/PyInstaller-COPYING.txt)

These notices concern third-party components; they do not publish or license this application's development source.

## FFmpeg and FFprobe

FFmpeg and FFprobe are **not bundled** in the executable or EXE-only release ZIP. The app first looks for a compatible matching pair on the computer. With the user's confirmation, it can download a Windows Full build from [gyan.dev](https://www.gyan.dev/ffmpeg/builds/), verify the provider-published SHA-256 and install it in a versioned folder beside the app. That separate download retains its own license and readme and is governed by its build configuration and GPLv3 terms.

[FFmpeg project](https://ffmpeg.org/) · [TkinterDnD2 project](https://github.com/Eliav2/tkinterdnd2)

Graphics drivers, Vulkan SDKs, CUDA toolkits, GPU firmware and AI models are not distributed or installed by this app. Optional NVIDIA/Vulkan features use the compatible driver already installed by the user.
