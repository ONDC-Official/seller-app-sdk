```shell
cd deploying_ansible
ansible-playbook -i ansible_hosts seller-app-install-for-ssl.yaml
enter the hostname which you might have mentioned in host file: preprod
please enter the domain which will be serving the requests: buyer-app-preprod.ondc.org
please enter the env file to copy, we are appending to .env, hence value can be -staging etc: -preprod

```