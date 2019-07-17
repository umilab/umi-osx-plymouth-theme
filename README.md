
# umi-osx Plymouth Theme

UMI OSX like designed boot splash

### Installation

```bash
# According the base directory is this project's directory

sudo mkdir -p /usr/share/plymouth/themes/umi-osx
sudo cp -R ./* /usr/share/plymouth/themes/umi-osx

sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/umi-osx/umi-osx.plymouth 100

# select umi-osx theme in list from following command
sudo update-alternatives --config default.plymouth

sudo update-initramfs -u
```
