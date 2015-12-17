# Projeto template para LaTeX

Projeto seguindo as normas ABNT.

## Ambiente preparado

Tenha os seguintes exes instalados:

* basic-miktex-2.9.5105.exe, baixar em: http://miktex.org/2.9/setup
* gs915w64.exe, baixar em: http://www.ghostscript.com/GPL_Ghostscript_9.15.html
* gsv50w64.exe, baixar em: http://pages.cs.wisc.edu/~ghost/gsview/get50.htm
* texmakerwin32_install.exe, baixa em: https://fossies.org/windows/misc/texmakerwin32_install.exe/

PS: O número da versão e da arquitetura servem de exemplos e podem variar. Os links eventualmente podem quebrar.

## Editando o projeto

Depois de tudo instalado, baixe o repositório para um local de sua preferência. Rode o arquivo Principal.tex, ele possui as configurações do projeto e ele também que carrega os demais .tex. Não inicie o projeto abrindo os demais .tex pois você estará abrindo apenas uma parte do projeto, e não ele como um todo..

## Adicionando dicionário em português

Extraia o conteúdo do /res/pt_BR.zip para C:/Program Files (x86)/Texmaker/, ou onde você tiver instalado o Texmaker.

Configure o Texmaker para ler o dicionário PT: 

Opções > Configurar o textmaker > Editor (na barra lateral esquerda) > Dicionário (Faça ele apontar para C:/Program Files (x86)/Texmaker/pt_PT.dic)

## Compilando

Deixe o arquivo Principal.tex como o último selecionado no Texmaker e depois escolha a opção "Compilar" no menu superior no Texmaker e aperta na seta azul a sua esquerda.

Caso você tenha adicionado bibliografias é necessário rodar com a opção "BibTeX" antes e rodar o "Compilar" duas vezes (sim, é um bug ou algo do gênero). Se a referência no documento estiver com **??** repita a operação até conseguir.

## Template

Tentei colocar um exemplo para cada coisa no projeto, coisas como código, figuras, referências para dentro do documento mesmo, bibliografia, agradecimento, sumário, lista de figuras, hifenização e etc..

O LaTeX é legal mas tem uns hackzinhos que tem que fazer de vez em quando, por exemplo para usar aspas use \`\` para que no documento fique: ` “ `, e ` '' ` para: ` ” `. Exemplo:  \`\`teste''  no .tex sairá  “teste” no pdf.

