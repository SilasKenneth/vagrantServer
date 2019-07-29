### Creating and connecting to a windows VM using Vagrant
The repo contains a **Vagrantfile** necessary for creating a windows VM and
connecting to it using a tool of your choice. For my case I use Windows Remote Desktop application which a free application by Microsoft to connect to windows machine remotely.

#### Getting the VM to be up.
Follow the below steps to run the vagrant VM in your machine and connect to it vie Windows Remote Desktop.



#### Requirements

- Free space of atleast **17 GB** to be used by the output of creating the VM using Vagrant.
- [VirtualBox](https://www.virtualbox.org/)
- [Vagrant](https://www.vagrantup.com/)
- [Windows Remote Desktop Application](https://www.microsoft.com/en-us/p/microsoft-remote-desktop/9wzdncrfj3ps?activetab=pivot:overviewtab)

#### Steps
To run the VM follow the steps below.
 - Clone the repo using `git clone https://github.com/SilasKenneth/vagrantServer.git`
 - Navigate to the repo folder using `cd vagrantServer`
 - Run `vagrant up`.
 - Wait for Vagrant to finish building the box. Once done, open Windows Remote Desktop application and click on Add desktop.
 - Enter the public IP address of your machine to connect as `vagrant` user. If you want to connect as another user, use the Private IP in the Vagrantfile.

 And that's it happy windowing. 🎉🎉🎉🎉🎉
