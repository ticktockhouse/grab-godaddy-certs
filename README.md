# Overview
This is the code that accompanies [my blog post]() detailing how I automated downloading of certs to a client's server.

# Howto

It should be possible to use the included `playbook.yml`. You will need to provide the relevant `certificateId` as an extra var, or enter it when prompted, e.g.:
```
ansible-playbook playbook.yml -e <certificate ID>
```
or:
```
ansible-playbook playbook.yml
```
...and you willl be prompted for the cert ID
