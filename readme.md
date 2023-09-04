# Nautilus Send To Bluetooth

This extension adds a context menu item to nautilus that allows you to send files to your Bluetooth devices

# Install on ArchLinux

Use this command to install it from AUR:

```bash
yay -S nautilus-send-to-bluetooth
```

then restart nautilus using `nautilus -q` command

# Install on other distros

Make sure `python3`, `nautilus-python`, `bluez` and `blueman` are installed.

then copy `SendToBluetooth.py` file to

`/usr/share/nautilus-python/extensions/`

or

`~/.local/share/nautilus-python/extensions/`

then restart nautilus using `nautilus -q` command

# License

This extension is licensed under GPL-3 or newer
