# ansible

# how to install ansible in ubuntu ec2 instance

# 1) From your control node, run the following command to include the official project’s PPA (personal package archive) in your system’s list of sources:

      sudo apt-add-repository ppa:ansible/ansible

# Press ENTER when prompted to accept the PPA addition.

# 2) Next, refresh your system’s package index so that it is aware of the packages available in the newly included PPA:

      sudo apt update

# 3) Following this update, you can install the Ansible software with:

      sudo apt install ansible -y
