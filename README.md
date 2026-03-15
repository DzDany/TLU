# Implementación de Funciones Lógicas con TLU (Threshold Logic Unit)

Este repositorio contiene un proyecto educativo desarrollado en un Jupyter Notebook (`main.ipynb`) que explora los fundamentos de las redes neuronales artificiales a través de la **Unidad Lógica de Umbral (TLU)**.

[Image of Threshold Logic Unit diagram showing inputs, weights, summation, and threshold function]

## 🎯 Objetivo

El objetivo principal es comprender cómo una neurona artificial simple puede ser configurada para comportarse como diferentes compuertas lógicas, estableciendo las bases para entender modelos más complejos como el Perceptrón.

## 🚀 Contenido del Código

El notebook está dividido en las siguientes etapas clave:

1.  **Definición de la TLU**: Implementación de una función en Python que calcula el producto punto entre entradas y pesos, aplicando un umbral de decisión.
2.  **Compuertas Básicas (Linealmente Separables)**:
    * **AND**: Se activa solo cuando ambas entradas son 1.
    * **OR**: Se activa cuando al menos una entrada es 1.
    * **NOT**: Implementación de la inversión lógica (una sola entrada).
3.  **Compuertas Complejas**:
    * **NAND y NOR**: Demostración de universalidad lógica.
    * **XOR**: Resolución del problema mediante la combinación de múltiples TLUs (Red Multicapa), ya que no es separable linealmente con una sola unidad.
4.  **Visualización de Fronteras de Decisión**:
    * Gráficos que muestran la línea de separación matemática entre las clases (0 y 1) en un plano cartesiano.

[Image of linear separation in logic gates showing points separated by a decision boundary line]

## 🛠️ Tecnologías Utilizadas

* **Python 3**: Lenguaje base.
* **NumPy**: Para el manejo de vectores y operaciones matemáticas.
* **Matplotlib**: Para la generación de gráficas de dispersión y líneas de decisión.

## 📊 Visualización de Resultados

El código incluye una función `plot_gate` que genera visualizaciones como las siguientes:
* **Puntos (o)**: Representan la salida lógica "1" (Verdadero).
* **Cruces (x)**: Representan la salida lógica "0" (Falso).
* **Línea continua**: Representa la frontera de decisión aprendida/configurada.

## 📝 Cómo utilizarlo

1.  Clona el repositorio:
    ```bash
    git clone [https://github.com/tu-usuario/nombre-repo.git](https://github.com/tu-usuario/nombre-repo.git)
    ```
2.  Asegúrate de tener instaladas las dependencias:
    ```bash
    pip install numpy matplotlib
    ```
3.  Ejecuta el entorno
