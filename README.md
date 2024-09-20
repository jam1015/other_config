# how to update grub
***make sure you customize grub for your system***
symlink the file `grub` to `etc/default/grub` and then run
`sudo grub-mkconfig -o /boot/grub/grub.cfg`
