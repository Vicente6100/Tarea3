# Tarea3
Tarea 3 Vicente


Descripción Este sistema permite a los usuarios jugar a un juego llamado GraphQuest

Este sistema ha sido desarrollado en lenguaje C y puede ejecutarse fácilmente utilizando Replit. Para comenzar a trabajar con el sistema en tu equipo local, sigue estos pasos:

Pasos para compilar y ejecutar:

Descarga el archivo .zip en una carpeta de tu elección.
Abre el proyecto en Replit
Entrar a https://replit.com/~.
Iniciar Sesión
Selecciona + > Import an existing proyect > Zip file y elige la carpeta donde se encuentra el proyecto.
Carga el archivo y selecciona `View app ´
Compila el código
Abrir la librería desde arriba a la derecha (Ctrl + Shift + L en su defecto)

Seleccionar 'Files'

Arrastrar el archivo .csv hasta la carpeta 'data'

Abre el archivo principal (tarea3.c).

Selecciona `+ > Shell ´ para abrir la terminal integrada

En la terminal, compila el programa con el siguiente comando (ajusta el nombre si el archivo principal tiene otro nombre):

  gcc tdas/*.c tarea3.c -Wno-unused-result -o tarea3
Luego ejecuta la aplicación con:

  ./tarea3
Funcionalidades :

FUNCIONANDO CORRECTAMENTE:

Cargar Laberinto
Iniciar partida ;
-> Recoger objeto
-> Descartar objeto; 
-> Movimiento hacia Arriba, Abajo, Izquierda y Derecha
-> Reiniciar partida
-> Verificar condiciones de victoria o derrota al llegar a la salida

PROBLEMAS CONOCIDOS :
-No detiene la carga de un segundo mapa en caso de que se haga
-La derrota solo se muestra al llegar a la salida, el tiempo se sigue descontando aun al acabarse
-El código no tiene documentación 

A MEJORAR :

OPTIMIZACION DEL TIEMPO DE DESARROLLO
Eficiencia al momento de cargar el archivo csv
Especificación de errores 
Condiciones de derrota
Posibilidad de volver a recoger objetos descartados
otras funcionalidades para mejorar la QOL
La visual del repositorio de github
El orden 

Ejemplo de uso


Paso 1: añadir el csv a los archivos accesibles

-Se comienza añadiendo el archivo a la carpeta data (graphquest.csv para este ejemplo).

Paso 2: cargar el csv


Opción seleccionada: 1) Cargar Laberinto
Buscar el archivo .csv en la carpeta data
Apretar click derecho
Seleccionar "Copy file path"
Apretar click derecho en la consola y seleccionar "paste"
Apretar Enter
El programa carga el laberinto y está listo para realizar las siguientes funciones


Paso 3:Iniciar el juego

Paso3.1: Moverse
Opción seleccionada: 3) Avanzar
Ingrese la dirección : 2) Abajo
El sistema procede a mostrar los datos de todas las canciones del genero 'spanish' (a excepción del género, ya que sería redundante).

Paso 3.2: Recoger objeto
Opción seleccionada: 1) Recoger objeto 
La lista muestra todos los objetos disponibles en la sala
Ingrese el objeto a recoger  : 1) Cuchillo peso: 1kg valor: 3pts
La lista muestra todos los objetos disponibles en la sala

Paso 3.3: Descartar objeto
Opción seleccionada: 2) Descartar objeto 
La lista muestra todos los objetos disponibles en el inventario
Ingrese el objeto a descartar  : 1) Cuchillo peso: 1kg valor: 3pts

Paso3.4: Reiniciar partida
Opción seleccionada: 4) Reiniciar partida
La partida se reinicia y el juego vuelve al estado original

Paso3.5: Salir
Opcion seleccionada: 5) Salir
El juego termina y la aplicacion se cierra


