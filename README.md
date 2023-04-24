# KinD Testing Repo

This is a repo for testing my devops code before shipping it to my "production" environment of my homelab. It is handy for develping/testing code in a smaller repo before it is consolidated into my main [homelab cookbooks repo](https://github.com/spicyFajitas/cookbooks).

## Ansible Playbooks

To test on a local machine, run the playbook using the command `ansible-playbook --connection=local server-playbook.yml -i 127.0.0.1`
