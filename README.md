# Setting Up a Virtual Machine with Vagrant and VirtualBox: A Beginner's Guide

## Project Overview:
This project introduces you to setting up a virtual machine (VM) using Vagrant and VirtualBox. By the end, you'll have a fully configured VM running Ubuntu 22.04, serving a basic web page via Nginx. This setup is perfect for development, testing, or learning environments.

### What is Vagrant?
Vagrant is an open-source tool that simplifies the management of virtual environments. With Vagrant, you can:

Define and provision VMs using a single configuration file (Vagrantfile).
Automate software installation and environment setup.
Create reproducible, portable environments for teams or personal use.

### What is VirtualBox?
VirtualBox is a hypervisor—a software that allows you to run virtual machines on your physical computer. It is developed by Oracle and supports running multiple operating systems (called "guest OS") on a single host machine.

### How Vagrant and VirtualBox Work Together
Vagrant Uses VirtualBox as a Provider:

Vagrant itself does not create or manage VMs directly. Instead, it relies on providers like VirtualBox, VMware, or cloud platforms to perform the virtualization.
When you run vagrant up, Vagrant communicates with VirtualBox to create and configure the VM as specified in the Vagrantfile.
Vagrant Simplifies VirtualBox Usage:

Without Vagrant, you would have to manually configure VMs through the VirtualBox GUI or command line, which can be tedious and error-prone.
Vagrant automates this by abstracting away VirtualBox's complexity. For example, setting up networking, provisioning software, or defining VM specifications is done in a simple Vagrantfile.

### Prerequisites:

![alt text](image/Vagrant-browser.png)
