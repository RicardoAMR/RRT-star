# Notebook del algoritmo de un RRT*

Este proyecto contiene un notebook en Python que, al ejecutarse, genera un mapa con obstáculos aleatorios, un comienzo y un objetivo. Este problema se resuelve mediante el algoritmo RRT*. Además, no solo mide el tiempo que tarda en obtener el camino hasta el objetivo, generando un archivo `.txt` con dicho tiempo registrado, también genera un archivo `.gif` donde se muestra el progreso de las iteraciones y cómo avanza hasta obtener el camino.

## Instrucciones de Uso

1. **Pre-requisitos**:
   - Asegúrate de tener instalado [Jupyter Notebook](https://jupyter.org/) o [JupyterLab](https://jupyter.org/install).
   - Tener instalado Python 3.7 o superior.

3. **Pasos dentro del Notebook**:
   - Simplemente ejecuta la única celda del notebook. 
   - Al finalizar, el notebook generará un archivo llamado `resultados.txt` que contiene el tiempo total de ejecución, además de una ventana con el mapa y el camino encontrado.
   - También se generará un archivo `rrt_star_animation.gif` donde guarda el progreso de la búsqueda con el tiempo.

4. **Salida**:
   - El archivo `resultados.txt` estará en el mismo directorio donde se encuentra el notebook.
   - El contenido del archivo mostrará el tiempo de ejecución total en segundos.
   - Una imagen al final del notebook mostrando el mapa con el camino obtenido.
   - El archivo `rrt_star_animation.gif` mostrando el progreso de obtención del camino.

## Estructura del Proyecto

- `rrt_star.ipynb`: Contiene el código que ejecuta las operaciones y mide el tiempo.
- `resultados.txt`: Archivo de salida que se genera automáticamente al ejecutar todas las celdas del notebook.
- `rrt_star_animation.gif`: Archivo de salida que se genera automáticamente al ejecutar la celda del notebook.
