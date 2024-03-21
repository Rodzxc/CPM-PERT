# CPM-PERT
## Gestión de Proyectos - Duración de tareas 

## Descripción
Te has preguntado cuanto puede durar la fabricación de un producto, un edificio, un emprendimiento o cualquier otro proyecto nuevo? 🤔

En este repositorio se calculan los tiempos de un conjunto de tareas necesarias para completar un proyecto.

## Objetivo

Calcular tiempos de ejecución, tareas críticas, holguras y determinar el tiempo total de un  proyecto con el fin de planificar, programar y controlar las tareas de manera inteligente.

## Resultados
- Diagrama de nodos con el camino crítico, Tiempos tempranos y tardios.
![Nodos](https://github.com/Rodzxc/CPM-PERT/assets/133074545/4dbd255e-fd47-45e8-8aa2-ab671594ff1c)
  
- Diagrama de Gantt con los progresos de cada tarea, holguras, encargados de las tareas y la criticidad (C).
- Probabilidad de terminar el proyecto mediante Distribución Triangular y PERT
- Probabilidad de terminar el proyecto mediante Distribución Normal y Simulación MonteCarlo

## Conclusión
Las probabilidades de finalizar el proyecto, en determinado tiempo, cambia dependiendo del criterio y del grado de incertidumbre asociada a la duración de cada tarea.

Los valores obtenidos en algunos casos no son idénticos o cercanos y esto se debe a que las distribuciones tienen diferentes enfoques.

Distribución Triangular y PERT:

- Estas distribuciones son útiles cuando la duración de las tareas no se conoce con certeza y existe una variedad de posibles escenarios. La distribución triangular es una aproximación simple pero efectiva que considera un valor más probable, un valor mínimo y un valor máximo para la duración de una tarea. La distribución PERT (Program Evaluation and Review Technique) es una versión más refinada que agrega la noción de la estimación más probable y utiliza una fórmula para calcular la media basada en estos tres valores.
Son  más flexibles que la distribución normal y pueden capturar mejor la incertidumbre en la duración de las tareas, especialmente si hay eventos extremos poco probables pero posibles.
Se aplica en proyectos nuevos donde, los tiempos se estiman en base a tareas similares.

Distribución Normal:

- Se utiliza cuando las duraciones de las tareas son más estables y, se puede presumir que siguen una distribución normal. Se aplica cuando se analizan métodos y tiempo en el estudio del trabajo.
