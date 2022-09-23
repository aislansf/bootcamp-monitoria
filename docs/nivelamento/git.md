# Git

O Git é uma parte importante da programação no dia a dia (especialmente se você estiver trabalhando em equipe) e é amplamente usado no setor de software.

Como existem muitos comandos que você pode utilizar, dominar o Git por completo leva tempo. Alguns comandos, no entanto, são usados com mais frequência (alguns, até, diariamente). Neste artigo, compartilharei e explicarei os 10 comandos do Git mais usados e que todo desenvolvedor deveria conhecer.

## 1. Git clone

Git clone é uma comando para baixar o código-fonte existente de um repositório remoto (como, por exemplo, o Github). Em outras palavras, git clone, basicamente, faz uma cópia idêntica da versão mais recente de um projeto em um repositório e a salva em seu computador.

Há algumas maneiras de baixar o código-fonte, mas, em geral, eu prefiro a maneira de clonar com https:

```
git clone <https://link-com-o-nome-do-repositório>
```

## 2. Git status

Esse comando apresenta todos os status de alterações dos arquivos, sendo possível identificar quais arquivos foram modificados

```
git status
```

## 3. Git Add

Esse comando realiza a inclusão ou modificação do arquivo no diretório local, preparando ele para ser entregue ao servidor remoto para a mesma aplicação que está sincronizada na máquina local.

Você pode aplicar de duas formas

- Adicionando todos os arquivos

```
git add .
```

- Adicionando especificando o nome do arquivo

```
git add <nome do arquivo>
```

## 4. Git commit 
O comando git commit captura um instantâneo das mudanças preparadas do projeto no momento. Os instantâneos com commit podem ser considerados versões "seguras" de um projeto, o Git nunca os altera, a menos que você peça a ele.

```
git commit -m "Mensagem do commit"
```

## 5. Git push 
O comando git push é usado para enviar o conteúdo do repositório local para um repositório remoto. 

```
git push origin HEAD
```

## 6. Git pull

O git pull é um comando usado para atualizar suas branches locais de acordo com as branches remotas. Ele é uma combinação de dois comandos: git fetch seguido por git merge.

```
git pull
```

## 7. Git branch

Branches (algo como ramificações, em português) são altamente importantes no mundo do git. Usando as branches, vários desenvolvedores conseguem trabalhar em paralelo no mesmo projeto simultaneamente. Podemos usar o comando git branch para criar, listar e excluir as branches.

Como visualizar as branchs
```
git branch ou git branch --list
```

Como excluir uma branch
```
git branch -d <nome-da-branch>
```

## 8. Git checkout 
Esse também é um dos comandos do Git mais usados. Para trabalhar em uma branch, primeiro, é preciso "entrar" nela. Usamos git checkout, na maioria dos casos, para trocar de uma branch para outra. Também podemos usar o comando para fazer o checkout de arquivos e commits.

```
git checkout <nome-da-branch>
```

Fazendo a troca de branch e criando ao mesmo tempo
```
git checkout -b <nome-da-branch>
```

## 9. Git merge
Quando você concluir o desenvolvimento em sua branch e quando tudo funcionar bem, a etapa final é fazer o merge (mesclar ou unir, em português) da branch com a branch pai (dev ou master/main, em geral). Isso é feito com o comando git merge.

Git merge, basicamente, integra sua branch com o recurso e todos os seus commits na branch de desenvolvimento (dev) ou na branch principal (master ou main). É importante lembrar que, primeiro, você precisa estar na branch específica na qual você quer fazer o merge de sua branch com o recurso.

Para fazer o merge precisa primeiro você deve estar na branch que você quer mergar

```
git checkout master
```

Antes do merge, atualize sua branch local:

```
git fetch
```

Faça o merge da sua branch do recurso:
```
git merge <nome da branch que será mergada com a master>
```

Por fim, faça o envio da master local para o remote
```
git push origin HEAD
```
