# [Tutorial] Usando Unittest 
### Framework de Testes Unitários do Python 
O módulo unittest fornece um conjunto amplo de ferramentas para a construção e execução de testes.

### Documentações de apoio:
  - [Biblioteca Python - Unittest: Início](https://docs.python.org/pt-br/dev/library/unittest.html)
  - [Biblioteca Python - Unittest: Métodos assertivos](https://docs.python.org/pt-br/dev/library/unittest.html#assert-methods)
  - [POO - Programação Orientada a Objetos](https://docs.python.org/pt-br/dev/library/unittest.html#assert-methods)

## Problema

Vamos imaginar um problema simples, você uma classe chamada func-math que contém algumas funções que executam calculos matemáticos. 
Neste exemplo inicial temos duas funções:
  - factorial (Calcula o fatorial de um número N)
  - fibonacci (Retorna a sequencia de Fibonacci até um valor N)

Precisamos testar essas funções para sabermos se de fato elas funcionam e retornam os valores esperados, para isso, criamos uma class chamada TestFuncMath que conterá as funções responsáveis por testar os métodos. 