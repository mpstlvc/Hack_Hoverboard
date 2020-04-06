# Compilation
Les sources disponibles sur ce Github permettent d'utiliser un par exemple une poignée de gaz pour un vélo électrique.  
Pour compiler le code source ([disponible ici](https://github.com/Lab-Origami/Hack_Hoverboard/tree/master/hoverboard-firmware-hack) il faut lancer la distribution Linux précédemment installée.  
Se rendre ensuite dans le répertoire "hoverboard-firmware-hack" en tapant la ligne de code ci-dessous  
***Attention, penser à adapter le chemin. Ici, le répertoire se trouve sur le bureau.***  
```Console  
fablab@DESKTOP-73ELB6A:~$ cd /mnt/c/Users/lenov/Desktop/hoverboard-firmware-hack
```    
Puis taper les commandes suivantes    
```Console
fablab@DESKTOP-73ELB6A:/mnt/c/Users/lenov/Desktop/hoverboard-firmware-hack$ make clean
fablab@DESKTOP-73ELB6A:/mnt/c/Users/lenov/Desktop/hoverboard-firmware-hack$ make
```  
Vérifier dans le répertoire build qu'il y a bien les fichiers "hover.hex" et "hover.elf"  
```Console  
fablab@DESKTOP-73ELB6A:/mnt/c/Users/lenov/Desktop/hoverboard-firmware-hack$ cd build/  
fablab@DESKTOP-73ELB6A:/mnt/c/Users/lenov/Desktop/hoverboard-firmware-hack$ ls    
```
_____  

# Aide mémoire  
Pour lister le contenu d'un répertoire utiliser la commande ls
```Console 
fablab@DESKTOP-73ELB6A:/mnt/c/Users/lenov/Desktop/hoverboard-firmware-hack$ ls  
```  
Pour remonter d'un niveau dans la hiérarchie, utiliser la commande cd ..  
```Console
fablab@DESKTOP-73ELB6A:/mnt/c/Users/lenov/Desktop/hoverboard-firmware-hack/build$ cd ..  
```  
