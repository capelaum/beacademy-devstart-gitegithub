# Git e Github

## Configuração inicial

```bash
# Configura usuário local global do git
git config --global user.name 'Luís Vinicius Capelletto'
git config --global user.email 'thecapellett@gmail.com'
```

## Repositórios

```bash
# Inicializa Repositório
git init

# Mostra o status do repositório atual (branch, alterações, etc)
git status

# Adiciona um arquivo ao commit
git add filename.ext

# Adiciona todos arquivos alterados do repositório ao commit
git add .

# Remove arquivo do commit
git rm --cached filename.ext

# Realiza um commit, com uma mensagem
git commit -m "Mensagem do commit (seguindo algum padrão)"

# Mostra o log ou histórico dos commits realizados no repositório
git log

```

## Branches

```bash
# Mostra a branch atual e lista as branches locais
git branch

# Cria uma nova branch
git branch nome-da-nova-branch

# Troca para uma branch
git checkout nome-da-branch

# Cria uma branch e troca para ela
git checkout -b nova-branch

# Remove uma branch
git branch -d nome-da-branch

# Faz a junção de uma branch na branch atual
git merge nome-da-branch
```

## Github

```bash
# Clona um repositório do github para sua máquina local
git clone git@github.com:user/beacademy-devstart-gitegithub

# Lista os repositórios remotos
git remote -v

# Salva ou empurra as alterações commitadas para o repositório remoto
git push

# Puxa as alterações do repositório remoto para o repositório local
git pull

```

## Stash

```bash
# Salva alterações que ainda não foram commitadas
git stash

# Restaura as alterações salvas em stash
git stash pop

# Lista as stashes
git stash list

# Restaura um stash específico
git stash pop stash@{1}
```
