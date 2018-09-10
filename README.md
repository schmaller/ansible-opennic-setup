# OpenNIC Setup with Ansible
This is a simple Ansible Script to use to setup an OpenNIC server with Ansible. It
currently only supports CentOS 7. I do plan to add Debian and Ubuntu support in the
future. It is also an open project, so feel free to fork and make your own changes.
I also welcome feedback.

## CentOS 7
* Installs and configures Firewalld
* Installs and configures Named
* Configures SELinux to allow Named without turning off SELinux

## Fedora 28
* **NOTE:** Make sure in your hosts file to add your Fedora servers like so "xxx.xxx.xxx.xxx ansible_python_interpreter=/usr/bin/python3"
* Installs and configures Firewalld
* Installs and configures Named
* Configures SELinux to allow Named without turning off SELinux

## Ubuntu 18.04 LTS
* Installs and configures Bind9
* Installs and sets UFW to allow SSH and Port 53 (doesn't do any other changes)

## To-Do
* Debian Support
* Ubuntu Support