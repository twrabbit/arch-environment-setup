# arch-environment-setup
A bash script to automate Arch Linux basic configuration after installation.

Welcome to Arch Environment Setup.<br>
This bash script will setup the basic on your new Arch Linux installation. This was designed mainly to be used after arch-installer, but feel free to read the code and see if serves to you.<br/>
It covers the following points:
<ul>
  <li>Root password change</li>
  <li>Hostname change</li>
  <li>Unprivileged usr creation</li>
  <li>Internet connection</li>
  <li>pacman.conf configuration</li>
  <li>System update</li>
  <li>Basic softwares installation:
    <ul>
      <li>openssh</li>
      <li>vim</li>
      <li>yaourt</li>
      <li>Graphic card driver (intel/nvidia/ati auto-detection)</li>
      <li>Wireless softwares</li>
      <li>Desktop Environment (gnone3 or xfce4)</li>
    </ul>
  </li>
  <li>.xinitrc creation in user home (if applicable)</li>
</ul>

Despite some efforts, this scritp was not designed to be user proof, so don't try to mess with it, because it will mess with your computer in return.


**Disclaimer:** This script comes with absolutely NO warranty and I bear NO responsibility for any damage or data loss in your computer or in any data storage connected to it. Use at your own risk! You have been warned!
