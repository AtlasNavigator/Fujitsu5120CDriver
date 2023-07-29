         --------------------------------------------------------
                           Fonte de dados TWAIN
                            < Vers�o 32 bits >
                             Arquivo Leia-me
                          2 de Novembro de 2012
                            Vers�o 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012

	Leia atentamente este arquivo antes de utilizar o produto. Este arquivo cont�m avisos
importantes e informa��es recentes, que n�o constam na ajuda on-line.

-----------------------------------------------------------------------------------------------
�ndice
-----------------------------------------------------------------------------------------------
1.	Requisitos de sistema
2.	Como instalar
3.	Administra��o da energia el�trica
4.	Uso do adaptador Adaptec SCSI
5.	Conectando dois ou mais scanners em um mesmo computador
6.	Precau��es requeridas na digitaliza��o duplex
7.	Especifica��es da �rea de digitaliza��o
8.	Obstru��o de papel
9.	Uso de 256 cores / 8 cores 
10.	Cuidados sobre o Tamanho autom�tico e Detec��o de alinhamento.
11.	Detec��o autom�tica de tamanho da p�gina
12.	Uso do Adobe Acrobat
13.	Corte da alimenta��o de energia durante a digitaliza��o
14.	Fontes do sistema 
15.	Configura��o da placa do SCSI (Bios)
16.	Controle de trabalho no Modo cache.
17.	Configura��o do Modo cache quando o n�mero de p�ginas � especificado
18.	Remo��o de p�ginas em branco
19.	Combinando "Digitaliza��o de p�gina longa" e "Overscan"
20.	Uso do SDTC
21.	Uso em ambientes de alto risco


-----------------------------------------------------------------------------------------------
1- Requisitos de sistema
-----------------------------------------------------------------------------------------------
	Este software requer os seguintes sistemas.
      1.CPU
Computador com processador Intel (R) Pentium (R) ou compat�vel, e equipado com portas SCSI e 
USB 1.1 / 2.0
      2.Sistema Operacional
     - Microsoft(R) Windows(R) 2000 Professional
     - Microsoft(R) Windows(R) XP Home Edition
     - Microsoft(R) Windows(R) XP Professional
     - Microsoft(R) Windows(R) XP Professional x64 Edition
     - Microsoft(R) Windows Server(TM) 2003, Standard Edition
     - Microsoft(R) Windows Server(TM) 2003 R2, Standard Edition
     - Microsoft(R) Windows Server(TM) 2003 R2, Standard x64 Edition
     - Windows Vista(TM) Home Basic (32/64bit)
     - Windows Vista(TM) Home Premium (32/64bit)
     - Windows Vista(TM) Business (32/64bit)
     - Windows Vista(TM) Enterprise (32/64bit)
     - Windows Vista(TM) Ultimate (32/64bit)
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

-----------------------------------------------------------------------------------------------
2- Como instalar
-----------------------------------------------------------------------------------------------
	
	-Instala��o efetuada a partir do SETUP DISK
	  Siga as instru��es da janela de di�logo exibida logo ap�s que o SETUP DISK for inserido.
	-Instala��o efetuada a partir da web ou outros tipos de m�dia
	  Rode o "setup.exe" e siga as indica��es que aparecer�o logo depois.
	-Para instalar o programa, use o login do administrador.


-----------------------------------------------------------------------------------------------
3- Administra��o da energia el�trica
-----------------------------------------------------------------------------------------------
	
	Se o computador entrar no modo de espera ou hibernar durante a digitaliza��o de 
documentos, erros de transfer�ncia de dados podem ocorrer, causando a falha na digitaliza��o. 
	Para evitar problemas, desative as op��es de energia e repita o processo novamente.


-----------------------------------------------------------------------------------------------
4- Uso do adaptador Adaptec SCSI
-----------------------------------------------------------------------------------------------
	Informa��es sobre adaptadores SCSI est�o dispon�veis no URL abaixo:

	http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html


-----------------------------------------------------------------------------------------------
5- Conectando dois ou mais scanners em um mesmo computador 
-----------------------------------------------------------------------------------------------
	
	No Windows 2000, este software n�o suporta conex�es m�ltiplas.
	Quando a conex�o for feita via USB, este software n�o suportar� dois ou mais aparelhos 
ao mesmo tempo.


-----------------------------------------------------------------------------------------------
6- Precau��es requeridas na digitaliza��o duplex
-----------------------------------------------------------------------------------------------
	
	-Para utilizar a digitaliza��o duplex deste software, � necess�rio que o aplicativo 
utilizado tenha suporte para a fun��o "Alimenta��o cont�nua".
	Desta forma, mesmo que a digitaliza��o duplex seja selecionada, ela poder� n�o ser 
efetuada dependendo do suporte do aplicativo.


-----------------------------------------------------------------------------------------------
7- Especifica��es da �rea de digitaliza��o
-----------------------------------------------------------------------------------------------
	
	A �rea de digitaliza��o pode ser especificada utilizando uma das tr�s unidades de 
medidas: Mil�metro (mm), Polegada (in) ou P�xel (px).
	Por�m, como o computador processa seus dados em 32 bits, um erro de at� 32 p�xels 
por linha � tolerado.


-----------------------------------------------------------------------------------------------
8- Obstru��o de papel
-----------------------------------------------------------------------------------------------
	Quando obstru��es de pap�is s�o detectadas, a mensagem "Obstru��o de papel" � exibida. 
Depois que o papel for removido e o bot�o [OK] da janela de mensagem for clicado, o scanner 
retornar� ao estado "pronto", aguardando novas ordens do aplicativo.
	No entanto, quando a obstru��o de papel ocorrer durante a digitaliza��o do cabe�alho 
do documento no modo simplex, e o bot�o [OK] da janela de mensagem for pressionado, um 
documento a mais poder� ser expelido pelo scanner. Neste caso, retorne o documento expelido 
ao alimentador do scanner e reinicie a leitura do documento novamente.


-----------------------------------------------------------------------------------------------
9- Uso de 8cores / 256 cores
-----------------------------------------------------------------------------------------------
	
	Este software � capaz de produzir imagens de 8 cores / 256 cores. Por�m, em alguns 
aplicativos, esta fun��o pode s�o funcionar muito bem. Ao utilizar o "Adobe Acrobat", 
"Adobe PhotoShop" ou "Kodak imaging", altere as configura��es de cor para "Preto e branco" 
ou "N�veis de cinza".


-----------------------------------------------------------------------------------------------
10- Cuidados sobre o Tamanho autom�tico e Detec��o de alinhamento
-----------------------------------------------------------------------------------------------
	
	Este driver possui fun��es que detectam automaticamente o tamanho e o alinhamento 
do documento, corrigindo-os se necess�rio. No entanto, certos aplicativos n�o suportam estas 
fun��es, n�o funcionando corretamente ou at� mesmo danificando as imagens. Ao usar os 
seguintes aplicativos, desative a fun��o [Detector autom�tico de tamanho e alinhamento]:
	- Adobe Photoshop
	- Adobe Acrobat
	- Kodak Imaging


-----------------------------------------------------------------------------------------------
11- Detec��o autom�tica de tamanho da p�gina
-----------------------------------------------------------------------------------------------

	Os scanners que possuem o Alimentador autom�tico de documentos tornam poss�veis 
fun��es como a Detec��o autom�tica de tamanho da p�gina.
	Por�m, quando o Modo de imagem "Meio-tom" � ativado, a Detec��o autom�tica de tamanho 
da p�gina poder� n�o funcionar corretamente. Para evitar tais problemas, selecione Preto e 
branco ou outros tipos de digitaliza��o, no menu Modo de imagem.


-----------------------------------------------------------------------------------------------
12- Uso do Adobe Acrobat
-----------------------------------------------------------------------------------------------

	As configura��es de f�brica do Adobe Acrobat anulam as configura��es feitas previamente 
em "Resolu��o", "Modo de digitaliza��o" e "Modo de imagem". As seguintes fun��es n�o poder�o 
ser utilizadas:
	- "8 cores" ou "256 cores"
	- "Detec��o autom�tica de tamanho da p�gina"
	- "Grau da rota��o" quando a "Detec��o de final da p�gina" estiver ativada
	- "Digitaliza��o de documento longo"


-----------------------------------------------------------------------------------------------
13- Corte da alimenta��o de energia durante a digitaliza��o
-----------------------------------------------------------------------------------------------

	Se o cabo de energia ou o cabo da interface for desligado durante a digitaliza��o, 
este software ser� encerrado incorretamente. 
	N�o remova os cabos de alimenta��o ou interface durante a digitaliza��o.


-----------------------------------------------------------------------------------------------
14- Fontes do sistema
-----------------------------------------------------------------------------------------------
	
	Algumas mensagens da caixa de di�logo deste software podem sair para fora da caixa, 
se a fonte do sistema for alterado para grande ou extra grande. Isto pode depender do sistema 
operacional e do acelerador de gr�fico usado.
	Neste caso, altere o tamanho da fonte do sistema para "normal". 


-----------------------------------------------------------------------------------------------
15- Configura��o da placa do SCSI (Bios)
-----------------------------------------------------------------------------------------------
	
	Para usar este software, a configura��o sobre "Desconectar" da placa do SCSI deve 
estar ativada.
	Quando placas de SCSI descritas acima no n�mero 4 forem usadas, n�o h� necessidade de 
alterar a configura��o, j� que o padr�o de f�brica � "ativado".
	Para informa��es mais detalhadas sobre as configura��es, consulte o manual de 
instru��es anexado � placa de SCSI utilizada.


-----------------------------------------------------------------------------------------------
16- Controle de trabalho no Modo cache
-----------------------------------------------------------------------------------------------

	Na tela de op��es de alguns scanners como o fi-4860C, fi-4990C e M4099D, quando uma 
das op��es "Usar a mem�ria do scanner" ou "Usar ambas as mem�rias" do menu "Modo de cache" for 
selecionada, as configura��es do "Controle de trabalho" ser�o anuladas.


-----------------------------------------------------------------------------------------------
17- Configura��o do Modo cache quando o n�mero de p�ginas � especificado
-----------------------------------------------------------------------------------------------

	Ao efetuar digitaliza��es especificando o n�mero da p�gina, n�o selecione nenhuma das 
op��es "Usar a mem�ria do scanner" ou "Usar ambas as mem�rias" do menu "Modo de cache".


-----------------------------------------------------------------------------------------------
18- Remo��o de p�ginas em branco
-----------------------------------------------------------------------------------------------
	
Quando a fun��o "Remover p�ginas em branco" � selecionada e a �ltima p�gina do lote de 
documentos estiver em branco, a janela do TWAIN poder� se encerrar automaticamente, depois 
de digitalizar a �ltima p�gina.


-----------------------------------------------------------------------------------------------
19- Combinando "Digitaliza��o de p�gina longa" e "Overscan"
-----------------------------------------------------------------------------------------------
	
	Se as fun��es "Digitaliza��o de p�gina longa" e "Overscan" forem selecionadas, o 
comprimento do documento ser� ajustado conforme o tamanho m�ximo do "Overscan".


-----------------------------------------------------------------------------------------------
20- Uso do SDTC
-----------------------------------------------------------------------------------------------

	Digitaliza��es efetuadas no Modo de imagem "Preto e branco" ou "SDTC" usando o 
"Fundo preto", n�o ser�o exibidas corretamente. Neste caso, ajuste o "Valor do DTC" entre 
1 a 3, no menu Avan�ado.


-----------------------------------------------------------------------------------------------
21- Uso em ambientes de alto risco
-----------------------------------------------------------------------------------------------

	Este aparelho foi elaborado e produzido assumindo a condi��o de que ser� usado em 
escrit�rios,resid�ncias, estabelecimentos comerciais e industriais, de uso prop�sito geral. O 
aparelho n�o foi elaborado e produzido para uso em ambientes de alto risco, onde envolve 
perigo � vida ou � sa�de, requerendo um alto n�vel de seguran�a. Locais como usinas nucleares, 
cockpits de aeronaves, torres de controle, controle de sistemas de transporte em massa, salas 
que cont�m equipamentos m�dicos essenciais� vida, sistemas de controle de m�sseis ou qualquer 
lugar onde � seguran�a n�o possa ser garantida s�o considerados ambientes de alto risco. O 
usu�rio dever� adotar medidas de seguran�a ao usar este produto 
em alguma dessas circunst�ncias.
	A PFU Inc. n�o se responsabilizar� por qualquer acidente causado em ambientes de alto 
risco, n�o atendendo a reclama��es ou pedidos de compensa��o feitas por usu�rios ou 
terceiros.


-----------------------------------------------------------------------------------------------
Este produto utiliza o seguinte componente.

libtiff

Copyright (c) 1988-1997 Sam Leffler

Copyright (c) 1991-1997 Silicon Graphics, Inc.

Permission to use, copy, modify, distribute, and sell this software and its documentation for any purpose is hereby granted without fee, provided that (i) the above copyright notices and this permission notice appear in all copies of the software and related documentation, and (ii) the names of Sam Leffler and Silicon Graphics may not be used in any advertising or publicity relating to the software without the specific, prior written permission of Sam Leffler and Silicon Graphics.

THE SOFTWARE IS PROVIDED "AS-IS" AND WITHOUT WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR OTHERWISE, INCLUDING WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. 

IN NO EVENT SHALL SAM LEFFLER OR SILICON GRAPHICS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND, OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER OR NOT ADVISED OF THE POSSIBILITY OF DAMAGE, AND ON ANY THEORY OF LIABILITY, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
-----------------------------------------------------------------------------------------------
	Microsoft e Windows s�o marcas registradas da Microsoft Corporation, registradas nos 
Estados unidos e outros pa�ses.
	O nome dos outros produtos s�o marcas registradas das respectivas companhias.
	
