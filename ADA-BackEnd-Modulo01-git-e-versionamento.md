# ADA SANTANDER - Curso Digital
# Módulo 01 - Git e Versionamento

## 01 - O que é Git?
Git é um sistema de versionamento de código, que guarda os registros de versão como snapshots do estado do projeto, além da referência/caminho para esse snapshot. O Snapshot é uma Hash do código. <br />
A maioria das operações feitas pelo Git são locais e por isso boa parte das operações são praticamente instantâneas devido à facilidade de acessar arquivos em seu próprio computador. <br />

## 02 - Instalando e configurando o Git
### Versão
> git --version
### Configurações Iniciais
> git config --global user.name "r4venj" <br />
> git config --global user.email r4venj@x.x

## 03 - Repositórios do Git
### Clone
> git clone https://github.com/R4VENJ/ADA-TrilhaDigital-Coders24-BackEnd.git
### Create
> git init

## 04 - Gravando mudanças no repositório
### Salvando modificações no Git
###### Mudança pelo VSCode
###### Mudança pelo site GitHub
### Estados do GIT
###### Untracked
###### Unmodified (SAVE)----> Modified
###### Modified (ADD)----> Staged
###### Staged (COMMIT)---->  Unmodified
#### Avançar de Unmodified to Modified 
> Editar Arquivo e Salvar
#### Retroceder de Modified to Unmodified
> git restore .\README.md

## 05 - Git diff e commit
#### Visualizar diferenças
> git diff
#### Avançar de Modified to Staged
> git add .\README.md
#### Retroceder de Staged to Modified
> git restore –staged .\README.md
#### Visualizar diferenças
> git diff –staged

## 06 - Git log e restore
#### Avançar de Staged to Unmodified
> git commit -m "add new title"
#### Avançar para Committed
> commit -m "add new text"
#### Log de Commits
> git log

## 07 - Repositórios remotos
### Publicar no GitHub
#### Verificar Remotes
> git remote
#### Subir
> git push origin main
#### Baixar
> git pull origin main
#### Fetch
> git fetch <br />
> git diff origin/main

## 08 - GitHub
https://github.com/R4VENJ/

## 09 - Git branch
### Nova Branch
> git branch NEWBRANCH
### Encontrar Head
> git branch <br />
> git log –oneline –decorate
### Alterar Head
> git log checkout NEWBRANCH

## 10 - Merging branches
### Merge Branching
> git merge NEWBRANCH



