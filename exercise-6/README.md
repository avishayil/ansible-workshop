# Ansible Workshop

Hi! Welcome to the **Ansible Workshop**. In this repository you can find variety of exercises that would help you to strengthen your Ansible skills.

## Exercise 6

> Run a playbook that provisions 2 Windows EC2 instances, installs Google Chrome and creating a shortcut to Ansible website that uses Google Chrome.

## Solution

- Install the required Ansible Python dependencies to work with AWS: `pip install boto`
- Install `awscli` on your Ansible controller: `pip install awscli`
- Make sure that you're logged in to your AWS account via `aws configure`
- Fill the neccesary fields on `host_vars/localhost`
- `ansible-playbook playbook.yml -v -e "ansible_user=Administrator ansible_password=$ansible_password"`
- -v stands for verbose, so we can see the output of our commands (and debug if necessary).
- -e stands for extra vars, where you can specify variables to use inside the playbook. `ansible_user` and `ansible_password` are **unique variables** used to login to Windows machines with username and password.

## Next Step

Finished with this exercise? Good Job! You're Done for now.
