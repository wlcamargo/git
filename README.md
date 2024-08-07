# Tutorial Git

Abrir ajuda do Git
-
    git --help 

Abrir log do Git
-
    git log 

Inicializar um repositório do Git
-
	git init
 Este comando é usado para iniciar um novo repositório Git em um diretório local. Após executá-lo, o Git começa a rastrear as alterações nesse diretório.

Verificar status do Git
-
    git status
O comando git status é usado para verificar o estado atual do seu repositório. Ele mostra quais arquivos foram modificados, quais estão prontos para commit e quais estão fora do rastreamento do Git.

Associar Email e UserName
-
    git config --global user.name "wallace camargo"
    git config --global user.email "wallacecpdg@gmail.com"


Vincular Git local ao Github
-
    git remote add origin https://github.com/wlcamargo/
Este comando associa seu repositório local a um repositório remoto no GitHub (ou em outro serviço Git). O "origin" é um nome comum para o repositório remoto, mas pode ser personalizado.

Adicionar arquivos ao Git
-
     git add .
Use git add . para adicionar todas as alterações no diretório de trabalho ao índice do Git, preparando-as para o commit. Você também pode adicionar arquivos específicos, substituindo "." pelo nome do arquivo.

Commit
-
      git commit -m "mensagem do commit"
Com este comando, você cria um commit que inclui as alterações no índice do Git. A mensagem do commit deve descrever brevemente o que foi alterado. Isso torna o histórico de commits mais legível e informativo.

Realizar Push das alterações
-
       git push
O comando git push envia os commits locais para o repositório remoto. Isso atualiza o repositório remoto com as alterações que você fez localmente.

Realizar Pull das alterações
-
       git pull
O comando git pull busca os commits do repositório remoto para o repositório local.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# Instruções para ignorar arquivos


Você pode configurar o Git para ignorar arquivos, pastas ou tipos de arquivos específicos usando um arquivo chamado .gitignore. Este arquivo lista os padrões de nomes de arquivos e diretórios que o Git deve ignorar quando estiver rastreando as mudanças em seu repositório. Aqui estão as instruções para criar e usar um arquivo .gitignore:

Crie um arquivo .gitignore no diretório raiz do seu repositório Git, se ele ainda não existir.

Comando para criar o arquivo git ignore
-
        touch .gitignore

Basta abrir o arquivo e editar com os conteúdos que deseja ignorar

Se você deseja ignorar todos os arquivos com extensão .log e uma pasta chamada logs, seu arquivo .gitignore pode ter um dos exemplos abaixo


Ignorar todos os arquivos .log
-
     *.log

Ignorar a pasta "logs"
-
    /logs/

# Git Flow

## Inicializar o git flow

    git flow init

## Adicionar uma branch release
    git flow feature start nova_branch

## Finalizar a branch de release
    git flow feature finish nova_branch


