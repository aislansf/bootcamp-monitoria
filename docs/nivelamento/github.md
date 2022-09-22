# Github

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





