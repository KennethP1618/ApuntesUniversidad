# Conteo y probabilidad

## Probabilidad de evento

P(E) = el número de resultado E / el número de resultados S = N(E) / N(S)

## Probabilidad como conjunto
E, especio muestral equivale a U conjunto universal.

A, es un evento.

AUB, almenos uno de los dos eventos A o B ocurre.

A∩B, los dos eventos ocurren.

A^c, el evento no ocurre.


Ejemplo 1:
Se lanza un dado de 6 caras

A = sale par
B= sale primo

Se desea AUB, par o primo
A = {2, 4, 6}
B = {2, 3, 5}

y el 1 queda fuera de los 2 conjuntos.

AUB = {2, 3, 4, 5, 6}

cantidad de elementos de la unión = 5
cantidad de elementos totales = 6(el dado completo)

Operación:
5/6 = 83.3%


Ejemplo 2:
A = sale par

B = Sale primo

Se desea que salga par y primo

A∩B = {2}

P(A∩B) = 1/6 = 16.7%


Ejemplo 3:
A = sale par

B = sale primo

Se desea que no salga par, A^c

A^c = {1, 3, 5}

3 / 6 = 50%


## Propiedades
- Si A y B son conjuntos excluyentes
P(AUB) = P(A) + P(B)

- Si A∩B ≠ ∅
P(AUB) P(A) + P(B) - P(A∩B)

- Si A y su complemento se suman:
P(A) + P(A^c) = 1 = 100%

- Si B es dependiente de A la ocurrencia de A influye en la ocurrencia de B entonces:
P(A∩B) = P(A) / P(B/A)
P(B/A) es la probabilidad del evento B asbiendo que a ocurrido A.
