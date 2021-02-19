
My 2020 Manjaro setup
=======================

Why Manjaro?

- try a rolling release distro
- try openbox

Hardware
----------

- Ryzen 5 3600 (A320, A520, B350, B450, B550, X370, X470, X570)  
- G.Skill Ripjaws V Black DDR4 2 x 16 Go 3200 MHz CAS 16  (144 €)  
- [Gigabyte B550 Aorus Elite](2020-setup-manjaro.md)
    - Realtek Semiconductor Co., Ltd. RTL8125 2.5GbE Controller (rev 05)
        - not supported on linux (will buy PCI card)
    - sensors may bot be recognized on linux (acceptable)
    - no aura control on linux (acceptable)
    - no bluetooth on linux (acceptable)
    - no hdmi audio on linux (acceptable)
    - usb3 issues on linux (acceptable)
- AMD/ATI RV790 Radeon HD 4890
- Realtek Semiconductor Co., Ltd. RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller (rev 06)

[Article: Building a Linux pc with B550 motherboard
](https://www.reddit.com/r/linuxhardware/comments/hctqn4/building_a_linux_pc_with_b550_motherboard/)

Manjaro base setup
--------------

Using my old SSD, I wanted a simple encrypted / and UEFI boot. 

Distro: Manjaro Architect.

```
Disk /dev/sda: 111.79 GiB, 120034123776 bytes, 234441648 sectors
Disk model: OCZ-AGILITY3    
Disklabel type: gpt

Device       Start       End   Sectors   Size Type
/dev/sda1     2048   1026047   1024000   500M EFI System
/dev/sda2  1026048   2050047   1024000   500M Linux filesystem
/dev/sda3  2050048 234441614 232391567 110.8G Linux LVM

Disk /dev/mapper/vg0: 110.81 GiB, 118982385152 bytes, 232387471 sectors

Disk /dev/mapper/vg0-lvolroot: 108.86 GiB, 116882669568 bytes, 228286464 sectors


/dev/mapper/vg0-lvolroot  /       ext4      	rw,relatime	0 0
/dev/sda2                 /boot   ext4      	rw,noatime	0 0
/dev/mapper/vg0-lvolswap  none    swap      	defaults,pri=-2	0 0
```

TODO: add links to all troubleshooting articles

Graphical setup
---------------


















