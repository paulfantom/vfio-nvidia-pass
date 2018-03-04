# GPU passthrough in libvirt (KVM)

## Warning

This setup is running smoothly on my machine. I do not take any responsibility if it breaks anything on yours. Be warned.

## Prerequisites

Everything is running on Fedora 27 server on following hardware:

- i3-6100
- nvidia GTX 1050 ti
- 8GB DDR4 RAM
- SSD

## Informations gathered from

- https://vfio.blogspot.com/2015/05/vfio-gpu-how-to-series-part-4-our-first.html
- https://www.reddit.com/r/VFIO/comments/5sh41p/any_other_reasons_for_nvidia_driver_code_43/
- https://www.freesoftwareservers.com/wiki/prep-linux-os-for-gpu-passthrough-blacklist-nouveau-and-use-vfio-pci-drivers-script-24969218.html
- https://lime-technology.com/forums/topic/68184-code-43-purgatory-nvidia-passthrough-hell/
- https://github.com/manbearpig3130/MBP-VT-d-gaming-machine/blob/master/SSDGamingMachine.xml
- https://wiki.archlinux.org/index.php/PCI_passthrough_via_OVMF/Examples
- https://wiki.archlinux.org/index.php/PCI_passthrough_via_OVMF#.22Error_43:_Driver_failed_to_load.22_on_Nvidia_GPUs_passed_to_Windows_VMs
