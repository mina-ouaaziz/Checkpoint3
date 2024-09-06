Partie 1 : Gestion des utilisateurs

Q.2.1.1

Q.2.1.2 Les préconisations à faire sont d'installer sudo, de mettre un mot de passe qui doit être fort et complexe, comprenant des lettres majuscules, minuscules, des chiffres et des caractères spéciaux et d'installer l'authentification SSH.

Partie 2 : Configuration de SSH



Partie 3 : Analyse du stockage


Q.2.3.5  Il reste 4 GO


Partie 4 : Sauvegardes

Q.2.4.1
bareos-dir : Planifie et gère les sauvegardes et les restaurations.
bareos-sd : Gère les supports de stockage pour sauvegarder et restaurer les données.
bareos-fd : Collecte les données sur les systèmes clients pour les sauvegarder et les restaurer.

Partie 5 : Filtrage et analyse réseau

Q.2.5.1 Quelles sont actuellement les règles appliquées sur Netfilter ?

Q.2.5.2 Les types de communications autorisées sont généralement listés sous les chaînes INPUT et FORWARD dans la sortie de iptables. Recherchez les règles qui ont la cible ACCEPT ou ALLOW, et notez les ports et adresses IP associés.

Q.2.5.3 Les types de communications interdites sont souvent marquées par les règles avec la cible DROP ou REJECT. Ces règles bloquent les paquets correspondant à certains critères, comme les ports spécifiques ou les adresses IP.

Q.2.5.4 Sur nftables, ajouter les règles nécessaires pour autoriser bareos à communiquer avec les clients bareos potentiellement présents sur l'ensemble des machines du réseau local sur lequel se trouve le serveur.
