# 2.vagrant
Vagrant Download Path : https://www.vagrantup.com/downloads.html
Oracle Virtual Box Download Path : https://www.virtualbox.org/wiki/Downloads
cmder shell Download Path : http://cmder.net/

#Post installation check the version by running below command
vagrant -v

#Create First Image
mkdir ubuntu
cd ubuntu
vagrant init hashicorp/precise32
vagrant up

#ssh to the virtual machine
vagrant ssh

#check and run ubuntu commands
uname -a

#Displaying GUI interface

#Sharing Files with VM

#Suspending the VM
vagrant suspend

#Resume the VM
vagrant resume

#Halting the VM/Shutdown
vagrant halt

#Destroying the VM
vagrant destroy

#Recreate/Reprovision the VM
vagrant up

#Help Tag
vagrant -h

