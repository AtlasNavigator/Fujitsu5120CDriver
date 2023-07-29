         --------------------------------------------------------
            Logiciel de gestion de la source de donn�es TWAIN
                           < version 32 bits >
                              Fichier README
                             2 novembre 2012
                           Version 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012


Veuillez lire ce fichier avant d'utiliser le produit.  Ce fichier comprend 
des remarques importantes ainsi que les informations les plus r�centes 
non comprises dans l'aide en ligne.

------------------------------------------------------------------------
Table des mati�res 
------------------------------------------------------------------------

1. Configuration syst�me requise
2. Installation
3. Remarques concernant la gestion de l'alimentation
4. Utilisation de l'adaptateur SCSI Adaptec
5. Remarques concernant le raccordement de plusieurs scanners au m�me PC
6. Remarques concernant la fonctionnalit� de num�risation recto verso
7. Remarques concernant la sp�cification de la zone de balayage 
8. Remarques concernant les bourrages de papier
9. Remarques concernant la num�risation en 256 et en 8 couleurs
10. D�tection automatique de la taille et du d�salignement 
11. Remarques concernant la d�tection automatique du format de page
12. Note � propos de l'utilisation d'Adobe Acrobat
13. Remarques concernant les coupures d'alimentation en cours de num�risation
14. Remarques concernant la police syst�me
15. Remarques concernant les param�tres du BIOS SCSI
16. Remarques concernant le contr�le des t�ches en mode m�moire cache
17. � propos des r�glages de la M�moire cache pour la saisie du nombre de feuilles 
     � num�riser
18. Remarques concernant la Sauter les pages vierges
19. � propos de la num�risation d'une page longue doubl�e d'un surbalayage
20. Notes � propos de l'option SDTC
21. Utilisation hautement s�curitaire obligatoire


-------------------------------------------------------------
1. Configuration syst�me requise
-------------------------------------------------------------

Ce logiciel fonctionne dans les environnements suivants :

  1) UC
      Processeur Pentium(MD) d'Intel (MD) ou processeur compatible 
      avec les adaptateurs SCSI-2 ou USB 1.1/2.0
     
  2) Syst�me d'exploitation
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
   Ins�rez le SETUP DISK et suivez les instructions pr�sent�es dans la bo�te de dialogue 
   de d�marrage.

 - Si vous avez obtenu l'installateur par la voie du Web ou s'il figure sur un autre 
   support :
   Ex�cutez setup.exe et suivez les instructions qui apparaissent � l'�cran.

 - Pour pouvoir installer le programme, assurez-vous d'avoir ouvert une session 
   en tant qu'utilisateur avec des privil�ges d'Administrateur.


---------------------------------------------------
3. Remarques concernant la gestion de l'alimentation 
---------------------------------------------------

Si votre ordinateur est en mode Veille ou en mode Hibernation alors qu'une 
num�risation est en cours d'ex�cution, la transmission des donn�es risque 
d'�chouer et la num�risation, d'�tre insatisfaisante.
Pour r�soudre ce probl�me, d�sactivez les fonctions relatives � l'�conomie 
d'�nergie puis, num�risez � nouveau vos documents.


-------------------------------------------------------------
4. Utilisation de l'adaptateur SCSI Adaptec 
-------------------------------------------------------------

Pour en savoir plus sur les adapteurs SCSI compatibles, consultez l'adresse URL suivante : 

http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html

---------------------------------------------------
5. Remarques concernant le raccordement de plusieurs scanners au m�me PC
---------------------------------------------------

Sous Windows 2000, ce logiciel ne prend pas en charge plusieurs p�riph�riques.

Ce logiciel ne prend pas en charge plusieurs p�riph�riques raccord�s � une interface 
USB.


---------------------------------------------------
6. Remarques concernant la fonctionnalit� de num�risation recto verso
---------------------------------------------------

Pour que vous puissiez utiliser la fonctionnalit� de num�risation recto verso, votre 
application doit prendre en charge la num�risation en continu des images.

Par cons�quent, la num�risation recto verso peut �tre impossible avec certaines 
applications m�me si elle activ�e. 


---------------------------------------------------
7. Remarques concernant la sp�cification de la zone de balayage
---------------------------------------------------

La zone de balayage peut �tre sp�cifi�e � l'aide de trois unit�s : le millim�tre (mm), 
le pouce et le pixel. Cependant, veuillez remarquer qu'un �cart maximal de 32 pixels 
est possible pour chaque ligne. 


---------------------------------------------------
8. Remarques concernant les bourrages de papier 
---------------------------------------------------

Lorsqu'un bourrage papier survient, un message d'erreur � cet effet s'affiche.
 
Retirez le papier coinc� et cliquez sur OK dans la bo�te pr�sentant le message d'erreur  
pour r�initialiser le logiciel et reprendre la num�risation. 

En mode de num�risation recto (le mode recto verso n'est pas s�lectionn�), si bourrage 
papier survient lorsque la partie sup�rieure d'une page est en cours de num�risation, 
une page suppl�mentaire peut �tre �ject�e lorsque vous cliquez sur bouton OK dans 
la bo�te de dialogue pr�sentant le message d'erreur. Dans ce cas, remettez la page 
�ject�e dans le bac d'alimentation et tentez de reprendre la num�risation.


---------------------------------------------------
9. Remarques concernant la num�risation en 256 et en 8 couleurs
---------------------------------------------------

Ce logiciel prend en charge 256 et 8 couleurs. Cependant, certaines applications ne 
prennent pas en charge ces profondeurs de couleur. En particulier, Adobe PhotoShop 
et Adobe Acrobat et Kodak Imaging les interpr�tent mal et produisent des images noires. 
Sous les syst�mes d'exploitation Windows, nous vous recommandons d'utiliser Image 
Professional 2.6, Imaging ou ScandAll2001 V.4.0 (ou plus �volu�e) lorsqu'une de ces 
deux profondeurs de couleur est s�lectionn�e. Vous pouvez aussi �viter d'utiliser 
256 et 8 couleurs si vous n'en avez pas besoin.


---------------------------------------------------
10. D�tection automatique de la taille et du d�salignement 
---------------------------------------------------

Ce pilote int�gre une fonction qui d�tecte automatiquement le d�salignement d'un 
document et le corrige � la sortie. Cependant, certaines applications ne supportent 
pas cette fonction et peuvent ne pas fonctionner correctement ou produire une image 
alt�r�e. Les applications suivantes posent probl�me; si vous les utilisez, d�sactivez 
la fonction [D�tection automatique de la taille et du d�salignement] : 
 - Adobe Photoshop
 - Adobe Acrobat
 - Kodak Imaging


---------------------------------------------------
11. Remarques concernant la d�tection automatique du format de page
---------------------------------------------------

Si vous utilisez la fonctionnalit� Demi-teintes, SSE ou S�paration automatique 
lorsque la d�tection automatique du format de page est active, il peut y avoir conflit 
entre une des trois premi�res fonctionnalit�s et la derni�re. 
Si les pixels blancs sont ad�quatement d�tect�s, l'image produite est g�n�ralement 
correcte. Sinon, l'image est entour�e d'un cadre noir. Ce probl�me est d� � la nature 
des fonctionnalit�s Demi-teintes, SEE et S�paration automatique, qui assurent le 
remplissage avec des pixels noirs et blancs, ainsi qu'aux limitations de la 
fonctionnalit� de d�tection automatique du format de page.


---------------------------------------------------
12. Note � propos de l'utilisation d'Adobe Acrobat
---------------------------------------------------

Les param�tres d'Acrobat annulant ceux d�finis dans les options "R�solution", 
"Type de num�risation" et "Mode image", ceux-ci peuvent ne pas �tre indiqu�s.
Les fonctions suivantes ne peuvent �tre exploit�es :
  - "256 couleurs" ou "8 couleurs"
  - D�tection automatique du format de page
  - "Degr�s de rotation" si la fonction "D�tection de fin de page" est coch�e
  - Num�risation Longue Page


---------------------------------------------------
13. Remarques concernant les coupures d'alimentation en cours de num�risation
---------------------------------------------------

Si le cordon d'alimentation ou le c�ble d'interface du scanner est d�branch� en cours 
de num�risation, l'ex�cution de ce logiciel peut prendre fin anormalement. Par 
cons�quent, vous ne devez pas les d�brancher pendant que le scanner fonctionne.


---------------------------------------------------
14. Remarques concernant la police syst�me
---------------------------------------------------

Dans les bo�tes de dialogue de ce logiciel, certaines cha�nes sont tronqu�es lorsque 
la police syst�me s�lectionn�e est trop grande. Ce probl�me d�pend du syst�me 
d'exploitation, de l'acc�l�rateur graphique et du pilote d'affichage que vous 
utilisez. S�lectionnez une police syst�me plus petite pour r�soudre ce probl�me.


---------------------------------------------------
15.  Remarques concernant les param�tres du BIOS SCSI
---------------------------------------------------

Lorsque vous utilisez ce logiciel, la valeur du param�tre DISCONNECT de l'adaptateur 
SCSI doit �tre valide.

Pour les adaptateurs SCSI d�crits � la section 4 pr�c�dente, il n'est pas n�cessaire 
de r�gler ce param�tre, car la valeur "Enable" est fix�e par d�faut.
  
Pour des d�tails sur le r�glage de ce param�tre, veuillez consulter le manuel 
d'instructions fourni avec votre adaptateur SCSI.   


---------------------------------------------------
16. Remarques concernant le contr�le des t�ches en mode m�moire cache
---------------------------------------------------

Avec les scanners fi-4860C, fi-4990C et M4099D, les options [Utiliser les deux 
m�moires] ou [Utiliser la m�moire du scanner] sont accessibles en mode m�moire dans 
la bo�te de dialogue pr�sentant les options du logiciel. Cependant, si l'option 
[Utiliser les deux m�moires] ou [Utiliser la m�moire du scanner] est s�lectionn�e, 
l'option [Contr�le des t�ches] est ignor�e dans cette bo�te de dialogue.


---------------------------------------------------
17. � propos des r�glages de la M�moire cache pour la saisie du nombre de feuilles 
     � num�riser
---------------------------------------------------

Si vous d�cidez de num�riser des documents en saisissant le nombre de feuilles 
(Compteur de pages) � num�riser depuis votre application, sous [Mode m�moire cache], 
s�lectionnez une option diff�rente de [Utiliser la m�moire du scanneur] ou  [Utiliser 
les deux m�moires].


---------------------------------------------------
18. Remarques concernant la Sauter les pages vierges 
---------------------------------------------------

Si la derni�re page num�ris�e est vierge et que l'option [Sauter les pages vierges] 
a �t� activ�e, parfois, la bo�te de dialogue Pilote Twain se fermera apr�s que la 
page vierge ai �t� supprim�e.


---------------------------------------------------
19. � propos de la num�risation d'une page longue doubl�e d'un surbalayage
---------------------------------------------------

Si vous d�cidez d'activer Surbalayage ou D�tection Automatique du format de page lors 
de la num�risation d'une page longue, la longueur maximale sera r�duite selon la zone 
du surbalayage.


---------------------------------------------------
20. Notes � propos de l'option SDTC
---------------------------------------------------

Si vous num�risez vos documents en activant Fond noir, d'une part, et Noir et blanc 
et Mode SDTC dans la rubrique Mode Image, d'autre part, les images num�ris�es 
risquent de ne pas �tre satisfaisantes. 
Le cas �ch�ant, r�glez la Variance DTC sur 1 ou 3 dans la rubrique SDTC de la bo�te 
de dialogue Avanc� puis, num�risez � nouveau vos documents.

---------------------------------------------------
21. Utilisation hautement s�curitaire obligatoire
---------------------------------------------------

Ce produit a �t� con�u, d�velopp� et fabriqu� pour des utilisations g�n�rales, 
comprenant, notamment, l'utilisation g�n�rale dans des bureaux, l'utilisation 
personnelle, l'utilisation � domicile et l'utilisateur courante en milieu industriel. 
Cependant, ce produit n'a pas �t� con�u, d�velopp� et fabriqu� pour l'utilisation 
dans des environnements pouvant pr�senter des risques et des dangers pour la vie � 
moins que des mesures de s�curit� extr�mement contraignantes soient prises, peuvent 
directement conduire � la mort, � des blessures personnelles, � des dommages physiques 
graves ou � toute autre perte, notamment, les centres de commande des r�acteurs 
nucl�aires dans les installations atomiques, les installations de contr�le 
automatique du trafic a�rien, les installations de contr�le du trafic a�rien, les 
centres de contr�le des op�rations de transport de masse, les installations 
d'instrumentation m�dicale de soutien vital et les centres de contr�le du lancement 
des missiles des syst�mes d'armement. Vous ne devez pas utiliser ce produit sans 
prendre les mesures requises pour assurer une utilisation hautement s�curitaire. En 
outre, PFU (ou toute autre soci�t� affili�e) n'est pas responsable envers le client 
ou tout tiers de tout dommage ou r�clamation associ� � l'utilisation hautement 
s�curitaire obligatoire du produit.


------------------------------------------------------------------------
Ce produit utilise le composant suivant.

libtiff

Copyright (c) 1988-1997 Sam Leffler

Copyright (c) 1991-1997 Silicon Graphics, Inc.

Permission to use, copy, modify, distribute, and sell this software and its documentation for any purpose is hereby granted without fee, provided that (i) the above copyright notices and this permission notice appear in all copies of the software and related documentation, and (ii) the names of Sam Leffler and Silicon Graphics may not be used in any advertising or publicity relating to the software without the specific, prior written permission of Sam Leffler and Silicon Graphics.

THE SOFTWARE IS PROVIDED "AS-IS" AND WITHOUT WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR OTHERWISE, INCLUDING WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. 

IN NO EVENT SHALL SAM LEFFLER OR SILICON GRAPHICS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND, OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER OR NOT ADVISED OF THE POSSIBILITY OF DAMAGE, AND ON ANY THEORY OF LIABILITY, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
------------------------------------------------------------------------
Microsoft et  Windows sont des marques d�pos�es de Microsoft Corporation aux 
Etats-Unis et/ou dans d'autres pays.
Les autres noms de soci�t� ou de produit sont des marques de commerce ou des 
marques d�pos�es d'entreprises individuelles.

