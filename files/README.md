# Vagrant

## Configuration
VAGRANT_DEFAULT_PROVIDER = vmware_workstation
VAGRANT_HOME = D:\VMs\.vagrant.d
VAGRANT_VMWARE_CLONE_DIRECTORY = D:\VMs\VMWare\vagrant




## run cluster vagrant file: 

```powershell
$env:VAGRANT_VAGRANTFILE="Vagrantfile_cluster"
$env:qty=2
$env:boxname=""
vagrant up
```
