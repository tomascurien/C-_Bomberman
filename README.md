# Bomberman SFML

Un clon del clásico **Bomberman** desarrollado en **C++** utilizando la biblioteca **SFML**, con sistemas de colisiones, enemigos, bombas, mejoras y pantallas de menú.

---

## 📋 Tabla de Contenidos

* [Características](#características)
* [Clases Principales](#clases-principales)
* [Capturas de Pantalla](#capturas-de-pantalla)
* [Tecnologías Utilizadas](#tecnologías-utilizadas)
* [Ejecución](#ejecución)
* [Estructura del Proyecto](#estructura-del-proyecto)
* [Autor](#autor)

---

## 🚀 Características

✔️ Pantalla de inicio con selector de opciones (Start / Reglas)
✔️ Generación aleatoria del escenario en cada partida
✔️ Movimiento fluido del jugador
✔️ Colocación de bombas con explosiones animadas
✔️ Enemigos con movimiento e interacciones con el entorno
✔️ Mejora de habilidades: velocidad, fantasma, rango de bomba
✔️ Sistema de colisiones con pared, bloques y explosiones
✔️ Reinicio completo del escenario al morir

---

## 🧩 Clases Principales

* **Intro** → Maneja el menú principal y la pantalla de reglas
* **Escenario** → Genera el mapa y administra la matriz del terreno
* **Personaje** → Control del jugador y sus interacciones
* **Bomba** → Colocación, explosión y destrucción del entorno
* **Enemigo** → IA básica y movimiento dentro de la matriz
* **Mejora** → Ubicación aleatoria y aplicación de bonus

---

## 🖼️ Capturas de Pantalla

<img width="851" height="752" alt="Screenshot_Bomberman" src="https://github.com/user-attachments/assets/ddc86b3e-cf8b-4e7c-9098-c56cb6f4cf12" />
<img width="255" height="253" alt="Screenshot_Explosion" src="https://github.com/user-attachments/assets/db062571-4ab0-4403-b7af-d059cbe59972" />
<img width="255" height="203" alt="Screenshot_Pelea" src="https://github.com/user-attachments/assets/76039966-ab7b-479e-9d3a-d6ba96ec8c7c" />


---

## 🛠️ Tecnologías Utilizadas

### Lenguaje y Librerías

* **C++17**
* **SFML 2.6**
* **TAU (Testing)**

### Herramientas

* CodeBlocks

---

## ▶️ Ejecución

1. Instalar SFML
2. Ejecutable en /bin/release
3. Ejecutar ProyectoBomberman.exe


---

## 📁 Estructura del Proyecto

```
📦 Bomberman
 ┣ 📂 Imagenes
 ┣ 📂 src
 ┃ ┣ Intro.cpp / .h
 ┃ ┣ Escenario.cpp / .h
 ┃ ┣ Personaje.cpp / .h
 ┃ ┣ Bomba.cpp / .h
 ┃ ┣ Enemigo.cpp / .h
 ┃ ┣ Mejora.cpp / .h
 ┣ main.cpp
 ┣ README.md
```

---

## 👤 Autor

Proyecto desarrollado por **Tomás Curien**.
