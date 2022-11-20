# ansible_code

This repository stores roles that deploy docker images

## How to use it

1. Run command to deploy apps
```sh
ansible-playbook -i test.yml -D playbook-deploy-goapps.yml -t deploy_testingAPI -C
```
2. You can test the API
```sh
sudo /bin/bash /root/run_api.sh
```