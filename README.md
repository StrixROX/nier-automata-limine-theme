# Nier Automata Limine Theme

(I can't figure out a simple way to take a screenshot of the actual bootloader screen so here's the image of the background... if you can help with that please make a PR 🙂)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/707abbd1-e694-4213-8dbf-daeb4aa3d4bd" />

Nier Automata inspired theme for [Limine Bootloader](https://github.com/limine-bootloader/limine). The background is taken from [YoRHa GRUB Theme](https://github.com/OliveThePuffin/yorha-grub-theme). The original repository features more resolutions for the background which you can use as per your display resolution.

> I missed the theme when I switched to Limine so I took the liberty to create a Limine version.

# Usage

1. Download `background.png` and place it in your boot partition (usually `/boot` or `/boot/efi`).
2. Prepend the contents of `nier-automata.conf` to your `limine.conf` file. (Refer [limine docs](https://github.com/limine-bootloader/limine/blob/v12.x/CONFIG.md#location-of-the-config-file) for its location)
3. Update limine.
```bash
sudo limine-update
```
