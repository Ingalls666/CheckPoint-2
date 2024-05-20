Q.2.1

- Sur l'ordinateur client, j'ai activé le bureau à distance et j'ai initialisé la connexion avec l'adresse IP du serveur et ensuite j'ai renseigné le compte cible et le mot de passe. une fois la prise en main effectué j'ai procédé à un copier/coller du dossier **C:\Script** du serveur vers **C:\** de l'ordinateur client. Une fois ceci effectué, j'ai rompu la connexion Client -> Serveur.

---

Q2.2

- Il ne se passe rien à l'execution du script.

- Start-Process -FilePath "powershell.exe" -ArgumentList "C:\ **Temp** \AddLocalUsers.ps1" -Verb RunAs -WindowStyle Maximized
L'erreur ce situe sur le chemin du script à executer. Le bon chemin à suivre est :"C:\ **Scripts** \AddLocalUsers.ps1".

Q.2.3

- le commandlet ```-Verb RunAs``` sert a effecter des scripts avec des privileges élevés.

Q.2.4

- le commandlet ```-WindowsStyle Maximized``` sert ouvrir la fenetre en taille maximale.

---

Q.2.5

- Dans la ligne d'importation du fichier CSV, le commandlet ```Select-Object``` demande de ne pas prendre en compte les 2 premières lignes du fichier. On modifie la valeur à 1.

Q.2.6

-Dans la variable ```$UserInfo```, il n'y a pas de ligne "*Description*". Ajouter la ligne "*Description*" avec la variable ```$Description``` qui est plus haut dans le script.

Q.2.7

- Dans la ligne d'importation du fichier CSV , nous allons supprimer les en-tetes " ```societe```,```service```,```mail```,```mobile```,```scriptPath```et```telephoneNumber```.

Q.2.8

- Dans la ligne qui affiche "L'utilisateur $Prenom.$Nom a été crée", on la modifie en "Le compte $Prenom.$Nom a été crée avec le mot de passe $Pass" avec le Commandlet ```-ForegroundColor Green``` en fin de ligne.

Q.2.9

- Il y a la méthode du "**Dot-Sourcing**" ou  de "**Import-Module**". Je vais utiliser "**Dot-sourcing**" car le script contient qu'une fonction, qui est une fonction de log.

Q.2.10

- À la condition ```If```, ajouter un ```Else``` et ```Write-Host``` " Le compte $Prenom.$Nom existe déjà" -ForegroundColor Red.

Q.2.11

- Dans la ligne ```AddLocalUsers```, modifiez le nom du groupes de "Utilisateur" en "Utilisateur**s**".

Q.2.12

- La variable ```$Name``` étant déjà existante dans le script, remplacez ```$Prenom.$Nom``` par ```$Name```.

Q.2.13

- Dans la ligne "**PasswordNeverExpires**" changez la valeur de ```$false``` en ```$true```.

Q.2.14

- Dans la fonctions "**Mot de Passe Aléatoire**" changez la valeur de longueur de **6** à **12**.

Q.2.15

- Supprimer le ```Start-Sleep``` du script.

Q.2.16

- La fonction```ManageAccentsAndCapitalLetters``` permet de remplacer les lettres avec accents en lettres sans accents.
    -Exemple : Ana**ï**s en Ana**i**s.
