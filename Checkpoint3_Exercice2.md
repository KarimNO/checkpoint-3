Exercice 2 - VM Linux

Partie 1 - Gestion des utilisateurs

Q.2.1.1 

![Capture d'écran 2025-03-07 110528](https://github.com/user-attachments/assets/e906cc1b-c54c-4d00-a7ec-5390f4c322ca)

Q.2.1.2 

Utiliser un mot de passe fort, Limiter les droits sudo, Désactiver la connexion directe en tant que root


Partie 2 - Configuration de SSH

Q.2.2.1 

![Capture d'écran 2025-03-07 111513](https://github.com/user-attachments/assets/015fe5b8-68f8-4da0-a788-aa50a0a99ab9)

Q.2.2.2 

![Capture d'écran 2025-03-07 111832](https://github.com/user-attachments/assets/08223c39-5a7a-4fbd-8af7-cb72600e409c)

Q.2.2.3 

![Capture d'écran 2025-03-07 112336](https://github.com/user-attachments/assets/c9d7fdd4-7410-4e51-87ce-92367b7c0c2e)

Partie 3 - Analyse du stockage

Q.2.3.1 

![Capture d'écran 2025-03-07 112522](https://github.com/user-attachments/assets/4b9d316c-9d2a-48f0-8db5-2f457c7ad429)

Q.2.3.2 

![Capture d'écran 2025-03-07 112638](https://github.com/user-attachments/assets/62c66b99-d0e2-4acc-b5d4-5c9fd22ba5db)

Q.2.3.3 

![Capture d'écran 2025-03-07 113555](https://github.com/user-attachments/assets/ad80f93c-632f-42db-9f9b-4795dd4811a5)

![Capture d'écran 2025-03-07 114714](https://github.com/user-attachments/assets/d70d3229-ba87-484c-bd00-01c3cb32ccd7)

![Capture d'écran 2025-03-07 114957](https://github.com/user-attachments/assets/c47492b7-19f8-4ab8-a5d4-33be6be186b2)

![Capture d'écran 2025-03-07 120045](https://github.com/user-attachments/assets/faffa764-ba5c-47c5-adcb-ffbba493a7b4)

Q.2.3.4 

![Capture d'écran 2025-03-07 121147](https://github.com/user-attachments/assets/7757e866-6e55-47ab-9d06-828da016b515)

![Capture d'écran 2025-03-07 121357](https://github.com/user-attachments/assets/df282bca-8b5c-436c-936b-38c88d2d14a8)

Q.2.3.5 

![Capture d'écran 2025-03-07 121850](https://github.com/user-attachments/assets/fedcadc2-2de3-4259-827f-0344382aaf4e)

Partie 4 - Sauvegardes

Q.2.4.1 

bareos-dir : Directeur, gère les jobs de sauvegarde
C'est le chef d'orchestre. Il est responsable de la planification, du contrôle et du lancement des tâches de sauvegardes. Il contrôle l'ensemble des autres composants.
Il est installé sur le serveur en charge de la gestion des sauvegardes.

bareos-sd : Storage Daemon, gère le stockage des sauvegardes

bareos-fd : File Daemon, s'exécute sur les clients pour effectuer les sauvegardes
Ce composant est installé sur chaque machine devant être sauvegardée.
Il est en charge de collecter les informations à sauvegarder et de les envoyer au Bareos Storage Daemon


Partie 5 - Filtrage et analyse réseau

Q.2.5.1 

![Capture d'écran 2025-03-07 122920](https://github.com/user-attachments/assets/612eb565-3416-46a2-b46e-bd0d9a6bfad7)

Q.2.5.2 

Les communications établies et liées, loopback, SSH (port 22), ICMP IPv4 et ICMP IPv6 sont autorisées.

Q.2.5.3 

Les communications avec un état invalide (cest a dire qui ne correspond à aucune connexion connue ou attendue) sont interdites car la règle "ct state invalid drop" indique explicitement de rejeter ces connexions.

Q.2.5.4 

![Capture d'écran 2025-03-07 135712](https://github.com/user-attachments/assets/bb6e0a39-4abb-4cc1-b20f-a3d4ec997af7)

Partie 6 - Analyse de logs

Q.2.6.1 

![Capture d'écran 2025-03-07 135228](https://github.com/user-attachments/assets/315474be-b29e-47c4-ac59-458d7b6d1d03)


ok : /24
nr : 
faux : 
