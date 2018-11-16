# Github

Arquivo da aula de Git para iniciantes

# git init

Inicia um repositório

# git log

Mosta o log das alterações

## git log --decorate

Log com informações detalhadas

## git log --author="Jose"

Filtra por author

## git log --graph

Mostra os log via gráfico

# git shortlog

Mostar o log sintético das alterações

## git shortlog -sn

Mostar apenas a quantidade de commits e a pessoa que commitou

# git show <#2322>

Mostra as alteraçoes referente a uma Hash específica

# git status

Status do repositório, Untracked, unModified, Modified, Staged

# git diff

Mostra as mudanças antes de commitar

## git diff --name-only

Mostra apenas o nome dos arquivos alterados

# git add -A

Adiciona os arquivos para o repositório

# git commit -am "Message"

Efetua um commit das alterações, a opção -a adiciona os aquivos ao repositório

## git commit -m "Trigger" --alow-empty

Faz um commit forçado, apenas para disparar um trigger

# git checkout <nome do arquivo>

Retorna um arquivo para um estado antes da edição

# git reset --soft --mixed --hard

--soft: Pega as modificações e matar o commit, porém o arquivo vai ficar em stage pronta para ser commitada novamente

--mixed: Mata o commit, e volta os arquivos para modified

--hard: Mata o commit e volta tudo (cuidado)

# GitHub

O Github utiliza o SSH que autentica um usuário ao servidor
[Gerar Chaves](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)

# git remote

## git remote add origin https://github.com/shpsyte/git-course.git

Adiciona um repositorio remoto ao local

## git remote -v

Mostra informações do repositório remoto

# git push

git push -u origin master (-u track)
Envia o repositório local para o remoto
