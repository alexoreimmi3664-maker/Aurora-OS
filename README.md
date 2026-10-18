# Aurora-OS
### Just an OS

This is a remix of Debian 13 (Trixie)
It has a bunch of bugs, I'm sure, and I don't recommend using it as your default OS.
Try it first with QEMU (https://qemu.org) and my QEMU VM MANAGER (https://github.com/alexoreimmi3664-maker/QEMU-GUI) for the best experience


Since the file is 2.5 GB, I don't really know how to upload it to GitHub.


## Downloading
Step 1:
Download the zip file.
Follow the instructions below.

## How to Rejoin the ISO File

Because the ISO file exceeds GitHub's file size limits, it has been split into smaller chunks. To reconstruct the original 2.5 GB ISO file, download all the `.part` files into the same folder and run the appropriate command for your Operating System:

### 🪟 Windows (Command Prompt or PowerShell)
```cmd
cmd /c copy /b aurora-os-amd64.hybrid.iso.part* aurora-os-amd64.hybrid.iso
```

### 🍎 macOS / 🐧 Linux (Terminal)
```bash
cat aurora-os-amd64.hybrid.iso.part* > aurora-os-amd64.hybrid.iso
```
