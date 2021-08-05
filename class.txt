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

` git diff main feature/{nome-sobrenome}`

10. Alteração mensagem com Amend

` git commit --amend -m “nova mensagem”`

11. Reverter commit

` git revert {id_commit}`

12. Salvar stash

```
git stash save “add uma atividade incompleta”
git stash list
git stash show
```

13. Unir 2 commit ou mais com Squash

Use: 
“pick ..
squash ..
squash ..”

```
git rebase -i HEAD~3
```

14. Adicione o arquivo .gitigone para não versionar arquivos com extensão .log, faço o teste.
 
15. Faça uma PR para o repositorio original https://github.com/hesketh-carlos/41SCJ
