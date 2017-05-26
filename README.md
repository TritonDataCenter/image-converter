# Image Converter

This is an experimental script that can be used to create a Triton KVM image from a from a given qcow2, vmdk or raw image file.

See `convert-image -h` for usage.

Note: You will need a fairly recent version of qemu-img. The script is known to work with qemu-img 2.4.0.1. You can install qemu-img on SmartOS with pkgsrc. The pkgsrc 2015Q4 release should have at least this version.
