# Práctica de Árbol AVL en Java

## 📌 Información General

- **Título:** Práctica de Implementación de Árbol AVL (Autobalanceado)
- **Asignatura:** Estructura de Datos
- **Carrera:** Computación
- **Estudiantes:** Nicolas Cedillo - Mateo Miller
- **Fecha:** 08 / 07 / 2025
- **Profesor:** Ing. Pablo Torres

---

## 🛠️ Descripción

Este proyecto en Java implementa y demuestra el funcionamiento de un **Árbol AVL** (Árbol Binario de Búsqueda Autobalanceado), mostrando cómo se mantienen equilibrados de manera automática mediante rotaciones en las inserciones.

Incluye:

- 🌳 **Inserción de nodos:** Agrega elementos al árbol y realiza rotaciones (simples y dobles) para mantener el equilibrio.
- 🔄 **Rotaciones automáticas:** Se ejecutan rotaciones derecha, izquierda, derecha-izquierda e izquierda-derecha según el factor de equilibrio.
- 📏 **Altura y balanceo:** Cada nodo almacena su altura y se calcula el factor de equilibrio tras cada inserción.
- 📋 **Recorridos y orden de inserción:** Permite mostrar los valores en orden de entrada y en recorrido inorden.
- 🖨️ **Detalle de operaciones:** Muestra en consola cada paso y rotación realizada durante la inserción.

---

## 🧪 Estructura

- `AVLTree.java`: Clase principal con métodos para inserción, rotaciones, recorridos y registro del orden de inserción.
- `Node.java`: Clase para representar un nodo del árbol AVL (valor, altura, hijo izquierdo y derecho).
- `App.java`: Punto de entrada que ejecuta los ejemplos y muestra los resultados en consola.

---

## 🚀 Ejecución

Para ejecutar el proyecto:

1. Compila el código:
    ```bash
    javac App.java
    ```
2. Ejecuta la aplicación:
    ```bash
    java App
    ```

---

## 🧑‍💻 Ejemplo de Salida

```
Nombres: Nicolas Cedillo - Mateo Miller
Insertando valor: 10
Nodo creado con valor: 10
Inserción completa de: 10

Insertando valor: 20
Ir a la derecha de 10
Nodo creado con valor: 20
Altura actualizada de 10: 2
Balance de 10: -1
Inserción completa de: 20

Insertando valor: 15
Ir a la derecha de 10
Ir a la izquierda de 20
Nodo creado con valor: 15
Altura actualizada de 20: 2
Balance de 20: 1
Altura actualizada de 10: 3
Balance de 10: -2
Rotación Derecha-Izquierda en 10
Ejecutando rotación derecha en 20
Rotación derecha completada. Nueva raíz del subárbol: 15
Ejecutando rotación izquierda en 10
Rotación izquierda completada. Nueva raíz del subárbol: 15
Inserción completa de: 15

Valores en orden de entrada:
10 20 15 
Recorrido inorden del árbol:
10 15 20 
```

---

## 📂 Organización de Archivos

```
AVLTree.java
Node.java
App.java
README.md
```
