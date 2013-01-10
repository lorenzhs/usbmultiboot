INSTALLATION
---

Assuming the USB key is `/dev/sdc` and the partition with the data files is mounted to `/mnt`, create a `boot` folder there and issue the following command as root:
`grub-install --no-floppy --boot-directory=/mnt/boot /dev/sdc`

When this has completed, copy the contents of this repository to `/mnt`. You might want to customize the `boot/grub/grub.cfg` first, though. You then should be able to boot from it
