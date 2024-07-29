Using the official archiso tool in Arch Linux, I built an Arch Linux live CD/USB ISO image with the baseline configuration file. The final ISO image can run perfectly on a VPS with more than 512MB of memory, enabling system reinstallation.

Commands:
pacman -S archiso
mkarchiso -v vps_archiso/