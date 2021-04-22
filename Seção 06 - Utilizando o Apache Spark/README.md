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














