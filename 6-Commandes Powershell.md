# Les commandes dans Powershell:

- **Start-Transcript :** c'est la première chose a taper quand on utilise powershell donc tout ce que l'on tape ou affiche apparaitra grace a cette commande 
  
![](Images.md/D.jpg)

---
- **Get-command** ***-noun < le mot ou lettre >*** **:** cela permet de trouver les commandes les plus important disponible dans powershell
  
---
-**Get-location :** nous montre ou nous sommes situé 

![](Images.md/loc.jpg)

---
-**Get-Childitem :** affiche le contenu d'un dossier
Il a un alias qui est **"dir"**

![](Images.md/chil.jpg)

---
  
- **Get-servive :** liste tout les services disponible avec le status, le nom et le nom d'affichage 

![](Images.md/E.jpg)

---
- **Get-process :** cela donne la liste des applications qui sont en cours d'utilisation et disponible. Si on veut que selectionner une seule application, il faut mettre **-Name Discord** (exemple).

![](Images.md/process.jpg) 
- Get-process -Name Discord **| get-member :** cela va montrer toute les propriétés et toutes les methodes associés à des objets spécifiques

![](Images.md/cool.jpg) 
- Get-process -Name Discord **| select-object * :** cette commande va nous permettre de voir les propriétées de Discord donc le nom, l'identifiant, ect ...

![](Images.md/A.jpg) 
- **(symbole dollar) luke = Get-process Discord :** ici on a crée une variable nommée "$luke" qui va prendre un objet "get-process Discord"

![](Images.md/B.jpg) 

---
-**New-item :** cette commande va créer un nouveau élement (item) et définit sa valeur.  Les types d'éléments qui peuvent être créés dépendent de l'emplacement de l'élément (item).

Exemple : **Créer un fichier** 

![](Images.md/nitem.jpg)

Avec **New-Item** on peut aussi: 

> -créer un répertoire
-créer un profil 
-créer un répertoir dans un répertoire 
-créer multiple fichiers 
-Utiliser "Wildcards" pour créer des fichiers dans plusieurs répertoires
-Créer un lien symbolique vers un fichier ou un dossier

**Pour voir des exemples de commande ci-dessus, voici le lien :** https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.management/new-item?view=powershell-7.1

---
- **cd\ :** nous ramène au début du document

---
- **ipconfig :** cela permet de voir nos adresses IP, ect

![](Images.md/C.jpg) 

---
- **get-history :** on peut voir toute les commandes utilisées 