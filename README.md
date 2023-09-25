Init_k8s
=========

Initialisation du cluster kubernetes avec kubeadm.

Requirements
------------

Machine debian ou ubuntu, récente.

Role Variables
--------------

- deploy_traefik: utilisation du ingress traefik, set à false 
- deploy_nginx: utilisation du ingress nginx, set à true 

Dependencies
------------

[role conf_k8s](https://github.com/Thibaut833/conf_k8s)

License
-------

CC BY-NC

Author Information
------------------

Thibaut RICHARD
