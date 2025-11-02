## Configuracoes iniciais do GitHub ##
#Configura o user.name# = git config --global user.name "phsilva1987"
#Configura o user.email# = git config --global user.email paulohs@me.com
#Configura o init.defaul# = git config --global init.defaul branch main

## Iniciar o Git HUB ##
git init
git add 
git commit -m "Colocar o porque esta alterando o arquivo"
git commit -a 
git commit -m "Colocar o porque da alteracao" --amend
git status
git log 
git log --oneline
git log -p = log detalhado do arquivo
git mv nome do arquivo atual  novo nome do arquivo

## Stages GitHub ##
restore
stage
unstage

## Removendo e restaurando Arquivos ##
Removendo arquivos
git rm hamburger.jpg

Restaurando arquivos 
git restore --staged hamburger.jpg
git restore NOME DO ARQUIVO


## Git Reset ##
git reset --soft e colocar o ponto "bfdd3aa"
git reset --mixed e colocar o ponto "bfdd3aa"
git reset --hard e colocar o ponto "bfdd3aa"s


## Git Alias ##
git config --global alias.log1 "log --oneline"

## Branch ##
Como Criar Branch
git branch Nome DA Branch
Exemplo = git branch DEV

Observacao: Voce pode criar quantas quiser

Como mudar de Branch
git switch DEV

Como Fazer o Merge
git merge -m "Merge Branch DEV para MAIN" DEV


Como remover uma branch 
git branch -d DEV
