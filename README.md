# Virtual-machines-archlinux
```
sudo pacman -S qemu-full virt-manager virt-viewer libvirt dnsmasq edk2-ovmf swtpm iptables-nft bridge-utils
```
```
sudo usermod -aG libvirt $USER
```
```
sudo systemctl enable virtqemud.socket
sudo systemctl enable virtnetworkd.socket
sudo systemctl enable virtnodedevd.socket
sudo systemctl enable virtnwfilterd.socket
sudo systemctl enable virtsecretd.socket
sudo systemctl enable virtsecretd.socket
sudo systemctl enable virtstoraged.socket
```
reboot
