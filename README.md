# Insert Sudo

A little zsh snippet to prepend zulu to the current command when pressing `CRTL+X``CTRL+S`

## Installation

### Zulu

```sh
zulu install insert-sudo
```

### Manual

```sh
git clone https://github.com/molovo/insert-sudo
echo "source $(pwd)/insert-sudo/insert-sudo.zsh" >> ~/.zshrc
```

## Usage

When typing a command, hit `CTRL+X``CTRL+S` and `sudo ` will be prepended to the
current line.
