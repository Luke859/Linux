# Les boucles 
### Une boucle dans un programme d’ordinateur est une séquence d'instructions qui sont répètées jusqu’à ce qu’une condition soit atteinte. 
###### Voici mes sources :https://www.it-connect.fr/powershell-et-les-boucles-foreach/
---
## 1- Boucles For 
-> La syntaxe d'une boucle For : 
>**For(<état initial>;<condition de répétition>;<incrémation>)**
> 
> **{** 
> 
> **// si la condition est vraie, on éxecute le bloc au-dessus**    
> 
> **}**
> 
> **// si la condition est fausse, la boucle For se termine et le script continue**

-> Si je detail le bloc:

-**L'état initial** sera une valeur de départ (ex : 2, 6)

-**La condition** de répétiton est de répéter la boucle jusqu'a ce que la valeur qu'on ai mit atteint le maximum qu'elle peut faire.

-**L'incrémentation**, c'est ici que l'on va préciser combien (une valeur) on va ajouter à notre valeur chaque tour (ex : +x soit +1, +2).

- **Exemple 1 : Boucle For simple** 
>![](Images.md/Po.jpg)

-Le cadre en orange est comme ce que l'on a vu au début sauf que ici j'ai mis un exemple. C'est notre script de la BoucleFor.

-Le cadre en rouge est le résultat de notre script éxecuter.

- **Example 2 : Boucle For de type texte (string)**
>![](Images.md/PH.jpg)

**Si je détail ce que j'ai mis dans le cadre orange :**

**Ma variable** -> "couleur", contient dans un tableau différentes couleurs. (ligne 1)

**Ma boucle For** -> ma variable "i" = 0; "i" plus petit que ma variable "couleur" qui est de longueur du tableau donc 5; on ajoute 1 à chaque tour "i++ = i + 1". (ligne 2)

**->** ![](Images.md/O.jpg) cela veut dire que notre variable "i" va récuperer la valeur que l'on veut dans le tableau de la variable "couleur"pour que chaque tour on aura une valeur différente. 
Les valeurs différentes sont dans le cadre rouge.

## 2-Boucle ForEach 
