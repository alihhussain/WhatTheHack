# What the Hack: Azure Arc enabled Servers  

Coaches for this WTH will be most successful if they have experience working with the following technologies:

* Azure IaaS
* Azure Arc enabled Servers
* Linux
* Terraform
* Shell scripts
* One or more of the following:
    * AWS
    * GCP
    * Other virtualization platforms (VMware, VirtualBox, Hyper-V)

## The Proctor's Guide and Lecture slide decks

Coaches can use the included [Azure Arc Overview](AzureArcOverview.potx) deck to set the stage for the hack and to explain at a high level the value of Azure Arc enabled Servers and the technical scenarios it enables for Hybrid Cloud Unified Operations.

One of the most valuable resource for students participating in this hack is the [Azure Arc Jumpstart repo](https://github.com/microsoft/azure_arc). Every challenge in this hack can be completed using the methods found in the repo. The repo is also a great way to familiarize yourself with Azure Arc before proctoring the hack. Resourceful hack participants will use the repo as needed, but try not to let it be a crutch or "easy button". Students will learn and retain more if they experiment and try different methods. 

### Challenge 0

For participants using Windows devices, having VSCode and Windows Subsystem for Linux 2 is ideal but not mandatory. 

For students who will use AWS or GCP, they should be setting up access to their AWS/GCP environments during this challenge. Use the [Azure Arc Jumpstart repo](https://github.com/microsoft/azure_arc) if needed to show students how to create new accounts with these providers.

### Challenge 1

Students will get the most out of the hack if they have a place *other* than Azure to create virtual machines. Ideally, students will use a public cloud provider like AWS or GCP, or they will use a local hypervisor such as VirtualBox. Hyper-V can also be used but it will require some deploying a virtual router and some additional network configuration to get working. 

### Challenge 2

Keep in mind that using Azure Policy will require some patience as Policy checks happen at regular intervals. Students will not see instant results on their resources when they initially create a Policy and remediation task. 
