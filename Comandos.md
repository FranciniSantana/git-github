# Aprenda Git e GITHUB do Zero https://www.youtube.com/watch?v=pyM5QLS2h6M

## Iniciando o versionamento do código:
 Ao iniciar um projeto do zero, na pasta do arquivo utilize o comando para dar início ao traqueamento com git

``` git init ```


## Preparando o arquivo para comitar
Após algum tempo de trabalho você prepara seus arquivos para serem enviados para o repositório remoto, então você começa usando o comando abaixo para adicioná-lo na "fila de commit".

``` git add . ou git add nome_do_arquivo```

## Fazendo o commit
Aqui você envia todos os pacotes de dados / arquivos para um ambiente que pode ser recuperado o histórico das suas versões.

```git commit -m "mensagem"```

## Criar repositório no github pública e seguir o passo a passo
Na primeira vez do projeto, você cria um repositório manualmente lá no github com esses comandos:

```git remote add origin link ```

```  git branch -M main```

``` git push -u origin main ```

## Passo a passo após estar trabalhando com documento já com repositório criado

```git status #Ao abrir o documento, ver as atualizações para lembrar o que foi feito de commit```

 ``` git add .   git add nomedocumento```

``` git commit -m "mensagem" ```

``` git push -u origin main ```

## Entender qual repositório remoto seu projeto está
``` git remote -v ```

# Remover projeto do repositório remoto
``` git remote remove origin```


## Branches

Comandos para trabalhar com branches locais e remotas

```git branch #listar as branches locais```

```git branch -r #listar as branches remotas```

```git checkout -b nome_da_branch # Cria uma nova branch localmente```

```git fetch # Atualiza commits, arquivos e refs (branches)```

```git fetch nome_repo_remoto nome_branch_remota```

```git pull nome_repo_remoto nome_repo_remoto/nome_dabranch```



## Commits
Melhorando os commits usando comandos

```git commit -m " texto do commit" # adiciona uma mensagem linha única```

```git commit -a #abre editor de mensagem de commit que pode trazer mais informações no commit```


``` git commit --amend -a # volta ao commit anterior com possibilidade de alterar mensagens```