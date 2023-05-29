# GIT
## INCIALIZANDO
### Cria Repositorio local:
```
git init
```
### Altera nome da local branch
```
git branch -M main
```
### Criando conexão com repositorio remoto:
```
git remote add origin <link do repositório>
```
## CLONANDO
### Clona master do repositorio remoto:
```
git clone <link do repositorio>
```
### Clona branch do repositorio remoto:
```
git clone --single-branch -b <BranchName> <link do repositório>
```
## PULL
### Realiza pull da branch especificada:
```
git pull origin <BranchName> --rebase
```
## BRANCH CHANGE
### Muda de branch
```
git checkout <BranchName>
```
### Cria nova branch e muda de branch
```
git checkout -b <NewBranch>
```
## CODE & PUSH
### Realizando stage de todas as modificações:
```
git add .
```
### Realizando commit das alterações em estado "staged":
```
git commit -m "mensagem da alteração"
```
### Realizando commit sem mensagem:
```
git commit --allow-empty-message
```
### Realizando push para branch atual:
```
$ git push -u origin <BranchName>
```
## MERGE
### Realiza merge da nova branch:
```
git merge <BranchName>
```