# winget  
## installation  
installer le fichier :   
> Microsoft.DesktopAppInstaller_8wekyb3d8bbwe.appxbundle  
> trouvé sur le site frandroid  
> https://www.frandroid.com/comment-faire/tutoriaux/713236_comment-utiliser-winget-et-winstall-app-pour-installer-vos-programmes-windows-10-en-une-seule-commande  
> url microsoft pour la doc :  
> https://docs.microsoft.com/fr-fr/windows/package-manager/winget/  
  
> ### Les Commandes   
La préversion actuelle de l’outil winget prend en charge les commandes suivantes.  
> winget info  // info sur les commandes ..etc sur winget  

hash :	Génère le hachage SHA256 pour le programme d’installation.  
help :	Affiche l’aide relative aux commandes de l’outil winget.  
install :	Installe l’application spécifiée.  
search : Recherche une application.  
show : Affiche les détails de l’application spécifiée.  
source : Ajoute, supprime et met à jour les dépôts du Gestionnaire de package Windows auxquels l’outil winget accède.  
validate : Valide un fichier manifeste pour l’envoi dans le dépôt du Gestionnaire de package Windows.  
#### exemple :  
winget install \<appname>  
winget search \<appname>  
winget --help  

Options :  
> La préversion actuelle de l’outil winget prend en charge les options suivantes.  

-v,--version : Cette option retourne la version actuelle de winget.   
--info : Fournit des informations détaillées sur winget, y compris les liens vers la licence et la déclaration de confidentialité.    
-?, --help : 	Fournit une aide supplémentaire sur winget. Formats de programmes d’installation pris en charge    
La préversion actuelle de l’outil winget prend en charge les types suivants de programmes d’installation.  
EXE  
MSIX  
MSI  

link : https://winstall.app/  
link : https://github.com/microsoft/winget-cli  
