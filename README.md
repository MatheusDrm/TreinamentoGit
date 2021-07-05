# Treinamento Git - Grupo Semear

O objetivo sera salvar alguns comandos do treinamento do semear.

- Repositorio -> pasta que contem os arquivos 
- Criar repositorio:
`mkdir (Nome_do_repositorio)` 
- inicializar repositorio:
`git init`
-  Abrir arquivo de texto:
`gedit README.md`
- working space -> `git add (Nome_do_arquivo)` ->index->`git commit (Nome_do_arquivo)` ou `git commit -m"comentario"`->head
- Checar a situacao das modificacoes: `git status`
- Desfazer as ultimas alteracoes: `git checkout`
- Destaca as ultimas modificacoes feitas no arquivo: 
`git diff README.md` 
- Passar arquivo para repositorio online:
`git push` 
- Comando para clonar repositorio
`git clone (link do repositorio)`
- Pegar as alteracoes do remoto e trazer para o seu repositorio local:
`git pull`
- Para visualizar o historico de commits utiiza-se o comando:
`git log`
- Comando para mostrar conteudo:
`cat README.md`
- Criar ramificacao:
`git checkout -b ramificacao1`
- Voltar para o master:
`git checkout master`
- passar ramificacao criada para o remoto
`git push origin ramificao1` ou `git push --set-upstream origin ramificacao1`
- Para juntar a ramificacao com a master usar o comando:
`git merge ramificacao1` 
