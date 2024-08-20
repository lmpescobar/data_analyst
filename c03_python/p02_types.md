# Types of Data - Numbers and Boolean Values

### 1. Números
Python soporta varios tipos de números:

#### a. **Enteros (`int`)**
- **Descripción**: Los enteros son números enteros, sin ningún punto decimal.
- **Ejemplo**: `5`, `-10`, `42`
- **Operaciones**: Se pueden realizar operaciones aritméticas como suma (`+`), resta (`-`), multiplicación (`*`), división (`/`), exponenciación (`**`), módulo (`%`), y división entera (`//`) con enteros.

#### b. **Números de Punto Flotante (`float`)**
- **Descripción**: Los `float` son números que tienen un punto decimal.
- **Ejemplo**: `3.14`, `-0.001`, `2.71828`
- **Operaciones**: Los `float` soportan las mismas operaciones aritméticas que los enteros, pero con mayor precisión debido a su capacidad para representar valores fraccionarios.

#### c. **Números Complejos (`complex`)**
- **Descripción**: Los números complejos son números que tienen una parte real y una parte imaginaria, representados como `a + bj`, donde `a` es la parte real y `b` es la parte imaginaria.
- **Ejemplo**: `3 + 4j`, `-2.5 + 0.5j`
- **Operaciones**: Se pueden realizar operaciones aritméticas con números complejos, incluyendo suma, resta, multiplicación y división, tratando ambas partes, real e imaginaria.

### 2. Valores Booleanos (`bool`)
- **Descripción**: Los valores booleanos representan uno de dos valores: `True` (Verdadero) o `False` (Falso). Se usan a menudo en declaraciones condicionales para controlar el flujo de un programa.
- **Ejemplo**: `True`, `False`
- **Operaciones**: Los valores booleanos pueden combinarse usando operadores lógicos:
  - **AND (`and`)**: Devuelve `True` si ambos operandos son verdaderos. Ejemplo: `True and False` resulta en `False`.
  - **OR (`or`)**: Devuelve `True` si al menos uno de los operandos es verdadero. Ejemplo: `True or False` resulta en `True`.
  - **NOT (`not`)**: Devuelve el valor opuesto del operando. Ejemplo: `not True` resulta en `False`.

#### Los valores booleanos se usan comúnmente en:
- **Condicionales**: Sentencias `if`, `elif`, `else` para controlar el flujo del programa.
- **Bucles**: Bucles `while`, donde se verifica una condición antes de cada iteración.

### Ejemplos:
```python
# Números
a = 10       # Entero
b = 3.14     # Flotante
c = 2 + 3j   # Número complejo

# Operaciones aritméticas
suma = a + b            # Suma
resta = a - b           # Resta
producto = a * b        # Multiplicación
cociente = a / b        # División

# Valores booleanos
esta_soleado = True
esta_lloviendo = False

# Operaciones lógicas
resultado_and = esta_soleado and esta_lloviendo   # False
resultado_or = esta_soleado or esta_lloviendo     # True
resultado_not = not esta_soleado                  # False
```