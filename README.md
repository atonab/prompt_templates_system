<div align="center">

# 📚 Prompt Templates System

![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![MkDocs Material](https://img.shields.io/badge/MkDocs_Material-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

*Sistema organizado y documentado de prompts para Inteligencia Artificial.*

</div>

## 🗂️ Sistemas organizado de prompts IA.

Este debe ser el acomodo para guardar una organización, por carpetas estructuradas y archivos de alguna manera seriados para diferenciarlos:

```md
docs/
├── imagenes/
├──── one pice/
├────── cartel wanted/
│       ├── 00-chatgpt.md
│       ├── 00-gemini.md
│       ├── 00-peticion.md
│       ├── 00-prompt-rojo.md
│       ├── 00-prompt-beige.md
│       ├── 01-peticion.md
│       ├── 01-template-prompt.md
│       ├── 02-prompt.md
```

---

Otra organización podría ser, teniendo otro nivel de carpeta y poner algún UUID o autoría:

**Autor:**
```md
docs/
├── imagenes/
├──── one pice/
├────── cartel wanted/
├──────── autor/
│         ├── 00-chatgpt.md
│         ├── 00-gemini.md
│         ├── 00-peticion.md
│         ├── 00-prompt-rojo.md
│         ├── 00-prompt-beige.md
│         ├── 01-peticion.md
│         ├── 01-template-prompt.md
│         ├── 02-prompt.md
```

**UUID:**
```md
docs/
├── imagenes/
├──── one pice/
├────── cartel wanted/
├──────── uuid/
│         ├── 00-chatgpt.md
│         ├── 00-gemini.md
│         ├── 00-peticion.md
│         ├── 00-prompt-rojo.md
│         ├── 00-prompt-beige.md
│         ├── 01-peticion.md
│         ├── 01-template-prompt.md
│         ├── 02-prompt.md
```

---

**Organizado en carpetas:**
- Definido por secciones como imagenes.
*Ej de Carpetas: imagenes/ , videos/, tablas/*
    - Dentro de esta carpeta el identificador especifico, si es un personaje o algo ese sería su nombre. 
    *# Ej: one pice/, los simpsons/*
        - El nombre de la función. # Ej si va ser plantilla para hacer el cartel de wanted en one pice llamamos a la carpeta algo como: cartel wanted/, o en los simpsons para hacer la foto estilo simpsons: estilo simpsons/.

**Organizado de archivos:**
- en el formato `00`-`descripcion de archivo`

Con este modo de serialización podemos tener diferentes *acciones* dentro de la misma serie, como poder tener diferentes colores, peticiones, una variante, un estilo especial, etc...

Si lo prefieres puedes organizar también con una carpeta adicional ya sea marcada como el nombre del `autor` o con un `uuid`.

Para sacar un UUID en una terminal podemos utilizar lo siguiente:

[UUID Tools](https://www.uuidtools.com/)

> [!NOTE]
> El sistema de organización está pensado para que sea de 3 niveles, pero se puede adicionar otra o diferentes capas siguiendo estas 3 primeras como modelo de organización.

---

# 📖 WIKI Interactiva

Toda esta estructura está documentada y servida como una página web estática con buscador, filtrado por etiquetas y modo oscuro/claro.

[https://atonab.github.io/prompt_templates_system/](https://atonab.github.io/prompt_templates_system/)

[![Visitar Wiki](https://img.shields.io/badge/Visitar_la_Wiki-000000?style=for-the-badge&logo=github&logoColor=white)](https://atonab.github.io/prompt_templates_system/)