# Capítulo 2: Valores, tipos de datos y variables 

## Clasificación del lenguaje

JavaScript es un lenguaje de programación _[dinámico](https://en.wikipedia.org/wiki/Dynamic_programming_language)_, _[multi-paradigma](https://en.wikipedia.org/wiki/Programming_paradigm#Multi-paradigm)_ y de _[alto nivel](https://en.wikipedia.org/wiki/High-level_programming_language)_.

> Estos términos se explicarán a lo largo de los capítulos.

## Valores y tipos de datos

Un **valor** es una pieza de información o dato utilizado en un programa. Los valores pueden clasificarse, según su _forma_ en lo que llamamos **tipos**. El tipo de un valor determina sus características y las operaciones que podemos realizar con él.

Cada lenguaje de programación tiene definidos sus valores y tipos propios.

### Number

Utilizamos el tipo **number** para representar valores numéricos, sin distinguir entre números naturales, enteros, reales, etc.

**Ejemplo:** 

```
-1
```

```
0
```

```
3.14
```

```
1/3
```

### Ejercicio

[number](http://www.asmarterwaytolearn.com/js/3.html)

### String

Representa valores de texto, conocidos como _cadenas de caracteres_. Se escriben entre comillas simples o dobles, sin mezclar.

**Ejemplo:** 

```"JavaScript no es Java"```

```'JavaScript se hizo en 10 días'```

Si queremos _unir_ diferentes strings, utilizamos una operación que se llama _concatenación_, con el operador **+** (el mismo que usamos para sumar números, pero en este caso *no estamos sumando*).

**Ejemplo:** 

```'Java' + 'Script' => 'JavaScript'```

### Ejercicio

[string](http://www.asmarterwaytolearn.com/js/2.html)

## Variables

Un programa almacena información utilizando _variables_. Una variable es un espacio que reservamos en la _memoria RAM_ y la identificamos con un nombre (por eso conocido como _identificador_). Luego de crear una variable y almacenar un valor en ella, podremos acceder y operar con este valor usando directamente el nombre de la variable.

## Tipado dinámico

En JavaScript, el **tipo** no está definido en la variable, sino en el **valor**. Es por esto que se trata de un lenguaje de programación _dinámico_. 

### Ejercicio

[nombres de variables](http://www.asmarterwaytolearn.com/js/4.html)  

> ✨ Utilizar nombres de variables lo más descriptivos posibles

## Declarando una variable

Antes de poder utilizar una variable (es decir, almacenar información en ella) debemos crearla. Esto se conoce como **declarar una variable**. Declarar una variable implica *reservar espacio en la memoria* para almacenar información. Nuestro programa luego podrá leer o escribir en este espacio de memoria al operar con la variable.

> ✨ Utilizar `const`por defecto. Si queremos *explícitamente definir un valor como variable*, utilizar `let`.

