         --------------------------------------------------------
                        TWAIN Datenquelle Software
                            < 32-bit version >
                              LIESMICH Datei
                            2. November, 2012
                           Version 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012


Bitte lesen Sie diese Datei bevor Sie das Produkt benutzen.  Diese Datei 
enthält wichtige Hinweise und ebenso die aktuellsten Zusatzinformationen,
die nicht in der Online-Hilfe beinhaltet sind.

------------------------------------------------------------------------
Inhalt 
------------------------------------------------------------------------
1. Systemanforderungen
2. Installation
3. Hinweise zur Energieverwaltung
4. Wenn Sie den von Adaptec hergestellten SCSI-Adapter benutzen
5. Hinweise für den Anschluss von zwei oder mehreren Scanner-Geräten an den
   selben PC.
6. Hinweise zum Duplex-Scannen
7. Hinweise zur Bestimmung des Scanbereiches 
8. Hinweise zu Papierstaus 
9. Hinweise zu 256 und 8 Farben
10. Vorsicht bei der Automatische Größen- und Fehlwinkelerkennung
11. Hinweise zur automatische Papiergrößenerkennug
12. Hinweise zur Benutzung von Adobe Acrobat
13. Während des Scannens wird das Gerät abgeschalten
14. Hinweise zum System Font
15. Hinweise zur SCSI BIOS Einstellung
16. Hinweise zur Auftragskontrolle im Speicherverwaltungs-Modus
17. Über die Einstellungen der Seitenzahl und des Speichermodus
18. Hinweise zu Leere Seiten überspringen
19. Über den Gebrauch der Funktion Überlänge kombiniert mit Scanbereich
20. Hinweis zur Benutzung von SDTC
21. Nutzung in Hochsicherheitsbereichen

-------------------------------------------------------------
1. Systemanforderungen
-------------------------------------------------------------

Diese Software benötigt folgende Umgebungsvoraussetzungen
 1) Zebtraleinheit
     Intel(R) Pentium(R) Prozesser oder kompatible Prozessoren
     die von SCSI-2 oder USB 1.1/2.0 unterstützt werden. 
     
  2) Betriebssystem
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

 - Für den auf der SETUP DISK Media vorhandenen Installer
   Legen Sie die SETUP DISK ein und folge Sie ab dem Startdialog den Bildschirmanweisungen.

 - Wenn der Istaller über Internet oder ein anderes Medium benutzt wird
   Führen Sie "setup.exe" aus und folgen Sie den Bildschirmanweisungen.

 - Bevor Sie das Programm installieren, melden Sie sich bitte als Benutzer mit 
   Administrator-Rechten an.


-----------------------------------------------------------------
3. Hiweise zur Energieverwaltung
-----------------------------------------------------------------

Wenn der PC in den Standby- oder Energiesparmodus eintritt, während der an den PC 
angeschlossene Scanner Dokumente scannt, führt dies eventuell zu einem Fehlschlagen 
des Scannens, da die Kommunikation zwischen PC und Scanner unterbrochen wird.
Um dieses Problem zu vermeiden, deaktivieren Sie bitte den Energiesparmodus 
und scannen dann die Dokumente erneut.


----------------------------------------------------------------
4. Wenn Sie den von Adaptec hergestellten SCSI-Adapter benutzen 
----------------------------------------------------------------

Informationen über kompatible SCSI-Adapter finden Sie unter der folgenden URL: 

http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html

--------------------------------------------------------------------------------------
5. Hinweise für den Anschluss von zwei oder mehreren Scanner-Geräten an den selben PC
--------------------------------------------------------------------------------------

Mit Windows2000, Unterstützt diese Software nicht mehrfache Geräte.

Wenn die USB-Schnittstelle verwendet wird, unterstützt diese Software nicht mehrfache 
Geräte.


---------------------------------------------------
6. Hinweise zum Duplex-Scannen
---------------------------------------------------

um die Duplex-Funktion dieser Software zu nutzen, muss die Anwendung die Sie benutzen 
die "fortlaufend Scannen" Funktion unterstützen.

Folgendermaßen können die Duplex-Bilddaten abhängig von der Anwendung nicht gescannt 
werden, auch wenn Duplex-Scannen ausgewählt ist. 


---------------------------------------------------
7. Hinweise zur Bestimmung des Scanbereiches
---------------------------------------------------

Der Scanbereich kann mit drei verschiedenen Einheiten bestimmt werden: Millimeter 
(mm), Inch, und Pixel. Bitte beachte Sie jedoch, dass der Scanbereich eine 
Fehlabweichung von maximal 32 Pixeln pro Zeile (für jede Einheit) aufweisen kan. 


---------------------------------------------------
8. Hinweise zu Papierstaus
---------------------------------------------------

Wenn es zu einem Papierstau kommt, wird folgende Fehlermeldung abgezeigt: 
"Papierstau" wird angezeigt.
 
Nachdem das eingeklemmte Dokumet entfern wurde und die OK Taste im Fehlermeldungs-
dialog gedrückt wurde, ist die Software wieder Eingabebereit und das Scannen kann
gestartet werden.

Für das Simplex-Scannen (Duplex-Scannen ist nicht ausgewählt) kann es vorkommen, 
dass ein extra Dokument mit dem Drücken der Ok Taste ausgegeben wird wenn es zu einem
Papierstau kommt während das erste (obere) Dokument gescannt wird. 
In diesem Fall legen Sie das extra ausgegebene Dokument zurück auf den Stapel und 
starten Sie den Scanvorgang erneut.


---------------------------------------------------
9. Hinweise zu 256 und 8 Farben
---------------------------------------------------

Diese Software unterstützt 256 und 8 Farben. Wir wissen dass einige 
Softwareanwendungen diese beiden Funktionen nicht unterstützen.
Zu diesen zähle: 
Adobe PhotoShop und Adobe Acrobat und Kodak Imaging, die nur ein schwarzes Bild 
erzeugen.
Wie empfehlen Ihnen,  Image Professional 2.6 oder Bildverarbeitungsprogramme im 
Windows BS und ScandAll2001 V.4.0 (oder später) für diese beiden Farbfunktionen zu 
verwenden. Oder benutzen Sie nicht den 256 und 8 Farbmodus, wenn Sie diesen nicht 
benötigen.


---------------------------------------------------
10. Vorsicht bei der Automatische Größen- und Fehlwinkelerkennung
---------------------------------------------------

Dieser Treiber unterstützt die automatische Papiergrößen- und Fehlwinkelerkennung. 
Bitte beachten Sie, daß einige Anwendungen diese Funktionen nicht unterstützen und 
somit unter Umständen nicht richtig arbeiten oder das Bildergebnis verfälschen. Bei 
folgenden Anwendungen wurden Probleme festgestellt:
  - Adobe Photoshop
  - Adobe Acrobat
  - Kodak Imaging
Sollten Sie diese benutzen, deaktivieren Sie bitte die Automatische Papiergrößen- 
und Fehlwinkelerkennung.


---------------------------------------------------
11. Hinweise zur automatische Papiergrößenerkennug
---------------------------------------------------

Wenn Rasterbild (Halbton), SEE oder der automatische Separations-Modus ausgewählt 
und die automatische Papiergrößenerkennung aktiviert ist.
Es hängt davon ab, ob schwarze/weiße Pixel und die Papiergröße während des Scannens 
erkannt werden. Wenn weiße Pixel erkannt werden, erstellt dies für gewöhnlich wie 
erwartet korrekte Bilder. Ansonsten können keine korrekten Bilder erstellt werden, 
die von einem schwarzen Rahmen umgeben sind. Das ist die Natur von Halbton, SEE und 
der automatischen Separation, dass Bilder mit schwarzen und weißen Pixeln gefüllt 
werden. Und dies ist ebenso die Begrenzung der automatischen Papiergrößenerkennung.


---------------------------------------------------
12. Hinweise zur Benutzung von Adobe Acrobat
---------------------------------------------------
Die Grundeinstellungen von Acrobat überschreiben die vorherigen Einstellungen für 
"Auflösung", Scan-Typ" und "Bildmodus".
Folgende Funktionen können nicht verwendet werden.
  - "256 Farben" und "8 Farben"
  - Automatische Papiergrößenerkennung
  - "Drehungsgrad" Auswahl wenn "Seitenende-Erkennung" verwendet wird.
  - Scannen von Überlängen


-----------------------------------------------------
13. Während des Scannens wird das Gerät abgeschalten
-----------------------------------------------------

Wenn während des Scannens das Netz- oder Schnittstellenkabel entfernt wird, beendet 
dies die Software auf eine nicht zulässige Weise.
Entfernen Sie daher diese nicht während des Scannens.


---------------------------------------------------
14. Hinweise zum System Font
---------------------------------------------------

Einige Strings von Dialogfeldern dieser Software werden abgeschnitten, Wenn der
System-font in GROß oder GRÖßER geädert wird. Dies hängt vom benutzten BS und dem 
Grafikbeschleuniger und den Anzeigen Treibern ab. 
In diesem Fall, wählen Sie einen kleineren System Font für eine normale Anzeige.   


---------------------------------------------------
15.  Hinweise zur SCSI BIOS Einstellung
---------------------------------------------------

Wenn Sie die Software benutzen, muss ebenso die Einstellung für "VERBIDUNG ABBRECHEN" 
der SCSI-Karte gültig sein.

Wenn Sie die in "4" beschriebenen SCSI-Karten verwenden, ist diese Änderung nicht 
nötig, da die Standarteinstellung bereits auf "VERBINDUNG ABBRECHEN Aktiviert" 
gesetzt ist.
  
Für Details bezüglich der Einstellungs-Verfahrensweise, siehe das der benutzten 
SCSI-Karte beigefügte Handbuch.   


----------------------------------------------------------------
16. Hinweise zur Auftragskontrolle im Speicherverwaltungs-Modus
----------------------------------------------------------------

Für einige Scanner-Geräte (fi-4860C, fi-4990C, und M4099D), erscheint "Beide Speicher 
benutzen" oder "Speicher des Scaners benutzen" im "Speicherverwaltungs-Modus" des 
Software Optionsdialoges. Aber wenn "Beide Speicher benutzen" oder "Speicher des 
Scanners benutzen" ausgewählt ist, wird die "Auftragskontroll" Einstellung im selben 
Optionsdialog ignoriert.


----------------------------------------------------------------
17. Über die Einstellungen der Seitenzahl und des Speichermodus
----------------------------------------------------------------

Wenn Sie über die Anwendung die Einstellung der Seitenzahl für das Scannen festlegen, 
lautet die Einstellung für den Speichermodus im [Option] Bildschirm "Speicher im 
Scanner verwenden". Stellen Sie bitte etwas anderes als "Beide Speicher verwenden" 
ein.


---------------------------------------------------
18. Nutzung in Hochsicherheitsbereichen
---------------------------------------------------

Wenn die Funktion [Leere Seiten überspringen] aktiviert 
ist, kann es vorkommen dass der [TWAIN Treiber] Dialog geschlossen wird wenn es sich 
bei der letzten Seite des Dokumentes um eine leere Seite handeln sollte.


---------------------------------------------------
19. Über den Gebrauch der Funktion Überlänge kombiniert mit Scanbereich
---------------------------------------------------

Wenn die Funktion Überscan/Automatische Papiergrößenerkennung zusammen mit Scannen 
von Überlängen ausgewählt wurde, wird die maximale Papiergröße um die Überscandistanz 
reduziert.


---------------------------------------------------
20. Hinweis zur Benutzung von SDTC
---------------------------------------------------

Wenn Sie für das Scannen den Bildmodus  "Schwarz/Weiß"  und den "SDTC-Modus" 
verwenden, kann das gescannte Bild eventuell nicht korrekt ausgegeben werden. 
Sollte dies der Fall sein, legen Sie bitte für die "DTC-Varianz" den Wert 1 oder 3 
im Erweitert Dialogfeld fest und scannen dann die Dokumente erneut.


---------------------------------------------------
21. Nutzung in Hochsicherheitsbereichen
---------------------------------------------------

Dieses Produkt wurde zur allgemeinen Verwendung entworfen, entwickelt und 
hergestellt, insbesondere für folgende Bereiche: In allgemeinen Büroeinrichtugen, 
zum persönlichen Gebrauch und im Haushalt.
Das Produkt wurde NICHT für den Einsatz in Umgebunge entworfen, entwickelt und 
hergestellt, in denen besonders hohe Risiken bestehen, wie Gefahr für Leib und Leben 
oder andere Gefahren, für die extrem hohe Sicherheitsvorkehrungen erforderlich sind 
und die andernfalls zu Todesfolge, Personenschäden oder sonstigen Verlusten führen 
könnten (im Folgenden "Verwendung in Hochsicherheitsbereichen" genannt). 
Zu diesen Umgebungen gehören u. a. (aber nicht darauf beschränkt) Kontrollsysteme 
für Kontrollreaktoren, Flugzeugsteuerungen, Steuerungen für den Betrieb von 
öffentlichen Verkehrsmitteln, lebenserhaltende Systeme und 
Waffensteuerungssysteme.
Verwenden Sie dieses Produkt NIEMALS, ohne sichergestellt zu haben, dass alle 
Sicherheitsvorkehrungen in ausreichendem Maße getroffen wurden, so dass sie den 
Anforderungen für die Verwendung in Hochsicherheits-bereichen entsprechen. Sollten 
Sie dieses Produkt in Hochsicherheitsbereichen verwenden wollen, setzen Sie sich vor 
dem Gebrauch mit unserem zuständigen Vertriebsmitarbeiter in Verbindung.
PFU LIMITED übernimmt keine Verantwortung und Haftung für Schäden, die durch den 
Gebrauch dieses Produkts durch den Benutzer in Hochsicherheitsanwendungen entstanden 
sind und ferner werden keine Ansprüche auf Entschädigung durch den Benutzer oder einer 
dritte Partei anerkannt.


-----------------------------------------------------------------------
Folgende Komponente wird in diesem Produkt verwendet.

libtiff

Copyright (c) 1988-1997 Sam Leffler

Copyright (c) 1991-1997 Silicon Graphics, Inc.

Permission to use, copy, modify, distribute, and sell this software and its documentation for any purpose is hereby granted without fee, provided that (i) the above copyright notices and this permission notice appear in all copies of the software and related documentation, and (ii) the names of Sam Leffler and Silicon Graphics may not be used in any advertising or publicity relating to the software without the specific, prior written permission of Sam Leffler and Silicon Graphics.

THE SOFTWARE IS PROVIDED "AS-IS" AND WITHOUT WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR OTHERWISE, INCLUDING WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. 

IN NO EVENT SHALL SAM LEFFLER OR SILICON GRAPHICS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND, OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER OR NOT ADVISED OF THE POSSIBILITY OF DAMAGE, AND ON ANY THEORY OF LIABILITY, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
-----------------------------------------------------------------------
Microsoft und  Windows sind eingetragene Warenzeichen der Microsoft Corporation, 
USA und/oder anderen Ländern.
Andere Firmen- und Produktnamen sind Warenzeichen oder eingetragene Warenzeichen der 
jeweiligen Firmen. 

