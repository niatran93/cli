# Command-Line Interface

- Switch TTY
  - `Ctrl + Alt + F1`
  - `chvt 1`
- Change hostname
  - `sudo hostnamectl set-hostname <new-hostname>`
- Add Sudoer
  - `adduser <username>`
  - `usermod -aG sudo <username>`

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
