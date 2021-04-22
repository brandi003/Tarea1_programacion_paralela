Para compilar este programa necesita posicionarse en la carpeta donde se encuentra este archivo y ejecutar make
Luego de la compilacion debera ejecutar el programa escribiendo la siguiente instruccion en la consola:
./test02
esto hara que el programa se ejecute con 1000 iteraciones y un tamaño del problema de 15000, Para cambiar estos valores
debera poner parametros, los cuales son los siguiente
nx: para el tamaño del problema
nt: para el numero de iteraciones
un ejemplo de ejecucion seria el siguiente
./test02 -nx 30000 -nt 20000

los archivos dentro de el proyecto siguen la siguiente estructura:

/bdiazv/
	+ tarea01/
		+ src/
			+ include/
				- global.hh
				- timing.hpp
			- global.cc
			- main.cc
			- Makefile
		- grafico.png
		- Makefile
		- README.txt	