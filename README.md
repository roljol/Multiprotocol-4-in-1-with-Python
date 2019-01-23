# Multiprotocol-4-in-1-with-Python

Parameter Pascal Langer 4 in 1 multi-protocol module via a graphical interface (GUI)

Hello users of the 4-in-1 multi-protocol module.

To better understand the parameterization of the module, I wrote a program in Python 2.7 (with graphical interface).
It is a beta version that accepts PPM and series modes.
This program adapts _Config.h and _MyConfig.h (Pascal Langer files) to my needs.
There are explanations accessible by a right-click (English or French).
It runs on Windows (XP and above) and Linux.
The GUI is not really pretty because I chose Windows-Linux compatibility in
using a tool called Tkinter but that's fine!

This program is called MUI (MUI.py for Linux and Windows or MUI.exe for Windows)

Installation:
under Windows, download dist.zip.
Put it in a folder called for example c:\MUI
Unzip it. Launch MUI.exe.
No other operation is necessary but if it does not work, install Python (preferably version 2.7)
then TCL if asked.
(TCL is linked to Tkinter graphical tools for Windows-Linux compatibility (Mac OS))
After launching MUI.exe you must first enter the path to access the
.INO, .H etc.. files created by Pascal Langer. This path should normally lead
on "DIY-Multiprotocol-TX-Module-master".
To do this, click [Indicate].
Quit MUI then restart it.
You can now start setting up the 4 in 1 module.

* Explanations on the use of MUI:
There are 3 configurations for 3 possible settings (Cfg1, Cfg2 and Cfg3).
Question: why so many configurations?
Answer: You can have multiple radio controls. You can also have the settings for those
of your friends.
To start, use the No.1 configuration called "Cfg1" which is displayed at launch.
In PPM mode, Pascal has provided up to 5 "Bank", so MUI accepts 5 "Bank".
Each configuration consists of:
- its general sub-configuration
- its sub-configuration of radio controlled models


* Mostly in PPM mode
- The frame "Gal: X | RC_model: X | Bank: X" -
Buttons :
[Default]: Loads the default configuration (the settings are to be redefined later).
It is materialized by the files in the Cfg0 folder.
[General]: Loads the general sub-configuration corresponding to Cfg1 or Cfg2 or Cfg3.
[RC model]: Load the sub-configuration of radio controlled models corresponding to Cfg1 or Cfg2 or Cfg3.
[Bank Options]: to choose the sub-configuration of radio controlled models corresponding to Cfg1 or Cfg2
or Cfg3.

- The "Save in CfgX BankX" frame -
Buttons :
[General]: Saves the general sub-configuration corresponding to the selected CfgX.
[RC model]: saves the sub-configuration of radio controlled models corresponding to the selected CfgX and
Bank selected.

- The "RC model of Cfg: X Bank: X" frame -
[Brand]: for the name of the manufacturer of the model. For example "Syma". (required information)
[RC model]: for the model name. For example "X5C". (required information)
A drop-down list (or Combobox) placed under "Protocol" and "Sub prot." contains the protocols and
known sub-protocols. Open there and choose a protocol by clicking on it.
The parameters of the chosen protocol are displayed, to validate your choice click on [Accept, Add RC model].
The right list corresponding to your choices then displays the manufacturer and the model.
For compliance with Pascal's work this list contains a maximum of 14 choices.

END OF EXPLANATIONS.
THERE WILL BE A SUITE IF MODELISTS ARE INTERRESSED BY MY WORK!




******************************** FRENCH ********************************

Bonjour utilisateurs du module multi-protocol 4 en 1.

Pour mieux comprendre le paramétrage du module, j'ai écris un programme en Python 2.7 (avec interface graphique).
C'est une version beta qui prend en compte PPM et série.
Ce programme adapte _Config.h et _MyConfig.h (les fichiers de Pascal Langer) à mes besoins.
Il y a des explications accessibles par un clic-droit (anglais ou français).
Il fonctionne sous Windows (XP et plus) et Linux.
L'interface graphique n'est pas véritablement jolie parce que j'ai choisi la compatibilité Windows-Linux en 
utilisant un outil appelé Tkinter mais ça va !

Ce programme s'appelle MUI (MUI.py pour Linux et Windows ou MUI.exe pour Windows)

Installation :
sous Windows, téléchargez dist.zip.
Placez le dans un dossier appelé par exemple c:\MUI
Décompressez le. Lancez MUI.exe.
Aucune autre opération n'est nécessaire mais si ça ne marche pas, installer Python (de préférence version 2.7) 
puis TCL si demandé.
( TCL est liè aux outils graphiques Tkinter permettant la compatibilité Windows-Linux-(Mac OS) )
Après avoir lancé MUI.exe vous devez en premier lieu renseigner le chemin permettant l'accès aux 
fichiers .INO, .H etc.. créés par Pascal Langer. Ce chemin doit normalement aboutir 
sur "DIY-Multiprotocol-TX-Module-master".
Pour cela, cliquez sur [Indicate].
Quitter MUI puis relancez le.
Vous pouvez maintenant commencer le paramétrage du module 4 en 1.

* Explications sur l'utilisation de MUI :
Il est prévu 3 configurations pour 3 paramétrages possibles (Cfg1, Cfg2 et Cfg3).
Question : pourquoi autant de configurations ?
Réponse : vous pouvez posséder plusieurs radiocommandes. Vous pouvez aussi avoir en charge le paramétrage de celles
de vos amis.
Pour commencer utiliser la configuration No 1 appelée "Cfg1" qui est affichée au lancement.
En mode PPM Pascal a prévu jusqu'à 5 "Bank", MUI accepte donc 5 "Bank".
Chaque configuration est constituée de :
- sa sous-configuration générale
- sa sous-configuration des modèles radiocommandés


* Pour l'essentiel en mode PPM
- Le cadre "Gal:X | RC_model:X | Bank:X" -
Les boutons :
[Default] : charge la configuration par défaut (les paramètres sont à redéfinir plus tard).
Elle est matérialisée par les fichiers du dossier Cfg0.
[General] : charge la sous-configuration générale correspondant à Cfg1 ou Cfg2 ou Cfg3.
[RC model] : charge la sous-configuration des modèles radiocommandés correspondant à Cfg1 ou Cfg2 ou Cfg3.
[les options Bank] : pour choisir la sous-configuration des modèles radiocommandés correspondant à Cfg1 ou Cfg2 
ou Cfg3.

- Le cadre "Save in CfgX BankX" -
Les boutons :
[General] : sauvegarde la sous-configuration générale correspondant au CfgX sélectionné.
[RC model] : sauvegarde la sous-configuration des modèles radiocommandés correspondant aux CfgX sélectionné et
Bank sélectionné.

- Le cadre "RC model of Cfg:X Bank:X" -
[Brand] : pour le nom du fabricant du modèle réduit. Par exemple "Syma". (renseignement obligatoire)
[RC model] : pour le nom du modèle. Par exemple "X5C". (renseignement obligatoire)
Une liste déroulante (ou Combobox) placée sous "Protocol" et "Sub prot." contient les protocoles et 
sous-protocoles connus. Ouvrez là et choisissez un protocole en cliquant dessus.
Les paramètres du protocole choisi s'affichent, pour valider votre choix cliquez sur [Accept, Add RC model].
La liste de droite correspondant à vos choix affiche alors le fabricant et le modèle.
Cette liste pour être conforme au travail de Pascal contient au maximum 14 choix.

FIN DES EXPLICATIONS.
IL Y AURA UNE SUITE SI DES MODELISTES SONT INTERRESSES PAR MON TRAVAIL !








