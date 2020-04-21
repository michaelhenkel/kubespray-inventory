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
vi ~/kubespray-inventory/mycluster/inventory.yaml
```
# Run playbook
```
cd ~/kubespray
ansible-playbook -i ~/kubespray-inventory/mycluster/inventory.yaml cluster.yml -b -v
```
