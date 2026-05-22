# 📋 Checklist Dinámico con Respaldo Inteligente

Un gestor de tareas (*To-Do / Checklist*) moderno, minimalista y ultraeficiente, diseñado para organizar tus actividades diarias en diferentes estados y pestañas de manera fluida y automatizada.

Este proyecto fue desarrollado íntegramente dentro del entorno **Antigravity** utilizando la metodología de **Vibecoding**, donde la inteligencia artificial y el desarrollo guiado por contexto se fusionan para crear software sin necesidad de escribir código de forma manual.

---

## 🛠️ Tecnologías Utilizadas

La aplicación destaca por un stack tecnológico limpio, ligero y extremadamente rápido, representado mediante los siguientes componentes:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

- **HTML5 & JavaScript Vanilla (ES6+):** Lógica pura del lado del cliente, manejo dinámico del DOM y control del flujo de estados sin frameworks pesados.
- **Tailwind CSS (vía CDN):** Framework de estilos utilitarios que dota a la aplicación de su estética moderna, responsiva y pulida.
- **LocalStorage API:** Mecanismo de persistencia nativo en el disco duro del dispositivo para mantener los datos al apagar el equipo.
- **JSON Data Handling:** Estructura de objetos ligera para la exportación e importación transparente de copias de seguridad.
- **Taste-Skill Architecture (`Leonxlnx/taste-skill`):** Implementación de reglas avanzadas de diseño instaladas mediante `pnpm` para eliminar patrones genéricos de IA y alcanzar un acabado visual comercial de gama alta.

---

## ✨ Características Principales

- 🔄 **Organización por Estados & Pestañas:** Clasifica tus tareas al instante en tres vistas dinámicas: *Todas*, *En Progreso* y *Completadas*. Al cambiar el estado de una tarea a "Terminada", esta se mueve automáticamente a su pestaña correspondiente.
- 💾 **Persistencia Local Inmune:** Utiliza el `LocalStorage` del navegador para que tus datos sigan ahí aunque cierres la pestaña, el navegador o apagues por completo tu computadora.
- 🛡️ **Respaldo Automático Inteligente por Actividad:** Para evitar pérdidas accidentales si se limpia la caché del navegador, la aplicación incluye un contador interno. Cada vez que acumulas exactamente **5 acciones** (crear tareas o cambiar estados), el sistema genera y descarga automáticamente un archivo de seguridad llamado `respaldo_tareas.json`.
- 🎨 **Interfaz Premium y Minimalista:** Diseñado bajo estándares estéticos de alta fidelidad, con un modo oscuro nativo suave (sin negros puros agresivos), tipografía curada, espaciados perfectos y un menú desplegable totalmente personalizado (*Custom Dropdown*) adaptado al diseño general,
