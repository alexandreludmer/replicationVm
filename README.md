# Projet non terminé

##### Problème :  Comme expliqué ci-dessous, j'ai choisis de créer une VM vagrant dans une VM vagrant. Résultat : Mon inception de VM ne peux pas se lancer à cause du module VT-X non activé...

##### Ce qui a été fait : 
 - configuration IP, son hostname et l'ouverture de port automatique avec Vagrant 
 - L'itération d'installation de paquets
 - Installation du Backend : https://github.com/gothinkster/node-express-realworld-example-app 
 - Installation du Frontend : https://github.com/gothinkster/react-redux-realworld-example-app
 - Manipulation d'Ansible 

# Begin

- TODO : https://fteychene.github.io/vagrant-ansible-epsi/Projet.pdf

## Prérequis :

Ce travail s'effectue depuis une bécane windows 10 

- Vagrant 
- Virtualbox

## Mon architecture :

![Image of Architecture](https://github.com/alexandreludmer/replicationVm/blob/master/Untitled%20Diagram.png)

## Installation : 

Sur la machine "Windows" : 
- Clone des dossiers "VagrantFileForWindows" et "VagrantFileForMonitor"
- Remplacer le fichier initial Vagrantfile par celui dans "VagrantFileForWindows" 
- Ouvrir le CMD
- Executez 'vagrant up' (Pour etre sur : 'vagrant up --provision')
- Executez 'vagrant ssh'

Sur la machine "Monitor" :
- Vagrant up 

## BUG ## 
![FailFish](https://git.io/FailFish)
![FailFish](https://git.io/FailFish)
![FailFish](https://git.io/FailFish)
![FailFish](https://git.io/FailFish)
![FailFish](https://git.io/FailFish)
![BabyRage](https://git.io/BabyRage)
![BabyRage](https://git.io/BabyRage)
![BabyRage](https://git.io/BabyRage)
![BabyRage](https://git.io/BabyRage)
![BabyRage](https://git.io/BabyRage)

