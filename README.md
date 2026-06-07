# Tabuada Completa em Python

Projeto simples desenvolvido em Python que exibe a tabuada de 1 a 10 utilizando estruturas de repetição (`while`).

## Tecnologias utilizadas

* Python 3



## Código

```python
tabuada = 1

while tabuada <= 10:
    x = 0

    while x <= 10:
        print(f"{tabuada} x {x} = {tabuada * x}")
        x += 1

    print(" ")
    tabuada += 1
```

## Exemplo de saída

```text
1 x 0 = 0
1 x 1 = 1
...
1 x 10 = 10

2 x 0 = 0
2 x 1 = 2
...
2 x 10 = 20
```

## Objetivo

Praticar:

* Estruturas de repetição (`while`)
* Variáveis
* Operadores matemáticos
* Formatação de strings com f-strings


