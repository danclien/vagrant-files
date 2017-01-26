# Notes

## Installing the Vagrant LXC plugin
```
vagrant plugin install vagrant-lxc
```

## Settings the default Vagrant provider to LXC

Add to `.profile` (`bash`) or `.zprofile` (`zsh`):
```
export VAGRANT_DEFAULT_PROVIDER='lxc'
```

## Scripts for LXC images
[https://github.com/obnoxxx/vagrant-lxc-base-boxes](https://github.com/obnoxxx/vagrant-lxc-base-boxes)

## Uploading the Ubuntu LXC image to Google Cloud Storage
```
gsutil cp <file> gs://static.danclien.com/vagrant/
```

## References
* [Vagrant LXC plugin](https://github.com/fgrehm/vagrant-lxc)
