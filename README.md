# Vagrant machines for Ansible testing

Vagrant machines created for testing Ansible

## Usage

Initialize VMs:

```bash
vagrant up
```

Log into one of the running VMs:

Available VMs are client or server.

Client has ansible and everything needed to run it out-of-the-box, configured
to act as the configuration master.

Server is just a debian VM, used for testing ansible configurations.


```bash
vagrant ssh client
```

```bash
vagrant ssh server
```
