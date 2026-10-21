# Error de sintaxis en Java

`.\ErrorJava.java:3: error: ')' or ',' expected`
        `System.out.println("Esto es un error de sintaxis";`
                                                         ^
`1 error`
`error: compilation failed`

Este error de sistaxis ocurrio porque se omitió el cierre de la instrucción System.out.println, dejando incompleta la llamada al método.

*Código con error:* `System.out.println("Esto es un error de sintaxis"`

*Solución*
- Se agregó el cierre ); para completar correctamente la instrucción.


*Código corregido:*`System.out.println("Esto es un error de sintaxis");`


Después de corregir el error, el programa volvió a ejecutarse correctamente.