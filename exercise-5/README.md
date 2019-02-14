# Ansible Workshop

Hi! Welcome to the **Ansible Workshop**. In this repository you can find variety of exercises that would help you to strengthen your Ansible skills.

## Exercise 5

> Run a playbook that installs and configures nginx on remote linux machine.

## Solution

- `ansible-playbook playbook.yml -i inventory.yml -v`
- -v stands for verbose, so we can see the output of our commands (and debug if necessary).
- -i stands for inventory, we point to a specific file where our hosts are defined.

## Next Step

Finished with this exercise? Good Job! You're Done for now.
