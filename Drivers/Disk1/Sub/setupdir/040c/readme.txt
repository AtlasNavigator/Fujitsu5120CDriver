         --------------------------------------------------------
            Logiciel de gestion de la source de données TWAIN
                           < version 32 bits >
                              Fichier README
                             2 novembre 2012
                           Version 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012


Veuillez lire ce fichier avant d'utiliser le produit.  Ce fichier comprend 
des remarques importantes ainsi que les informations les plus récentes 
non comprises dans l'aide en ligne.

------------------------------------------------------------------------
Table des matières 
------------------------------------------------------------------------

1. Configuration système requise
2. Installation
3. Remarques concernant la gestion de l'alimentation
4. Utilisation de l'adaptateur SCSI Adaptec
5. Remarques concernant le raccordement de plusieurs scanners au même PC
6. Remarques concernant la fonctionnalité de numérisation recto verso
7. Remarques concernant la spécification de la zone de balayage 
8. Remarques concernant les bourrages de papier
9. Remarques concernant la numérisation en 256 et en 8 couleurs
10. Détection automatique de la taille et du désalignement 
11. Remarques concernant la détection automatique du format de page
12. Note à propos de l'utilisation d'Adobe Acrobat
13. Remarques concernant les coupures d'alimentation en cours de numérisation
14. Remarques concernant la police système
15. Remarques concernant les paramètres du BIOS SCSI
16. Remarques concernant le contrôle des tâches en mode mémoire cache
17. À propos des réglages de la Mémoire cache pour la saisie du nombre de feuilles 
     à numériser
18. Remarques concernant la Sauter les pages vierges
19. À propos de la numérisation d'une page longue doublée d'un surbalayage
20. Notes à propos de l'option SDTC
21. Utilisation hautement sécuritaire obligatoire


-------------------------------------------------------------
1. Configuration système requise
-------------------------------------------------------------

Ce logiciel fonctionne dans les environnements suivants :

  1) UC
      Processeur Pentium(MD) d'Intel (MD) ou processeur compatible 
      avec les adaptateurs SCSI-2 ou USB 1.1/2.0
     
  2) Système d'exploitation
     - Microsoft(R) Windows(R) 2000 Professional
     - Microsoft(R) Windows(R) XP Home Edition
     - Microsoft(R) Windows(R) XP Professional
     - Microsoft(R) Windows(R) XP Professional x64 Edition
     - Microsoft(R) Windows Server(TM) 2003, Standard Edition
     - Microsoft(R) Windows Server(TM) 2003 R2, Standard Edition
     - Microsoft(R) Windows Server(TM) 2003 R2, Standard x64 Edition
     - Windows Vista(R) Home Basic (32/64bit)
     - Windows Vista(R) Home Premium (32/64bit)
     - Windows Vista(R) Business (32/64bit)
     - Windows Vista(R) Enterprise (32/64bit)
     - Windows Vista(R) Ultimate (32/64bit)
     - Microsoft(R) Windows Server(TM) 2008, Standard Edition (32/64bit)
     - Windows(R) 7 Home Premium(32/64bit)
     - Windows(R) 7 Professional(32/64bit)
     - Windows(R) 7 Enterprise(32/64bit)
     - Windows(R) 7 Ultimate (32/64bit)
     - Microsoft(R) Windows Server(TM) 2008 R2, Standard
     - Windows(R) 8 (32/64bit)
     - Windows(R) 8 Pro(32/64bit)
     - Windows(R) 8 Enterprise(32/64bit)
     - Microsoft(R) Windows Server(TM) 2012, Standard

-------------------------------------------------------------
2. Installation
-------------------------------------------------------------

 - Si vous utilisez l'installateur fourni sur SETUP DISK :
   Insérez le SETUP DISK et suivez les instructions présentées dans la boîte de dialogue 
   de démarrage.

 - Si vous avez obtenu l'installateur par la voie du Web ou s'il figure sur un autre 
   support :
   Exécutez setup.exe et suivez les instructions qui apparaissent à l'écran.

 - Pour pouvoir installer le programme, assurez-vous d'avoir ouvert une session 
   en tant qu'utilisateur avec des privilèges d'Administrateur.


---------------------------------------------------
3. Remarques concernant la gestion de l'alimentation 
---------------------------------------------------

Si votre ordinateur est en mode Veille ou en mode Hibernation alors qu'une 
numérisation est en cours d'exécution, la transmission des données risque 
d'échouer et la numérisation, d'être insatisfaisante.
Pour résoudre ce problème, désactivez les fonctions relatives à l'économie 
d'énergie puis, numérisez à nouveau vos documents.


-------------------------------------------------------------
4. Utilisation de l'adaptateur SCSI Adaptec 
-------------------------------------------------------------

Pour en savoir plus sur les adapteurs SCSI compatibles, consultez l'adresse URL suivante : 

http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html

---------------------------------------------------
5. Remarques concernant le raccordement de plusieurs scanners au même PC
---------------------------------------------------

Sous Windows 2000, ce logiciel ne prend pas en charge plusieurs périphériques.

Ce logiciel ne prend pas en charge plusieurs périphériques raccordés à une interface 
USB.


---------------------------------------------------
6. Remarques concernant la fonctionnalité de numérisation recto verso
---------------------------------------------------

Pour que vous puissiez utiliser la fonctionnalité de numérisation recto verso, votre 
application doit prendre en charge la numérisation en continu des images.

Par conséquent, la numérisation recto verso peut être impossible avec certaines 
applications même si elle activée. 


---------------------------------------------------
7. Remarques concernant la spécification de la zone de balayage
---------------------------------------------------

La zone de balayage peut être spécifiée à l'aide de trois unités : le millimètre (mm), 
le pouce et le pixel. Cependant, veuillez remarquer qu'un écart maximal de 32 pixels 
est possible pour chaque ligne. 


---------------------------------------------------
8. Remarques concernant les bourrages de papier 
---------------------------------------------------

Lorsqu'un bourrage papier survient, un message d'erreur à cet effet s'affiche.
 
Retirez le papier coincé et cliquez sur OK dans la boîte présentant le message d'erreur  
pour réinitialiser le logiciel et reprendre la numérisation. 

En mode de numérisation recto (le mode recto verso n'est pas sélectionné), si bourrage 
papier survient lorsque la partie supérieure d'une page est en cours de numérisation, 
une page supplémentaire peut être éjectée lorsque vous cliquez sur bouton OK dans 
la boîte de dialogue présentant le message d'erreur. Dans ce cas, remettez la page 
éjectée dans le bac d'alimentation et tentez de reprendre la numérisation.


---------------------------------------------------
9. Remarques concernant la numérisation en 256 et en 8 couleurs
---------------------------------------------------

Ce logiciel prend en charge 256 et 8 couleurs. Cependant, certaines applications ne 
prennent pas en charge ces profondeurs de couleur. En particulier, Adobe PhotoShop 
et Adobe Acrobat et Kodak Imaging les interprètent mal et produisent des images noires. 
Sous les systèmes d'exploitation Windows, nous vous recommandons d'utiliser Image 
Professional 2.6, Imaging ou ScandAll2001 V.4.0 (ou plus évoluée) lorsqu'une de ces 
deux profondeurs de couleur est sélectionnée. Vous pouvez aussi éviter d'utiliser 
256 et 8 couleurs si vous n'en avez pas besoin.


---------------------------------------------------
10. Détection automatique de la taille et du désalignement 
---------------------------------------------------

Ce pilote intègre une fonction qui détecte automatiquement le désalignement d'un 
document et le corrige à la sortie. Cependant, certaines applications ne supportent 
pas cette fonction et peuvent ne pas fonctionner correctement ou produire une image 
altérée. Les applications suivantes posent problème; si vous les utilisez, désactivez 
la fonction [Détection automatique de la taille et du désalignement] : 
 - Adobe Photoshop
 - Adobe Acrobat
 - Kodak Imaging


---------------------------------------------------
11. Remarques concernant la détection automatique du format de page
---------------------------------------------------

Si vous utilisez la fonctionnalité Demi-teintes, SSE ou Séparation automatique 
lorsque la détection automatique du format de page est active, il peut y avoir conflit 
entre une des trois premières fonctionnalités et la dernière. 
Si les pixels blancs sont adéquatement détectés, l'image produite est généralement 
correcte. Sinon, l'image est entourée d'un cadre noir. Ce problème est dû à la nature 
des fonctionnalités Demi-teintes, SEE et Séparation automatique, qui assurent le 
remplissage avec des pixels noirs et blancs, ainsi qu'aux limitations de la 
fonctionnalité de détection automatique du format de page.


---------------------------------------------------
12. Note à propos de l'utilisation d'Adobe Acrobat
---------------------------------------------------

Les paramètres d'Acrobat annulant ceux définis dans les options "Résolution", 
"Type de numérisation" et "Mode image", ceux-ci peuvent ne pas être indiqués.
Les fonctions suivantes ne peuvent être exploitées :
  - "256 couleurs" ou "8 couleurs"
  - Détection automatique du format de page
  - "Degrés de rotation" si la fonction "Détection de fin de page" est cochée
  - Numérisation Longue Page


---------------------------------------------------
13. Remarques concernant les coupures d'alimentation en cours de numérisation
---------------------------------------------------

Si le cordon d'alimentation ou le câble d'interface du scanner est débranché en cours 
de numérisation, l'exécution de ce logiciel peut prendre fin anormalement. Par 
conséquent, vous ne devez pas les débrancher pendant que le scanner fonctionne.


---------------------------------------------------
14. Remarques concernant la police système
---------------------------------------------------

Dans les boîtes de dialogue de ce logiciel, certaines chaînes sont tronquées lorsque 
la police système sélectionnée est trop grande. Ce problème dépend du système 
d'exploitation, de l'accélérateur graphique et du pilote d'affichage que vous 
utilisez. Sélectionnez une police système plus petite pour résoudre ce problème.


---------------------------------------------------
15.  Remarques concernant les paramètres du BIOS SCSI
---------------------------------------------------

Lorsque vous utilisez ce logiciel, la valeur du paramètre DISCONNECT de l'adaptateur 
SCSI doit être valide.

Pour les adaptateurs SCSI décrits à la section 4 précédente, il n'est pas nécessaire 
de régler ce paramètre, car la valeur "Enable" est fixée par défaut.
  
Pour des détails sur le réglage de ce paramètre, veuillez consulter le manuel 
d'instructions fourni avec votre adaptateur SCSI.   


---------------------------------------------------
16. Remarques concernant le contrôle des tâches en mode mémoire cache
---------------------------------------------------

Avec les scanners fi-4860C, fi-4990C et M4099D, les options [Utiliser les deux 
mémoires] ou [Utiliser la mémoire du scanner] sont accessibles en mode mémoire dans 
la boîte de dialogue présentant les options du logiciel. Cependant, si l'option 
[Utiliser les deux mémoires] ou [Utiliser la mémoire du scanner] est sélectionnée, 
l'option [Contrôle des tâches] est ignorée dans cette boîte de dialogue.


---------------------------------------------------
17. À propos des réglages de la Mémoire cache pour la saisie du nombre de feuilles 
     à numériser
---------------------------------------------------

Si vous décidez de numériser des documents en saisissant le nombre de feuilles 
(Compteur de pages) à numériser depuis votre application, sous [Mode mémoire cache], 
sélectionnez une option différente de [Utiliser la mémoire du scanneur] ou  [Utiliser 
les deux mémoires].


---------------------------------------------------
18. Remarques concernant la Sauter les pages vierges 
---------------------------------------------------

Si la dernière page numérisée est vierge et que l'option [Sauter les pages vierges] 
a été activée, parfois, la boîte de dialogue Pilote Twain se fermera après que la 
page vierge ai été supprimée.


---------------------------------------------------
19. À propos de la numérisation d'une page longue doublée d'un surbalayage
---------------------------------------------------

Si vous décidez d'activer Surbalayage ou Détection Automatique du format de page lors 
de la numérisation d'une page longue, la longueur maximale sera réduite selon la zone 
du surbalayage.


---------------------------------------------------
20. Notes à propos de l'option SDTC
---------------------------------------------------

Si vous numérisez vos documents en activant Fond noir, d'une part, et Noir et blanc 
et Mode SDTC dans la rubrique Mode Image, d'autre part, les images numérisées 
risquent de ne pas être satisfaisantes. 
Le cas échéant, réglez la Variance DTC sur 1 ou 3 dans la rubrique SDTC de la boîte 
de dialogue Avancé puis, numérisez à nouveau vos documents.

---------------------------------------------------
21. Utilisation hautement sécuritaire obligatoire
---------------------------------------------------

Ce produit a été conçu, développé et fabriqué pour des utilisations générales, 
comprenant, notamment, l'utilisation générale dans des bureaux, l'utilisation 
personnelle, l'utilisation à domicile et l'utilisateur courante en milieu industriel. 
Cependant, ce produit n'a pas été conçu, développé et fabriqué pour l'utilisation 
dans des environnements pouvant présenter des risques et des dangers pour la vie à 
moins que des mesures de sécurité extrêmement contraignantes soient prises, peuvent 
directement conduire à la mort, à des blessures personnelles, à des dommages physiques 
graves ou à toute autre perte, notamment, les centres de commande des réacteurs 
nucléaires dans les installations atomiques, les installations de contrôle 
automatique du trafic aérien, les installations de contrôle du trafic aérien, les 
centres de contrôle des opérations de transport de masse, les installations 
d'instrumentation médicale de soutien vital et les centres de contrôle du lancement 
des missiles des systèmes d'armement. Vous ne devez pas utiliser ce produit sans 
prendre les mesures requises pour assurer une utilisation hautement sécuritaire. En 
outre, PFU (ou toute autre société affiliée) n'est pas responsable envers le client 
ou tout tiers de tout dommage ou réclamation associé à l'utilisation hautement 
sécuritaire obligatoire du produit.


------------------------------------------------------------------------
Ce produit utilise le composant suivant.

libtiff

Copyright (c) 1988-1997 Sam Leffler

Copyright (c) 1991-1997 Silicon Graphics, Inc.

Permission to use, copy, modify, distribute, and sell this software and its documentation for any purpose is hereby granted without fee, provided that (i) the above copyright notices and this permission notice appear in all copies of the software and related documentation, and (ii) the names of Sam Leffler and Silicon Graphics may not be used in any advertising or publicity relating to the software without the specific, prior written permission of Sam Leffler and Silicon Graphics.

THE SOFTWARE IS PROVIDED "AS-IS" AND WITHOUT WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR OTHERWISE, INCLUDING WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. 

IN NO EVENT SHALL SAM LEFFLER OR SILICON GRAPHICS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND, OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER OR NOT ADVISED OF THE POSSIBILITY OF DAMAGE, AND ON ANY THEORY OF LIABILITY, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
------------------------------------------------------------------------
Microsoft et  Windows sont des marques déposées de Microsoft Corporation aux 
Etats-Unis et/ou dans d'autres pays.
Les autres noms de société ou de produit sont des marques de commerce ou des 
marques déposées d'entreprises individuelles.

