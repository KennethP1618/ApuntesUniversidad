# Clase 2
Lunes 6 de abril del 2026
## Proposición recíproca o conversa
q->p , se lee "q entonces p". Se da la conclución primero y luego la causa.
> En estos casos se debe analizar cuál es la causa y cuál es el efecto.

### Tabla de la verdad
|  q | p  | q->p  |
| :------------: | :------------: | :------------: |
| V  |V   |V   |
|   V|  F |   F|
|   F|   V|   V|
|   F|   F|   V|
## Proposición inversa
~p->~q. Se niega la causa y el efecto.
>Si no p entonces no q.

### Tabla de la verdad
|  q | p  | ~p->~q  |
| :------------: | :------------: | :------------: |
| V  |V   |V   |
|   V|  F |   V|
|   F|   V|   F|
|   F|   F|   V|
## Contrapositiva, contrapusta o contrarecíproca
~q->~p
### Tabla de la verdad
| p  |q   |~q   |~p   |~q->~p   |
| :------------: | :------------: | :------------: | :------------: | :------------: |
|  V |V   |F   | F  |V   |
|   V|  F | V  |  F |  F |
|   F|   V|  F |   V|   V|
|   F|   F|   V|   V|   V|
## Bicondicional
p<->q, si y solo si.
>p<->q son verdaderas solo cuando ambas proposiciones son V o F.

### Tabla de la verdad
|  p |q   |p<->q   |
| :------------: | :------------: | :------------: |
|   V|V   |V   |
|   V|  F |  F |
|  F |   V|   F|
|   F|   F|  V |

## Tautología
Es una proposición que es verdadera para todos los valores posibles de sus variables.
Ejemplo: (p->q)<->(~q->~p)
## Falacia
Es una proposición que es falsa en todos sus valores posibles de sus variables.
Ejemplo: p^~p
## Contingencia
La proposición puede ser verdadera o falsa dependiendo de los valores de sus variables.
Ejemplo: (p->q)^(pvq)
>Todos los análisis de las proposiciones se basan en lo general, lo usual o la norma en que suelen ocurrir los eventos.

## Equivalencia lógica
Dos expreciones que son diferentes pero con resultados iguales.
signo: ≡

Ejemplo: (p->q)≡(~q->~p)
 >(p->q) y (~q->~p) tienen la misma tabla de la verdad.
 
# Leyes de álgebra de proposiciones
## Idempotencia
Dada una misma proposición con operador ^,v el resultado es la proposición

pvp≡p

p^p≡p
## Asociativa
Reorganizar los paréntesis no cambia su valor

(pvq)^r ≡ pv(q^r)

(p^r)^r ≡ p^(q^r)
>Solo se puede hacer esto, solo si los operadores son iguales.

## Conmutativa
El orden de las proposiciones no importa.

pvq ≡ qvp
## Distributiva
pv(q^r) ≡ (pvq)^(pvr)
>El operador afuera del paréntesis se coloca dentro, y el que está adentro se coloca afuera.

## Involución
Doble negación
~~ p ≡ p
## DeMorgan
El operador cambia de ^ a v , y viceversa.

Ejemplo: 
~(pvq) ≡ ~p^~q

~(p^q) ≡ ~p v ~q
# Resumen
|  p->q |p^q   |p<->q   |pvq   |
| :------------: | :------------: | :------------: | :------------: |
|   V+F = F|V+V = V   |V+V = F+F = V   |F+F = F   |
