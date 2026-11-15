# Bitacora de prompts

Laboratorio 06: Fundamentos de Ingenieria de Prompts. Herramienta de IA usada: chatgpt

## Ejercicio 2: Tokens y ventana de contexto

| Texto                              | Caracteres | Tokens |
| ---------------------------------- | ---------- | ------ |
| Los estudiantes programan en Java. | 35         | 8      |
| The students program in Java.      | 30         | 7      |
| desafortunadamente                 | 18         | 4      |

## Explicar con mis palabras pasos 4 y 5

Como se menciona lo que pasa en los pasos 4 y 5 no es más que el contexto de chat de la inteligencia artifical con la que se esta hablando. La I.A no tiene el contexto cuando se cambia de chat o se inicia una nueva conversación.

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos                             |
| ----------- | -------------- | ----------------------------------------------------- |
| 0           | 100.0%         | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5         | 65.3%          | LibroYa, BiblioTec, BiblioTec, BiblioTec, BiblioTec   |
| 1           | 44.5%          | BiblioTec, BiblioTec, BiblioTec, LectoGo, PrestaLibro |
| 1.8         | 32.2%          | LibroYa, BiblioTec, PrestaLibro, LectoGo, PrestaLibro |

## Ejercicio 4: Prompt vago vs estructurado

| Criterio                            | Prompt vago | Prompt estructurado |
| ----------------------------------- | ----------- | ------------------- |
| Menciona el objetivo del sistema    | No          | Sí                  |
| Menciona a los usuarios principales | No          | Sí                  |
| Tiene exactamente 3 funcionalidades | No          | Sí                  |
| Esta en 3 parrafos                  | No          | Sí                  |
| Lo usaria en un informe real        | No          | Sí                  |

## Ejercicio 5: Anatomia de un prompt

| Componente  | Texto de mi prompt                                                                                                                                                                                                                                                                                                                 |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Rol         | Actua como desarrollador Java. Crea un programa en Java.                                                                                                                                                                                                                                                                           |
| Instruccion | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda.                                                                                                                                                                                                                                |
| Contexto    | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos codigo, nombre, precio y stock.                                                                                                                                                     |
| Ejemplo     | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos codigo, nombre, precio y stock. Explica primero la estructura de la clase y luego presenta el codigo Java. Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |
| Formato     | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos codigo, nombre, precio y stock. Explica primero la estructura de la clase y luego presenta el codigo Java.                                                                          |

## ¿Que cambio en cada componente?

1.-Lo que basicamente ví fue que al principio con el primer componente la I.A me sugirió de que manera lo podría hacer el proyecto. \
2.-Con el segundo componente la I.A se pudo a codificar pero ya haciendo con lo que me había sugerido. En el otro componente cambio lo que había hecho con los requirimiento que se lo había dicho. \
3.-Posteriormente en los otros componentes volvío a rehacer el código con lo que se le mencionó, además de indicarme la estructura de las carpetas del proyecto y de que manera se vería la hecho además de darme un resumen de lo que había hecho.
