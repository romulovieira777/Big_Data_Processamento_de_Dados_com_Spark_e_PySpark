### :computer: Comandos em Python que foram usados nos Arquivos acima: :rocket:
**O que faz a função append:**

Adiciona qualquer valor completo, por exemplo, se enviarmos um objeto, ele adiciona o objeto, se enviarmos uma lista, ele adiciona a lista inteira ao invés de seus itens.

**Sintaxe**

~~~py
append(<variável>):
~~~

**Exemplo**

~~~py
lista_04.append('Gorila')
~~~

**O que faz a função def:**

É para definir uma função que é uma sequência de comandos que executa alguma tarefa e que tem um nome.

**Sintaxe**

~~~py
def nome(<parâmetros>):
    comandos:
~~~

**Exemplo**

~~~py
def hello(meu_nome):
    print('Olá',meu_nome)
~~~

**O que faz a função else:**

A instrução else é uma instrução dependente, isto é, uma instrução que não pode ser utilizada sozinha. A instrução else só é executada se a condição do if for falsa.

**Sintaxe**

~~~py
else:
~~~

**Exemplo**

~~~py
idade = 18
if idade >= 18:
    print('maior de idade')
else:
    print('menor de idade')
~~~

**O que faz a função False:**

É usada para dizer se na condição o valor é False.

**Sintaxe**

~~~py
return False
~~~

**Exemplo**

~~~py
def impar(num):
    if num % 2 > 0:
        return True
    else:
        return False
~~~

**O que faz a função filter:**

Usada para criar um novo iterador a partir de um iterável existente (como uma list a ou um dicionário) que irá filtrar de forma eficiente os elementos usando uma função que fornecemos.

**Sintaxe**

~~~py
filter(<variável>)
~~~

**Exemplo**

~~~py
list(filter(func_par, lista))
~~~

**O que faz a função float:**

Devolve um número de ponto flutuante construído a partir de um número ou string.

**Sintaxe**

~~~py
float(<variável>)
~~~

**Exemplo**

~~~py
nota1 = float(input("Entre com a primeira nota: "))
~~~

**O que faz a função for:**

Executa um ciclo para cada elemento do objeto que está sendo iterado.

**Sintaxe**

~~~py
for <variável> in <objeto iterável>:
    bloco de instrução
~~~

**Exemplo**

~~~py
for numero in range(1, 6):
    print(numero)
~~~

**O que faz a função from:**

É usada para especificar a biblioteca.

**Sintaxe**

~~~py
import <biblioteca> from <caminho>
~~~

**Exemplo**

~~~py
from calculadora import Calculator
~~~

**O que faz a função if:**

É uma estrutura de condição que permite avaliar uma expressão e, de acordo com seu resultado, executar uma determinada ação.

**Sintaxe**

~~~py
if(<variável>)
~~~

**Exemplo**

~~~py
idade = 18
if idade < 20:
    print('Você é jovem!')
~~~

**O que faz a função import:**

É uma linha com o caminho completo para o arquivo python que contem o módulo que se deseja importar.

**Sintaxe**

~~~py
import <biblioteca>
~~~

**Exemplo**

~~~py
import re
~~~

**O que faz a função in:**

Verifica se o operando a sua esquerda, está contido na lista a sua direita.

**Sintaxe**

~~~py
 in (<variável>)
~~~

**Exemplo**

~~~py
2 and 3 in range(1,6)
~~~

**O que faz a função lambda:**

Permite escrever funções anônimas/sem-nome usando apenas uma linha de código.

**Sintaxe**

~~~py
lambda(<condição>):
~~~

**Exemplo**

~~~py
impar = lambda x: x % 2 > 0
~~~

**O que faz a função list:**

Transforma um conjunto de dados em lista.

**Sintaxe**

~~~py
list(<variável>)
~~~

**Exemplo**

~~~py
list(filter(func_par, lista))
~~~

**O que faz a função map:**

Pega uma lista e a transforma numa nova lista, executando algum tipo de operação em cada elemento.

**Sintaxe**

~~~py
map(<variável>)
~~~

**Exemplo**

~~~py
lista_map = map(impar, lista)
~~~

**O que faz a função parallelize:**

Permite executar várias funções ao mesmo tempo. Ela pode ser muito útil para tornar um código com muitos ciclos mais rápido, além de permitir mensagens durante scripts com um longo tempo de execução.

**Sintaxe**

~~~py
parallelize(<variável>)
~~~

**Exemplo**

~~~py
rddList = sc.parallelize(range(1000000), 10)
~~~

**O que faz a função print:**

Imprimir um argumento passado na tela.

**Sintaxe**

~~~py
print(<variável>)
~~~

**Exemplo**

~~~py
print('Olá, Mundo!')
~~~

**O que faz a função range:**

Permite-nos especificar o início da sequência, o passo, e o valor final.

**Sintaxe**

~~~py
range(<variável>):
~~~

**Exemplo**

~~~py
range(0, 10)
~~~

**O que faz a função reduce:**

Serve pra "reduzir" um iterável (como uma lista) a um único valor.

**Sintaxe**

~~~py
reduce(<variável>):
~~~

**Exemplo**

~~~py
soma = rddList.reduce(lambda acumulador, numero: acumulador + numero)
~~~

**O que faz a função return:**

É utilizada para declarar a informação a ser retornada pela função.

**Sintaxe**

~~~py
return(<condição>):
~~~

**Exemplo**

~~~py
def soma(x,y):
    num = x * y
    return num
~~~

**O que faz a função True:**

Retorna o valor 1 se for verdadeira.

**Sintaxe**

~~~py
True( <variável> ):
~~~

**Exemplo**

~~~py
def impar(num):
    if num % 2 > 0:
        return True
    else:
        return False
~~~


**O que faz a função type:**

Retorna o tipo de um objeto.

**Sintaxe**

~~~py
type( <variável> ):
~~~

**Exemplo**

~~~py
print(type(tuple_01))
~~~



### Operadores Aritméticos em Python
| Operadores Aritméticos | Operação                  |
|------------------------|---------------------------|
| +                      | Soma os Valores           |
| -                      | Subtração dos Valores     |
| *                      | Multiplicação dos Valores |
| **                     | Calcula a Potência        |
| /                      | Divisão dos Valores       |
| %                      | Resto da Divisão          |


### Operadores Condicionais em Python
| Operadores Condicionais | Operação                  |
|-------------------------|---------------------------|
| >                       | Maior que                 |
| <                       | Menor que                 |
| >=                      | Maior ou igual            |
| <=                      | Menor ou igual            |
| ==                      | Igual                     |
| !=                      | Diferente                 |
| and                     | E                         |
| or                      | Ou                        |
