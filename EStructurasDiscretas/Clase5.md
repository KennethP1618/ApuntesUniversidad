# Clase 5
Miércoles 15 de abril del 2026

# Inferencia lógica y lógica de predicados
## Inferencia
Herramientas para la declaración de una o mas premisas.

## Tipos de inferencia
### Transductiva
De lo particular a lo particular o de lo general a lo general. Predice valores.
Ejemplo:
LLegó tarde la primera semana, llegará taarde el lunes.

### Inductiva
De lo particular a lo general. Conclucion provable pero no certera.
Ejemplo:
El profesor llegó tarde una semana entonces, llegará tarde todo el semestre.

### Deductiva
De lo general a lo particular. Conclución 100% certera.
Ejemplo:
Siempre que llueve hay nubes -> hoy llueve -> Hoy hay nubes.

### Abductiva
Analiza posibilidades sin conclución certera.
Ejemplo:
Si llueve hay nuebes. Hoy hay nubes, ¿Llovió?

# Lógica propocicional
## Argumento (Intuitivo)
1. Todos los hobbits habitan en la comarca.
> Esto sería p.

2. Ningúngún habitante de la comarca sufre de estrés.
> Esto sería q

3. Por lo tanto, ningún hobbit sufre de estrés.

Analicemos solo p
∀x( H(x) -> C(x) )
>Todo esto representa SOLO p.

Significado de los símbolos:
- ∀: cuantificador universal.
- H: representa a los Hobbitses.
- C: representa a la comarca
- x: individuo o elemnto
>Nota: Generalmente se usan letras mayúsculas para representar los elementos en la propocicion.

# Cuantificadores
## ∀: cuantificador universal.
∀x(H(x) -> M(x))
Todos los hombres son mortales.

##  Ǝ: cuantificador existencial
 Ǝx( H(x) ^ C(x) )
Algunos hobbitses son comilones.

# Propociciones categóricas
## Universal afirmativa (A)
∀x(L(x) -> P(x))
Todos los limeños son peruanos.

## Universal negativa (E)
∀x(C(x) -> ~A(x))
Ningún congresista es adolescente.

## Particular afirmativa (I)
Ǝx( U(x) ^ S(x) )
Algunos universitarios son San Marquinos.

## Particular negativa (O)
Ǝx( J(x) ^ ~C(x) )
Algunos jueces no son corruptos.
