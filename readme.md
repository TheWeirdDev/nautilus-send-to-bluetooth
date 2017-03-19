# nautilus-send-to-bluetooth

Simple way to send files to bluetooth devices using nautilus file manager

# Install on ArchLinux
Use this command to install it from AUR:

```bash
yaourt -S nautilus-send-to-bluetooth
```

then restart nautilus using `nautilus -q` command


# Install on Ubuntu based distros
Install dependencies using this command:

```bash
sudo apt install python-nautilus nautilus bluez gnome-bluetooth python3
```
then copy 'SendToBluetooth.py' file to '/usr/share/nautilus-python/extensions/'

then restart nautilus using `nautilus -q` command

# Install on other distros
Make sure dependencies are installed (or alternatives in your distro):

```
python
python2-nautilus (or python-nautilus)
gnome-bluetooth
nautilus
bluez
```

then copy 'SendToBluetooth.py' file to '/usr/share/nautilus-python/extensions/'

then restart nautilus using `nautilus -q` command
