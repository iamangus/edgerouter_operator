# edgerouter_operator
Ansible Operator to manage port-forward entries on a Ubiquiti Edgerouter

# Steps
https://sdk.operatorframework.io/docs/installation/


operator-sdk new edgerouter-operator \
    --api-version=Service/v1 \
    --kind=Service \
    --type=ansible
