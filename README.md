Modifiquen el programa del Parser en Python para que sea capaz de reconocer variables y llamadas a funciones como expresiones.
Los nombres de variables y funciones se forman como identificadores que empiezan con una letra minúscula o un guion bajo, seguido por cero o más letras minúsculas, guiones bajos y/o dígitos.
Las funciones pueden tener 0 o más argumentos separados por comas, los cuales pueden ser expresiones.
Ejemplos de expresiones válidas:

###Sample input

a + _e $
5.3 * (2 + x2) $
y5(2, hola, 3.4, 3 * 5) $
2 / (ratio(4) – t_int(2.3, 1.5)) $

###Sample output


sdsd




###¿Cómo?

1. Modifiquen el scanner para aceptar comas e identificadores.
2. Modifiquen la gramática original para aceptar variables y llamadas a funciones como expresiones.
3. Eliminen la ambigüedad en la gramática modificando, si existen, reglas que incluyan recursión izquierda o factores comunes por la izquierda.
4. Modifiquen el código de las funciones que implementan la gramática no ambigua.
5. Prueben el programa y verifiquen que trabaje correctamente.
6. Suban su programa a Blackboard (uno solo de los integrantes).
