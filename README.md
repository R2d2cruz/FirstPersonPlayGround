# First Person Playground

**First Person Playground** es un proyecto de prueba desarrollado en **Unreal Engine 5** diseñado para explorar y poner en práctica las mecánicas fundamentales del motor: movimiento en primera persona, combate cuerpo a cuerpo básico, inteligencia artificial con rutas de patrullaje, gestión de interfaz de usuario y persistencia de datos durante la sesión de juego.

---

## 🎮 Características del Juego

### 🏠 Menú Principal Inteligente
- **Pantalla de Inicio Dinámica:** La interfaz cambia según el estado del juego.
- **Registro de Estado:** Muestra si el jugador entra por primera vez o si viene de una partida previa.
- **Estadísticas de Partida:** Muestra si la última partida fue una victoria o una derrota, junto con el número total de enemigos derrotados.

### 🏰 Nivel 1: La Torre
- **Vista en Primera Persona:** Experiencia inmersiva centrada en la perspectiva del personaje principal.
- **Objetivo Principal:** Derrotar o esquivar a los enemigos y alcanzar el **punto azul de victoria** ubicado en lo alto de la torre.
- **Inteligencia Artificial (Enemigos):** Cuenta con 3 enemigos en el nivel que realizan rondas de patrullaje e interactúan mediante un sistema de navegación (*NavMesh*).

---

## 🕹️ Controles

El juego utiliza el esquema de control estándar para PC en primera persona:

| Acción | Tecla / Botón |
| :--- | :--- |
| **Moverse** | `W` `A` `S` `D` |
| **Saltar** | `Espacio` |
| **Correr** | `Shift Izquierdo` |
| **Ataque Básico (Puño)** | `Clic Izquierdo` |
| **Combo (Puño + Puño)** | `Doble Clic Izquierdo` |
| **Ataque Cargado** | `Mantener Clic Izquierdo` |
| **Patada** | `Clic Derecho` |

---

## 🛠️ Detalles Técnicos

* **Motor:** Unreal Engine 5
* **Lógica:** Implementada mediante **Blueprints**
* **Mecánicas Clave:**
  * Uso de **Game Instance** para conservar contadores y estados entre niveles.
  * Sistema de combate basado en montajes de animación (*Anim Montages*).
  * Lógica de patrullaje e IA con *NavMeshBoundsVolume*.
  * Interfaz de usuario interactiva creada con *UMG Widgets*.

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/first-person-playground.git](https://github.com/tu-usuario/first-person-playground.git)
