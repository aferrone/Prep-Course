Explicacion de conceptos:



--------


Concepto N°1 Variables

Las variables son la base de la programacion, ellas contienen, dependiendo del codigo que le escribamos dentro
diferentes usos y fines para la programacion. ellas contienen codigos o valores que nosotros le enseñemos, configuremos y se grabaran en el sistema para luego llamarlas y que apliquen tal funcion asignada.
es como un juego de cartas : 

1° tengo 1 carta con Diamante : a esta le coloco el nombre de var Diamante
2° a esta var Diamante le agrego un valor de AS = 12 puntos  " Var Diamante = 12 
3° al momento de necesitarla en el juego solo tengo que llamarla y aplicará la funcion de 12 puntos.

Concepto N°2 Strings 

Strings serian bloques de texto que agreguemos. 
al agregarle un nombre en letras a nuestra carta como var "Diamante" estamos creando un String que seria "Diamante".
Tambien puede llamarse Numbers si el nombre fuese escrito solo en numeros, ejemplo " var 12 "  en vez de "var diamante " 


Concepto N°3 Funciones ( argumentos "return" )

Una funcion en un codigo que vamos a crear, el cual tendra un fin especifico cuando sea llamado por nosotros.
Es como la carta Var Diamante, esta Variable ( carta Diamante) tiene un valor de 12 puntos. 
si se enfrenta contra una carta de 11 puntos, no va a hacer nada hasta que yo no aplique la palabra clave para que mi carta se presente ante esta y gane con su valor mas elevado. 
tendria que enseñarle a la carta las diferentes palabras para que actue:

function presentar ( presentaria su valor de 12 puntos)
var Diamante ( estoy llamando a la carta )
var 12 ( le estoy diciendo que valor contiene)

un argumento es cuando le agregas mas opciones a una misma funcion, por ejemplo que la carta var diamante, diga hola cuando sea presentada. Entonces tendria 2 funciones encerradas en una, presentarse y saludar.

La declaracion return es una manera de finalizar el camino del juego, indicas que no hay vuelta atras ni mas opciones al realizar la ultima function. A manera simple, una vez presntada la Var Diamante de 12 puntos, que saludara, y peleara contra la de 11 puntos, de por finalizada la accion indicando que hasta ese punto se puede toamr accion.

Concepto N°4 Declaraciones If

Se puede optar por estas declaraciones si se le quiere agregar una opcion a desarrollar a la funcion dependiendo de lo que se presente. 
ejmeplo con la carta Var diamante, se le puede agregar if si se crea una variable con la carta de 11 puntos, que si en dado caso que la carta de 11 puntos, sea en realidad una de 12, que la nuestra var diamante tome la opcion de no presentarse, en este caso eso seria una ( Declaracion If)

Concepto N°5 valores Booleanos ( true - false) 

Son aquellos valores que agregamos como opciones decisivas, dependiendo de los desencadenadores que configuremos.
Son opciones binarias, como Si o No.

Volvemos a la carta "Var Diamante", si le agregamos valor Booleano, podemos hacer que se de cuenta si tienn que presentar su valor de 12 puntos dependiendo de si la carta de 11 es o no lo que se espera.
Se le agregaria el valor de true si la carta que de 11 es en realidad de 11 puntos, y esto desencadenaria que nuestra var diamante omita la declaracion If y presente su valor de 12 puntos junto con el String "hola".
Del caso contrario que la carta de 11 sea una de mayor valor, nuestra var diamante lanzara un False, desencadenando la declaracion if y tome la opcion de no presentar su valor.



