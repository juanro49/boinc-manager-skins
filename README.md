# boinc-manager-skins
Paquete Debian con skins para BOINC Manager

## Instalación GNU/Linux
### [PatoJAD Repo](https://patojad.com.ar/repositorio/)
- Añadir PatoJAD Repo al sistema
```
echo 'deb https://gitlab.com/patojad/repository/raw/patojad/debs/ patojad main' | sudo tee /etc/apt/sources.list.d/patojad.list
wget -qO - https://gitlab.com/LynxOS/repository/raw/lynxos/LynxPub.gpg | apt-key add -
sudo apt update
```
- Instalar paquete
```
sudo apt install boinc-manager-skins
```

### Paquete deb
```
wget https://github.com/juanro49/boinc-manager-skins/releases/download/1.1/boinc-manager-skins_1.1_all.deb
sudo dpkg -i boinc-manager-skins_1.1_all.deb
```

## Instalación Windows
- Descargar [este zip](https://github.com/juanro49/boinc-manager-skins/archive/1.1.zip) y abrirlo con [7zip](https://7zip-es.updatestar.com/)
- Copiar el contenido de la ruta **zip/boinc-manager-skins-1.1/var/lib/boinc/skins** a **C:\Program Files\BOINC\Skins**

## Sobre BOINC
BOINC le permite ayudar a la investigación científica de vanguardia utilizando su ordenador (Windows, Mac, Linux) o un dispositivo Android. De esta forma, cualquier persona puede colaborar desde casa dejando que su ordenador o smartphone realice operaciones de cálculo. Es fácil y seguro.
Existen varios proyectos como el de [**Ibercivis**](https://instatecno.com/csic-boinc-farmacos-contra-coronavirus/) con los que se puede colaborar.

Mas información sobre BOINC en su [web oficial](https://boinc.berkeley.edu/index.php) y en [**Canal@Boinc**](http://www.canalboinc.es/).

## Skins
Skins incluidas hasta el momento (si conoces alguna mas, no dudes en compartirla para añadirla al paquete)
<img src="https://i.imgur.com/ngOS4uu.png" height="450"/><img src="https://i.imgur.com/owoFT5k.png" height="450"/><img src="https://i.imgur.com/mAbc2Qy.png" height="450"/><img src="https://i.imgur.com/C8zlcY1.png" height="450"/><img src="https://i.imgur.com/nLgoIH8.png" height="450"/><img src="https://i.imgur.com/2IAs7iY.png" height="450"/><img src="https://i.imgur.com/AJJUUBa.png" height="450"/><img src="https://i.imgur.com/3NHV5VV.png" height="450"/>
