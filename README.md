# dzi_dot_files

```bash

sudo apt install i3-gaps xss-lock picom scrot i3blocks
```

```bash
sudo apt install libxcb-res0-dev/kali-rolling
sudo apt install libx11-xcb-dev/kali-rolling
sudo apt build-dep dwm
```

## Timeshift on btrfs with autosnap

```bash
sudo apt install timeshift grub-btrfs

git clone https://github.com/wmutschl/timeshift-autosnap-apt.git /home/$USER/timeshift-autosnap-apt
cd /home/$USER/timeshift-autosnap-apt
sudo make install
```
Test
```bash
sudo timeshift-autosnap-apt
```
