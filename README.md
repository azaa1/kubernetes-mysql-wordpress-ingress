This repository will create : 
  1. MySQL - ReplicaSet
  2. Wordpress - Deployment
  3. Ingress 
  
You need to create 2 secrets: 
1. For MySQL 
2. For TLS 

Please change the YAML files based on your configurations. 

Run the files in the following order. 

1. kubectl create -f mysql-deployment.yaml
2. kubectl create -f wordpress-deployment.yaml
3. kubectl create -f ingress.yaml

**** NOTE ****

You need to resolve DNS on your server. 
