Los operadores relacionales comparan datos numéricos, de serie de caracteres o lógicos. El resultado de la comparación, ya sea Verdadero ( 1 ) o falso ( 0 ), puede utilizarse para tomar una decisión referente al flujo del programa (consulte la sentencia IF ). 
La Tabla 1 lista los operadores relacionales.
   1.EQ o =               Igualdad                X = Y
   2.NE o #               Desigualdad             X # Y
   3.>< o <>              Desigualdad             X <> Y
   4.LT o <               Menor que               X < Y
   5.GT o >               Mayor que               X > Y
   6.LE o <= o =< o #>    Menor que o igual a     X <= Y
   7.GE o >= o => o #<    Mayor que o igual a     X >= Y 
Cuando en una expresión se utilizan tanto operadores aritméticos como operadores relacionales, las operaciones aritméticas se realizan primero. Por ejemplo, la expresión:
X + Y < (T - 1) / Z
Las comparaciones de series se efectúan comparando los valores ASCII de los caracteres únicos de cada serie. La serie con el equivalente de código ASCII numérico más alto se considera mayor. Si todos los códigos ASCII son iguales, las series se consideran iguales.
Si las dos series tienen longitudes distintas, pero por lo demás la serie más corta es idéntica al principio de la serie más larga, la serie más larga se considera mayor.
Un espacio se evalúa como menor que cero. Los espacios iniciales y finales son significativos. Si dos series se pueden convertir en valores numéricos, la comparación siempre se realiza numéricamente.
