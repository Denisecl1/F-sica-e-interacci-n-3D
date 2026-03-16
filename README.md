# Simulación de Colisiones en Three.js

## Descripción del Proyecto

Este proyecto consiste en una simulación interactiva en **Three.js** que demuestra el uso de colisiones en entornos tridimensionales utilizando una estructura espacial **Octree**.

El usuario puede desplazarse dentro del escenario, interactuar con objetos físicos y observar el comportamiento de colisiones entre el jugador, el entorno y diferentes esferas generadas dentro de la simulación.

El objetivo principal es comprender el funcionamiento de los sistemas de detección de colisiones en entornos 3D y su aplicación en motores gráficos modernos.

---

## Tecnologías Utilizadas

* **Three.js** – Biblioteca para gráficos 3D en la web
* **JavaScript (ES Modules)**
* **GLTFLoader** – Carga de modelos 3D
* **Octree** – Optimización para detección de colisiones
* **Capsule Collider** – Colisión del jugador
* **lil-gui** – Panel de depuración
* **Stats.js** – Monitor de rendimiento (FPS)

---

## Funcionalidades Implementadas

* Navegación dentro de un entorno 3D
* Sistema de colisión con el escenario
* Física básica con gravedad
* Interacción mediante lanzamiento de esferas
* Colisiones entre esferas
* Colisión entre el jugador y los objetos
* Sistema de depuración visual con Octree
* Interfaz gráfica de control

---

## Controles de Interacción

| Acción          | Control             |
| --------------- | ------------------- |
| Mover jugador   | **W A S D**         |
| Saltar          | **SPACE**           |
| Mirar alrededor | **Mouse**           |
| Lanzar esferas  | **Click del mouse** |

---

## Estructura del Proyecto

```
project/
│
├── index.html
├── main.css
├── models/
│   └── gltf/
│       └── collision-world.glb
│
└── js/
    └── main.js
```

---

## Funcionamiento General

1. Se crea la escena 3D utilizando **Three.js**.
2. Se carga un modelo del escenario mediante **GLTFLoader**.
3. El modelo se convierte en una estructura **Octree** para optimizar las colisiones.
4. El jugador se representa mediante un **Capsule Collider**.
5. Se aplican físicas básicas como gravedad y velocidad.
6. Se generan esferas que interactúan físicamente con el entorno y el jugador.

---

## Ejecución del Proyecto

1. Clonar el repositorio

```
git clone https://github.com/tuusuario/turepositorio.git
```

2. Abrir el proyecto en un servidor local (por ejemplo con VSCode Live Server).

3. Ejecutar el archivo:

```
index.html
```

---

## Objetivo Académico

Este proyecto fue desarrollado como parte de una actividad académica con el propósito de:

* Comprender el uso de motores gráficos en la web.
* Implementar detección de colisiones en entornos 3D.
* Aplicar estructuras espaciales como **Octree** para optimización.
* Analizar la interacción física entre objetos en tiempo real.

---

## Autor

** Diana Denise Campos Lozano | ITIC'S**

Proyecto desarrollado con fines educativos para el aprendizaje de gráficos 3D y simulación de colisiones en la web.
