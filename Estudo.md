# Repositório para Estudos
## Criando pasta

+ Criar pasta:

Digitar:

```
mkdir <nome-da-pasta>
```

+ Criando arquivos:

Digitar:

```
touch <nome-do-arquivo.extensão>
```

+ Se localizando:

```
ls
```

## Modificando Repositórios

+ Adicionando à staging area:

Antes de algum commit, é sempre necessário usar o git add:

```
git add --all // Adicionar todos os arquivos.
git add <nome_do_arquivo> // Adicionar apenas um arquivo.
git add .<extensao> // Todos arquivos da extensão desejada.
```

+ Commit:

```
git commit -m "<nome_do_commit>"
```

+ Verificando alterações(Depois do commit):

```
git log -p // Com todos os detalhes.
git log --pretty=oneline // Apenas linhas.
gitk // Visual grafico;
```

+ Modificando commit:

Depois de fazer todas as alterações, digitar:

```
git commit --amend -m "<nome_do_commit>"
```

## Algus comandos

+ Feito por leocomelli:

https://gist.github.com/leocomelli/2545add34e4fec21ec16
