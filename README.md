# Procédure  
## Matériel nécessaire
* Un hoverboard fonctionnel
* Une clé usb [ST-Link V2](https://www.amazon.fr/gp/product/B07H9XV2W2/ref=ppx_yo_dt_b_asin_title_o07_s00?ie=UTF8&psc=1)
* Tournevis
* Fer à souder
* Connecteurs mâle de PCB
* Fils de connexion
* Multimètre
* Adapteur USB-série (facultatif mais utile pour calibration ADC)

## Etapes
1. Démonter l'hoverboard
2. Démonter la carte mère du refroidisseur. Dévisser les vis cruciformes.  
3. Souder 4 connecteurs de PCB mâle à l’emplacement « Interface de programmation » dans l’image ci-dessous  <img src="hoverboard_motherboard_fr.jpg">  
4. Remonter la carte mère sur refroidisseur  
5. Récupérer les sources [ici](https://github.com/Lab-Origami/Hack_Hoverboard/tree/master/hoverboard-firmware-hack)
6. Compiler les sources   
6.1 [Mettre en place l'environnement sous Windows 10](environnement.md)  
6.2 [Compilation](compilation.md)
7. Installer l'[utilitaire de flashage](st_link_utility.md)  
7.1 [Flasher le fichier précédemment compilé sur la carte principale](flashage.md)
  
  
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Ce(tte) œuvre est mise à disposition selon les termes de la <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Licence Creative Commons Attribution -  Partage dans les Mêmes Conditions 4.0 International</a>.
