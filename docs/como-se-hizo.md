# ⚙️ Arquitectura y Flujo de Trabajo

Este sistema no es solo una página web; es una arquitectura descentralizada diseñada para gestionar prompts de Inteligencia Artificial. Está construido pensando en que cada usuario pueda tener su propio entorno privado, mientras colabora con una base de datos global.

> [!NOTE]
> Este proyecto utiliza **MkDocs** con el tema **Material for MkDocs**, alojado y desplegado automáticamente mediante **GitHub Pages** y **GitHub Actions**.

---

## 🏗️ El Modelo "Hub & Spoke" (Centro y Radios)

Para mantener la organización, utilizamos un modelo de bifurcación (Fork) y submódulos. 

### 1. Tu Wiki Personal (El Fork)
No necesitas empezar desde cero. Puedes clonar toda la estructura, configuraciones y automatizaciones a tu propia cuenta de GitHub haciendo un **Fork**.

* Al hacer Fork, obtienes una copia exacta de este repositorio.
* Podrás agregar tus propios prompts en tus carpetas locales.
* Tu Wiki se publicará en tu propia dirección (ej. `tu-usuario.github.io/prompt_templates_system`).
* **Tus prompts serán tuyos:** Lo que agregues a tu repositorio bifurcado no afectará el repositorio principal.

### 2. Sincronización de Mejoras (Sync Fork)
Si el repositorio original (`atonab/prompt_templates_system`) recibe actualizaciones en su motor (nuevos plugins, mejoras de diseño o corrección de errores), no te quedarás atrás. 

Desde tu repositorio en GitHub, simplemente haz clic en el botón **"Sync Fork"** (Sincronizar bifurcación). Esto descargará las mejoras del sistema central sin borrar ni sobrescribir los prompts personales que hayas creado.

---

## 🌍 La Base de Datos Global (Comunidad)

Para evitar que los prompts personales se mezclen con los públicos, el sistema utiliza un repositorio hermano llamado `prompt_ts_global`. Este repositorio está incrustado en todas las Wikis mediante un **Git Submodule**.

### ¿Cómo funciona la colaboración?
1. **Lectura:** Cuando despliegas tu Wiki, el sistema descarga automáticamente los prompts aprobados de la comunidad y los muestra en la carpeta `docs/comunidad/`.
2. **Aportación:** Si has creado un prompt increíble en tu Wiki personal y quieres compartirlo con el mundo, no haces un *Pull Request* al motor principal. En su lugar, haces el *Pull Request* directamente al repositorio global (`prompt_ts_global`).
3. **Actualización:** Una vez que tu prompt es aprobado en el repositorio global, todas las Wikis del mundo que sincronicen su submódulo verán aparecer tu prompt en sus sistemas.

> [!TIP]
> **¿Quieres aportar?** Visita el repositorio global (enlace pendiente) para leer las guías de contribución y el formato estándar de los archivos `.md`.