# 🐾 Woofitos (Demo UI/UX) - Dispensador IoT

Bienvenido al demostrador visual interactivo de **Woofitos**. 

Este repositorio aloja la versión *Frontend Estática* del panel de control de Woofitos, optimizada para visualizarse desde GitHub Pages. El objetivo de este proyecto es demostrar las capacidades de diseño de interfaces web (UI), experiencia de usuario (UX) y manipulación del DOM mediante Vanilla JavaScript, simulando un entorno de **Internet de las Cosas (IoT)**.

> ⚠️ **NOTA IMPORTANTE:** Esta es una versión "Maqueta" interactiva (Mockup) diseñada exclusivamente para este portafolio. Las conexiones a bases de datos y la telemetría en tiempo real mediante Sockets han sido reemplazadas por simuladores en JavaScript para permitir su ejecución en navegadores sin necesidad de hardware.

🔗 **[¡Prueba la Demo Interactiva Aquí!](https://David-Bermudez1532.github.io)**

## ✨ Características de la Interfaz

* 🎨 **Diseño Moderno:** Interfaz responsiva *Single Page Application* (SPA) basada en Glassmorphism y Dark Mode, diseñada para usarse en dispositivos móviles y de escritorio.
* 🔐 **Simulación de Login:** Flujo completo de inicio de sesión y simulación de la recuperación de contraseña basada en "Preguntas de Seguridad".
* 📊 **Telemetría Animada:** Panel de control principal que simula la recepción de datos de un sensor analógico (como una celda de carga o potenciómetro) en tiempo real, cambiando de color (Verde/Amarillo/Rojo) según el nivel del plato.
* 🛡️ **Panel de Administración (Hidden Feature):** Interfaz secreta (CRUD) de gestión de usuarios (Bóveda), accesible únicamente mediante roles simulados de Administrador, donde se demuestran funciones de borrado de bases de datos.

## ⚙️ Arquitectura del Proyecto Original (Hardware Real)

Aunque esta versión es solo el cascarón visual, el producto real detrás de Woofitos fue construido utilizando la siguiente arquitectura:

* **Microcontrolador:** Arduino UNO Q (STM32 + Linux MPU).
* **Backend:** Python + Flask + Socket.IO para comunicación bidireccional de baja latencia.
* **Hardware:** Potenciómetro (simulador de peso) y Servomotor (dispensador de comida).
* **Base de Datos:** SQLite3 con Control de Acceso Basado en Roles (RBAC).
* **Conexión RPC:** Comunicación directa entre el Firmware (C++) y el Servidor Web (Python) usando `Arduino_RouterBridge`.

## 🛠️ Tecnologías Utilizadas en este Demo
* HTML5 (Semántico)
* CSS3 (Vanilla, Flexbox/Grid)
* JavaScript (ES6+, LocalStorage, SetInterval)

---
*Diseñado y programado por David Bermudez.*
