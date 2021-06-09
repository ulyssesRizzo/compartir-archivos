Zelio Soft2


Ce document contient des informations importantes sur le logiciel Zelio Soft2. Lisez-le en intégralité avant d'exécuter le logiciel.

Ce document n'a vocation ni à remplacer la documentation de ces produits, ni à déterminer l'adéquation ou la fiabilité de ces produits pour des applications utilisateur spécifiques. 
Il incombe à chaque utilisateur ou intégrateur d'effectuer une analyse des risques complète et appropriée, ainsi qu'une évaluation et un test des produits en fonction de l'application
 prévue ou de son utilisation. Ni la société Schneider Electric ni aucune de ses sociétés affiliées ou filiales ne peuvent être tenues pour responsables de la mauvaise utilisation des 
informations contenues dans le présent document. Toutes les réglementations locales, régionales et nationales pertinentes doivent être respectées lors de l'installation et de l'utilisation de ce produit.
Lorsque des équipements sont utilisés pour des applications présentant des exigences techniques de sécurité, suivez les instructions appropriées. La non-utilisation du logiciel Schneider Electric ou d'un 
logiciel approuvé avec nos produits matériels peut entraîner des blessures, des dommages ou un fonctionnement incorrect. Le non-respect de cette consigne peut provoquer des lésions corporelles ou des dommages
 matériels. Si vous avez des suggestions d'amélioration ou de correction ou si vous avez relevé des erreurs dans cette publication, merci de nous en informer. Aucune partie de ce document ne peut être reproduite, 
sous quelque forme ou par quelque moyen que ce soit, électronique ou mécanique (y compris par photocopie), sans l'autorisation écrite de Schneider Electric.

Copyright © Décembre 2016 – Schneider Electric. Tous droits réservés.


==================================================================

*************************** Version 5.0 ************************
Firmware FBD V4.07 / V4.3.01
Firmware LADDER V4.05 / V4.2.05
Firmware LADDER EXTENDED V4.09 / V4.3.03
Firmware SR2COM01 V1.0.13


Augmentation des capacités LADDER à 240 lignes si SR2COM01 non utilisé
Augmentation des ressources LADDER à 28 Timers, 28 Compteurs, 56 Bits Internes (M, N) si SR2COM01 non utilisé
Si SR2COM01 est utilisé, les capacités et ressources restent identiques à la version précédente de Zelio Soft2.

Augmentation des capacités mémoires FBD et du nombre de blocs max à 500 blocs
Compatibilité avec Windows 10 (32 et 64 bits) – voir note importante ci-dessous 


Note: Une application LD réalisée avec une version précédente de Zelio Soft 2 et ouverte avec la version V5.0 peut augmenter le temps de cycle jusqu’à 2 ms. 

IMPORTANT : Le driver USB fourni avec Zelio Soft2 n’est pas compatible avec Windows 10. Windows 10 installe son propre driver USB. Sur certains PCs sous Windows 10, les temps de transferts peuvent être plus longs. 


*************************** Version 4.6 ************************
Firmware FBD V4.2.05
Firmware LADDER V4.2.05
Firmware SR2COM01 V1.0.13

Compatibilité avec Windows 7 (64 bits) et Windows 8.1 (64 bits).
Ajout du driver 64bits pour le câble SR2USB01.
Nouvelle DLL de communication pour le module Bluetooth SR2BTC01.
Correction du bug de la fonction TIME PROG.

*************************** Version 4.5 ************************
Firmware FBD V4.2.04
Firmware LADDER V4.2.04
Firmware SR2COM01 V1.0.13

Mise à l'image Schneider Electric (nouveaux écran de démarrage et logo).

Correction de la modification par la face avant de la fonction TIME PROG.
Evolution du test de compatibilité du firmware avant le transfert de la cartouche.

******************************************** Version 4.4 *********************************************** 
Firmware FBD V4.2.03
Firmware LADDER V4.2.03
Firmware SR2COM01 V1.0.13

Ajout de fonctions FBD dédiées Solaire : Suntrack et Sunrise/Sunset

Correction du fichier d'initialisation Modem GSM SR2MOD02
Amélioration du boot Z2
Amélioration de l'aide en ligne

Correction de problèmes d'affichage sur OS Japonais

---------------------------------------------- Windows Vista et Windows 7 -----------------------------------------
Pour les OS Windows Vista et Windows Seven seulement:

Compatibilité avec Windows Vista (32 bits) et Windows 7 (32 bits)

Ajout des drivers modems pour Windows Vista et Windows 7
Voir le fichier readme "(INSTALLATION_PATH)\DriverModem\MODEM_DRIVER_INSTALL_xxV1.txt"
où (INSTALLATION_PATH) est le nom du répertoire d'installation de Zelio Soft 2
et xx reflète la langue d'installation (EN/ES/DE/FR/IT/PT)

Ajout des drivers pour le convertisseur USB/série SR2CBL06 pour Windows Vista et Windows 7

*************************** Version 4.3 ************************
Firmware FBD v4.02
Firmware LADDER v4.02
Firmware SR2COM01 v1.0.12

Corrections de bugs et amélioration du compilateur

*************************** Version 4.2 ************************
Firmware FBD v4.01
Firmware LADDER v4.01
Firmware SR2COM01 v1.0.12

- Correction du fichier d'initialisation 'Modem RTC SR2MOD01'

*************************** Version 4.1 ************************
Firmware FBD v4.01
Firmware LADDER v4.01
Firmware SR2COM01 v1.0.12

*************************** Version 3.1 ************************
Firmware FBD v3.09
Firmware LADDER v3.09
Firmware SR2COM01 v1.0.12

- IMPORTANT : Lors d'opération de mise à jour de Firmware (par cartouche SR2MEM02 ou par PC),
l'alimentation du module ne doit pas être interrompue avant la fin du transfert. En cas de 
coupure d'alimentation pendant le transfert du Firmware le produit peut paraître endommagé (écran vierge sur module avec écran ou clignotement rapide de la 
LED sur module sans écran) .
LE REMETTRE SOUS TENSION et recommencez l'opération de mise à jour de Firmware (Menu : 
Module/Mettre à jour le FIRMWARE du module). 

- IMPORTANT : la connexion des extensions doit se faire hors tension. 
Se référer à l'Instruction de Service fournie avec l'extension. 

- Remarques sur l'envoi d'E-mail par SMS:
L'interface de communication SR2COM01 construit ses messages avec la trame suivante:
<adresse Email du destinataire><nom de la station distante> <date heure> <objet du message d'alarme><corps du message d'alarme>
(Les caractères '<' et '>' de la trame ci dessus sont uniquement utilisés pour representer la delimitation des différents champs, ils ne sont pas présents dans la trame envoyée.)
Par conséquent, veillez à respecter la syntaxe spécifique au service Email de l'opérateur choisi.
Pour cela, intégrez les caractères spécifiques dans les annuaires (destinataires et/ou stations distantes) et/ou dans les messages (objet et/ou corps).

- L'interface de communication SR2COM01 doit être réinitialisée à chaque changement de type de liaison (Câbles SR2CBL01 ou SR2CBL07).
Attendre la fin du clignotement de la LED avant de débuter le transfert programme ou la mise en marche du module logique.

- Avec une interface SR2COM01 et un réseau téléphonique utilisant une numérotation avec préfixe, intégrez les caractères suppléméntaires dans la syntaxe du numéro de téléphone (destinataires et/ou station distante).

- Pour envoyer des commandes depuis l'atelier ZelioLogicAlarm, la syntaxe du numéro de téléphone (format international ou non,prefixe ou non) utilisée doit correspondre à celle utilisée pour la configuration de la station distante dans l'atelier ZelioSoft2

- Pour recevoir des messages d'alarmes provenant d'une interface de communication SR1COM01 dans le logiciel ZelioSoftAlarm, il est nécessaire de configurer le modem coté PC en
9600 bauds, 8bits sans parité.


*************************** Version 2.4 ************************
Firmware FBD v2.18
Firmware LADDER v2.19

*************************** Version 2.2 ************************
Le fonctionnement de l'horloge des modules SR2 et SR3 est 
différent de celui des modules SR1. Si l'horloge est mise à ON
le lundi à 23 heures et mise à OFF le lundi à 1 heure, elle ne 
passe pas à OFF le mardi à 1 heure mais effectivement le lundi 
suivant à 1 heure. Si aucune autre commande n'a été faite, 
l'horloge reste positionnée à ON tous les autres jours de la 
semaine. Il faut vérifier le fontionnement des horloges lors 
de l'aide au transfert des programmes fonctionnant sur les 
modules SR1 vers les modules SR2 et SR3.

Les menus CHANGER J/H, CHANGER ETE/HIV ainsi que le menu 
PARAMETRE uniquement en mode LADDER ne sont plus protégés par 
le mot de passe.
 
*************************** Version 2.1 ************************
Firmware FBD v2.16
Firmware LADDER v2.16

*************************** Version 2.0 ************************
Cette version permet de programmer les applications d'automatisme 
soit par des schémas LADDER comme avec Zelio Soft soit en 
utilisant le langage FBD (Fonctional Bloc Diagram).

Des aides en ligne sont accessibles en cliquant sur les points 
d'interrogations des barres d'outils, des fenêtres de paramétrage 
des blocs fonctions et par la touche F1 du clavier du PC sur les 
menus désignés (vidéo inversée).

Cette version fournit une aide au transfert des programmes 
fonctionnant sur les modules logiques SR1 vers les modules 
logiques SR2 et SR3. Seuls les programmes produits avec la version
 1.5 de Zelio Soft sont traités.Pour effectuer le transfert, il 
suffit d'ouvrir le programme .zel dans Zelio Soft 2. L'atelier 
logiciel effectue les correspondances suivantes :

   Zelio Logic1     Zelio Logic 2 
   SR1 B121JD  vers SR2 B121JD   (2 entrées mixtes en plus)
   SR1 A101BD  vers SR2 A101BD   
   SR1 B121BD  vers SR2 B121BD   (2 entrées mixtes en plus)
   SR1 B122BD  vers SR2 B122BD   (2 entrées mixtes en plus)
   SR1 B101B   vers SR2 B121B    (2 entrées TOR en plus)
   SR1 A101FU  vers SR2 A101FU
   SR1 B101FU  vers SR2 B121FU   (2 entrées TOR en plus)
   SR1 A201BD  vers SR2 A201BD   (2 entrées mixtes en plus)
   SR1 B201BD  vers SR2 B201BD   (4 entrées mixtes en plus)
   SR1 B201B   vers SR2 B201B
   SR1 A201FU  vers SR2 A201FU
   SR1 B201FU  vers SR2 B201FU

Il conviendra de vérifier les mises en correspondances des entrées
et le fonctionnement du programme porté. L'utilisateur pourra 
ensuite enregistrer le programme sous Zelio Soft 2. Il est 
également possible par le menu "Module" de remplacer le module 
logic SR2 par un module SR3 avec le même nombre ou avec un nombre 
supérieur d'entrées - sorties.

Remarque :
Avec les systèmes Windows 95 et 98, les drivers de périphériques 
non "intelligents" peuvent saturer la liaison série et provoquer 
des ruptures de communications entre le PC et le module.

Il est interdit de changer l'heure courante du module entre 2 
heures et 3 heures du matin le jour du changement de l'heure d'été
 en heure d'hiver.

Anomalie connue et non encore corrigée :
Les touches Zx utilisées dans le programme ne sont pas accessibles
dans le mode MONITORING sur la face avant du module. 



 

 
