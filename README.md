# Hatsune Miku Grub Theme

A theme of Hatsune Miku for Grub!

## Installation

1. Download & Unzip

2. Copy `HatsuneMiku/[preffered size]-HatsuneMiku` into grub themes directory:

```bash
sudo cp -r HatsuneMiku/4k-HatsuneMiku /usr/share/grub/themes
```

3. Edit `grub` file:

```bash
sudo nano /etc/default/grub
```

4. Change your default theme to HatsuneMiku:

```bash
GRUB_THEME="/usr/share/grub/themes/4k-HatsuneMiku/theme.txt"
```

5. Update grub:

```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
# or
sudo update-grub
```

6. Reboot the computer
