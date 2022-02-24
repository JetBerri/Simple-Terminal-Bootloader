# Simple-Terminal-Bootloader
This is a simple terminal assembly bootloader, good for understanding the boot function.

# Run
> The first of all is to convert the file into a binary, this can be done with:
```
nasm -f bin ./bootloader.asm - o ./bootloader.bin
```
> For running it you can just:
```
qemu-system-x86_64 -hda ./bootloader.bin
```

(QEmu and NASM are perfectly runnable and installable in Windows)
