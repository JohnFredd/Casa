# Casa 3D en Unity 🏠  
Un proyecto educativo desarrollado en **Unity** que consiste en la creación de una pequeña escena 3D: una casa simple construida con buenas prácticas de desarrollo y un jugador en primera persona para explorarla.

Incluye piso, paredes, columnas, texturas básicas y un controlador FPS descargado desde la Asset Store.

---

## 📋 Descripción del Proyecto

Este proyecto es un prototipo de escenario 3D hecho con Unity que demuestra conceptos fundamentales como:

- Construcción de estructuras 3D simples
- Organización del proyecto (prefabs, empties, materiales)
- Movimiento básico en primera persona
- Uso de texturas con mapas: albedo, normal map, AO, height
- Buenas prácticas de jerarquía y organización.

---

## 🎮 Características Principales

### **Control del Jugador**
Se utiliza un **Personaje en Primera Persona (FPS Controller)** obtenido desde la Asset Store.

**Controles:**
- **W, A, S, D** – Movimiento básico
- **Mouse** – Mirar alrededor
- **Espacio** – Saltar (si el controlador lo permite)

### **Mundo de Juego**
- Casa hecha con cubos escalados (paredes, columnas, piso)
- Jerarquía organizada mediante empties
- Materiales con texturas PBR (albedo, normal, AO)
- Objetos marcados como **Static** para optimización

---

## 📁 Estructura del Proyecto
~~~
Assets/
├── Materials/ # Materiales finales del proyecto
├── Textures/ # Texturas descargadas (albedo, normal, AO…)
├── Prefabs/ # Prefabs estructurales
├── Starter Assets/ # Assets del personaje en primera persona
├── Scenes/
│ └── MainScene.unity # Escena principal

~~~

# 🎨 Materiales y Texturas

El proyecto utiliza mapas PBR:

- **Base Map (Color)**
- **Normal Map (IGL/OpenGL)**
- **Ambient Occlusion Map**
- **Height Map (para displacement)**
- **Smoothness** ajustado manualmente


## 🎯 Buenas Prácticas Aplicadas

- Jerarquías limpias con vacíos organizadores (e.g., `Columns`, `Walls`, `Player`)
- Nombres descriptivos:  
  - `KColumn01` (Kitchen Column)  
  - `LRColumn01` (Living Room Column)
- Objetos marcados como **Static** para mejorar rendimiento
- Prefabs reutilizables (columnas, paredes)
- Separación de carpetas por **Materials**, **Textures**, **Models**, **Player**, etc.
- Manejo de versiones con git usando `.gitignore` y `README.md`.

## 🚀 Cómo Ejecutar

1. Clona el repositorio:

~~~
git clone <URL_DEL_REPOSITORIO>
~~~

2. Abre Unity Hub  
3. Selecciona **Open Project**  
4. Navega hasta la carpeta del proyecto  
5. Abre la escena: **MainScene**
6. Presiona **Play** para explorar la casa en primera persona.

---

## 🎓 Propósito Educativo

Este proyecto busca poner en práctica:

- Organización profesional en Unity
- Creación de estructuras simples
- Configuración de materiales PBR
- Control de jugador en primera persona
- Gestión de escenas y jerarquías
- Uso eficiente de prefabs y objetos estáticos

---

## Hecho por

**John Freddy Belalcazar Rojas**  
Codigo de estudiante 202182464
john.freddy.belalcazar@correounivalle.edu.co
---