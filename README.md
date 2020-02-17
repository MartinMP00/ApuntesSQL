# ApuntesSQL

## <ins> Introducción al SQL </ins> <br>

> - Usamos el SELECT para escoger un atributo de la base de datos. <br>
> - Usamos FROM para indicar la base de datos de la que sacamos algo.<br>
> - Usamos WHERE para indicar que queremos coger de la base de datos, lo que queramos escoger debe estar entre ''. Ej: WHERE name = 'Germany'. <br>
> - La palabra IN nos deja comprobar si un ítem está en la lista de la base de datos. <br>
> - BETWEEN nos deja comprobar por rango un atributo. Ej: área BETWEEN 200 AND 560. <br>
> - Podemos usar >, <, >=, <= para partir desde un número concreto. Ej: population >300000. <br>
> - Usamos LIKE si queremos hacer una comparación entre un atributo y una expresión común o un texto, también podemos usar NOT LIKE como negativo. <br>
> - Si queremos hacer uso de una palabra concreta para una consulta, debemos meter la palabra entre porcentajes. Ej: name LIKE %Spain%. <br>
> - Podemos usar ROUND para redondear el número a dos decimales. <br>
> - Utilizamos LENGTH para obtener el número de caracteres en un string. <br>
> - Podemos usar LEFT para dejar aislada la primera letra de un string. <br>
> - ORDER BY lo utilizamos para ordenar según el parámetro introducido. <br>
> - Usamos CONCAT para unir dos valores en una única string, un uso muy frecuente es poner un número con un %. Ej: CONCAT (3, '%') <br>
> - Para instanciar una variable/tabla con el nombre que nosotros queramos usamos AS. <br>
> - SUM sirve para sumar todas las variables almacenadas en un atributo de la tabla. <br>
> - DISTINCT lo podemos usar para escoger solo una vez cada variable almacenada en un atributo de la tabla. Ej: SELECT DISTINCT (continent) nos mostraría una vez cada continente sin repetirlos. <br>
> - GROUP BY agrupa todos los elementos de un atributo en uno.
> - HAVING es una cláusula que podemos usar para comprobar si un atributo cumple una condición concreta. Ej: HAVING SUM(SaleAmount) > 1000
>
