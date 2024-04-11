# go-api-interview
## Preguntas teóricas
* <b>¿Qué son "short variables"?</b>
  * Variables declaradas con el operador de variable corta `:=` cuyo tipo de dato será inferido por el compilador una vez que se le asigne algún valor
* <b>¿Cuándo puedes utilizar "short variables" y cuando no?</b>
  * Se pueden usar cuando son declaradas por primera vez dentro de una función, ya que cuando se declaran fuera de una función estas sólo pueden hacerse con var y no con el operador de varible corta `:=`
* <b>¿Qué significa inferencia de tipos de datos?</b>
  * Significa que no se ha especificado explícitamente el tipo de dato de una variable y será el compilador quien lo infiera a partir de lo que encuentre del lado derecho del símbolo `=`
* <b>¿Puede una constante declararse de manera corta como son "short variables"?</b>
  * No, además de que deben llevar la palabra reservada `const` en lugar de `var`
* <b>¿Qué es "defer"?</b>
  * Palabra reservada que postpone la ejecución de una función hasta el final del bloque de la función que le llamó
* <b>¿Qué son los "pointer"?</b>
  * Los punteros son variables que guardan direcciones de memoria la cual puede ser reservada dinámicamente en el heap, su desventaja reside en que el garbage collector hace pausas para encargarse de limpiarlas
* <b>¿Qué es "struct"?</b>
  * Una estructura es una coleción de campos (variables), los cuales dependiendo de su nivel de accesso (público o privado) podrán ser accedidos con el operador del punto `.` o algún receiver (método)
* <b>¿Qué es "goroutine"?</b>
  * Es la unidad de trabajo empleada en golang al momento de usar concurrencia, se crean anteponiendo la palabra reservada `go` al llamado de alguna función. Las gorutinas al ser un híbrido entre proceso (process) e hilo (thread), consumen pocos recursos al momento de crearse[1]

## Descripción API

## Referencias
[1] J. Cutajar, Learn Concurrent Programming with Go. Manning Publications Co. LLC, 2024.<br>
