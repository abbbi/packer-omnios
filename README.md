Packer definition to build omnios community edition libvirt provider image.

Based on omnios-r151038v.iso

 * SSH enabled
 * Root/vagrant user passwords: vagrant
 * German timezone settings
 
Build via:

 wget https://downloads.omnios.org/media/stable/omnios-r151038v.iso
 
 packer build omnios.json
