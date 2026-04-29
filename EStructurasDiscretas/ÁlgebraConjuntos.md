# Algebra de conjuntos
Miércoles 29 de abril

# Leyes

## Idempotencia
- AUA = A
- A∩A = A

## Asociativa
- (AUB)UC = AU(BUC)
- (A∩B)∩C = A∩(B∩C)

## Conmutativa
- AUB = BUA
- A∩B = B∩A

## Distributiva
- AU(B∩C) = (AUB)∩(AUC)
- A∩(BUC) = (A∩B)U(A∩C)

## Involución
(Ac)c = A

## De Morgan
- (AUB)c = Ac ∩ Bc
- (A∩B)c = Ac U Bc
>El orden no interesa, si se está hablando de conjuntos
Ejemplo: {3,5} = {5,3}

## Parejas ordenadas
Conjunto ordenado, consiste en un conjunto de dos elementos donde uno designa el orden de los elemntos. Se usa paréntesis.
>El orden si importa.

## Conjunto producto
Sea A y B conjuntos. El conjunti de todos las parejas ordenadas (a,b) en donde a∈A y b∈B se llama producto.

AxB = {(a,b); a∈A, b∈B}

AxA = A^2

Los resultados se irán formando en pares ordenados.

Sea A = {1, 2, 3} y B = {a, b} entonces
- AxB = {(1, a), (1, b), (2, a), (2, b), (3, a), (3, b)}
número de elementos = 6.
Notación: n(AxB)= 6 o |AxB| =6
- AxA = {(1, 1),(1,2),(1,3), (2,1), (2,2), (2,3),(3,1),(3,2),(3,3)}
|AxA| = 9

## Relaciones
Sea A y B.  Una relación binaria R de A en B se asigna a cada pareja ordenada (a,b) en AxB.
- a está relacionada con b. aRb
- a no está relacionada con b. aR̶b
A = {huevos,leche,maíz}
B = {Vacas, cabras, gallinas}
R = {(huevos,gallinas),(leche,vacas),(leche,cabras)}

## Relacion de equivalencia
se usa "~" para representar equivalencía

### Tipos de equivalencia
- Reflexiva: para cada elemento "a" en S. Entonces a~a.
- Simetría: si a~b entonces b~a.
- Transitiva: si a~b y b~c entonces a~c.

## Producto carteciano
Sea AxBxCx...
Ejemplo:
A = {1,2}; B = {a,b}; C = {x, y}
AxBxC = {(1,a,x),(1,a,y),(1,b,x),(1,b,y),(2,a,x),(2,b,y),(2,b,x),(2,b,y)}
|AxBxC| = 8
>Se puede representar mediante un grafo.

## Funciones
Cada elemento le corresponde un único valor.
f: A->B
Función de A en B, B es codominio y A el dominio.
Ejemplo:
Sea A = {a, b, c} y B = {r, s, t, u}
f(a) = r, f(b) = u, f(c) = r, f(d) = s
