![](Images.md/imagespswh.jpg)
## Les commandes :

- **Start-Transcript :** c'est la première chose a taper quand on utilise powershell donc tout ce que l'on tape ou affiche apparaitra grace a cette commande 
  
![](Images.md/D.jpg)
- **Get-command** ***-noun < le mot ou lettre >*** **:** cela permet de trouver les commandes les plus important dispo dans powershell
- **Get-help < get-service (exemple de commande)>:** comme le dit la commande c'est pour de l'aide avec les autres commandes disponible 
  
- **Get-servive :** liste tout les services disponible avec le status, le nom et le nom d'affichage 

![](Images.md/E.jpg)
- **get-alias** < name > **:** cela va permettre de nous donner la definition d'un alias 

![](Images.md/alias.jpg)
- **get-alias :** ce qui donne toute la liste des alias disponible sur powershell

![](Images.md/wow.jpg) 
- **get-process :** cela donne la liste des applications qui sont en cours d'utilisation et disponible. Si on veut que selectionner une seul appli, il faut mettre **-Name Discord** (exemple).

![](Images.md/process.jpg) 
- get-process -Name Discord **| get-member :** cela va montrer toute les propriétés et toutes les methodes associés à des objets spécifiques

![](Images.md/cool.jpg) 
- get-process -Name Discord **| select-object * :** cette commande va nosu permettre de voir les propriétes de Discord donc le nom, l'identifiant, ect ...

![](Images.md/A.jpg) 
- **(symbole dollar) luke = get-process Discord :** ici on a creé une variable nommé "$luke" qui va prendre un objet "get-process Discord"

![](Images.md/B.jpg) 
- **cd\ :** nous ramene au debut du document
- **ipconfig :** cela permet de voir nos adresses IP, ect

![](Images.md/C.jpg) 
- **get-history :** on peut voir toute les commandes utilisées 