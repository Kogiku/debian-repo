**Using third-party repositories as instructed below is not supported by the Debian project and could break your system now or when you upgrade later. Use with caution at your own risk!**
1. Download packages containing the apt source file and public GPG key:
```
wget https://kogiku.github.io/debian-repo/pool/main/k/kogiku-apt-source_20200106-1_all.deb
wget https://kogiku.github.io/debian-repo/pool/main/k/kogiku-archive-keyring_20200106-1_all.deb
```
2. Then (as root) install the downloaded packages and update:
```
apt install ./kogiku-*.deb
apt update
```
Included packages:
 * **apindex** (from https://github.com/libthinkpad/apindex)
 * **bsnes-plus** (from https://github.com/devinacker/bsnes-plus)
 * **cmdpack** (from https://github.com/chungy/cmdpack)
 * **exhale** (from https://gitlab.com/ecodis/exhale)
 * **gnome-icon-theme-s** (from https://github.com/Kogiku/gnome-icon-theme-s)
 * **gogo:i386** (from https://github.com/teragonaudio/gogo-no-coda)
 * **nauz-file-detector** (from https://github.com/horsicq/Nauz-File-Detector)
 * **ncnn** (from https://github.com/Tencent/ncnn)
 * **patchmatrix** (from https://github.com/OpenMusicKontrollers/patchmatrix)
 * **realsr-ncnn-vulkan** (from https://github.com/nihui/realsr-ncnn-vulkan)
 * **sc-controller** (from https://github.com/Ryochan7/sc-controller)
 * **solarc-theme** (from https://github.com/schemar/solarc-theme)
 * **spek-alternative** (from https://github.com/withmorten/spek-alternative)
 * **srmd-ncnn-vulkan** (from https://github.com/nihui/srmd-ncnn-vulkan)
 * **ucon64** (from https://ucon64.sourceforge.io)
 * **waifu2x-ncnn-vulkan** (from https://github.com/nihui/waifu2x-ncnn-vulkan)
 * **xelfviewer** (from https://github.com/horsicq/XELFViewer)
