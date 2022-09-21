# Python 

Python é uma linguagem de programação de alto nível, interpretada de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte. Foi lançada por Guido van Rossum em 1991.

## Possibilidades com Python 

- Análise de dados
- Desenvolvimento web
- Desenvolvimento de apps
- Automação web e scraping
- Automação de tarefas

## Variáveis

Variáveis em Python são lugares reservados na memória de um dispositivo para o armazenamento de dados que posteriormente vão ser usados na execução de uma solução digital. Essas variáveis podem ter formatos e tamanhos diferentes, entre outras particularidades.

No geral os tipos são:

- Inteiro (int)
- Ponto Flutuante ou Decimal (float)
- String (str)
- Boolean (bool)

### Inteiro (int)

O tipo inteiro é um tipo composto por caracteres numéricos (algarismos) inteiros. 

Você pode fazer a declaração do **inteiro** dessa forma:

```
idade = 18
```

Caso você queira ver se realmente o tipo é **inteiro**, pode executar esse comando:

```
print(type(idade))
```

### Ponto Flutuante ou  Decimal (float)

É um tipo composto por caracteres numéricos (algarismo) decimais. Por exemplo, altura e peso.

Para declarar uma variável do tipo **float** no python pode executar dessa forma:

```
altura = 1.80
```

Caso você queira ver se realmente o tipo é **float**, pode executar esse comando:

```
print(type(altura))
```

### Texto String (str)

É um conjunto de caracteres dispostos numa determinada ordem, geralmente utilizada para representar palavras, frases ou textos.

Para declarar uma variável do tipo **str** no python pode executar dessa forma:

```
nome = 'Aislan Freitas'
```

Caso você queira ver se realmente o tipo é **str**, pode executar esse comando:

```
print(type(nome))
```

### Booleano (bool)

Tipo de dado lógico que pode assumir apenas dois valores: falso ou verdadeiro (False ou True em Python). Na lógica computacional, podem ser considerados como 0 ou 1.

Para declarar uma variável do tipo **bool** no python pode executar dessa forma:

```
chuva = True
```

Caso você queira ver se realmente o tipo é **bool**, pode executar esse comando:

```
print(type(chuva))
```

## Operadores

Os operadores são usados na construção de expressões, as quais contém um número variado de operandos. Por exemplo, na expressão a + b, temos o operador de aritmético + e operandos são as variáveis a e b.

Na linguagem Python temos a seguinte separação entre os diferentes tipos de operadores:

- Aritméticos
- Atribuição
- Comparação
- Lógicos
- Identidade
- Associação

### Aritméticos

Os operadores aritméticos realizam operações matemáticas como soma, subtração, multiplicação, divisão e outros. Na tabela a seguir apresenta as operações:

|Operador|Nome|Função
|:---:|:---:|:---|
|+|Adição|Realiza a soma de ambos operandos|
|-|Subtração|Realiza a subtração de ambos operandos
|*|Multiplicação|Realiza a multiplicação de ambos operandos
|/|Divisão|Realiza a Divisão de ambos operandos
|//|Divisão inteira|Realiza a divisão entre operandos e a parte decimal de ambos operandos
|%|Módulo|Retorna o resto da divisão de ambos operandos
|**|Exponenciação|Retorna o resultado da elevação da potência pelo outro

Agora você pode utilizar os exemplos abaixo
```
quatro = 4
dois = 2

soma = quatro + dois
print(soma)  # Resultado: 6

subtracao = quatro - dois
print(subtracao)  # Resultado: 2

multiplicacao = quatro * dois
print(multiplicacao)  # Resultado: 8

divisao = quatro / dois
print(divisao)  # Resultado: 2.0

divisao_interna = quatro // dois
print(divisao_interna)  # Resultado: 2

modulo = quatro % dois
print(modulo)  # Resultado: 0

exponenciacao = quatro ** dois
print(exponenciacao)  # Resultado: 16

```

### Atribuição

Esse operador tem como objetivo atribuir valores às variáveis, na tabela a seguir são apresentadas as possibilidades

| Operador|Equivalente a
|:---:|:---:|
|=|x = 1|
|+=|x = x + 1|
|-=|x = x - 1|
|*=|x = x * 1|
|/=|x = x / 1|
|%=|x = x % 1|

Agora você pode seguir os exemplos a seguir:

```
numero = 5

numero += 7
print(numero)  # Resultado será 12

numero -= 3
print(numero)  # Resultado será 2

numero *= 2
print(numero)  # Resultado será 10

numero /= 4
print(numero)  # Resultado será 1.25

numero %= 2
print(numero)  # Resultado será 1

```

### Comparação

Os operadores de comparação são usados para comparar valores, o que vai retornar True ou False, dependendo da condição. Na tabela  a seguir temos exemplos de comparações

|Operador|Nome|Função|
|:---|:---|:---|
|==|Igual a|Verifica se um valor é igual ao outro|
|!=|Diferente de|Verifica se um valor é diferente ao outro|
|>|Maior que|Verifica se um valor é maior que outro|
|>=|Maior ou igual|Verifica se um valor é maior ou igual ao outro|
|<|Menor que|Verifica se um valor é menor que outro|
|<=|Menor ou igual|Verifica se um valor é menor ou igual ao outro|

Com os operadores de comparação é possível construir vários exemplos, mas neste caso vou destacar um exemplo comparando apenas um número entre os operadores

```
var = 5

if var == 5:
    print('Os valores são iguais')

if var != 7:
    print('O valor não é igual a 7')

if var > 2:
    print('O valor da variável é maior de 2')

if var >= 5:
    print('O valor da variável é maior ou igual a 5')

if var < 7:
    print('O valor da variável é menor que 7')

if var <= 5:
    print('O valor da variável é menor ou igual a 5')
```

### Lógico

Os operadores lógicos são usados para unir duas ou mais expressões condicionais. Isso é feito por meio de conectivos, como podemos ver na tabela a seguir

|Operador|Definição|
|:---:|:---|
|and|Retorna True se ambas as afirmações forem verdadeiras|
|or|Retorna True se uma das afirmações for verdadeira|
|not|Retorna Falso se o resultado for verdadeiro|

Digite o exemplo abaixo

```
num1 = 7
num2 = 4

# Exemplo and
if num1 > 3 and num2 < 8:
    print("As Duas condições são verdadeiras")

# Exemplo or
if num1 > 4 or num2 <= 8:
    print("Uma ou duas das condições são verdadeiras")

# Exemplo not
if not (num1 < 30 and num2 < 8):
    print('Inverte o resultado da condição entre os parênteses')
```

### Identidade

Estes Operadores são utilizados para comparar objetos, verificando se os objetos testados referenciam o mesmo objeto (is) ou não (is not).

|Operador|Definição|
|:---|:---|
|is|Retorna True se ambas as variáveis são o mesmo objeto|
|is not|Retorna True se ambas as variáveis não forem o mesmo objeto|

```
lista = [1, 2, 3]
outra_lista = [1, 2, 3]
recebe_lista = lista

# Recebe True, pois são o mesmo objeto
print(f"São o mesmo objeto? {lista is recebe_lista}")

# Retorna False, pois são objetos diferentes
print(f"São o mesmo objeto? {lista is outra_lista}")

# Retorna True, pois são objetos diferentes
print(f"São o mesmo objeto? {lista is not outra_lista}")
```

### Associação

Eles servem para verificar se determinado objeto está associado ou pertence a determinada estrutura de dados.

|Operador|Função|
|:---|:---|
|in|Retorna True caso o valor seja encontrado na sequência|
|not in|Retorna True caso o valor não seja encontrado na sequência|

Exemplo de um caso de utilizando o operador de associação

```
lista = ["Python", 'Academy', "Operadores", 'Condições']

# Verifica se existe a string dentro da lista
print('Python' in lista)  # Saída: True

# Verifica se não existe a string dentro da lista
print('SQL' not in lista) # Saída: True
```

## Estrutura de controle de fluxo
Se quisermos ser capazes de escrever aplicativos realmente úteis, precisamos de técnicas para guiar o programa em diferentes direções, dependendo das circunstâncias. Para fazer isso, precisamos ter instruções que possam testar uma determinada condição e poder alterar o comportamento do programa de acordo com a resposta. Para isso temos dois controles de fluxos

- Seleção
- Repetição

### Seleção
#### Se - if
```
x = int(raw_input("Informe sua senha: "))
if x == 1234:
print ('Senha correta!')
```

#### Senão - elif
```
x = int(raw_input("Favor digitar um inteiro: "))
if x < 0:
x = 0
print 'Negativo alterado para zero'
elif x == 0:
print 'Zero'
elif x == 1:
print 'Unidade'
else:
print 'Mais'
```

### Repetição
#### Para - for
```
a = ['gato', 'janela', 'defenestrar']
for x in a:
print x, len(x)

```

#### Enquanto - while

```
contador = 0
while (contador < 5):
print(contador)
contador   = contador + 1
```

#### Variar - range
```
a = ['Mary', 'had', 'a', 'little', 'lamb']
for i in range(len(a)):
print i, a[i]
```

## Coleções de dados e dicionários
### Listas
```
# Listas
programadores = ['Victor', 'Juliana', 'Samuel', 'Caio', 'Luana']
print(type(programadores)) # type ‘list’
print(len(programadores)) # 5
print(programadores[4]) # Luana

# Substituindo na posição indicada
programadores[1] = 'Carolina'

# Adicionando item na lista
programadores.append('Renato')
programadores.insert(1, 'Rafael')

# Removendo itens da lista
programadores.remove('Victor')
programadores.pop(0)

```

### Tuplas
```
# tuplas
times_rj = ('Botafogo', 'Flamengo', 'Fluminense', 'Vasco')

# Acessando elemento
times_rj[2]

# Apresentando erro das tuplas imutáveis 
vogais = ('a', 'e', 'i', 'o', 'u')
vogais[1] = 'E'

```

### Dicionários
```
dados_cliente = {
    'Nome': 'Renan',
    'Endereco': 'Rua Cruzeiro do Sul',
    'Telefone': '982503645'
}
print(dados_cliente['Nome']) # Renan

#Adicionado dado
dados_cliente['Idade'] = 40

# removendo 
dados_cliente.pop('Telefone', None)

```

## Funções
Em Python, uma função é uma sequência de comandos que executa alguma tarefa e que tem um nome. A sua principal finalidade é nos ajudar a organizar programas em pedaços que correspondam a como imaginamos uma solução do problema.

### Argumentos

```
def NOME( PARAMETROS ):
    COMANDOS
```

Criando uma função que soma

```
def soma(x,y):
    num = x + y
print(soma(10,20))
```

### Retornos
```
def soma(x,y):
    num = x + y
    return num
```

## Classes

```
# Definindo o nome da classe
class calculadora:
    
    # definindo objeto da classe
    var3 = 999
    
    # definindo método da classe
    def soma(var1,var2):
        resultado = var1 + var2
        return resultado

    def subtracao(var1,var2):
        resultado = var1 - var2
        return resultado    

    def divisao(var1,var2):
        resultado = var1 / var2
        return resultado  

    def multiplicacao(var1,var2):
        resultado = var1 + var2
        return resultado
```








