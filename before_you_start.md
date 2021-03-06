## Before you start

### Testing SSH
If you haven't yet done so, you should make sure you have created SSH keys and are able to use them to connect to a remote machine.

Github has a comprehensive guide for all major operating systems: [Connecting to Github with SSH](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

## Optional setup (for the afternoon)
This is optional setup for the ["local environment"](https://github.com/CorndelWithSoftwire/DevOps-Course-Workshop-Module-04/blob/main/during_the_workshop.md#creating-a-local-environment) section of the afternoon exercise, but it will be required for the project exercise.
### Hypervisor
Vagrant requires a hypervisor installed on your development machine. Oracle VirtualBox is a free cross-platform hypervisor, or if you are on Windows then Hyper-V is also an option.
* VirtualBox ([installation instructions](https://www.virtualbox.org/manual/ch02.html))
* Hyper-V (Windows only) ([installation instructions](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v))

### Vagrant
We will be using a configuration management tool called Vagrant.
* Download page: [vagrantup.com/downloads](https://www.vagrantup.com/downloads)
* Installation instructions: [vagrantup.com/docs/installation](https://www.vagrantup.com/docs/installation)

Once you have installed the version appropriate to your system, check you have access to Vagrant in the shell you are using:
```bash
vagrant --version
```
