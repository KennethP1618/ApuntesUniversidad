# Combinatoria
## Regla del producto
si se puede hacer algo de "a" formas y otras de "b" formas entonces hay (a.b) formas de hacer ambas cosas.
> Es como el producto carteciano en conjuntos

## Permutaciones (sin repetición)
Dados n objetos distintos llamados permutacion a una ordenación particular de los n objetos en una fila.
- Fórmula: n!
Ejempos:
1. Hay 6 posibles permutaciones con 3 letras a, b, c: abc, acb, bac, bca, cab, cba.
3! = 6
2. Con la palabra DISCO cuantas palabras distintas(con o sin sentido) se pueden formar
5! = 120

## Permutaciones con repetición
n! / (a!)(b!)(c!)
Ejemplo:
1. Con los números 2, 4, 4, 6, 6 ¿cuántos números de 5 cifras se pueden formar?
5! /(1!)(2!)(2!) = 30

## Variaciones
Cada una de las tuplas que se pueden formar tomando elementos de un conjunto 
n! / (n-r)!
> Variaciones de n en r

## Variaciones con repetición
n^r

## Combinación (sin repetición)
El orden no importa
n! / r!(n-r)!

## Combinaciones (con repeticion)
El número de combinaciones de n elementos distintos, tomados r a la vez.
(n + r - 1)! / r!(n - 1)!
