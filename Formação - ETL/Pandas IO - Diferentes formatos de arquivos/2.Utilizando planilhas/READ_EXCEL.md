# READ_EXCEL.md

## Introdução

O **Microsoft Excel** é uma das ferramentas de planilha mais utilizadas no mundo, sendo amplamente utilizado para armazenar e analisar dados em formato de tabela. No vídeo anterior, demonstramos como a função `read_excel` pode ser utilizada para ler um arquivo Excel no formato **xlsx**. No entanto, essa função é capaz de ler arquivos em outros formatos, como: **xls**, **xlsm**, **xlsb**, **odf**, **ods** e **odt**.

Vamos entender um pouco mais sobre esses diferentes tipos de arquivos?

## Formatos de Arquivo

### xls

O **xls** é um formato de arquivo do Excel mais antigo e usado até a versão de 2003.

### xlsx

Já o **xlsx** é o formato de arquivo padrão do Excel a partir da versão 2007. Esse formato é baseado em **XML** (Extensible Markup Language - Linguagem de marcação extensível) e é amplamente suportado por outras ferramentas de planilha eletrônica, incluindo o Google Planilhas.

> **Atenção:** Se surgiram algumas dúvidas com o termo XML, não se preocupe! Mais adiante teremos uma aula sobre esse tema. Nela você entenderá o que é esse formato, na medida em que lê e escreve em XML.

### xlsm

Há também o **xlsm**, uma extensão de arquivo usada pelo Excel para armazenar planilhas que contêm as macros. Estas são sequências de comandos ou instruções que podem ser executadas automaticamente para realizar tarefas específicas na planilha.

Então, o formato **xlsm** permite que as macros sejam salvas juntamente com a planilha, para que possam ser executadas sempre que a planilha for aberta.

### xlsb

Por fim, temos o formato **xlsb**, uma extensão de arquivo usada pelo Excel para armazenar planilhas em formato binário. A codificação binária permite que as planilhas sejam abertas e salvas com mais rapidez do que aquelas no formato **xlsx**.

## Formatos Abertos

Já os formatos **odf**, **ods** e **odt** são arquivos abertos, livres e universais que podem ser usados por qualquer software, ou seja, foram criados para serem independentes de plataformas, isso significa que podem ser usados em sistemas operacionais diferentes, como **Windows**, **Linux** e **Mac OS**.

Além disso, são independentes de aplicativos e podem ser usados em vários programas diferentes, incluindo o **OpenOffice**, o **LibreOffice**, o **Google Docs** e o **Microsoft Office**. Esse padrão de arquivos foi criado e é mantido pela **OASIS** (Organization for the Advancement of Structured Information Standards), uma organização internacional criada para desenvolver e promover padrões digitais para uso na Internet.

## Conclusão

Legal! Agora sabemos um pouco mais sobre todos os tipos de arquivos que podem ser lidos com a função `read_excel`.

## Referências

Caso queira aprofundar o assunto, deixamos alguns links para materiais que foram utilizados como referência:

- [Formatos de arquivos com suporte no Excel](https://support.microsoft.com/pt-br/office/formatos-de-arquivos-com-suporte-no-excel-0943ff2c-6014-4e8d-aaea-b83d51d46247)
- [OpenDocument](https://pt.wikipedia.org/wiki/OpenDocument)
