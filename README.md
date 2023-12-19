# AuroraOS

To build the iso you need a ArchLinux environment. Derivates may work but not tested. You can use a virtual machine if you don't have a system with ArchLinux.

Install qemu and archiso
```bash
sudo pacman -S archiso qemu-full
```

Then run the build script.
```bash
sudo bash build.sh
```

Test the newly created iso in a live environment with qemu
```bash
bash run.sh
```

Refer to the docs for more info on how to tweak the system <br>
https://wiki.archlinux.org/title/Archiso
