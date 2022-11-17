# Utilizando GIT

Git é um Sistema de Controle de Versão Distribuído (Distributed Version Control System - DVCS) que permite aos clientes clonar um repositório inteiro do projeto em seu disco. Em outras palavras, Git permite o armazenamento e a manipulação simultânea das versões de um arquivo em múltiplos servidores (computadores). Se um servidor morrer, o repositório do projeto ainda é recuperável de outro servidor que tenha uma cópia. 


## Instalando Git

Vamos usar o cliente da linha de comando e , no serviço do Github. Git __não é__ o Github, Github é o serviço, Git é sistema.[Download do Git](https://git-scm.com/) e[download do Gihthub](https://desktop.github.com/)

## Configurando

```
git init

git add .

git commit -m "primeiro commit"

git remote add origin <git-repo>

git push
```

## Gerenciando repositórios

```
git branch

git branch nova-branch

git branch -d branch-para-apagar

git checkout nome-branch
```
