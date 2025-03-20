
### Plymouth theme file locations:
```bash
## Main location where base themes that come with the
## system are going to be located
/usr/share/plymouth/themes

## More of a community theme location
/lib/plymouth/themes
```


### Set custom file as current default plymouth?
```bash
ln -sf /lib/plymouth/themes/vinyl/vinyl.plymouth /etc/alternatives/default.plymouth
```


Refreshing configuration:
```bash
sudo update-initramfs -u -k all
```