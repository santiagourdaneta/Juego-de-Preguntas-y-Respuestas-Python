# 🧠 QuizMaster: Tu Reto de Conocimientos en Consola (Python)

**QuizMaster** es un sencillo pero adictivo juego de preguntas y respuestas desarrollado enteramente en **Python** para ser ejecutado directamente en la consola (CLI). Este proyecto se enfoca en la implementación de una **lógica de juego interactiva** y **modular**, ideal para entender los flujos de control (`if/else`, `while`), la gestión de estructuras de datos (`listas` y `diccionarios`), y la interacción con el usuario a través de la entrada estándar.

## ✨ Características Funcionales

* **Juego Interactivo:** Ciclo de preguntas y respuestas gestionado completamente en la consola.
* **Múltiples Opciones:** Cada pregunta presenta opciones para una experiencia de usuario dirigida.
* **Feedback Instantáneo:** El usuario recibe una confirmación inmediata si la respuesta es correcta o incorrecta.
* **Sistema de Puntuación:** Se mantiene un contador de aciertos y se presenta una puntuación final, incluyendo el porcentaje de éxito.
* **Estructura de Datos Clara:** Las preguntas y opciones se manejan de manera organizada mediante una lista de diccionarios, facilitando la expansión del contenido.

## 🛠️ Tecnología Principal

| Componente | Tecnología | Propósito |
| :--- | :--- | :--- |
| **Lenguaje Base** | **Python 3.x** | Lenguaje de programación principal. |
| **Interfaz** | **CLI (Consola/Terminal)** | Interacción de entrada/salida a través de la terminal. |
| **Estructuras** | **Listas y Diccionarios** | Modelado de datos para preguntas, opciones y respuestas correctas. |

## 🚀 Instalación y Ejecución

Dado que el proyecto utiliza solo la librería estándar de Python, no se requieren dependencias externas.

### Prerrequisitos

* **Python 3.x** instalado en tu sistema.

### Pasos de Ejecución

1.  **Clonar el Repositorio:**
    ```bash
    git clone [https://github.com/santiagourdaneta/Juego-de-Preguntas-y-Respuestas-Python.git](https://github.com/santiagourdaneta/Juego-de-Preguntas-y-Respuestas-Python.git)
    cd Juego-de-Preguntas-y-Respuestas-Python
    ```

2.  **Ejecutar el Script:**
    Ejecuta el archivo principal usando el intérprete de Python:
    ```bash
    python main.py
    ```

3.  **Jugar:**
    Sigue las instrucciones en la consola para seleccionar tus respuestas y ver tu puntuación final.

## 💡 Extensibilidad

La lógica del juego está separada del contenido. Para añadir nuevas preguntas o modificar las existentes, simplemente edita la estructura de datos 

`quiz_questions` en `main.py`, manteniendo el formato `{'question': '...', 'options': [...], 'answer_index': ...}`.
