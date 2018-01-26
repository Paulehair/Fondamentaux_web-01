# Liste des commandes essentielles du shell

## Collaborateurs
1. Hector Travaillé : https://github.com/LeKawa
2. Paule Herman https://github.com/Paulehair
3. Maxime Oger https://github.com/maximeoger
4. Ye Marc https://github.com/ye-marc


## Historique des interfaces UNIX

Le Shell Unix est un langage permettant d'interpréter des actions en lignes de commandes,
cela permet de communiquer avec un système d'exploitation pour accéder à ses fonctionnalités internes qui pour la plupart ne sont pas accessible autrement.
On l’utilise principalement pour communiquer sur un serveur ou un système d’exploitation sans interface graphique.


Le premier shell est le Thompson Shell apparu en 1971 avec la première version d’Unix et écrit par Ken Thompson, l'un des créateurs d'Unix.

* Tout d'abord que l'ancêtre de tous les shells est le sh (Bourne Shell). C'est le plus vieux et il est installé sur tous les OS basés sur Unix. Il est néanmoins pauvre en fonctionnalités par rapport aux autres shells.
* **bash :** Le bash (Bourne Again Shell) est le shell par défaut de la plupart des distributions Linux mais aussi celui du terminal de Mac OS X.
* **ksh :** Korn Shell. Un shell puissant assez présent ( sur les Unix propriétaires ) , mais aussi disponible en version libre, compatible avec bash.
* **csh :** C Shell. Un shell utilisant une syntaxe proche du langage C.
* **tcsh :** Tenex C Shell. Amélioration du C Shell.
* **zsh :** Paul Falstad crée le Zsh en 1990.
* **Z Shell :** Shell assez récent reprenant les meilleures idées de bash, ksh et tcsh.





## Les différentes utilisations du shell

## Liste des Commandes du Shell

Ci dessous, une liste non exhaustive des commandes basiques d'UNIX, pour ouvrir votre terminal sous mac `cmd + t`.

### Commandes de Base

| Commande | Nom | Description |
| -------- | --- | ----------- |
| `man`| manual | affiche le manuel de la commande spécifiée
|   `pwd`  | Print Working Directory | Affiche la position de l'utilisateur dans l'arborescence du système |
|   `ls`   | List segment | Affiche une liste du contenu du répertoire actuel |
| `cd` | change directory | change de répertoire à partir du répertoire actuel |
| `mkdir` | make directory | crée un nouveau dossier dans le répertoire actuel |
| `cp` | copy | copie le répertoire ou le fichier ciblé dans le répertoire de destination |
| `touch` | touch | crée un fichier dans le répertoire actuel |
| `rmdir` | remove directory | supprime le répertoire cible |
| `rm` | remove | supprime le fichier cible |
|`open` | open | ouvre le répertoire cible |
| `mv` | move | déplace ou renomme un fichier |
| `locate` | locate | recherche dans la base de données du système, le nom de chemin spécifié|


### commandes avancées

| Commande | Nom | Description |
| -------- | --- | ----------- |
| `mmv` | mass move and rename | déplace et renomme plusieurs fichiers |
| `la -A` | - | Affiche la liste de toutes les entrées sauf celles commençant par . et .. |
| `la -a` | - | inclut les fichiers commençant par un point (.) |
| `la -l` | - | inclut les permissions, propriétaires, tailles et dates de modifications |
| `sudo` | substitute user do | permet d'exécuter une commande en tant qu'administrateur |
