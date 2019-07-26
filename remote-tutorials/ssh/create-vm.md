---
Order: 2
Area: ssh
TOCTitle: Create a VM
PageTitle: Create a virtual machine on Azure
MetaDescription: Create a virtual machine on Azure
DateApproved: 7/26/2019
---
# Create a virtual machine

If you don't have an existing Linux virtual machine, you can create a new VM through the [Azure Portal](https://portal.azure.com). In the Azure Portal, search for "Virtual Machines", and choose **Add**. From there, you can select your Azure subscription and create a new resource group, if you don't already have one.

![Create a virtual machine](images/ssh/create-vm.png)

Now you can specify details of your VM, such as the name, the size of, and the base image. We will choose Ubuntu Server 18.04 LTS for this example, but you can choose recent versions of other Linux distros and look at our [supported SSH servers](https://code.visualstudio.com/docs/remote/troubleshooting#_installing-a-supported-ssh-server).

![Virtual machine instance details](images/ssh/vm-instance-details.png)

Next,

----

<a class="tutorial-next-btn" href="/remote-tutorials/ssh/create-ssh-key">I've created a virtual machine</a> <a class="tutorial-feedback-btn" onclick="reportIssue('remote-tutorials-ssh', 'create-vm')" href="javascript:void(0)">I ran into an issue</a>