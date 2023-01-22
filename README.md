# proxmox_tf
A python script that works with Terraform to create a new VM in Proxmox

# How to use it
- Check this post first: https://andreypicado.com/create-a-virtual-machine-in-proxmox-with-terraform-and-python/

- The following things a required for this script to work:
  - A Proxmox instance with an .iso located in one of the storage containers
  - Python 3.9.14
  - pip 22.3.1
  - Terraform v1.3.7
  - python-terraform 0.10.1


- Clone this repo: `git clone https://github.com/andreypicado506/proxmox_tf.git`

- Go to the ./tf directory: `cd ./proxmox_tf/tf`

- Provide execution permissions to main.py `chmod +x ./main.py`

- Call main.py with the relevant parameters:

`./main.py -pp 'strongPassword' -vn 'newvm01'`
