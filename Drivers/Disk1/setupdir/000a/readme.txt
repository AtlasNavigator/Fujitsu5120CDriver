         --------------------------------------------------------
                    Software de fuente de datos TWAIN
                            < versión 32-bit >
                              Archivo LÉAME
                          2 de noviembre de 2012
                           Versión 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012


Léase este archivo antes de la utilización del producto. El archivo incluye notas 
importantes y la información más actualizada, la cual no podrá encontrarla en la ayuda 
por teléfono (On-line).

------------------------------------------------------------------------
Tabla de contenidos 
------------------------------------------------------------------------

1. Requerimientos del Sistema 
2. Cómo Instalar 
3. Precauciones la administración de energía eléctrica
4. Utilizando el adaptador Adaptec-made SCSI 
5. Precauciones en dos o más escáneres en un mismo ordenador 
6. Precauciones en los elementos de la digitalización Dúplex 
7. Precauciones en las especificaciones del área de digitalización 
8. Precauciones en los documentos atascados 
9. Precauciones en 256 color y 8 color 
10. Precauciones con la Detección Automática de Tamaño y Enderezado
11. Precauciones en la Detección Automática del Tamaño de Página 
12. Aviso del Uso del Adobe Acrobat
13. Precauciones de apagamiento durante la digitalización
14. Precauciones en las fuentes (tipo de letra)
15. Precauciones en los ajustes SCSI BIOS 
16. Precauciones en Control de Funciones (Job Control) con Modo Caché 
17. Acerca del Uso Simultáneo de la configuración para establecer la cantidad de 
     hojas a escanear y del Modo de Caché
18. Precauciones en Omitir página Vacía
19. Acerca del uso de la función Página larga combinada con Sobre exploración
20. Nota acerca del uso del SDTC
21. Utilización Aplicaciones de Alta-Seguridad 


-------------------------------------------------------------
1. Requerimientos del Sistema 
-------------------------------------------------------------

Este software requiere de los siguientes entornos (o ambientes).

  1) CPU
     Procesador Intel(R) Pentium(R) o compatible 
     Con disposición SCSI-2 ó USB 1.1/2.0
     
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
2. Cómo Instalar 
-------------------------------------------------------------

 - Instalación realizada por el medio de SETUP DISK.
   Inserte el SETUP DISK y prosiga con las instrucciones en el diálogo de inicio.

 - Instalación realizada a través del Web o otro medio.
   Ejecute "setup.exe" y prosiga con las instrucciones mostradas en la pantalla.

 - Asegúrese de hacer sesión  al sistema como un usuario que tenga privilegios 
   de Administrador para la instalación del programa.


---------------------------------------------------
3. Precauciones la administración de energía eléctrica.
---------------------------------------------------

Si el ordenador entra en el modo de suspensión o hibernación cuando el escáner 
se encuentra digitalizando documentos, la digitalización podría fallar debido a 
un error de transmisión de datos.
Para evitar este problema, deshabilite las opciones de energía, y luego digitalice 
otra vez.


-------------------------------------------------------------
4. Utilizando el adaptador Adaptec-made SCSI 
-------------------------------------------------------------

La información acerca de los adaptadores SCSI que pueden ser conectados 
podrá encontrarse en el siguiente URL:

http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html

---------------------------------------------------
5. Precauciones en dos o más escáneres en un mismo ordenador 
---------------------------------------------------

En Windows2000, este software no dispone de dispositivo-múltiple.

También este software no dispone de dispositivo-múltiple si utiliza interfaz USB. 


---------------------------------------------------
6. Precauciones en los elementos de digitalización Dúplex 
---------------------------------------------------

Para la utilización de los elementos de digitalización de Dúplex en este software, 
la aplicación utilizada tendrá que disponer los elementos de 
"Escaneo Continuado" (continuous-scanning) de datos de imagen.

Por lo tanto, de acuerdo a la aplicación, aún si la configuración de digitalización 
Dúplex es establecida, el dato de imagen Dúplex no podrá ser digitalizado.


---------------------------------------------------
7. Precauciones en las especificaciones de la digitalización Dúplex 
---------------------------------------------------

El área de digitalización podrá ser especificada utilizando 3 tipos de unidades, las 
cuales son milímetros(mm),pulgadas y píxeles. 
Hágase saber que área de digitalización pueda tener un error máximo de 32 píxeles 
por línea en cada unidad. 


---------------------------------------------------
8. Precauciones en los documentos atascados 
---------------------------------------------------

El mensaje de error,"Papel Atascado", se visualizará cuando algún papel se atasque 
en el escáner.
 
Después de que extraiga el documento atascado y pulse el botón "Aceptar" en el diálogo 
de mensaje de error, el software regresará al estado listo para realizar operaciones 
de digitalización. 

Sin embargo, si se realiza la digitalización en Simplex (digitalización Dúplex no 
es seccionada) y ocurra un atascamiento de papel cuando el cabezal del documento se 
encuentre escaneando, pueda que un papel extra sea expulsado a la bandeja al pulsar 
el botón "Aceptar" en el diálogo de mensaje de error. Si este es el caso, regrese 
el documento expulsado en la bandeja de entrada y realice la digitalización de nuevo.


---------------------------------------------------
9. Precauciones en 256 color y 8 color 
---------------------------------------------------

Este software dispone de 256 color y 8 color. Hágase saber que algunos software no 
disponen de estos dos elementos, tales como Adobe PhotoShop y Adobe Acrobat y Kodak 
Imaging, las cuales producen imágenes en blanco y negro.
Se recomienda el uso de las aplicaciones Image Professional 2.6 o Imaging en sistemas 
operativos de Windows y ScandAll2001 V.4.0 (o posterior) para el uso de estos elementos 
de colores. Por otro lado, si no requiere de dichos elementos, simplemente, no los 
utilice.


---------------------------------------------------
10. Precauciones con la Detección Automática de Tamaño y Enderezado
---------------------------------------------------

Este Driver tiene la funcione de  Detección automática de enderezado. Puede ocurrir 
que alguna aplicaciones no soporten esta opción, entonces la imagen puede ocurrir 
que salga corrupta. Si usa alguna de estas Aplicaciones: Adobe Photoshop, Acrobat, 
Kodak Imaging, por favor desactive la función de Detección automática  de Tamaño y 
Enderezado  


---------------------------------------------------
11. Precauciones en la Detección Automática del Tamaño de Página 
---------------------------------------------------

Cuando Medios Tonos, SEE o Modo de Digitalización de Separación Automática se 
selecciona simultáneamente con la Detección Automática de Tamaño de Página, la 
correcta digitalización depende de los píxeles blancos y negros y de la detección 
del tamaño de página.
Si el píxel blanco es detectado, normalmente produce una imagen correcta como uno 
espera. Por otro lado, no producirá una imagen correcta, debido a que ésta pueda estar 
enmarcado con color negro. 
Esto es debido a la naturaleza del Medio Tonos, SEE y Separación Automática de imagen, 
que llenan los píxeles blancos y negros y la limitación de la función de Detección 
Automática del Tamaño de Página.


---------------------------------------------------
12. Aviso del Uso del Adobe Acrobat
---------------------------------------------------

Las configuraciones por defecto de Acrobat anularán las configuraciones previamente 
definidas de "Resolución", "Tipo de Escaneo" y "Modo de Imagen".
Las siguientes funciones no pueden ser utilizadas.
  - "256 Colores" ó "8 colores"
  - Detección Automática para Tamaño de Página
  - Selección de "Grado de Rotación" cuando "Detección del Final de la Página" esté 
    seleccionada.
  - Digitalización de "Página Larga"


---------------------------------------------------
13. Precauciones de apagamiento durante la digitalización 
---------------------------------------------------

Si el cable de alimentación o de interfaz del escáner se desconecte durante la 
digitalización, el software pueda ser terminado bruscamente. No extraiga los dichos 
cables durante la digitalización. 


---------------------------------------------------
14. Precauciones en las fuentes (tipo de letra)
---------------------------------------------------

De acuerdo  al OS, acelerador de gráficos, y controlador de pantalla que utilice, 
algunas cadenas en la caja de diálogo serán cortadas si el sistema de fuentes (tipo 
de letra) es cambiado  en tamaños más grandes. Si este es el caso, seleccione fuentes 
más pequeñas para una normal visualización.   


---------------------------------------------------
15.  Precauciones en los ajustes SCSI BIOS 
---------------------------------------------------

Especifique la configuración "DESCONECTADO" en el tablero de SCSI al utilizar este 
software. 

Si le tablero de SCSI está configurado como se describe en la sección 4 de este archivo, 
los cambios no serán requeridos debido ha que el tablero ya está configurado en 
"DESCONEXIÓN HABILITADA".
  
Para obtener más detalles en el procedimiento de ajustes, consulte el manual de 
instrucciones adjunto al tablero de SCSI utilizado.   


---------------------------------------------------
16. Precauciones en Control de Funciones (Job Control)con modo Caché 
---------------------------------------------------

En los modelos de escáneres: fi-4860C, fi-4990C, y M4099D, los mensajes "Use Ambas 
Memorias" o "Use Memoria del escáner" aparecerán en "Modo Caché", en el diálogo de 
opción del software.
Sin embargo, si selecciona la configuración "Use Ambas Memorias" o "Use Memoria del 
escáner", "Control de Funciones" ("Job Control") será ignorado en el mismo diálogo 
de opción.


---------------------------------------------------
17. Acerca del Uso Simultáneo de la configuración para establecer la cantidad de 
     hojas a escanear y del Modo de Caché
---------------------------------------------------

Cuando utiliza la configuración para establecer la cantidad de hojas a escanear, NO 
seleccione "Utilizar Memoria en Escáner" ni tampoco "Utilizar Ambas Memorias" en la 
configuración del Modo Caché de la ventana de diálogo de opciones.


---------------------------------------------------
18. Precauciones en Omitir página Vacía 
---------------------------------------------------

Cuando la función "Omitir página vacía" está habilitada, si la última página del 
documento digitalizado está en blanco (vacía), la ventana de diálogo "Manejador TWAIN" 
podría cerrarse después de omitir la página en blanco.


---------------------------------------------------
19. Acerca del uso de la función Página larga combinada con Sobre exploración
---------------------------------------------------

Si la función "Sobre exploración" o "Detección Automática para Tamaño de Página" es 
seleccionada para la digitalización de "Páginas largas", la longitud máxima de papel 
será reducida por la distancia de la sobre exploración.


---------------------------------------------------
20. Nota acerca del uso del SDTC 
---------------------------------------------------

Si digitaliza documentos en [Fondo negro] usando [Blanco/Negro] y [Modo SDTC] como el 
Modo Imagen, las imágenes de los documentos digitalizados podrían generarse 
incorrectamente. 
En este caso, en la ventana [Avance] especifique la [Variación del DTC] a 1 o 3 y 
digitalice documentos. 


---------------------------------------------------
21. Utilización Aplicaciones de Alta-Seguridad 
---------------------------------------------------

Este producto es diseñado, desarrollado y fabricado para uso general sin limitación 
para el uso general de oficina, uso personal, uso en el hogar y uso en ordinaria 
industria. Sin embargo, no es diseñado, desarrollado y fabricado para el uso en los 
ambientes soportando extremadamente potenciales de riesgos o peligros fatales, los 
cuales requieren de extremada medidas de seguridad. De lo contrario esta pueda causar 
la muerte, heridas personales, graves daños físicos u otros daños si limares (de aquí 
en adelante llamado "Utilización Aplicaciones de Alta-Seguridad"). Estas también 
incluyen sin ninguna limitación control de reacciones nucleares de las facilidades 
de alimentación nuclear, control de vuelo automático de aviones, control de operación 
en sistemas de transporte masivo, equipo medico para la vida sustentada, control de 
lanzamiento de misiles en sistemas de armas, y cuando la seguridad en cuestión no 
se asegura. 
NO deberá utilizar este producto sin asegurarse que todas las necesarias medidas de 
seguridad hayan sido suficientemente tomadas para cumplir con los requerimientos 
necesarios para su uso en las Aplicaciones de Alta-Seguridad. 
En adición, PFU LIMITED (u otra compañía afiliada) no asume ninguna responsabilidad 
en absoluto para los daños surgiendo del uso de este producto por el usuario en las 
aplicaciones de alta seguridad, y para cualquiera reclamación o indemnización de daños 
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
Estados Unidos y otros  países.
Los nombres de otros productos son las marcas o maracas registradas de las respectivas 
compañías.

