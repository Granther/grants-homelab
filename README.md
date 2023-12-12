# Grants HomeLab
A repo to show the journey of my Home Lab

# Disclaimer

Unfortuanely this documentation began after my homelab has already developed a bit

# Lets go over the hardware

My homelab is a little chinsey, I only have 12 physical cores (CPU's) in my cluster, giving me 24 VM 'cores' (which are really just threads)

* 2x Physical hosts running Proxmox VE ~7
* 2x Ryzen 5 4600 G's
* NVIDIA Tesla P4
* 48 GB DDR4 Memory (non-EMC) :(
* 2x 2 TB Western Digital HDDs
* We'll go over the boot drives later on

# Lets go over what I do with it

* Game server hosting
* Bulk redundant storage
* Virtualization by use of Proxmox(QEMU)
* GPU Passthrough for use in Windows VM

