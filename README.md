# 🎮 Tetris

Implementación del clásico videojuego **Tetris** desarrollada en **Python** utilizando la librería **Pygame**.  
El juego permite controlar la caída y rotación de bloques para completar líneas horizontales y obtener puntos.

Este proyecto fue realizado como trabajo práctico para la materia **Programación I – Universidad tecnológica nacional - Avellaneda**.

---

# 👤 Alumno

Adrián Falasca

# 🛠 Tecnologías utilizadas

- Python 3.12
- Pygame
- SQLite3

---

# 🚀 Características del juego

- Pantalla de inicio con título y opciones
- Ingreso del nombre del jugador desde la interfaz gráfica
- Control de movimiento de los bloques
- Aparición aleatoria de piezas
- Sistema de puntuación (score)
- Cronómetro de partida
- Tres niveles de dificultad
- Ranking con los mejores puntajes
- Pantalla de fin de partida

---

# 🧩 Tipos de bloques

El juego incluye cuatro tipos de piezas:

- Rectángulo
- Cuadrado
- Forma de **T**
- Forma de **L**

---

# 🎮 Modalidad del juego

- Los bloques aparecen de forma **aleatoria**.
- El jugador puede moverlos **hacia la izquierda o derecha** dentro del área de juego.
- Los bloques **descienden automáticamente**.
- Una vez que un bloque llega al fondo, queda fijo.
- El jugador obtiene puntos al completar **líneas horizontales**.
- La partida finaliza cuando **no hay más movimientos posibles** o se termina el tiempo.

---

# 🏆 Sistema de puntuación

El juego guarda el puntaje del jugador al finalizar cada partida.

Se utiliza una base de datos **SQLite3** con una tabla que almacena:

- Nombre del jugador
- Score obtenido

Además, el juego muestra un **Top 5 de mejores puntajes** ordenado de mayor a menor.

---

# 🖥 Pantallas del juego

El juego incluye las siguientes pantallas:

- Pantalla de inicio
- Pantalla de juego
- Pantalla de ranking (Top 5)
- Pantalla de fin de partida

---

# 📦 Instalación y Ejecución

1. **Clonar el repositorio**

```bash
git clone https://github.com/AdrianFalasca/tetris-python.git
```

2. **Entrar en la carpeta del proyecto**

```bash
cd tetris-python
```

3. **Instalar la librería Pygame**

```bash
pip install pygame
```

4. **Ejecutar el juego**), ejecutá:

```bash
python -m tetris.main
```
