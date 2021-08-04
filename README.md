# 41SCJ
Repositório turma 41SCJ

## Orientações
1. Faça o Fork deste repositório

2. Clone seu repositorio para a maquina local

3. Configure seu nome e e-mail.

``` 
git config --global user.name "Seu nome"
git config --global user.email “seu_email_fiap@fiap.com.br”
git config -l
``` 

4. Crie um novo diretorio com seu nome-sobrenome

5. Crie uma nova branch com seu nome-sobrenome

`git checkout -b {nome-sobrenome}`

6. Dentro do novo diretorio crie um arquivo classe.txt no diretorio do projeto

```
git add classe.txt
git status
```

7. Faça o commit do arquivo.

` git commit -m “novo arquivo”`

8. verifique o log.

` git log --all --decorate --oneline –graph`

9. Verifique a diferença entre a sua branch e main?

`git diff main feature/{nome-sobrenome}`
