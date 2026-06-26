# PROY-2026-GRUPO 2

Repositorio del grupo 2 para el proyecto del ramo *Proyecto Inicial (IWG400)* – 2026.

## 👥 Integrantes del grupo

| Nombre y Apellido | Usuario GitHub | Correo USM               | Rol USM      |
| ----------------- | -------------- | ------------------------ | ------------ |
| Andrés Vásquez    | @guyuu         | avasquezf@usm.cl         | 202630027-7  |
| Javier Alvarez    | @TheShrike253  | jalvaresp@usm.cl         | 202630036-6  |
| Julian Landeros   | @ChleJulian    | jlanderos@usm.cl         | 202630024-2  |

## 📝 Descripción breve del proyecto

>Mini tesla es un auto a control remoto con integracion de ia unico en la placa de desarrollo "Arduino UNO Q", Este es un "juguete" seguro para niños y el bolsillo, Ya que tanto su diseño como sus sensores permiten el uso en infantes con neurodivergencias los cuales tiendan a destruir sus juguetes, Asi aportando al mundo con un poco de ayuda a la diversidad infantil

---

## 🎯 Objetivos

- Objetivo general:
  - *Desarrollar un vehículo robótico controlado remotamente desde una página web HTML, utilizando Arduino UNO Q y comunicación a través de una red Wi-Fi local.*

- Objetivos específicos:
  - *Diseñar y ensamblar el chasis y los componentes electrónicos del vehículo sobre Arduino UNO Q.*
  - *Crear una interfaz web en HTML que permita al usuario controlar el vehículo de forma intuitiva.*
  - *Establecer una comunicación estable entre el vehículo y la página web dentro de la misma red Wi-Fi.*
  - *Implementar los movimientos básicos del vehículo: avance, retroceso y giros a izquierda y derecha.*
  - *Ejecutar pruebas de funcionamiento para validar la estabilidad de la conexión y la respuesta del control remoto.*
  - *Explorar la integración de un modelo de inteligencia artificial (LLM) para el reconocimiento de paredes, documentando los avances y resultados obtenidos.*

---

## 🧩 Alcance del proyecto

> El proyecto abarca el diseño físico del vehículo, el desarrollo del sistema de control remoto vía web y las pruebas de funcionamiento del conjunto. Ambos dispositivos —el vehículo y el navegador— deben encontrarse conectados a la misma red Wi-Fi para que el sistema opere correctamente.
>
> Quedan fuera del alcance la navegación autónoma y el reconocimiento inteligente de obstáculos. Si bien se investigó la posibilidad de integrar un LLM para la detección de paredes, se determinó que su implementación resultaba innecesaria para los objetivos planteados, ya que el sistema de control remoto manual cubre de forma suficiente las necesidades del proyecto. Por esta razón, dicha funcionalidad se limita a una exploración documentada y no forma parte del producto final.

---

## 🛠️ Tecnologías y herramientas utilizadas

- Lenguaje(s) de programación:
  - Python, JavaScript, C++ y HTML
- Microcontroladores
  - Arduino UNO Q, ESP32
  - L298n Mini
- Sensores
  - Sensor hc-sr04
-Motores
 -2 Motores DC

---

## 🗂️ Estructura del repositorio

```
/PROY-2026-GRUPO-2
│
├── Docs/               # Documentación general y reportes
├── Test-projects/      # Casos de prueba
└── README.md           # Este archivo
```

---

## 🚀 Instrucciones de Instalacion y Uso


1. Carga del proyecto
No es necesario utilizar comandos en la terminal para clonar el proyecto. Debe abrir la carpeta principal, denominada Mini-tesla-final/, directamente en App Lab.

2. Gestión de dependencias
El sistema resuelve todos los requerimientos de forma automática, por lo que no requiere instalaciones manuales.

3. Ejecución: Se ejecuta presionando el botón de "Run"/"Iniciar" dentro de App Lab, que compila el sketch, lo sube al microcontrolador, y arranca la app Python en el lado Linux de la placa al mismo tiempo. Cuando arranca bien, App Lab muestra un banner con la IP local de la placa (ej. http://192.168.x.x:7000) — esa es la URL que abres desde el celular/PC, en la misma red WiFi.

---

## 📐 Diseño del Sistema
![Diagrama de Conexiones](./assets/diagrama_conexiones.png)

*Explicacion grafica de como es la conexion entre el microcontrolador y los sensores*

---

## 📅 Cronograma de trabajo

[Carta Gantt](https://usmcl-my.sharepoint.com/:x:/r/personal/jalvarezp_usm_cl/Documents/Carta%20gantt%20editada.xlsx?d=w62360be1ce6241b5a0af8534450cbacc&csf=1&web=1&e=oKIsLb)

---

## 📚 Bibliografía

[programacion](https://docs.arduino.cc/programming/)
[software](https://docs.arduino.cc/software/)

---

## 📌 Notas adicionales

> *Espacio para dejar cualquier comentario útil, como pendientes, acuerdos del grupo, consideraciones especiales, etc.*
