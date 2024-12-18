Este trabajo consta de tres apartados

En el primero se realiza un análisis de las características de una base de datos de flores. El objetivo es desarrollar un motor capaz de reconocer los diferentes tipos de flores en una imagen. Para ello buscaremos que características representan mejor nuestros datos y con ellas foramr un vector de características. Las características que probaremos principalmente son:

Color: Histograma RGB
Forma: Histograma de gradientes orientados (HOG)
Textura: Patrones binarios locales (LBP)

En el segundo apartado solucionaremos el problema de reconocer piezas en un tablero de ajedrez. La idea es la misma que en el primer apartado, por lo que deberemos encontrar el vector de características que mejor representa a cada pieza.

Por último, en el tercer apartado volveremos a la base de datos de flores, para encontrar una solución mas eficiente que la del primer apartado. Para ello utilizaremos redes neuronales que deberemos ajustar para desarrollar un motor de busqueda aceptable.