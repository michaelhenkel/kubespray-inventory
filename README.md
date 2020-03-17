# Get Kubespray
```
git clone https://github.com/kubernetes-sigs/kubespray
```
# Get Kubespray configuration
```
git clone https://github.com/michaelhenkel/kubespray-inventory
```
# Edit inventory file
```
vi ~/kubespray-inventory/mycluster/inventory.ini
```
# Run playbook
```
cd ~/kubespray
ansible-playbook -i ~/kubespray-inventory/mycluster/inventory.ini cluster.yml -b -v
```
