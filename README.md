Simulación de Sistemas Cuánticos – Capítulo 4
Descripción general

Este proyecto implementa un simulador de sistemas cuánticos basado en los conceptos introducidos en el Capítulo 4 del texto guía, siguiendo los ejercicios y retos propuestos.
El sistema permite representar y analizar el comportamiento de una partícula confinada a un conjunto discreto de posiciones en una línea, así como realizar cálculos fundamentales de la mecánica cuántica con vectores ket, matrices hermitianas y operadores unitarios.

El proyecto fue desarrollado en Python (usando Jupyter Notebook) y subido a GitHub de manera incremental según los avances semanales.

Funcionalidades principales
  1. Sistema cuántico discreto
     Permite definir el número de posiciones y asignar un vector ket que describe el estado cuántico de la partícula.
     Calcula la probabilidad de encontrar la partícula en una posición determinada.

  2. Amplitud y probabilidad de transición
     Dado un segundo vector ket, el sistema calcula la probabilidad de transición del primer estado al segundo tras una observación.
     Implementa el concepto de amplitud de transición mediante el producto interno entre kets.

  3. Observables y operadores
     Verifica si una matriz dada es hermitiana.
     Si lo es, calcula la media (valor esperado) y la varianza del observable en el estado dado.
     Determina los valores propios y las probabilidades de transición a los vectores propios después de una observación.

  4. Dinámica del sistema
     Simula la evolución de un estado inicial aplicando una serie de matrices unitarias (Un).
     Calcula el estado final después de aplicar las transformaciones cuánticas.

Ejemplos incluidos
El proyecto incluye ejemplos desarrollados a partir de los ejercicios propuestos en el libro:

- Problema 4.3.1
- Problema 4.3.2
- Problema 4.4.1
- Problema 4.4.2
Además, se incluyen las discusiones teóricas y de resultados correspondientes a los ejercicios 4.5.2 y 4.5.3.
