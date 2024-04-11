# go-api-interview
## Preguntas teóricas
* ¿Qué son "short variables"?
  * Variables declaradas con el operador de variable corta `:=` cuyo tipo de dato será inferido por el compilador una vez que se le asigne algún valor
* ¿Cuándo puedes utilizar "short variables" y cuando no?
  * Se pueden usar cuando son declaradas por primera vez dentro de una función, ya que cuando se declaran fuera de una función estas sólo pueden hacerse con var y no con el operador de varible corta `:=`
* ¿Qué significa inferencia de tipos de datos?
  * Significa que no se ha especificado explícitamente el tipo de dato de una variable y será el compilador quien lo infiera a partir de lo que encuentre del lado derecho del símbolo `=`
* ¿Puede una constante declararse de manera corta como son "short variables"?
  * No, además de que deben llevar la palabra reservada `const` en lugar de `var`
* ¿Qué es "defer"?
  * Postpone la ejecución de una función hasta el final del bloque de la función que le llamó
* ¿Qué son los "pointer"?
  * Los punteros son variables que guardan direcciones de memoria la cual puede ser reservada dinámicamente en el heap, su desventaja reside en que el garbage collector hace pausas para encargarse de limpiarlas
* ¿Qué es "struct"?
  * Una estructura es una coleción de campos (variables), los cuales dependiendo de su nivel de accesso (público o privado) podrán ser accedidos con el operador del punto `.` o algún receiver (método)
* ¿Qué es "goroutine"?
  * Es la unidad de trabajo empleada en golang al momento de usar concurrencia, se crean anteponiendo la palabra reservada `go` al llamado de alguna función. Las gorutinas al ser un híbrido entre proceso (process) e hilo (thread), consumen pocos recursos al momento de crearse

## Descripción API

## Referencias
