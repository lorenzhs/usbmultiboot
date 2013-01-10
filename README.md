==INSTALLATION==

Assuming the USB key is /dev/sdc and the partition with the data files is mounted to /mnt, issue the following command as root:
  grub-install --no-floppy --boot-directory=/mnt/boot /dev/sdc

When this has completed, copy your iso files to /mnt/boot/iso/ and the grub.cfg to /mnt/boot/grub/grub.cfg.
You then should be able to boot from it
