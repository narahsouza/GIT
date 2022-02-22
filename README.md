# GIT

Alguns comandos básicos do GIT

### Verificar configurações

`git config --list`

### Inserir usuário e e-mail

`git config --global user.name [username]`

`git config --global user.email [e-mail]`

### Remover usuário e e-mail

`git config --global --unset user.name`

`git config --global --unset user.email`

### Iniciar um novo repositório local

`git init`

### Download repositório remoto

`git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY`

### Verificar e atualizar caminho remoto

`git remote -v`

`git remote remove origin`

`git remote add origin [url]`

`git remote set-url origin [url]`

### Atualizar com alterações do repositório remoto

`git pull`

### Remover arquivo ou pasta

`git rm -r [nome]`

### Branches

`git branch`

`git branch [branch]`

`git checkout [branch]`

### Status das alterações

`git status`

### Adicionar arquivos

`git add *`

### Confirmar as alterações

`git commit`

`git commit -m [mensagem]`

### Envio das alterações

`git push`

***
