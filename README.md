# ans-ubuntu-deploy_db2

This repository is a series of ansible playbooks to deploy Db2 11.5.x on Ubuntu Linux 20.04. Update the supplied hosts file to match your environment.

Download the files as a zip using the green button, or clone the repository to your machine using Git.

Note : Replace $REPO/db2/files/v11.5.8_linuxx64_server_dec.tar.gz with your Db2 installation archive from IBM.

## Playbook Execution
```bash
ansible-playbook -i hosts site.yml
```
