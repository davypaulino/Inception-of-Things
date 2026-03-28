# Inception Of Things

> 

## Learn about

- Ansible
- Chef
- Puppet


## What is Vagrant?
> vagrant is a cli tool to create and manager virtual machines setups.

- [X] install vagrant with pacman.
- [X] create my first vagrant image.
- [X] install virtual box on arch linux.
- [ ] learn how to publish a box image on [HCP Vagrant Registry](https://portal.cloud.hashicorp.com/vagrant/discover).

## Boxes
> Boxes are like images `iso` for vagrant.


## Commands

**up machine from VagrantFile**
```bash
vagrant up
```

**shutdown the machine without lost changes and state**
```bash
vagrant suspend
```

**restore the environment to its previous state**
```bash
vagrant resume
```

**shutdown the machine grateful**
```bash
vagrant halt
```

**destroy the machine**
```bash
vagrant destroy
```

**remove box image**
```bash
vagrant box remove <image-name>
```

**update vm with the new configuration on vagrant file**
```bash
vagrant reload --provision
```


