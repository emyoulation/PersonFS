## français _(Franca, French)_
PersonFS est un [gramplet](https://www.gramps-project.org/wiki/index.php/Gramplets) pour interfacer Gramps avec FamilySearch.com

Plus d'informations dans [LisezMoi.md](LisezMoi.md)   
La version française [LisezMoi.md](LisezMoi.md) est la documentation la plus complète et la plus fréquemment mise à jour.

Attention : ne marche pas avec la version windows AIO de gramps. Sous windows utilisez gramps avec WSL : voir [Notoj/gramps_wsl.md](Notoj/gramps_wsl.md)

## Esperanto _(espéranto)_
PersonFS tio estas [gramplet](https://www.gramps-project.org/wiki/index.php/Gramplets) por interligi Gramps kun FamilySearch.com

Pliaj informoj en [LeguMin.md](LeguMin.md)  
La franca ([LizesMoi.md](LeguMin.md)) estas la plej kompleta kaj ofte ĝisdatigita dokumentaro. 

Averto: ne funkcias kun la fenestro AIO-versio de gramps. Sub fenestroj uzu gramps kun WSL: vidu Notoj/gramps_wsl.md

## English _(Angla, anglais)_
PersonFS is a [gramplet](https://www.gramps-project.org/wiki/index.php/Gramplets) to interface gramps with FamilySearch.com

For more information, see [README.en.md](README.en.md)  
The French ([LizesMoi.md](LeguMin.md)) is the most complete and frequently updated documentation.

Warnings : 
 
* Is not compatible with Windows AIO release of Gramps.
* you need to patch Gramps with command ` sudo sed -i 's/int(path)/path/' /usr/lib/python3/dist-packages/gramps/gui/listmodel.py `
* you need to install python modules requests and gedcomx-v1 (>=1.0.8) with ` pip install --upgrade requests gedcomx-v1 `
