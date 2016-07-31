![Ti Logo](http://terminaldeinformacao.com/wp-content/uploads/2016/03/tema.jpg)
[Terminal de Informação](http://terminaldeinformacao.com)

# AdvPL
Fontes desenvolvidos utilizando a linguagem AdvPL com intuito de auxiliar e ajudar outros analistas.
Abaixo as categorias, explicando um pouco sobre cada fonte.

####Exemplos
1. Dialogs
   * **zExempF1.prw**: Exemplo de Help (F1) de campo, em Dialog customizada
2. MVC
   * **zMVCMd1.prw**: Exemplo de cadastro MVC - Modelo 1
   * **zMVCMd3.prw**: Exemplo de cadastro MVC - Modelo 3
   * **zMVCMdX.prw**: Exemplo de cadastro MVC - Modelo X
3. Outros
   * **zMotBaixa.prw**: Exemplo de acesso a tabela de Motivos de Baixa do Financeiro
4. Pontos de Entrada
   * **MBlkColor.prw**: Ponto de entrada MBlkColor, alterando cor de registros bloqueados nas grids
5. Vídeo Aulas
   * 002 - Conceitos Básicos
      * **zCorpo.prw**: Exemplo de Corpo de Programa em AdvPL
   * 003 - Variáveis e Constantes
      * **zConstantes.prw**: Exemplo de utilização de Constantes
	  * **zVariaveis.prw**: Exemplo de utilização de Variáveis
   * 004 - Escopo de Variáveis
      * **escopo.png**: Exemplificação de escopo de variáveis
	  * **zEscopo.prw**: Fonte demonstrando o escopo de variáveis
   * 005 - Operadores
      * **zOperadores.prw**: Exemplo de utilização de operadores
   * 006 - Laços e Testes
      * **zLacos.prw**: Exemplos de laços de repetição
	  * **zTestes.prw**: Exemplos de testes condicionais
   * 007 - Tipos de Funções
      * **zTpFuncA.prw**: Exemplificação de funções (User, Static, etc)
	  * **zTpFuncB.prw**: Exemplificação de funções (User, Static, etc)
   * 008 - Manipulação de Banco de Dados
      * **zBanco.prw**: Exemplo de manipulação de Banco de Dados
   * 009 - Utilizando Índices e Posicionamento
      * **exemplificação.xlsx**: Exemplo de índices utilizando planilha
	  * **zIndPos.prw**: Exemplificação de utilização de Índices e Posicionamentos
   * 010 - Gravação de Registros via RecLock
	  * **zGravacao.prw**: Gravação de registros no Protheus, via RecLock
   * 011 - Gravação de Registros via MsExecAuto
      * **exemplo.png**: Exemplo do funcionamento de um ExecAuto
	  * **zExecAuto.prw**: Gravação de registros no Protheus, via MsExecAuto (Cadastro de Produtos)
   * 012 - Consultas SQL
	  * **zEmbedd.prw**: Exemplo de Consulta SQL com Embedded
	  * **zTCQuery.prw**: Exemplo de Consulta SQL com TCQuery
   * 013 - Como debugar um fonte no TDS
	  * **zDebug.prw**: Exemplo de Rotina para demonstração do Debug do TDS
   * 015 - Orientação a Objetos
	  * **zCadPessoa.prw**: Exemplo de Rotina instanciando a classe Pessoa
	  * **zPessoa.prw**: Exemplo de Classe em AdvPL
   * 016 - Utilizando Pontos de Entrada
	  * **A010TOK.prw**: Exemplo de Ponto de Entrada no cadastro de Produtos
   * 017 - Conceitos MVC
	  * **modelo_mvc.png**: Exemplo de modelo da estrutura MVC em AdvPL
	  * **zUpdTab.prw**: Fonte para criação de tabelas que serão utilizadas como exemplo
	  
####Fontes
   * **zAbreArq.prw**: Função que abre arquivo, conforme sistema operacional (por exemplo, abrir um .txt pelo notepad)
   * **zAltSC5.prw**: Função para alteração de pedido de venda já liberado / faturado
   * **zArrToTxt.prw**: Função recursiva, que transforma array em texto
   * **zCodAno.prw**: Função sequencial de código / ano
   * **zConsArr.prw**: Consulta Específica (F3), com dados de Array
   * **zConsMark.prw**: Consulta Específica (F3), com marcação de dados
   * **zCriaLog.prw**: Função para gravar log de registro na base
   * **zDtExtenso.prw**: Função que transforma uma variável data, na forma extensa (por exemplo, 27 de Setembro de 2015)
   * **zExcel2DBF.prw**: Função de conversão de arquivos XLS para DBF
   * **zImpAux.prw**: Função que imprime o TMSPrinter em sequência diferente
   * **zLastPerg.prw**: Função que retorna a última pergunta da memória
   * **zLogin.prw**: Função que carrega uma tela de login
   * **zPegaMac.prw**: Função que pega o MAC Address de máquinas com Windows instalado
   * **zSemanas.prw**: Função que retorna as semanas entre duas datas
   * **zSM0CNPJ.prw**: Função que busca o código da filial, conforme o CNPJ
   * **zTamImg.prw**: Função que retorna o tamanho de uma imagem em pixels
   * **zTransNum.prw**: Função que transforma uma variável numérica em texto (para exportação de arquivos)
   * **zVerTrans.prw**: Função que verifica se um pedido já foi transmitido na filial
   * **zVal2Hora.prw**: Função que converte valor numérico para hora (por exemplo, 1.50 -> 1h30)

####Projetos
1. Carga Dados Genérico
   * **exemplos.rar**: Exemplos de arquivos para importação dos dados
   * **zCargaGen.prw**: Fonte de Carga Dados Genérico (importação de cadastro)
2. Dicionário de Dados
   * **zCadSX6.prw**: Função para cadastro de parâmetros (SX6), similar ao AxCadastro e mBrowse
   * **zCpySX1.prw**: Função para cópia de grupo de perguntas
   * **zCriaTab.prw**: Função que cria tabelas "a quente" via código fonte
   * **zTstDicio.prw**: Função de testes das funções do dicionário de dados
3. Integração com Excel
   * **teste_aux.xml**: Exemplo de arquivo do Excel, com listagem de clientes e fornecedores
   * **teste_pedido.xml**: Exemplo de arquivo do Excel, com dados de pedidos de venda
   * **teste_sb1.xml**: Exemplo de arquivo do Excel, com listagem de produtos
   * **testes.prw**: Função de testes utilizando a classe zExcelXML.prw
   * **zExcelXML.prw**: Classe criada para integração com Excel, utilizando arquivos XML
4. Integração com WebCam
   * **escapi.dll**: DLL utilizada para integração com WebCam
   * **imageload2.dll**: DLL utilizada para integração com WebCam
   * **zPegaWeb.prw**: Função responsável por fazer a integração do Protheus com WebCam
   * **zTstWeb.prw**: Função que testa a utilização da rotina de WebCam no cadastro de clientes pelo Ações Relacionadas
5. ProtheusDOC
   * **PDoc_Ti.rar**: Arquivo compactado com a base do Protheus Doc