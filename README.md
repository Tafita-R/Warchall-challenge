# Warchall-challenge
Je vais vous expliquer les étapes pour obtenir les mots de passe de Wechall niveaux 0 à 5.

*Connexion via SSH :
- Vous verrez l'adresse IP fournie pour vous connecter via SSH .Exemple: ssh -p 125643 rakoto@warchall.net
- Ouvrez Cmd et connectez-vous avec les informations fournies. Exemple: Login: Rakoto rakoto@192.168.178.128's password: rakoto

*Résolution des niveaux : rakoto@warchall.net.
- Une fois connecté, entrez l'adresse IP de Warchall, c'est-à-dire « ssh -p 125643 rakoto@warchall.net »
- Saisissez le mot de passe warchall, et maintenant vous pouvez résoudre les niveaux.

Niveau 0
Utilisez pwd dans le répertoire actuel bash cd /home/level ls cd 00_* ls cat 
Mot de Passe: "Bitwarrior"

Niveau 1
Utilisez cd pour changer de répertoire. cd blue/hats/grey/ solution ; patience cat 
Mot de passe : "patience"

Niveau 2
cd documents ls cat 
Mot de passe : "HiddenIsConfig"

Niveau 3
Utilisez ls -al pour voir les dossiers et fichiers cachés. cd . bash_history Mot de passe : "RepeatingHistory"

Niveau 4
Revenez dans le dossier de départ. ls cd level cd 04 ls chmod +r # Pour modifier les autorisations du fichier en lecture pour l'utilisateur. cat README2-md 
Mot de passe : "AndOfCourseIDoKnowChown"

Niveau 5
cd /home/level 05_* ls cat README.md Mot de passe : "OKPRIVATE"

Grâce à ma compréhension approfondie du système et à mes compétences en Git, j'ai réussi à relever avec succès les défis présentés dans le Warchall - Chapitre I. Cela met en évidence l'importance de maîtriser le système et les commandes shell dans le domaine de l'informatique système.

Nb: les commandes à utiliser :
* cd : Change le répertoire.
* pwd : Affiche le répertoire actuel.
* ls -la : Affiche les fichiers cachés.
* cat : Permet de lire un fichier.
* ls : Affiche le contenu d'un répertoire.
* chmod : Commande pour changer les autorisations de fichier.
* chmod +r : Ajoute les autorisations de lecture au fichier..
