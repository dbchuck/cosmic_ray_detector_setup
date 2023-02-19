# cosmic_ray_detector_setup

This repository is for using Anisble to provision computers to be cosmic ray detectors using the detector: https://github.com/dbchuck/cosmic_ray_detector

## Configuration
* Create your inventory file in the base (this) directory.
* Copy the example file group_vars/all.yml.example to group_vars/all.yml and customize the values.

## Install
Install Ansible dependencies first: `ansible-galaxy install -r ansible-requirements.yml`
Run this command: `ansible-playbook setup.yml -i inventory.ini`

### Fix Arch repository gpg issues
https://gist.github.com/ph20/183acf405386da62281d15b4c51ff08e
