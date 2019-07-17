
# UMI-OSX Plymouth Theme

UMI OSX like designed boot splash

### Installation

```bash
# According the base directory is this project's directory

sudo mkdir -p /lib/plymouth/themes/UMI-OSX
sudo cp -R ./* /lib/plymouth/themes/UMI-OSX

sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/UMI-OSX/umi-osx.plymouth 100

# select umi-osx theme in list from following command
sudo update-alternatives --config default.plymouth

sudo update-initramfs -u
```
