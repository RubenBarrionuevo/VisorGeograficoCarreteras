# Visor Geográfico – Ministerio de Transportes

## 📍 Descripción general

Este proyecto proporciona una **página HTML ligera y optimizada** que actúa como **punto de acceso al Visor Geográfico** desarrollado para el **Ministerio de Transportes**, permitiendo la consulta de **información georreferenciada en tiempo real** a través de un entorno web seguro y responsive.

La solución se basa en la carga del sistema principal mediante un `iframe` a pantalla completa, garantizando una experiencia de usuario fluida, sin distracciones y compatible con dispositivos de escritorio y móviles.

---

## 🎯 Objetivo del proyecto

- Facilitar el **acceso centralizado** al Visor Geográfico institucional.
- Garantizar una **visualización completa y adaptable** en cualquier resolución.
- Mantener una **estructura simple, mantenible y fácilmente desplegable**.
- Asegurar compatibilidad con estándares web modernos y dispositivos móviles.

---

## 🧩 Características principales

- Carga del visor mediante `iframe` a **pantalla completa**.
- Diseño **responsive** gracias al uso de `viewport`.
- Inclusión completa de **favicons oficiales** para múltiples dispositivos y plataformas.
- Metadatos configurados para idioma, autoría y compatibilidad.
- Código HTML limpio, minimalista y sin dependencias externas.

---

## 🛠️ Tecnologías utilizadas

- **HTML5**
- **CSS3**
- **Iframe embebido**
- **Metadatos PWA (manifest.json)**

---

## 📂 Estructura del proyecto

index.html
statics/
 ├── favicon.ico
 └── manifest.json
## 🌐 Acceso al visor

El visor se carga directamente desde la siguiente URL:
https://verticeb.com/ma2/login.php

Este endpoint corresponde al sistema de autenticación y acceso al Visor Geográfico.

## 🔐 Consideraciones de seguridad

- El acceso y control de usuarios se gestiona exclusivamente desde el sistema embebido (login.php).
- Esta página actúa únicamente como contenedor visual, sin manejar credenciales ni lógica de negocio.
- El sistema cuenta con un sistema de acceso robusto, no se permite usar este iframe desde otra dirección, tampoco el acceso a personas no autorizadas.

## ✍️ Autor

Rubén Barrionuevo Jiménez

## 🏛️ Nota institucional

Este proyecto está diseñado como interfaz de acceso a un visor geográfico destinado a la consulta de información georreferenciada en tiempo real, en el marco de los sistemas del Ministerio de Transportes.
