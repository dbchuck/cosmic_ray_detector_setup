# cosmic_ray_detector_setup

This repository is for using Anisble to provision computers to be cosmic ray detectors using the detector: https://github.com/dbchuck/cosmic_ray_detector

## Configuration
Create your inventory file in the base (this) directory.
Copy the example file group_vars/all.yml.example to group_vars/all.yml and customize the values.

## Install
Run this command: `ansible-playbook setup.yml -i inventory.ini`