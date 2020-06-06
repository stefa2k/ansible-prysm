# prysm-ansible
Setup an Ethereum 2.0 node with prysm (docker) and tools in seconds with ansible!

## Components installed

* Docker container management
* [prysm-docker-compose](https://github.com/stefa2k/prysm-docker-compose)
* [ethdo](https://github.com/wealdtech/ethdo) 

## Usage
Create an inventory (not included) and run:
```
ansible-playbook -i inventory.eth2.yaml docker.yaml eth2node.yaml
```

## Configuration
### User
Change the variable `prysm_user` in `eth2node.yaml`.
### Installation directory
Change the variable `prysm_install_path` in `eth2node.yaml`.
