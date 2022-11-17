# TypeScript

TypeScript es un lenguaje de programación libre y de código abierto desarrollado y mantenido por Microsoft. Es un superconjunto de JavaScript, que esencialmente añade tipos estáticos y objetos basados en clases.

## ¿Qué tipo de ejecución tiene el lenguaje?

TypeScript es un lenguaje compilado o Transpilado fuertemente tipado el cual para ejecutarse se compila/traduce a JavaScript.

## ¿Para qué tipo de desarrollo se utiliza normalmente el lenguaje?

TypeScript es usado para desarrollar aplicaciones JavaScript que se ejecutarán en el lado del cliente o del servidor, o extensiones para programas (Node.js y Deno).

## ¿Con que ide o editor de texto puede utilizar el lenguaje? Nombre de una librería o framework famoso del mismo.

Visual Studio Code, un editor de texto de Microsoft, integra decenas de herramientas muy interesantes para Typescript. Tales como:

- Instrucciones de imports automáticos
- Transpilado automático a JavaScript
- Codelens con conteo de referencias a una clase, función o variable
- Soporte para JSDoc
- Y más

Algunos frameworks de TypeScript son:

- NestJS
- FeatherJS
- LoopbackJS
- AdonisJS
- Ts.Ed

# Investigar y realizar en la sintaxis del lenguaje dado, la siguiente operación matemática

```TypeScript
const x:number = 4;
const y:number = 5;
const z:number = x + y;

console.log(z);
```

output : `9`

# Erlang

Erlang es un lenguaje de programación concurrente (u orientado a la concurrencia) y un sistema de ejecución que incluye una máquina virtual (BEAM) y bibliotecas (OTP).

## ¿Qué tipo de ejecución tiene el lenguaje?

El subconjunto de programación secuencial de Erlang es un lenguaje funcional, con evaluación estricta, asignación única, y tipado dinámico.

Proporciona el cambio en caliente de código de forma que este se puede cambiar sin parar el sistema. Originalmente, Erlang era un lenguaje propietario de Ericsson, pero fue cedido como software de código abierto en 1998. La implementación de Ericsson es principalmente interpretada, pero también incluye un compilador HiPE (sólo soportado en algunas plataformas).

## ¿Para qué tipo de desarrollo se utiliza normalmente el lenguaje?

Fue diseñado en la compañía Ericsson para realizar aplicaciones distribuidas, tolerantes de fallos, soft-real-time y de funcionamiento ininterrumpido.

## ¿Con que ide o editor de texto puede utilizar el lenguaje? Nombre de una librería o framework famoso del mismo.

Emacs es un editor de texto con una gran cantidad de funciones, muy popular entre programadores y usuarios técnicos. GNU Emacs es parte del proyecto GNU y la versión más popular de Emacs con una gran actividad en su desarrollo. El manual de GNU Emacs lo describe como «un editor extensible, personalizable, auto-documentado y de tiempo real».

ErlIde es otro editor de texto diseñado para erlang, el cual permite
- Resaltado de sintaxis de código
- Mostrar estructura de código en esquema
- Búsqueda y navegación a la definición/referencias de elementos de código
- Autocompletado para elementos de código
- presentación de documentación del código y OTP
- Sangría correcta del código


# Investigar y realizar en la sintaxis del lenguaje dado, la siguiente operación matemática

```erlang
main(_) -> 
X=4, Y=5, Z= X + Y, io:format("~w",[Z]).
```

output : `9`
