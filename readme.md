# nautilus-send-to-bluetooth

Simple way to send files to bluetooth devices using nautilus file manager

# Install on ArchLinux
use this command to install it from AUR:

```bash
yaourt -S nautilus-send-to-bluetooth
```

then restart nautilus using `nautilus -q` command

# Install on other distros
make sure dependencies are installed (or alternatives in your distro):

```
python
python2-nautilus
gnome-bluetooth
nautilus
```

then copy 'SendToBluetooth.py' file to '/usr/share/nautilus-python/extensions/'

then restart nautilus using `nautilus -q` command
