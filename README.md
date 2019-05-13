# Clement CARDARELLI

## TP DevOps : Kubernetes

### Configuration Préalable

Modifiez les adresses des hotes afin de correspondre à votre infrastructure

* modifier le fichier hosts.ini afin d'ajouter ou retirer les noeuds nécessaire
* configurez un fichier yaml pour chaque noeud dans host_vars/kube-0X.yml
* vérifiez que tout fonctionne
`` ansible all -a "echo Ok" ``

### Setup
lancer le playbook setup
`` ansible-playbook plays/k8s-setup.yml ``
