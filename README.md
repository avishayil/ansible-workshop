# Ansible Workshop

Hi! Welcome to the **Ansible Workshop**. In this repository you can find variety of exercises that would help you to strengthen your Ansible skills.

## Pre-Requisites

In order to get started with Ansible, we will need the following:

- In order to provision machines quickly, you'll need a provisioner like vagrant, virtualbox, or even AWS account. If you work for an enterprise company, you may use your company virtual machine provisioner. You can even use Docker if it's more comfortable for you.
- Within this provisioner, you'll need to have an **Ansible Controller** - a linux machine that is going to have Ansible installed. This machine is called **controller** because it controls target hosts. Any Centos, RHEL or Ubuntu Linux machine will be good as a controller.
- Except from the controller, we'll need target hosts to control, which we will run our playbooks against. Any Linux flavour will be good. We'll need some Windows machines too. Let's get started with one Linux target and one Windows target.

## Installing Ansible

Once we started an SSH session in our Ansible Controller, we need to check if python is installed. Simply by typing `python -V`. If you see some output, you're probably good. The latest versions of CentOS, Red Hat Enterprise Linux (RHEL) and Ubuntu **come with Python 2.7 out of the box**.
After you make sure that you can run python, let's install Ansible using `pip`, the python package manager.
- `pip install ansible`

If you don't have `pip` installed, see [this link](https://pip.pypa.io/en/stable/installing/) for info how to install it on your Linux **Ansible Controller**.

## Getting Started

- Clone this repository - `git clone https://github.com/avishayil/ansible-workshop`.
- Get your KeyPair for logging in to the Linux target host, use ssh-agent to log in to the Ansible Controller and agent forwarding.

Finished all the initial setup? Head to [Exercise 1](exercise-1) to start polishing your skills with Ansible.