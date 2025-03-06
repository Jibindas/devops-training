To install Ansible on Windows, you generally have two main options: using ** Windows Subsystem for Linux (WSL)** or setting up a **Linux virtual machine**. Ansible is natively built for Linux-based systems, so using WSL is the easiest approach to run Ansible on Windows.

# Option 1: Install Ansible on Windows using WSL (Windows Subsystem for Linux)
## 1. Enable WSL on Windows
> Open PowerShell as Administrator and run:
> > wsl --install
* If WSL is already enabled, you can skip this step.

## 2. Install a Linux distribution:
> After enabling WSL, you can install a Linux distribution of your choice from the Microsoft Store (Ubuntu is commonly used).
> Once installed, launch the Linux distribution (e.g., Ubuntu) and set up a user account.

## 3. Update your WSL distribution:
> Open the WSL terminal and run the following commands to update your Linux distribution
> > sudo apt update <br />
sudo apt upgrade

## 4. Install Ansible:

> In the WSL terminal, run the following commands to install Ansible:
> > sudo apt install software-properties-common<br />
> > sudo add-apt-repository --yes --update ppa:ansible/ansible<br />
> > sudo apt install ansible

## 5. Verify Installation:
> Once installed, you can verify the installation by running:
> > ansible --version


# Option 2: Install Ansible using a Virtual Machine

Alternatively, you can use a virtual machine running a Linux OS like Ubuntu or CentOS. You can use virtualization software such as VirtualBox, VMware, or Hyper-V.

**Steps:**
## 1. Create a Virtual Machine (VM):
* Download and install a virtualization software such as VirtualBox or VMware.
* Create a new virtual machine and install a Linux distribution like Ubuntu.

## 2. Install Ansible on the Virtual Machine:
* Once the VM is set up and running, follow the same steps for installing Ansible as you would on a native Linux system. For example:
> sudo apt update<br />
sudo apt install ansible 


