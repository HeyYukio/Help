
# SSH
## Verificando existência de uma key:
```
ls -al ~/.ssh
```
## Gerando ume nova ssh-key:
```
ssh-keygen -t ed25519 -C "your_email@example.com"
```
## Startando a chave:
```
eval "$(ssh-agent -s)"
```
## Adicionando a chave a um ssh-agent:
```
ssh-add ~/.ssh/id_ed25519
```
## Copiando a public key para o clipboard:
```
cat ~/.ssh/id_ed25519.pub
```