npm - node package manager

package.json

JSON

JavaScript Object Notation

nodemon  es node monitor 
mocha es para pruebas, pruebas automatizadas. tiene criterio para saber si esa prueba fue satisfactoria o no. Test unitario.
mocha --recursive
usa describe(), it(). 
Describe espera un titulo como parámetro (describe el tipo de la case), un segundo parámetro una función.
It recibe un string que describe lo que va a pasar si se cumple lo que describe el Describe.

Se separa el test en tres partes
//preparación
//ejercicio
//validación

test driven development // su objetivo no es hacer pruebas QA, su objetivo es crear software de calidad

nodemon puede ejecutar mocha
nodemon --exec mocha --recursive