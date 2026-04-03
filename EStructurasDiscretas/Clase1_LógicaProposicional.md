# Clase 1
## Lógica propocicional y operaciones lógicas
Puntos importantes a tomar e cuenta para analizar propociciones:
>- Las exclamaciones no son propociciones.
- Los nombres no son propociciones.
- Verbos sin conjugar no son propociciones.

## Operadores
### Negación
solo se aplica a **una sola** propocicion.
Forma: ~p
Se lee como "no p".
Forma alternativa: p̄
Se lee como "p barra o barra p".

#### Tabla de la verdad
|  p | ~p  |
| ------------ | ------------ |
|  V |  F |
|  F |  V |

>Este operador no es conectivo.

Ejemplo:
p: 2+3>1
q: Hace frío

>Nota: aquí es más difícil negar p ya que es una expreción matemática.

Para las negaciones es válido cambiar la oración.
q: Hace frío
~q: Hace calor

##Conjunción
Permite unir, conectar propociciones.
Forma: p^q
Se lee como "p y q"

#### Tabla de la verdad

|  p |  q |  p^q |
| ------------ | ------------ | ------------ |
|  V |V   |V|
|  V |F| F|
|   F| V| F|
|   F|  F| F|

>Nota: si ambas prepociciones son verdaderas el resultado es verdadero.

#### Tabla de la verdad con 3 prepociciones
| p  |q   |r   |   p^q^r|
| :------------: | :------------: | :------------: | :------------: |
| V  |  V |   V|   V|
|  V |   V|   F|   F|
|   V|   F|   V|   F|
|   V|   F|   F|   F|
|   F|   V|   V|   F|
|   F|   V|   F|   F|
|   F|   F|   V|   F|
|   F|   F|   F|   F|

###Disyunción
Forma: p v q 
Se lee "p ó q"

>Nota: La disyunción no es el opuesto a la conjunción

#### Tabla de la verdad

|  p |  q |  p v q |
| ------------ | ------------ | ------------ |
|  V |V   |V|
|  V |F| V|
|   F| V| V|
|   F|  F| F|

Existen 2 casos especiales de disyunción:

#### Excluyente
Ejemplo: Casos de la vida real.
p: Fui al trabajo en auto.
q: Fui al trabajo en bus.

>o voy en bus, o voy en auto. No se puede en ambos.

#### Inclusivo
p: pasé matemáticas
q: reprobé francés
p v q: es posible pasar matemáticas y no aprobar francés y viceversa.

###Condicional
Forma: p -> q
Se lee como "si p entonses q".
p: antecedente o hipótesis.
q: conclución o consecuente.

#### Tabla de la verdad

|  p |  q |  p -> q |
| ------------ | ------------ | ------------ |
|  V |V   |V|
|  V |F| F|
|   F| V| V|
|   F|  F| V|

>Nota: si p es verdadero y q es falso el resultado es falso.
