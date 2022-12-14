# Command-Line Interface

## NEWEST

- Use localtime instead of UTC
  - `timedatectl set-local-rtc 1`
- Wipe Disk
  - `sudo wipefs -a /dev/sda`
  - `sudo dd if=/dev/zero of=/dev/sda` or `sudo shred /dev/sda`
- Switch TTY
  - `Ctrl + Alt + F1`
  - `chvt 1`
- Change hostname
  - `sudo hostnamectl set-hostname <new-hostname>`
- Add Sudoer
  - `adduser <username>`
  - `usermod -aG sudo <username>`

## Format USB
- `df`
- `sudo umount /dev/sdb1`
  - `sudo mkfs.vfat /dev/sdb1`
  - `sudo mkfs.ntfs /dev/sdb1`
  - `sudo mkfs.exfat /dev/sdb1`
- `sudo fsck /dev/sdb1` Verify USB Drive Formatting

## Tools

- cheat.sh
  - `curl cheat.sh/<command-to-search>`
  - install: `curl -s https://cht.sh/:cht.sh | sudo tee /usr/local/bin/cht.sh && sudo chmod +x /usr/local/bin/cht.sh`
    - `cht.sh <command-to-search>`
  - install shell: install `xsel rlwrap`
    - `cht.sh --shell`
- `tldr`

## System monitor
- `duf`
- `inxi` - a full featured system information script
  - `inxi -b` --basic = Show basic output, short form
  - `inxi -Fz` = Full info
- `gpustat`
  - `gpustat -cpi`
