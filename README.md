# Plataforma IoT – Proyecto de Tesis

Sistema IoT desarrollado como proyecto de tesis de **Ingeniería en Telecomunicaciones**.<br>
El objetivo del trabajo fue diseñar e implementar un **prototipo funcional de punta a punta**,<br>
integrando hardware, software embebido, backend y frontend web.

## 📌 Contexto del proyecto

Este proyecto forma parte del trabajo final de la carrera de Ingeniería en Telecomunicaciones.<br>
El enfoque fue principalmente **práctico**, priorizando la integración real de todos los<br>
componentes de una plataforma IoT: desde el dispositivo físico hasta la visualización de datos<br>
en una aplicación web.

El sistema permite gestionar dispositivos IoT, comunicarse mediante MQTT, almacenar datos<br>
y administrarlos desde una plataforma web.


## 🧩 Arquitectura general

  <img src="infografiaProyecto.jpg" alt="Diagrama" style="max-width: 250px; width: 80%;" >


La solución está compuesta por los siguientes módulos:

- **Dispositivo IoT** basado en ESP32
- **Backend (API REST)** para autenticación, gestión de usuarios y dispositivos
- **Frontend web** para administración y visualización de información
- **Documentación pública de la API**

Cada componente fue desarrollado y probado de forma independiente, y luego integrado
en <br>un sistema completo.


## 📦 Componentes del proyecto

### 🔌 Firmware – Dispositivo IoT (ESP32)

Firmware del dispositivo IoT prototipo, encargado de la comunicación y el envío de datos <br>
hacia la plataforma.

👉 Repositorio:  
https://github.com/adriangallicet/ESP32firmware


### 🌐 Plataforma IoT – Backend, Frontend y Despliegue

Repositorio principal que contiene la implementación completa del sistema, incluyendo:

Backend (API REST): encargado de la autenticación, gestión de dispositivos, usuarios y datos.<br> La autenticación se realiza mediante cookies HTTP-only.

Frontend (Plataforma Web): interfaz para la administración de dispositivos IoT y la visualización<br> de información en tiempo real.

Configuración de despliegue: archivos necesarios para la ejecución del sistema en <br>entornos contenerizados (Docker).

👉 Código fuente:
https://github.com/adriangallicet/plataforma-IoT

👉 Documentación de la API:
https://adriangallicet.github.io/api_doc/

## Documento de tesis

El documento completo del trabajo, donde se describe el diseño conceptual,
la arquitectura del<br> sistema y el proceso de desarrollo, se encuentra disponible en:

📄 https://docs.google.com/document/d/1W36_iQEKb8CZaM5dWwVYeTbvXX8ZUFgp/edit?usp=sharing&ouid=107966421185917265597&rtpof=true&sd=true



## 🚧 Estado del proyecto

- ✔ Prototipo de dispositivo IoT funcional
- ✔ API REST implementada y documentada
- ✔ Plataforma web operativa
- ✔ Comunicación mediante MQTT
- ✔ Autenticación basada en cookies
- ✔ Proyecto **cerrado académicamente**

El proyecto queda **abierto a mejoras y extensiones futuras**.


## 🎓 Alcance académico

Este trabajo fue desarrollado con fines académicos como parte de la tesis de
Ingeniería en <br>Telecomunicaciones.  El foco estuvo puesto en la arquitectura del sistema, la integración de <br>tecnologías
y la implementación de una solución IoT realista y funcional.


## 🎥 Demo

Actualmente no hay una demo online.
Está previsto agregar una **demo visual (GIF o video corto)** <br>mostrando el funcionamiento
general de la plataforma y la interacción con el dispositivo IoT.


## 👤 Autor

**Adrián Gallicet**  
Proyecto de tesis – Ingeniería en Telecomunicaciones

