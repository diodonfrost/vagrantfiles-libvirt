# Vagrantfiles-libvirt

This repository contains Vagrantfiles to run a virtual machine using Libvirt as the provider. The virtual machine is based on a pre-configured image and can be used for development, testing, or experimentation purposes.

## Prerequisites

Before using this repository, you need to have the following installed on your machine:

1. [Vagrant](https://www.vagrantup.com/downloads.html) (version 2.2.0 or higher)
2. [libvirt](https://libvirt.org/downloads.html) (version 6.0.0 or higher)
3. [vagrant-libvirt](https://github.com/vagrant-libvirt/vagrant-libvirt) (version 0.3.0 or higher)
4. [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) (version 2.9.0 or higher)

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/diodonfrost/vagrantfiles-libvirt.git
cd libvirt-vagrant-image
```

2. Start and provision the VM:

```bash
vagrant up --provider=libvirt
```

3. SSH into the VM:

```bash
vagrant ssh
```

4. Destroy the VM when you're done:

```bash
vagrant destroy
```

## Customizing the Virtual Machine

The virtual machine is based on a pre-configured image, but you can customize it by modifying the Vagrantfile or the scripts in the `scripts` directory. For example, you can change the amount of memory or the number of CPUs allocated to the virtual machine by editing the `Vagrantfile`.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue with any improvements, bug fixes, or suggestions.

## License

Apache 2
