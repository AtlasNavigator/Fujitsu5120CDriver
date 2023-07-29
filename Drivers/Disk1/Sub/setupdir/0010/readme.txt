         --------------------------------------------------------
                    Software della sorgente dati TWAIN
                           <versione a 32 bit>
                               File LEGGIMI
                             2 novembre 2012
                           Versione 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012


Leggere il contenuto del presente file prima di utilizzare questo prodotto.  Il file 
contiene informazioni importanti, oltre agli ultimi aggiornamenti non compresi nella 
Guida in linea.

------------------------------------------------------------------------
Sommario
------------------------------------------------------------------------

1. Requisiti di sistema
2. Installazione
3. Informazioni sul risparmio di energia
4. Uso di un adattatore SCSI Adaptec
5. Informazioni sull'uso di due o più dispositivi di scansione sullo stesso PC
6. Informazioni sulla funzione di scansione fronte-retro
7. Informazioni sulla definizione dell'area di scansione
8. Informazioni sull'inceppamento dei documenti 
9. Informazioni sulle modalità a 256 colori e a 8 colori
10. Rilevazione automatica di dimensione e angolazione
11. Informazioni sul rilevamento di dimensione pagina automatico
12. Note usate per Adobe Acrobat
13. Informazioni sullo spegnimento durante la scansione
14. Informazioni sui caratteri di sistema
15. Informazioni sull'impostazione SCSI BIOS
16. Informazioni sul controllo dei lavori con la modalità cache
17. Riguardo all'impostazione Modalità Cache quando si specificano i numeri dei fogli 
    da scansionare.
18. Informazioni sullo Saltare pagina bianca 
19. Riguardo l'uso della scansione Pagina lunga combinata con l'Overscan
20. Note usate per SDTC
21. Uso in situazioni che richiedono un alto grado di sicurezza


-------------------------------------------------------------
1. Requisiti di sistema
-------------------------------------------------------------

L'uso di questo software richiede quanto segue:

  1) CPU
     Processore Intel(R) Pentium(R) o processore compatibile
     supporto SCSI-2 o USB 1.1/2.0
     
  2) Sistema operativo
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
2. Installazione
-------------------------------------------------------------

 - Con programma di installazione contenuto nel supporto SETUP DISK
   Seguire le istruzioni fornite nella finestra di dialogo di avvio visualizzata dopo 
   l'inserimento del SETUP DISK.

 - Con programma di installazione scaricato dal Web o su altro supporto
   Eseguire "setup.exe" e seguire le istruzioni visualizzate.

 - Assicurarsi di accedere come utente con i diritti di "Administrator" per 
   installare il programma.


---------------------------------------------------
3. Informazioni sul risparmio di energia
---------------------------------------------------

Se un computer entra nel sistema standby o modalità sospensione mentre uno 
scanner sta scansionando dei documenti, la scansione può fallire a causa di 
una rottura delle comunicazioni dei dati.
Per evitare questo problema, disattivare le opzioni risparmio energia, e poi 
scansionare i documenti.


-------------------------------------------------------------
4. Uso di un adattatore SCSI Adaptec
-------------------------------------------------------------

Informazione riguardo gli adattatori collegati a SCSI è disponibile all'URL: 

http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html


-------------------------------------------------------------------------------
5. Informazioni sull'uso di due o più dispositivi di scansione sullo stesso PC
-------------------------------------------------------------------------------

In Windows 2000, questo software non è compatibile con l'uso di più dispositivi.

Se viene utilizzata l'interfaccia USB, questo software non è compatibile con l'uso 
di più dispositivi.


-----------------------------------------------------------
6. Informazioni sulla funzione di scansione fronte-retro
-----------------------------------------------------------

Per utilizzare la funzione di scansione fronte-retro con questo software, 
l'applicazione impiegata deve essere compatibile con la funzione di scansione 
continua dei dati di immagine.

Pertanto, a seconda dell'applicazione, è possibile che la scansione dei dati di 
immagine in fronte-retro non venga eseguita, anche se è stata impostata la scansione 
fronte-retro. 


-----------------------------------------------------------
7. Informazioni sulla definizione dell'area di scansione
-----------------------------------------------------------

L'area di scansione può essere definita mediante uno dei tre tipi di unità di misura 
disponibili: millimetri, pollici e pixel. Tuttavia,  l'area di scansione può 
presentare un margine di errore massimo di 32 pixel per riga per ciascuna unità. 


---------------------------------------------------
8. Informazioni sull'inceppamento dei documenti 
---------------------------------------------------

Se si verifica l'inceppamento di un documento viene visualizzato il messaggio "Carta inceppata".
 
Dopo la rimozione dei documenti inceppati e la selezione del pulsante OK nella finestra 
del messaggio di errore, vengono ripristinate le condizioni di immissione di dati 
del software ed è possibile avviare una nuova scansione. 

Tuttavia, durante la scansione su lato singolo (ossia, quando non è specificata la 
scansione fronte-retro), se l'inceppamento avviene durante la scansione della parte 
superiore del documento, è possibile che venga espulso un ulteriore documento tra 
quelli presenti nel vassoio quando viene selezionato il pulsante OK nella finestra 
del messaggio di errore.
In tal caso, reinserire il documento espulso nel vassoio e riavviare la scansione.


-----------------------------------------------------------
9. Informazioni sulle modalità a 256 colori e a 8 colori
-----------------------------------------------------------

Questo software è compatibile con le modalità a 256 colori e a 8 colori. È noto che 
alcune applicazioni software non supportano queste due modalità. Si tratta delle 
applicazioni Adobe PhotoShop e Adobe Acrobat e Kodak Imaging, le quali generano 
un'immagine interamente nera.
Per utilizzare queste due modalità, si consiglia di eseguire Image Professional 2.6 
o Imaging del sistema operativo Windows OS e ScandAll2001 V.4.0 (o superiore). In 
alternativa, se queste modalità non sono strettamente necessarie, evitare di 
utilizzarle.


-------------------------------------------------------------------
10. Rilevazione automatica di dimensione e angolazione
-------------------------------------------------------------------

Questo driver ha la funzione di rilevare automaticamente la dimensione e la angolazione 
di un documento e fornisce una corretta emissione. Tuttavia, alcune applicazioni non 
prestano assistenza a questa funzione e può darsi non funzioni correttamente, o 
l'immagine lanciata può danneggiarsi. le seguenti applicazioni presentano dei 
problemi. Se usate queste applicazioni, invalidate la funzione di [Rilevazione 
automatica di dimensione e di angolazione]
 - Adobe Photoshop
 - Adobe Acrobat
 - Kodak Imaging


-------------------------------------------------------------------
11. Informazioni sul rilevamento di dimensione pagina automatico
-------------------------------------------------------------------

Con le modalità di scansione Mezzi toni, SEE o Separazione automatica quando è attivato 
Rilevamento di dimensione pagina automatica,l'utilizzo dipende dal rilevamento dei 
pixel bianchi/neri e delle dimensioni della carta. 
Se vengono rilevati i pixel bianchi, l'immagine viene ottenuta in genere in maniera corretta.
In caso contrario, l'immagine non viene ottenuta correttamente e può apparire 
racchiusa da una cornice nera.
Ciò è dovuto alla natura delle funzioni Mezzi toni, SEE e Separazione automatica, 
le quali riempiono l'immagine di pixel bianchi/neri, e alle limitazioni della funzione 
Rilevamento di dimensione pagina automatica.


---------------------------------------------------
12. Note usate per Adobe Acrobat
---------------------------------------------------

Peché le impostazioni della "Risoluzione", del "Tipo di scansione" e del "Modo di 
immagine" sono valide per le impostazioni di Acrobat, le impostazioni precedenti non 
verranno mostrate.
Le seguenti funzioni non possono essere usate.
  - "256 Colori" o "8 Colori"
  - Rilevazione di dimensione pagina automatica
  - Selezionare il "Grado di rotazione" quando "Rilevazione di fine pagina" è 
    selezionata.
  - Scansione Pagina Lunga


----------------------------------------------------------
13. Informazioni sullo spegnimento durante la scansione
----------------------------------------------------------

Lo scollegamento del cavo di alimentazione o del cavo di interfaccia dello scanner 
durante la scansione può determinare una chiusura non corretta di questo software.
Pertanto, non rimuovere i suddetti cavi durante la scansione.


---------------------------------------------------
14. Informazioni sui caratteri di sistema
---------------------------------------------------

Se nel sistema sono impostati i caratteri GRANDI o di dimensioni maggiori, alcune 
delle stringhe di testo delle finestre di dialogo di questo software possono risultare 
tagliate. Ciò dipende dal sistema operativo, dall'acceleratore grafico e dai driver video in uso.  
In tal caso, selezionare caratteri di sistema più piccoli per ottenere una 
visualizzazione normale.   


---------------------------------------------------
15.  Informazioni sull'impostazione SCSI BIOS
---------------------------------------------------

Durante l'uso di questo software, è  necessario che l'impostazione DISCONNECT della scheda SCSI sia valida.

Se vengono utilizzate le schede SCSI descritte al  precedente punto 4, la modifica 
non è richiesta perché il valore di impostazione standard è già "DISCONNECT Enable".
  
Per i dettagli sulle procedure di impostazione, fare riferimento al manuale d'uso 
allegato alla scheda SCSI utilizzata.   


------------------------------------------------------------------
16. Informazioni sul controllo dei lavori con la modalità cache
------------------------------------------------------------------

Con alcuni dispositivi di scansione (fi-4860C, fi-4990C, M4099D), nella modalità 
cache della finestra di dialogo delle opzioni del software, viene visualizzata 
l'opzione "Usare ambedue le memorie" o "Usare memoria nello scanner".
Tuttavia, se viene selezionata l'opzione "Usare ambedue le memorie" o "Usare memoria 
nello scanner", l'impostazione di controllo dei lavori viene ignorata nella finestra 
di dialogo delle opzioni.


------------------------------------------------------------------
17. Riguardo all'impostazione Modalità Cache quando si specificano i numeri dei fogli 
    da scansionare
------------------------------------------------------------------

Quando si scansionano i documenti specificando il numero dei fogli (Contatore pagine) 
da scansionare nell'applicazione, nella "Modalità Cache", selezionare una 
impostazione diversa da "Usare la memoria nello scanner" o "Usare ambedue le memorie".


------------------------------------------------------------------
18. Informazioni sullo Saltare pagina bianca 
------------------------------------------------------------------

Quando la funzione "Saltare pagina bianca" è abilitata, se l'ultima pagina del 
documento scansionato è bianca, possono esserci casi in cui la finestra di dialogo 
"TWAIN driver" sia chiusa dopo che la pagina bianca è stata saltata.


------------------------------------------------------------------
19. Riguardo l'uso della scansione Pagina lunga combinata con l'Overscan
------------------------------------------------------------------

Se Sovrascansione/Rilevazione di dimensione pagina automatica è selezionata insieme 
a una scansione pagina lunga, il massimo della lunghezza pagina è ridotto dalla 
distanza di sovrascansione.


------------------------------------------------------------------
20. Note usate per SDTC
------------------------------------------------------------------

Se si scansionano documenti con "Sfondo nero" usando "Bianco e nero", "Modalità SDTC" e 
come Modalità immagine, le immagini documento scansionate potrebbero non essere generate 
correttamente. 
In questo caso, impostare "Varianza DTC" a 1 o 3 sotto SDTC nella finestra  Avanza e 
scansionare i documenti.


------------------------------------------------------------------
21. Uso in situazioni che richiedono un alto grado di sicurezza
------------------------------------------------------------------

Questo Prodotto è stato progettato, sviluppato e realizzato per un uso generale, 
compreso  l'uso in ambiente di lavoro, l'uso personale, l'uso domestico e l'uso 
ordinario industriale; tuttavia, non è stato progettato, sviluppato e realizzato per 
un uso che comporta rischi o pericoli gravi che, in assenza di misure di sicurezza 
estremamente efficaci, possono condurre a morte, ferimento e altri danni fisici o 
perdite (di seguito "Uso ad alto rischio per la sicurezza"), compresi tra l'altro 
il controllo di reattori nucleari negli impianti atomici nucleari, il controllo del 
volo di velivoli, il controllo del traffico aereo, il controllo operativo nei sistemi 
di trasporto di massa, il controllo di apparecchiature medicali di emergenza, il 
controllo del lancio di missili nei sistemi militari. 
Questo Prodotto non può essere utilizzato senza che vengano adottate le misure di 
sicurezza sufficienti richieste per l'Uso ad alto rischio per la sicurezza. 
Inoltre, PFU (o le altre società affiliate) non è responsabile nei confronti del 
Cliente e/o di terzi per eventuali azioni legali o richieste di risarcimento derivanti 
da controversie sull'Uso ad alto rischio per la sicurezza del Prodotto.


------------------------------------------------------------------------
In questo prodotto viene usato il seguente componente:

libtiff

Copyright (c) 1988-1997 Sam Leffler

Copyright (c) 1991-1997 Silicon Graphics, Inc.

Permission to use, copy, modify, distribute, and sell this software and its documentation for any purpose is hereby granted without fee, provided that (i) the above copyright notices and this permission notice appear in all copies of the software and related documentation, and (ii) the names of Sam Leffler and Silicon Graphics may not be used in any advertising or publicity relating to the software without the specific, prior written permission of Sam Leffler and Silicon Graphics.

THE SOFTWARE IS PROVIDED "AS-IS" AND WITHOUT WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR OTHERWISE, INCLUDING WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. 

IN NO EVENT SHALL SAM LEFFLER OR SILICON GRAPHICS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND, OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER OR NOT ADVISED OF THE POSSIBILITY OF DAMAGE, AND ON ANY THEORY OF LIABILITY, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
------------------------------------------------------------------------
Microsoft e Windows sono marchi registrati della Microsoft Corporation negli 
Stati Uniti d'America e/o negli altri Paesi. 
Gli altri nomi di società e di prodotti possono essere marchi di fabbrica o marchi 
registrati di singole società.
