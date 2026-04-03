# Virtual-machines-arch-artix
```
sudo pacman -S qemu-full virt-manager virt-viewer libvirt dnsmasq edk2-ovmf swtpm iptables-nft bridge-utils
```
also for artix
```
sudo pacman -S libvirt-<init>
```
add your user to the libvirt group
```
sudo usermod -aG libvirt $USER
```
enable services
```
sudo systemctl enable libvirtd
```
or (example, use whatever init u got)
```
sudo dinitctl enable libvirtd
```

reboot
