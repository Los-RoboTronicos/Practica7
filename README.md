# Practica7
## Integrantes
- Uriel Vladimir Alvarez Tapia 20121191
- Miguel Angel Castañeda Garcia 20120015
- Diana Alejandra Mendoza Mendoza 20121226

## Introducción 
![Imagen de WhatsApp 2024-10-23 a las 18 57 04_5238e339](https://github.com/user-attachments/assets/310d48d0-d1df-41e2-b3de-be46eb8b265c)


El comando "pallet" permite al programador definir una estructura de coordenadas que organiza elementos en una disposición regular, generalmente en filas y columnas. Este tipo de configuración es útil cuando se deben realizar tareas repetitivas como apilar productos, manipular cajas o partes en una bandeja, o realizar recogida y colocación de elementos desde una superficie estructurada.
Características principales:
	1. Definición de patrones: Permite configurar matrices en 2D o 3D, ajustando el número de filas, columnas y, en algunos casos, niveles de altura.
	2. Optimización del ciclo: Minimiza el tiempo de programación y asegura precisión en tareas repetitivas de movimiento, lo que es crucial para aplicaciones de fabricación y logística.
Sintaxis del Comando Pallet en Epson RC+

Pallet PalletID, Columnas, Filas, X0, Y0, Z0, X*, Y*. 

Donde:
PalletID es el número de pallet creado; número de comlunas y filas respectiamente.
X0, Y0 y Z0 el punto de referencia de inicio del pallet (puede ser una esquina).
X* y Y* corresponde al ancho y largo de cada sección del pallet.
## Objetivos
Relalizar un dibujo estilo *pixel art* mediante el uso del comando pallet.
## Desarrollo
Como primer paso se seleccionó el patrón a realizar, siendo designado en este caso el dibujo se muestra en la figura 2:
![Creep](https://github.com/user-attachments/assets/b0537dc3-f394-406c-84fe-6a07e2a7e0d0)

Una vez enseñados los puntos, se declaro el pallet y se procedio a realizar el uso fila tras fila comenzando desde la fila uno hasta la fila 7. La declaración y la primera fila se muestran en la figura 4. Además de settear las configuraciones de velocidad y aceleración.
![image](https://github.com/user-attachments/assets/e7d273ef-8510-4c26-82eb-eaeecf861119)

En la figura 5, se muestran las filas 2-7. Enfatizando el uso de ciclos for para la  reduccióm de código.

![image](https://github.com/user-attachments/assets/14938a2a-9c0c-4446-a1d0-4dfae4eceaa3)


## Resultados
Los resultados obtenidos fueron guardados en archivos de video, por lo que es imposible mostrarlo en este documento; sin embargo, la figura 6 muestra el resultado final del código con el modelo finalizado.
![Imagen de WhatsApp 2024-10-23 a las 18 20 36_69198a81](https://github.com/user-attachments/assets/a7ece047-7fb3-4068-9255-1e2911f704b3)



## Conclusiones
- **Uriel Vladimir Alvarez Tapia:** Mediante el comando pallet, se puede agilizar el proceso de creación de pallets permite agilizar la creacion de mallas para situaciones especificas de acomodo o de productos. Además de que el uso de ciclos *for* representa una fuerte optimización de recorrido de de esta matriz y genera un gran numero de puntos predefinidos.
- 
- **Miguel Angel Castañeda Garcia:** A lo largo del ejercicio, se definió una cuadrícula de puntos que representaban los píxeles individuales del dibujo, y el robot fue programado para moverse de manera ordenada por cada uno de los puntos correspondientes.
El uso del comando "pallet" resultó ser fundamental para organizar el espacio de trabajo en una matriz regular, facilitando la programación al permitir el control eficiente del movimiento del robot entre filas y columnas. 

La automatización de este proceso redujo significativamente el tiempo de desarrollo del proyecto, ya que solo fue necesario definir parámetros clave como las dimensiones de la matriz y el espaciamiento entre los puntos, en lugar de especificar manualmente cada posición.
Además, el robot se desempeñó con precisión en la colocación de cada "píxel" en su lugar correspondiente, lo que permitió obtener un resultado final exacto y sin errores de posicionamiento. Esto demuestra cómo la combinación de programación avanzada y herramientas eficientes como el comando "pallet" puede transformar tareas complejas en procesos sencillos y repetibles.


- **Diana Alejandra Mendoza Mendoza:**  En esta práctica, se utilizó un ciclo for para apilar fusibles ajustando el eje Z según la medida de cada uno. A pesar de un pequeño error de medición que afectó la posición de liberación del fusible, el proceso fue exitoso y se logró observar cómo los ciclos for permiten realizar tareas repetitivas con modificaciones precisas en cada iteración. Esto demostró la importancia de los ciclos en la programación de robots industriales, brindando eficiencia en tareas automatizadas.**
