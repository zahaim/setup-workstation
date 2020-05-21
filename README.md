  
# setup my workstation with ansible
```sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository --yes ppa:ansible/ansible
sudo apt update
sudo apt install ansible```

# then run it like 
`sudo ansible-pull -U https://github.com/zahaim/setup-workstation.git tasks/main.yaml`
