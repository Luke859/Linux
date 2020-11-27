## Comment installer Powershell sur Windows :




---
## Comment installer Powershell sur Linux plus precisement Debian 10 :

-**Nous allons le faire via un dépôt de packages dans Debian 10** : 

- **1er étape -> Télécharger le répertoire clés GPG de Microsoft**
> wget https://packages.microsoft.com/config/debian/10/packages-microsoft-prod.deb

- **2eme étape -> Inserer le répertoire clés GPG de Microsoft**
>sudo dpkg -i packages-microsoft-prod.deb

- **3eme étape -> Il faut mettre à jour la liste des produits**
>sudo apt-get update

- **4eme étape -> Installer Powershell**
>sudo apt-install -y powershell

- **Dernière étape -> lancer powershell**
>pwsh 
