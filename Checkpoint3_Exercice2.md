# Exercice 2

## Partie 1 : Gestion des utilisateurs

### Q.2.1.1
L'utilisateur `mina` est bien créé.  
![Capture d'écran 2024-09-06 143352](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20143352.png)

### Q.2.1.2
Les préconisations à faire sont d'installer `sudo`, de mettre un mot de passe fort et complexe comprenant des lettres majuscules, minuscules, des chiffres et des caractères spéciaux, et d'activer l'authentification SSH.

## Partie 2 : Configuration de SSH

### Q.2.2.1
L'accès à distance de l'utilisateur `root` est désactivé.  
![Capture d'écran 2024-09-06 145446](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20145446.png)

### Q.2.2.2
L'accès à distance de mon compte personnel est activé uniquement.  
![Capture d'écran 2024-09-06 145558](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20145558.png)

### Q.2.2.3
La mise en place de l'authentification par clé est validée et l'authentification par mot de passe est désactivée.  
![Capture d'écran 2024-09-06 150423](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20150423.png)

## Partie 3 : Analyse du stockage

### Q.2.3.1
Voici les systèmes de fichiers actuellement montés.  
![Capture d'écran 2024-09-06 150823](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20150823.png)

### Q.2.3.2
Voici les types de systèmes utilisés.  
![Capture d'écran 2024-09-06 151046](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20151046.png)

### Q.2.3.3
Le nouveau disque de 8 Go a été ajouté et le volume RAID a été réparé.  
![Capture d'écran 2024-09-06 151643](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20151643.png)  
![Capture d'écran 2024-09-06 152245](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20152245.png)

### Q.2.3.4
Le nouveau volume logique LVM de 2 Gio a été ajouté et configuré.  
![Capture d'écran 2024-09-06 153644](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20153644.png)  
![Capture d'écran 2024-09-06 161902](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20161902.png)

### Q.2.3.5
Il reste 4 Go d'espace libre.

## Partie 4 : Sauvegardes

### Q.2.4.1
Dans la structure Bareos :
- `bareos-dir` planifie et gère les sauvegardes et les restaurations,
- `bareos-sd` gère les supports de stockage pour sauvegarder et restaurer les données,
- `bareos-fd` collecte les données sur les systèmes clients pour les sauvegarder et les restaurer.

## Partie 5 : Filtrage et analyse réseau

### Q.2.5.1
Les règles appliquées sont :  
![Capture d'écran 2024-09-06 191657](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20191657.png)

### Q.2.5.2
Les types de communications autorisées sont :  
![Capture d'écran 2024-09-06 191657](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20191657.png)

### Q.2.5.3
Voici les règles appliquées :  
![Capture d'écran 2024-09-06 163054](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20163054.png)

### Q.2.5.4
Voici les règles nécessaires pour autoriser Bareos à communiquer avec les clients Bareos.  
![Capture d'écran 2024-09-06 163634](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20163634.png)  
![Capture d'écran 2024-09-06 165024](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20165024.png)

## Partie 6 : Analyse de logs

### Q.2.6.1
Voici la date et l'heure concernant les authentifications.  
![Capture d'écran 2024-09-06 171348](https://github.com/mina-ouaaziz/Checkpoint3/blob/main/ressources/Capture%20d'écran%202024-09-06%20171348.png)

