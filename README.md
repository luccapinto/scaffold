[![Python application test with Github Actions](https://github.com/luccapinto/scaffold/actions/workflows/main.yml/badge.svg)](https://github.com/luccapinto/scaffold/actions/workflows/main.yml)

# scaffold
This is a project scaffold for python

## How to use in cloud
* Create a virtual machine
* Create a virtual enviroment (python -m venv ~/.scaffold)
* Activate (source ~/.scaffold/bin/activate)
* Get your ssh key (ssh-keygen -t rsa)
* Click enter 3x
* Copy the path and read with "cat <path>"
* ![image](https://github.com/luccapinto/scaffold/assets/78231371/5d46085f-d7f6-45b7-8b38-fb1460fd9ac4)
* Open Github config > SSH and GPG keys > new SSH key
* Copy the ssh key of the repository and paste in the VM (git clone <repository_ssh_key>)
* ![image](https://github.com/luccapinto/scaffold/assets/78231371/4b1efd7d-82d0-4133-8806-328089c3a4de)
* Go to the folder (cd scaffold)
* Install, test and format (make all)
