# Connect

## Lien vers l'exo
https://github.com/01-edu/public/tree/master/subjects/connect

## Exporter les 3 machines depuis virualbox
- machine 
- ajouter
- ajoute les machines une par une

## Démarrer les 3 machines
aprés l'ajout, démarrer les 3 machines à la fois

## Utiliser la machine 2
la machine 2 est accessible avec
- login: root
- password: une seul espace

## Changer l'IP
aller dans le dossier netplan et modifier le fichier de configuration
- nano /etc/network/interfaces
- modifier l'ip de maniére statique
```
auto enp0s3
iface enp0s3 inet static
    address 192.168.0.3
    netmask 255.255.255.0
    gateway 192.168.0.1
```
- modifier l'ip de maniére dynamique
```
auto enp0s3
iface enp0s3 inet dhcp
```

## Auteur
- **Nom** : Mouhamed DIOUF
- **GitHub** : [mouhameddiouf](https://github.com/seydi-ahmed)
- **Email** : seydiahmedelcheikh@gmail.com
- **Numéro** : +221776221681
- **Réseaux** : [LinkedIn](https://linkedin.com/in/mouhamed-diouf-435207174)