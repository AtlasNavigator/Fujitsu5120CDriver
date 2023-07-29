         --------------------------------------------------------
                           Fonte de dados TWAIN
                            < Versão 32 bits >
                             Arquivo Leia-me
                          2 de Novembro de 2012
                            Versão 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012

	Leia atentamente este arquivo antes de utilizar o produto. Este arquivo contém avisos
importantes e informações recentes, que não constam na ajuda on-line.

-----------------------------------------------------------------------------------------------
Índice
-----------------------------------------------------------------------------------------------
1.	Requisitos de sistema
2.	Como instalar
3.	Administração da energia elétrica
4.	Uso do adaptador Adaptec SCSI
5.	Conectando dois ou mais scanners em um mesmo computador
6.	Precauções requeridas na digitalização duplex
7.	Especificações da área de digitalização
8.	Obstrução de papel
9.	Uso de 256 cores / 8 cores 
10.	Cuidados sobre o Tamanho automático e Detecção de alinhamento.
11.	Detecção automática de tamanho da página
12.	Uso do Adobe Acrobat
13.	Corte da alimentação de energia durante a digitalização
14.	Fontes do sistema 
15.	Configuração da placa do SCSI (Bios)
16.	Controle de trabalho no Modo cache.
17.	Configuração do Modo cache quando o número de páginas é especificado
18.	Remoção de páginas em branco
19.	Combinando "Digitalização de página longa" e "Overscan"
20.	Uso do SDTC
21.	Uso em ambientes de alto risco


-----------------------------------------------------------------------------------------------
1- Requisitos de sistema
-----------------------------------------------------------------------------------------------
	Este software requer os seguintes sistemas.
      1.CPU
Computador com processador Intel (R) Pentium (R) ou compatível, e equipado com portas SCSI e 
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
	
	-Instalação efetuada a partir do SETUP DISK
	  Siga as instruções da janela de diálogo exibida logo após que o SETUP DISK for inserido.
	-Instalação efetuada a partir da web ou outros tipos de mídia
	  Rode o "setup.exe" e siga as indicações que aparecerão logo depois.
	-Para instalar o programa, use o login do administrador.


-----------------------------------------------------------------------------------------------
3- Administração da energia elétrica
-----------------------------------------------------------------------------------------------
	
	Se o computador entrar no modo de espera ou hibernar durante a digitalização de 
documentos, erros de transferência de dados podem ocorrer, causando a falha na digitalização. 
	Para evitar problemas, desative as opções de energia e repita o processo novamente.


-----------------------------------------------------------------------------------------------
4- Uso do adaptador Adaptec SCSI
-----------------------------------------------------------------------------------------------
	Informações sobre adaptadores SCSI estão disponíveis no URL abaixo:

	http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html


-----------------------------------------------------------------------------------------------
5- Conectando dois ou mais scanners em um mesmo computador 
-----------------------------------------------------------------------------------------------
	
	No Windows 2000, este software não suporta conexões múltiplas.
	Quando a conexão for feita via USB, este software não suportará dois ou mais aparelhos 
ao mesmo tempo.


-----------------------------------------------------------------------------------------------
6- Precauções requeridas na digitalização duplex
-----------------------------------------------------------------------------------------------
	
	-Para utilizar a digitalização duplex deste software, é necessário que o aplicativo 
utilizado tenha suporte para a função "Alimentação contínua".
	Desta forma, mesmo que a digitalização duplex seja selecionada, ela poderá não ser 
efetuada dependendo do suporte do aplicativo.


-----------------------------------------------------------------------------------------------
7- Especificações da área de digitalização
-----------------------------------------------------------------------------------------------
	
	A área de digitalização pode ser especificada utilizando uma das três unidades de 
medidas: Milímetro (mm), Polegada (in) ou Píxel (px).
	Porém, como o computador processa seus dados em 32 bits, um erro de até 32 píxels 
por linha é tolerado.


-----------------------------------------------------------------------------------------------
8- Obstrução de papel
-----------------------------------------------------------------------------------------------
	Quando obstruções de papéis são detectadas, a mensagem "Obstrução de papel" é exibida. 
Depois que o papel for removido e o botão [OK] da janela de mensagem for clicado, o scanner 
retornará ao estado "pronto", aguardando novas ordens do aplicativo.
	No entanto, quando a obstrução de papel ocorrer durante a digitalização do cabeçalho 
do documento no modo simplex, e o botão [OK] da janela de mensagem for pressionado, um 
documento a mais poderá ser expelido pelo scanner. Neste caso, retorne o documento expelido 
ao alimentador do scanner e reinicie a leitura do documento novamente.


-----------------------------------------------------------------------------------------------
9- Uso de 8cores / 256 cores
-----------------------------------------------------------------------------------------------
	
	Este software é capaz de produzir imagens de 8 cores / 256 cores. Porém, em alguns 
aplicativos, esta função pode são funcionar muito bem. Ao utilizar o "Adobe Acrobat", 
"Adobe PhotoShop" ou "Kodak imaging", altere as configurações de cor para "Preto e branco" 
ou "Níveis de cinza".


-----------------------------------------------------------------------------------------------
10- Cuidados sobre o Tamanho automático e Detecção de alinhamento
-----------------------------------------------------------------------------------------------
	
	Este driver possui funções que detectam automaticamente o tamanho e o alinhamento 
do documento, corrigindo-os se necessário. No entanto, certos aplicativos não suportam estas 
funções, não funcionando corretamente ou até mesmo danificando as imagens. Ao usar os 
seguintes aplicativos, desative a função [Detector automático de tamanho e alinhamento]:
	- Adobe Photoshop
	- Adobe Acrobat
	- Kodak Imaging


-----------------------------------------------------------------------------------------------
11- Detecção automática de tamanho da página
-----------------------------------------------------------------------------------------------

	Os scanners que possuem o Alimentador automático de documentos tornam possíveis 
funções como a Detecção automática de tamanho da página.
	Porém, quando o Modo de imagem "Meio-tom" é ativado, a Detecção automática de tamanho 
da página poderá não funcionar corretamente. Para evitar tais problemas, selecione Preto e 
branco ou outros tipos de digitalização, no menu Modo de imagem.


-----------------------------------------------------------------------------------------------
12- Uso do Adobe Acrobat
-----------------------------------------------------------------------------------------------

	As configurações de fábrica do Adobe Acrobat anulam as configurações feitas previamente 
em "Resolução", "Modo de digitalização" e "Modo de imagem". As seguintes funções não poderão 
ser utilizadas:
	- "8 cores" ou "256 cores"
	- "Detecção automática de tamanho da página"
	- "Grau da rotação" quando a "Detecção de final da página" estiver ativada
	- "Digitalização de documento longo"


-----------------------------------------------------------------------------------------------
13- Corte da alimentação de energia durante a digitalização
-----------------------------------------------------------------------------------------------

	Se o cabo de energia ou o cabo da interface for desligado durante a digitalização, 
este software será encerrado incorretamente. 
	Não remova os cabos de alimentação ou interface durante a digitalização.


-----------------------------------------------------------------------------------------------
14- Fontes do sistema
-----------------------------------------------------------------------------------------------
	
	Algumas mensagens da caixa de diálogo deste software podem sair para fora da caixa, 
se a fonte do sistema for alterado para grande ou extra grande. Isto pode depender do sistema 
operacional e do acelerador de gráfico usado.
	Neste caso, altere o tamanho da fonte do sistema para "normal". 


-----------------------------------------------------------------------------------------------
15- Configuração da placa do SCSI (Bios)
-----------------------------------------------------------------------------------------------
	
	Para usar este software, a configuração sobre "Desconectar" da placa do SCSI deve 
estar ativada.
	Quando placas de SCSI descritas acima no número 4 forem usadas, não há necessidade de 
alterar a configuração, já que o padrão de fábrica é "ativado".
	Para informações mais detalhadas sobre as configurações, consulte o manual de 
instruções anexado à placa de SCSI utilizada.


-----------------------------------------------------------------------------------------------
16- Controle de trabalho no Modo cache
-----------------------------------------------------------------------------------------------

	Na tela de opções de alguns scanners como o fi-4860C, fi-4990C e M4099D, quando uma 
das opções "Usar a memória do scanner" ou "Usar ambas as memórias" do menu "Modo de cache" for 
selecionada, as configurações do "Controle de trabalho" serão anuladas.


-----------------------------------------------------------------------------------------------
17- Configuração do Modo cache quando o número de páginas é especificado
-----------------------------------------------------------------------------------------------

	Ao efetuar digitalizações especificando o número da página, não selecione nenhuma das 
opções "Usar a memória do scanner" ou "Usar ambas as memórias" do menu "Modo de cache".


-----------------------------------------------------------------------------------------------
18- Remoção de páginas em branco
-----------------------------------------------------------------------------------------------
	
Quando a função "Remover páginas em branco" é selecionada e a última página do lote de 
documentos estiver em branco, a janela do TWAIN poderá se encerrar automaticamente, depois 
de digitalizar a última página.


-----------------------------------------------------------------------------------------------
19- Combinando "Digitalização de página longa" e "Overscan"
-----------------------------------------------------------------------------------------------
	
	Se as funções "Digitalização de página longa" e "Overscan" forem selecionadas, o 
comprimento do documento será ajustado conforme o tamanho máximo do "Overscan".


-----------------------------------------------------------------------------------------------
20- Uso do SDTC
-----------------------------------------------------------------------------------------------

	Digitalizações efetuadas no Modo de imagem "Preto e branco" ou "SDTC" usando o 
"Fundo preto", não serão exibidas corretamente. Neste caso, ajuste o "Valor do DTC" entre 
1 a 3, no menu Avançado.


-----------------------------------------------------------------------------------------------
21- Uso em ambientes de alto risco
-----------------------------------------------------------------------------------------------

	Este aparelho foi elaborado e produzido assumindo a condição de que será usado em 
escritórios,residências, estabelecimentos comerciais e industriais, de uso propósito geral. O 
aparelho não foi elaborado e produzido para uso em ambientes de alto risco, onde envolve 
perigo à vida ou à saúde, requerendo um alto nível de segurança. Locais como usinas nucleares, 
cockpits de aeronaves, torres de controle, controle de sistemas de transporte em massa, salas 
que contém equipamentos médicos essenciaisà vida, sistemas de controle de mísseis ou qualquer 
lugar onde à segurança não possa ser garantida são considerados ambientes de alto risco. O 
usuário deverá adotar medidas de segurança ao usar este produto 
em alguma dessas circunstâncias.
	A PFU Inc. não se responsabilizará por qualquer acidente causado em ambientes de alto 
risco, não atendendo a reclamações ou pedidos de compensação feitas por usuários ou 
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
	Microsoft e Windows são marcas registradas da Microsoft Corporation, registradas nos 
Estados unidos e outros países.
	O nome dos outros produtos são marcas registradas das respectivas companhias.
	
