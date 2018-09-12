# Atelier d'ntroduction à la programmation en langage python et à l'électronique sur la plateforme Raspberry Pi

**Par Vincent Cusson**<br>
**Pour le cours EDM3840**
___

### Installer l'OS sur le PI

#### OS images
- [Raspbian](https://www.raspberrypi.org/downloads/raspbian/) - The official supported Raspberry Pi OS, based on Debian and available as a lite version.
- [NOOBS](https://www.raspberrypi.org/downloads/noobs/) - New Out Of the Box Software, an easy OS installer for beginners.

#### Outils
- [PiBakery](http://www.pibakery.org/) - The blocks based, easy to use setup tool for Raspberry Pi.
- [ApplePi Bakery](http://www.tweaking4all.com/software/macosx-software/macosx-apple-pi-baker/) - macOS application to easily install/backup/restore images onto an SD card.
- [Etcher](https://www.etcher.io/) - SD card burner app that is simple for end users, extensible for developers, and works on any platform.


### Accéder au PI

  - Connexion physique à l'aide d'un moniteur, d'une souris et d'un clavier.

  - VNC -  Accès à distance à l'interface graphique du Pi, visualisé dans une fenêtre sur un autre ordinateur.
    - *VNC Connect* de *RealVNC* est inclus avec Raspbian
    - [Tutoriel sur le site officiel](https://www.raspberrypi.org/documentation/remote-access/vnc/README.md)


  - SSH - Accéder à la ligne de commande du Pi depuis un autre ordinateur.
    - [Tutoriel sur le site officiel](https://www.raspberrypi.org/documentation/remote-access/ssh/README.md)

      - Sur Mac - [Terminal](https://www.raspberrypi.org/documentation/remote-access/ssh/windows.md)
      - Sur windows - [PuTTY](https://www.raspberrypi.org/documentation/remote-access/ssh/windows.md)


  - SFTP - Copier des fichiers entre votre Pi et un autre ordinateur.

    - [Tutoriel sur le site officiel](https://www.raspberrypi.org/documentation/remote-access/ssh/sftp.md)


### Introduction à GNU/Linux
  - ##### OS
  - ##### Terminal vs GUI
  - ##### Package manager
    Outil(s) automatisant le processus d'installation, désinstallation, mise à jour de logiciels installés sur un système informatique.

    - Terminal - [APT](https://help.ubuntu.com/community/AptGet/Howto)

      ```sudo apt-get update```<br>
      ```sudo apt-get upgrade```<br>
      ```sudo apt-cache search <search_term>```<br>
      ```sudo apt-get install <package_name>```<br>
      ```sudo apt-get remove <package_name>```<br>

    - GUI - [Synaptic](https://help.ubuntu.com/community/SynapticHowto)



  - ##### Editeur de texte
  - ##### Configuration
    - Réseau
https://projects.raspberrypi.org/en/projects/raspberry-pi-using/10

### Python

  - ##### Python2 vs Python3
  - ##### Hello, world! dans le Terminal
    ```python``` <br>
    ```print("Hello, World!")```

  - ##### Hello, world! comme premier script
     ```nano premierScript.py```<br>
     ```print("Hello, World!")```<br>
     ```python premierScript.py```<br>

  - ##### PyPI et pip
    *Repository* pour les packages Python tiers open-source.<br>
     ```sudo apt-get install python-pip```<br>
     ```pip install <package_name>```<br>
     ```pip uninstall <package_name>```<br>

  - ##### IDE RPI

### Électronique
  - GPIO
    - http://www.pingo.io/docs/
  - Branchement senseurs/actuateurs

### Node-RED, Processing et Pure Data
  - GPIO
 - [Processing library](https://processing.org/reference/libraries/io/GPIO.html)
 - [Pure Data example patcher](https://forum.pdpatchrepo.info/topic/9997/gpio-raspberry-p3-and-pure-data/2)
 - [Node-RED tutorial](https://projects.raspberrypi.org/en/projects/getting-started-with-node-red/7)
  - Communication OSC
    - [En Pure Data](http://write.flossmanuals.net/pure-data/send-and-receive/)

### Ressources

##### Raspberry PI
- [Site officiel](https://www.raspberrypi.org/)
- [Forum officiel](https://www.raspberrypi.org/forums/)
- [StackExchange](https://raspberrypi.stackexchange.com/)
- [Reddit](https://www.reddit.com/r/raspberry_pi)
- [Reddit Projects](https://www.reddit.com/r/RASPBERRY_PI_PROJECTS)
- [Awesome Raspberry Pi](https://github.com/thibmaek/awesome-raspberry-pi)

##### Bash et GNU/Linux
- [Codecademy Bash course](https://www.codecademy.com/learn/learn-the-command-line)

##### Python
- [Codecademy Python course](https://www.codecademy.com/learn/learn-python)
- [Weather API example](https://github.com/AnthonyBloomer/weather-api)
- [Twitter API example](https://github.com/ryanmcgrath/twython)
- [Awesome Python](https://github.com/vinta/awesome-python)
- [GPIO library](https://www.raspberrypi.org/documentation/usage/gpio/python/README.md)

##### Électronique
- [TOF wiki](http://wiki.t-o-f.info/EDM4640/EDM4640)
- [Fritzing](http://fritzing.org/home/)
