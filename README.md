# dotfiles
minhas configurações de usuário linux

## Dependências

```shell
sudo apt install stow
```

## Inicialização

Na pasta raiz do projeto execute:

```shell
stow .
```

Exporte os shellscripts para o terminal usar, adicione essa linha ao seu `~/.bashrc`

```shell
export PATH="$PATH:$HOME/caruazu-scripts"
```

atualize o bash
```shell
source ~/.bashrc
```
