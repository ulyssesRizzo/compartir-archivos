Zelio Soft2


Ce document contient des informations importantes sur le logiciel Zelio Soft2. Lisez-le en int�gralit� avant d'ex�cuter le logiciel.

Ce document n'a vocation ni � remplacer la documentation de ces produits, ni � d�terminer l'ad�quation ou la fiabilit� de ces produits pour des applications utilisateur sp�cifiques. 
Il incombe � chaque utilisateur ou int�grateur d'effectuer une analyse des risques compl�te et appropri�e, ainsi qu'une �valuation et un test des produits en fonction de l'application
 pr�vue ou de son utilisation. Ni la soci�t� Schneider Electric ni aucune de ses soci�t�s affili�es ou filiales ne peuvent �tre tenues pour responsables de la mauvaise utilisation des 
informations contenues dans le pr�sent document. Toutes les r�glementations locales, r�gionales et nationales pertinentes doivent �tre respect�es lors de l'installation et de l'utilisation de ce produit.
Lorsque des �quipements sont utilis�s pour des applications pr�sentant des exigences techniques de s�curit�, suivez les instructions appropri�es. La non-utilisation du logiciel Schneider Electric ou d'un 
logiciel approuv� avec nos produits mat�riels peut entra�ner des blessures, des dommages ou un fonctionnement incorrect. Le non-respect de cette consigne peut provoquer des l�sions corporelles ou des dommages
 mat�riels. Si vous avez des suggestions d'am�lioration ou de correction ou si vous avez relev� des erreurs dans cette publication, merci de nous en informer. Aucune partie de ce document ne peut �tre reproduite, 
sous quelque forme ou par quelque moyen que ce soit, �lectronique ou m�canique (y compris par photocopie), sans l'autorisation �crite de Schneider Electric.

Copyright � D�cembre 2016 � Schneider Electric. Tous droits r�serv�s.


==================================================================

*************************** Version 5.0 ************************
Firmware FBD V4.07 / V4.3.01
Firmware LADDER V4.05 / V4.2.05
Firmware LADDER EXTENDED V4.09 / V4.3.03
Firmware SR2COM01 V1.0.13


Augmentation des capacit�s LADDER � 240 lignes si SR2COM01 non utilis�
Augmentation des ressources LADDER � 28 Timers, 28 Compteurs, 56 Bits Internes (M, N) si SR2COM01 non utilis�
Si SR2COM01 est utilis�, les capacit�s et ressources restent identiques � la version pr�c�dente de Zelio Soft2.

Augmentation des capacit�s m�moires FBD et du nombre de blocs max � 500 blocs
Compatibilit� avec Windows 10 (32 et 64 bits) � voir note importante ci-dessous 


Note: Une application LD r�alis�e avec une version pr�c�dente de Zelio Soft 2 et ouverte avec la version V5.0 peut augmenter le temps de cycle jusqu�� 2 ms. 

IMPORTANT : Le driver USB fourni avec Zelio Soft2 n�est pas compatible avec Windows 10. Windows 10 installe son propre driver USB. Sur certains PCs sous Windows 10, les temps de transferts peuvent �tre plus longs. 


*************************** Version 4.6 ************************
Firmware FBD V4.2.05
Firmware LADDER V4.2.05
Firmware SR2COM01 V1.0.13

Compatibilit� avec Windows 7 (64 bits) et Windows 8.1 (64 bits).
Ajout du driver 64bits pour le c�ble SR2USB01.
Nouvelle DLL de communication pour le module Bluetooth SR2BTC01.
Correction du bug de la fonction TIME PROG.

*************************** Version 4.5 ************************
Firmware FBD V4.2.04
Firmware LADDER V4.2.04
Firmware SR2COM01 V1.0.13

Mise � l'image Schneider Electric (nouveaux �cran de d�marrage et logo).

Correction de la modification par la face avant de la fonction TIME PROG.
Evolution du test de compatibilit� du firmware avant le transfert de la cartouche.

******************************************** Version 4.4 *********************************************** 
Firmware FBD V4.2.03
Firmware LADDER V4.2.03
Firmware SR2COM01 V1.0.13

Ajout de fonctions FBD d�di�es Solaire : Suntrack et Sunrise/Sunset

Correction du fichier d'initialisation Modem GSM SR2MOD02
Am�lioration du boot Z2
Am�lioration de l'aide en ligne

Correction de probl�mes d'affichage sur OS Japonais

---------------------------------------------- Windows Vista et Windows 7 -----------------------------------------
Pour les OS Windows Vista et Windows Seven seulement:

Compatibilit� avec Windows Vista (32 bits) et Windows 7 (32 bits)

Ajout des drivers modems pour Windows Vista et Windows 7
Voir le fichier readme "(INSTALLATION_PATH)\DriverModem\MODEM_DRIVER_INSTALL_xxV1.txt"
o� (INSTALLATION_PATH) est le nom du r�pertoire d'installation de Zelio Soft 2
et xx refl�te la langue d'installation (EN/ES/DE/FR/IT/PT)

Ajout des drivers pour le convertisseur USB/s�rie SR2CBL06 pour Windows Vista et Windows 7

*************************** Version 4.3 ************************
Firmware FBD v4.02
Firmware LADDER v4.02
Firmware SR2COM01 v1.0.12

Corrections de bugs et am�lioration du compilateur

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

- IMPORTANT : Lors d'op�ration de mise � jour de Firmware (par cartouche SR2MEM02 ou par PC),
l'alimentation du module ne doit pas �tre interrompue avant la fin du transfert. En cas de 
coupure d'alimentation pendant le transfert du Firmware le produit peut para�tre endommag� (�cran vierge sur module avec �cran ou clignotement rapide de la 
LED sur module sans �cran) .
LE REMETTRE SOUS TENSION et recommencez l'op�ration de mise � jour de Firmware (Menu : 
Module/Mettre � jour le FIRMWARE du module). 

- IMPORTANT : la connexion des extensions doit se faire hors tension. 
Se r�f�rer � l'Instruction de Service fournie avec l'extension. 

- Remarques sur l'envoi d'E-mail par SMS:
L'interface de communication SR2COM01 construit ses messages avec la trame suivante:
<adresse Email du destinataire><nom de la station distante> <date heure> <objet du message d'alarme><corps du message d'alarme>
(Les caract�res '<' et '>' de la trame ci dessus sont uniquement utilis�s pour representer la delimitation des diff�rents champs, ils ne sont pas pr�sents dans la trame envoy�e.)
Par cons�quent, veillez � respecter la syntaxe sp�cifique au service Email de l'op�rateur choisi.
Pour cela, int�grez les caract�res sp�cifiques dans les annuaires (destinataires et/ou stations distantes) et/ou dans les messages (objet et/ou corps).

- L'interface de communication SR2COM01 doit �tre r�initialis�e � chaque changement de type de liaison (C�bles SR2CBL01 ou SR2CBL07).
Attendre la fin du clignotement de la LED avant de d�buter le transfert programme ou la mise en marche du module logique.

- Avec une interface SR2COM01 et un r�seau t�l�phonique utilisant une num�rotation avec pr�fixe, int�grez les caract�res suppl�m�ntaires dans la syntaxe du num�ro de t�l�phone (destinataires et/ou station distante).

- Pour envoyer des commandes depuis l'atelier ZelioLogicAlarm, la syntaxe du num�ro de t�l�phone (format international ou non,prefixe ou non) utilis�e doit correspondre � celle utilis�e pour la configuration de la station distante dans l'atelier ZelioSoft2

- Pour recevoir des messages d'alarmes provenant d'une interface de communication SR1COM01 dans le logiciel ZelioSoftAlarm, il est n�cessaire de configurer le modem cot� PC en
9600 bauds, 8bits sans parit�.


*************************** Version 2.4 ************************
Firmware FBD v2.18
Firmware LADDER v2.19

*************************** Version 2.2 ************************
Le fonctionnement de l'horloge des modules SR2 et SR3 est 
diff�rent de celui des modules SR1. Si l'horloge est mise � ON
le lundi � 23 heures et mise � OFF le lundi � 1 heure, elle ne 
passe pas � OFF le mardi � 1 heure mais effectivement le lundi 
suivant � 1 heure. Si aucune autre commande n'a �t� faite, 
l'horloge reste positionn�e � ON tous les autres jours de la 
semaine. Il faut v�rifier le fontionnement des horloges lors 
de l'aide au transfert des programmes fonctionnant sur les 
modules SR1 vers les modules SR2 et SR3.

Les menus CHANGER J/H, CHANGER ETE/HIV ainsi que le menu 
PARAMETRE uniquement en mode LADDER ne sont plus prot�g�s par 
le mot de passe.
 
*************************** Version 2.1 ************************
Firmware FBD v2.16
Firmware LADDER v2.16

*************************** Version 2.0 ************************
Cette version permet de programmer les applications d'automatisme 
soit par des sch�mas LADDER comme avec Zelio Soft soit en 
utilisant le langage FBD (Fonctional Bloc Diagram).

Des aides en ligne sont accessibles en cliquant sur les points 
d'interrogations des barres d'outils, des fen�tres de param�trage 
des blocs fonctions et par la touche F1 du clavier du PC sur les 
menus d�sign�s (vid�o invers�e).

Cette version fournit une aide au transfert des programmes 
fonctionnant sur les modules logiques SR1 vers les modules 
logiques SR2 et SR3. Seuls les programmes produits avec la version
 1.5 de Zelio Soft sont trait�s.Pour effectuer le transfert, il 
suffit d'ouvrir le programme .zel dans Zelio Soft 2. L'atelier 
logiciel effectue les correspondances suivantes :

   Zelio Logic1     Zelio Logic 2 
   SR1 B121JD  vers SR2 B121JD   (2 entr�es mixtes en plus)
   SR1 A101BD  vers SR2 A101BD   
   SR1 B121BD  vers SR2 B121BD   (2 entr�es mixtes en plus)
   SR1 B122BD  vers SR2 B122BD   (2 entr�es mixtes en plus)
   SR1 B101B   vers SR2 B121B    (2 entr�es TOR en plus)
   SR1 A101FU  vers SR2 A101FU
   SR1 B101FU  vers SR2 B121FU   (2 entr�es TOR en plus)
   SR1 A201BD  vers SR2 A201BD   (2 entr�es mixtes en plus)
   SR1 B201BD  vers SR2 B201BD   (4 entr�es mixtes en plus)
   SR1 B201B   vers SR2 B201B
   SR1 A201FU  vers SR2 A201FU
   SR1 B201FU  vers SR2 B201FU

Il conviendra de v�rifier les mises en correspondances des entr�es
et le fonctionnement du programme port�. L'utilisateur pourra 
ensuite enregistrer le programme sous Zelio Soft 2. Il est 
�galement possible par le menu "Module" de remplacer le module 
logic SR2 par un module SR3 avec le m�me nombre ou avec un nombre 
sup�rieur d'entr�es - sorties.

Remarque :
Avec les syst�mes Windows 95 et 98, les drivers de p�riph�riques 
non "intelligents" peuvent saturer la liaison s�rie et provoquer 
des ruptures de communications entre le PC et le module.

Il est interdit de changer l'heure courante du module entre 2 
heures et 3 heures du matin le jour du changement de l'heure d'�t�
 en heure d'hiver.

Anomalie connue et non encore corrig�e :
Les touches Zx utilis�es dans le programme ne sont pas accessibles
dans le mode MONITORING sur la face avant du module. 



 

 
