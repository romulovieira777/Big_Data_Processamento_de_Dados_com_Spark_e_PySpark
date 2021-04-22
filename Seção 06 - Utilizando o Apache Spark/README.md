### :computer: Comandos em Python que foram usados nos Arquivos acima: :rocket:
**O que faz a função append:**

Transforma em array um conjunto de dados.

**Sintaxe**

~~~py
array(<variável>):
~~~

**Exemplo**

~~~py
a = np.array(range(100))
~~~

**O que faz a função as:**

Coloca um apelido na variável.

**Sintaxe**

~~~py
as(<variável>):
~~~

**Exemplo**

~~~py
import numpy as np
~~~

**O que faz a função collect:**

Disponibiliza um mecanismo de gerência de memória automático que é responsável por alocar memória para seus objetos e desalocá-la quando esses objetos não possuem mais referência para eles.

**Sintaxe**

~~~py
collect(<variável>):
~~~

**Exemplo**

~~~py
dados_nativos.collect()
~~~

**O que faz a função count:**

Retorna a quantidade de vezes que um mesmo elemento está contido numa lista.

**Sintaxe**

~~~py
count(<variável>):
~~~

**Exemplo**

~~~py
contador = rdd5.count()
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

**O que faz a função getNumPartitions:**

Retorna o número de partições em RDD

**Sintaxe**

~~~py
getNumPartitions <vairável>
~~~

**Exemplo**

~~~py
rdd.getNumPartitions()
~~~

**O que faz a função glom:**

Retorne um RDD criado pela união de todos os elementos de cada partição em uma lista

**Sintaxe**

~~~py
glom <vairável>
~~~

**Exemplo**

~~~py
print(rdd4.glom().collect())
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

**O que faz a função intersection:**

Retorna os elementos que aparecem em ambos conjuntos.

**Sintaxe**

~~~py
 intersection (<variável>)
~~~

**Exemplo**

~~~py
dados1 = sc.parallelize(['A', 'B', 'C', 'D', 'E'])
dados2 = sc.parallelize(['A', 'E', 'I', 'O', 'U'])

result = dados1.intersection(dados2)
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

**O que faz a função str:**

Converte um dado para string.

**Sintaxe**

~~~py
str( <variável> ):
~~~

**Exemplo**

~~~py
str(height)
~~~

**O que faz a função take:**

Pegue os primeiros elementos num do RDD.

**Sintaxe**

~~~py
take( <variável> ):
~~~

**Exemplo**

~~~py
dados1 = sc.parallelize(['A', 'B', 'C', 'D', 'E'])
dados2 = sc.parallelize(['A', 'E', 'I', 'O', 'U'])

result = dados1.intersection(dados2)
result.take(10)
~~~

**O que faz a função takeSample:**

Retorne um subconjunto de amostra de tamanho fixo deste RDD.

**Sintaxe**

~~~py
takeSample( <variável> ):
~~~

**Exemplo**

~~~py
rdd = sc.parallelize(range(0, 10))
len(rdd.takeSample(True, 20, 1))
~~~

**O que faz a função textFile:**

Leia um arquivo de texto do HDFS, um sistema de arquivos local (disponível em todos os nós) ou qualquer URI de sistema de arquivos compatível com Hadoop e retorne-o como um RDD de Strings. Os arquivos de texto devem ser codificados como UTF-8.

**Sintaxe**

~~~py
textFile( <variável> ):
~~~

**Exemplo**

~~~py
rddANSI = sc.textFile('Biblia-ANSI.txt')
print(rddANSI.take(1000))
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

