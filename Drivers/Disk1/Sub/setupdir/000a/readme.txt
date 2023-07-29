         --------------------------------------------------------
                    Software de fuente de datos TWAIN
                            < versi�n 32-bit >
                              Archivo L�AME
                          2 de noviembre de 2012
                           Versi�n 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012


L�ase este archivo antes de la utilizaci�n del producto. El archivo incluye notas 
importantes y la informaci�n m�s actualizada, la cual no podr� encontrarla en la ayuda 
por tel�fono (On-line).

------------------------------------------------------------------------
Tabla de contenidos 
------------------------------------------------------------------------

1. Requerimientos del Sistema 
2. C�mo Instalar 
3. Precauciones la administraci�n de energ�a el�ctrica
4. Utilizando el adaptador Adaptec-made SCSI 
5. Precauciones en dos o m�s esc�neres en un mismo ordenador 
6. Precauciones en los elementos de la digitalizaci�n D�plex 
7. Precauciones en las especificaciones del �rea de digitalizaci�n 
8. Precauciones en los documentos atascados 
9. Precauciones en 256 color y 8 color 
10. Precauciones con la Detecci�n Autom�tica de Tama�o y Enderezado
11. Precauciones en la Detecci�n Autom�tica del Tama�o de P�gina 
12. Aviso del Uso del Adobe Acrobat
13. Precauciones de apagamiento durante la digitalizaci�n
14. Precauciones en las fuentes (tipo de letra)
15. Precauciones en los ajustes SCSI BIOS 
16. Precauciones en Control de Funciones (Job Control) con Modo Cach� 
17. Acerca del Uso Simult�neo de la configuraci�n para establecer la cantidad de 
     hojas a escanear y del Modo de Cach�
18. Precauciones en Omitir p�gina Vac�a
19. Acerca del uso de la funci�n P�gina larga combinada con Sobre exploraci�n
20. Nota acerca del uso del SDTC
21. Utilizaci�n Aplicaciones de Alta-Seguridad 


-------------------------------------------------------------
1. Requerimientos del Sistema 
-------------------------------------------------------------

Este software requiere de los siguientes entornos (o ambientes).

  1) CPU
     Procesador Intel(R) Pentium(R) o compatible 
     Con disposici�n SCSI-2 � USB 1.1/2.0
     
  2) Sistema Operativo 
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
2. C�mo Instalar 
-------------------------------------------------------------

 - Instalaci�n realizada por el medio de SETUP DISK.
   Inserte el SETUP DISK y prosiga con las instrucciones en el di�logo de inicio.

 - Instalaci�n realizada a trav�s del Web o otro medio.
   Ejecute "setup.exe" y prosiga con las instrucciones mostradas en la pantalla.

 - Aseg�rese de hacer sesi�n  al sistema como un usuario que tenga privilegios 
   de Administrador para la instalaci�n del programa.


---------------------------------------------------
3. Precauciones la administraci�n de energ�a el�ctrica.
---------------------------------------------------

Si el ordenador entra en el modo de suspensi�n o hibernaci�n cuando el esc�ner 
se encuentra digitalizando documentos, la digitalizaci�n podr�a fallar debido a 
un error de transmisi�n de datos.
Para evitar este problema, deshabilite las opciones de energ�a, y luego digitalice 
otra vez.


-------------------------------------------------------------
4. Utilizando el adaptador Adaptec-made SCSI 
-------------------------------------------------------------

La informaci�n acerca de los adaptadores SCSI que pueden ser conectados 
podr� encontrarse en el siguiente URL:

http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html

---------------------------------------------------
5. Precauciones en dos o m�s esc�neres en un mismo ordenador 
---------------------------------------------------

En Windows2000, este software no dispone de dispositivo-m�ltiple.

Tambi�n este software no dispone de dispositivo-m�ltiple si utiliza interfaz USB. 


---------------------------------------------------
6. Precauciones en los elementos de digitalizaci�n D�plex 
---------------------------------------------------

Para la utilizaci�n de los elementos de digitalizaci�n de D�plex en este software, 
la aplicaci�n utilizada tendr� que disponer los elementos de 
"Escaneo Continuado" (continuous-scanning) de datos de imagen.

Por lo tanto, de acuerdo a la aplicaci�n, a�n si la configuraci�n de digitalizaci�n 
D�plex es establecida, el dato de imagen D�plex no podr� ser digitalizado.


---------------------------------------------------
7. Precauciones en las especificaciones de la digitalizaci�n D�plex 
---------------------------------------------------

El �rea de digitalizaci�n podr� ser especificada utilizando 3 tipos de unidades, las 
cuales son mil�metros(mm),pulgadas y p�xeles. 
H�gase saber que �rea de digitalizaci�n pueda tener un error m�ximo de 32 p�xeles 
por l�nea en cada unidad. 


---------------------------------------------------
8. Precauciones en los documentos atascados 
---------------------------------------------------

El mensaje de error,"Papel Atascado", se visualizar� cuando alg�n papel se atasque 
en el esc�ner.
 
Despu�s de que extraiga el documento atascado y pulse el bot�n "Aceptar" en el di�logo 
de mensaje de error, el software regresar� al estado listo para realizar operaciones 
de digitalizaci�n. 

Sin embargo, si se realiza la digitalizaci�n en Simplex (digitalizaci�n D�plex no 
es seccionada) y ocurra un atascamiento de papel cuando el cabezal del documento se 
encuentre escaneando, pueda que un papel extra sea expulsado a la bandeja al pulsar 
el bot�n "Aceptar" en el di�logo de mensaje de error. Si este es el caso, regrese 
el documento expulsado en la bandeja de entrada y realice la digitalizaci�n de nuevo.


---------------------------------------------------
9. Precauciones en 256 color y 8 color 
---------------------------------------------------

Este software dispone de 256 color y 8 color. H�gase saber que algunos software no 
disponen de estos dos elementos, tales como Adobe PhotoShop y Adobe Acrobat y Kodak 
Imaging, las cuales producen im�genes en blanco y negro.
Se recomienda el uso de las aplicaciones Image Professional 2.6 o Imaging en sistemas 
operativos de Windows y ScandAll2001 V.4.0 (o posterior) para el uso de estos elementos 
de colores. Por otro lado, si no requiere de dichos elementos, simplemente, no los 
utilice.


---------------------------------------------------
10. Precauciones con la Detecci�n Autom�tica de Tama�o y Enderezado
---------------------------------------------------

Este Driver tiene la funcione de  Detecci�n autom�tica de enderezado. Puede ocurrir 
que alguna aplicaciones no soporten esta opci�n, entonces la imagen puede ocurrir 
que salga corrupta. Si usa alguna de estas Aplicaciones: Adobe Photoshop, Acrobat, 
Kodak Imaging, por favor desactive la funci�n de Detecci�n autom�tica  de Tama�o y 
Enderezado  


---------------------------------------------------
11. Precauciones en la Detecci�n Autom�tica del Tama�o de P�gina 
---------------------------------------------------

Cuando Medios Tonos, SEE o Modo de Digitalizaci�n de Separaci�n Autom�tica se 
selecciona simult�neamente con la Detecci�n Autom�tica de Tama�o de P�gina, la 
correcta digitalizaci�n depende de los p�xeles blancos y negros y de la detecci�n 
del tama�o de p�gina.
Si el p�xel blanco es detectado, normalmente produce una imagen correcta como uno 
espera. Por otro lado, no producir� una imagen correcta, debido a que �sta pueda estar 
enmarcado con color negro. 
Esto es debido a la naturaleza del Medio Tonos, SEE y Separaci�n Autom�tica de imagen, 
que llenan los p�xeles blancos y negros y la limitaci�n de la funci�n de Detecci�n 
Autom�tica del Tama�o de P�gina.


---------------------------------------------------
12. Aviso del Uso del Adobe Acrobat
---------------------------------------------------

Las configuraciones por defecto de Acrobat anular�n las configuraciones previamente 
definidas de "Resoluci�n", "Tipo de Escaneo" y "Modo de Imagen".
Las siguientes funciones no pueden ser utilizadas.
  - "256 Colores" � "8 colores"
  - Detecci�n Autom�tica para Tama�o de P�gina
  - Selecci�n de "Grado de Rotaci�n" cuando "Detecci�n del Final de la P�gina" est� 
    seleccionada.
  - Digitalizaci�n de "P�gina Larga"


---------------------------------------------------
13. Precauciones de apagamiento durante la digitalizaci�n 
---------------------------------------------------

Si el cable de alimentaci�n o de interfaz del esc�ner se desconecte durante la 
digitalizaci�n, el software pueda ser terminado bruscamente. No extraiga los dichos 
cables durante la digitalizaci�n. 


---------------------------------------------------
14. Precauciones en las fuentes (tipo de letra)
---------------------------------------------------

De acuerdo  al OS, acelerador de gr�ficos, y controlador de pantalla que utilice, 
algunas cadenas en la caja de di�logo ser�n cortadas si el sistema de fuentes (tipo 
de letra) es cambiado  en tama�os m�s grandes. Si este es el caso, seleccione fuentes 
m�s peque�as para una normal visualizaci�n.   


---------------------------------------------------
15.  Precauciones en los ajustes SCSI BIOS 
---------------------------------------------------

Especifique la configuraci�n "DESCONECTADO" en el tablero de SCSI al utilizar este 
software. 

Si le tablero de SCSI est� configurado como se describe en la secci�n 4 de este archivo, 
los cambios no ser�n requeridos debido ha que el tablero ya est� configurado en 
"DESCONEXI�N HABILITADA".
  
Para obtener m�s detalles en el procedimiento de ajustes, consulte el manual de 
instrucciones adjunto al tablero de SCSI utilizado.   


---------------------------------------------------
16. Precauciones en Control de Funciones (Job Control)con modo Cach� 
---------------------------------------------------

En los modelos de esc�neres: fi-4860C, fi-4990C, y M4099D, los mensajes "Use Ambas 
Memorias" o "Use Memoria del esc�ner" aparecer�n en "Modo Cach�", en el di�logo de 
opci�n del software.
Sin embargo, si selecciona la configuraci�n "Use Ambas Memorias" o "Use Memoria del 
esc�ner", "Control de Funciones" ("Job Control") ser� ignorado en el mismo di�logo 
de opci�n.


---------------------------------------------------
17. Acerca del Uso Simult�neo de la configuraci�n para establecer la cantidad de 
     hojas a escanear y del Modo de Cach�
---------------------------------------------------

Cuando utiliza la configuraci�n para establecer la cantidad de hojas a escanear, NO 
seleccione "Utilizar Memoria en Esc�ner" ni tampoco "Utilizar Ambas Memorias" en la 
configuraci�n del Modo Cach� de la ventana de di�logo de opciones.


---------------------------------------------------
18. Precauciones en Omitir p�gina Vac�a 
---------------------------------------------------

Cuando la funci�n "Omitir p�gina vac�a" est� habilitada, si la �ltima p�gina del 
documento digitalizado est� en blanco (vac�a), la ventana de di�logo "Manejador TWAIN" 
podr�a cerrarse despu�s de omitir la p�gina en blanco.


---------------------------------------------------
19. Acerca del uso de la funci�n P�gina larga combinada con Sobre exploraci�n
---------------------------------------------------

Si la funci�n "Sobre exploraci�n" o "Detecci�n Autom�tica para Tama�o de P�gina" es 
seleccionada para la digitalizaci�n de "P�ginas largas", la longitud m�xima de papel 
ser� reducida por la distancia de la sobre exploraci�n.


---------------------------------------------------
20. Nota acerca del uso del SDTC 
---------------------------------------------------

Si digitaliza documentos en [Fondo negro] usando [Blanco/Negro] y [Modo SDTC] como el 
Modo Imagen, las im�genes de los documentos digitalizados podr�an generarse 
incorrectamente. 
En este caso, en la ventana [Avance] especifique la [Variaci�n del DTC] a 1 o 3 y 
digitalice documentos. 


---------------------------------------------------
21. Utilizaci�n Aplicaciones de Alta-Seguridad 
---------------------------------------------------

Este producto es dise�ado, desarrollado y fabricado para uso general sin limitaci�n 
para el uso general de oficina, uso personal, uso en el hogar y uso en ordinaria 
industria. Sin embargo, no es dise�ado, desarrollado y fabricado para el uso en los 
ambientes soportando extremadamente potenciales de riesgos o peligros fatales, los 
cuales requieren de extremada medidas de seguridad. De lo contrario esta pueda causar 
la muerte, heridas personales, graves da�os f�sicos u otros da�os si limares (de aqu� 
en adelante llamado "Utilizaci�n Aplicaciones de Alta-Seguridad"). Estas tambi�n 
incluyen sin ninguna limitaci�n control de reacciones nucleares de las facilidades 
de alimentaci�n nuclear, control de vuelo autom�tico de aviones, control de operaci�n 
en sistemas de transporte masivo, equipo medico para la vida sustentada, control de 
lanzamiento de misiles en sistemas de armas, y cuando la seguridad en cuesti�n no 
se asegura. 
NO deber� utilizar este producto sin asegurarse que todas las necesarias medidas de 
seguridad hayan sido suficientemente tomadas para cumplir con los requerimientos 
necesarios para su uso en las Aplicaciones de Alta-Seguridad. 
En adici�n, PFU LIMITED (u otra compa��a afiliada) no asume ninguna responsabilidad 
en absoluto para los da�os surgiendo del uso de este producto por el usuario en las 
aplicaciones de alta seguridad, y para cualquiera reclamaci�n o indemnizaci�n de da�os 
por el usuario o un tercero.


------------------------------------------------------------------------
En este producto se usa el siguiente componente:

libtiff

Copyright (c) 1988-1997 Sam Leffler

Copyright (c) 1991-1997 Silicon Graphics, Inc.

Permission to use, copy, modify, distribute, and sell this software and its documentation for any purpose is hereby granted without fee, provided that (i) the above copyright notices and this permission notice appear in all copies of the software and related documentation, and (ii) the names of Sam Leffler and Silicon Graphics may not be used in any advertising or publicity relating to the software without the specific, prior written permission of Sam Leffler and Silicon Graphics.

THE SOFTWARE IS PROVIDED "AS-IS" AND WITHOUT WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR OTHERWISE, INCLUDING WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. 

IN NO EVENT SHALL SAM LEFFLER OR SILICON GRAPHICS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND, OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER OR NOT ADVISED OF THE POSSIBILITY OF DAMAGE, AND ON ANY THEORY OF LIABILITY, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
------------------------------------------------------------------------
Microsoft y Windows son marcas registradas de Microsoft Corporation en los 
Estados Unidos y otros  pa�ses.
Los nombres de otros productos son las marcas o maracas registradas de las respectivas 
compa��as.

