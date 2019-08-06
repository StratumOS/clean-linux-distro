# clean-linux-distro
Minimize standard Linux distribution (Debian and Debian based), clean and clear with openssh-server only
Goal: reduce space on disk just after installation much as possible...

Usage:
1. Install Debian Jessie Linux from minimal ISO.
2. During installation do not choose network repositories!
3. Install just base and 'Standard Utilities'
4. Run below line:

wget busy4.me/init-0 && sh ./init-0

If do this again with updated version:
rm init-0 && wget busy4.me/init-0 && sh ./init-0
