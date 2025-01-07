# Pautas de contribución

¡Gracias por contribuir a este proyecto! Esta guía explica cómo organizar las configuraciones y agregar contenido nuevo siguiendo el esquema del repositorio.

---

## Estructura del repositorio

El repositorio está organizado de la siguiente manera:

```
/
├── README.md                 (Documento principal del proyecto)
├── CONTRIBUTING.md           (Pautas de contribución)
│
├── configs/                  (Directorio de todas las configuraciones)
    ├── Anemo/                (Organizado por elementos)
    │   ├── Kaedehara Kazuha/
    │       └── C6 On-Field ST.json     (Configuración en formato JSON)
    │       └── C6 On-Field MT.json
    │       └── Kaedehara Kazuha.md     (Documento principal con explicaciones)
    ├── Electro/
    │   └── Clorinde/
    │       └── C1 Aggravate Combo [Q 5N3E].json
    │       └── Clorinde.md
    ├── Dendro/
    │   └── Alhaitham/
    │       └── C0 Aggravate Combo.json
    │       └── Alhaitham.md
    ├── Geo/
    │   └── Albedo/
    │       └── Dynamic Transient Blossoms.json
    │       └── Skill And Burst Damage.json
    │       └── Albedo.md
    ├── Hydro/
    │   └── Barbara/
    │       └── C0 Aggravate Combo.json
    │       └── Barbara.md
    ├── Pyro/
    │   └── Amber/
    |   └── Hu Tao/
    |   └── etc...
    └── .../
```

### Detalles importantes:

1. **Directorio `configs/`:**

   - Todas las configuraciones se ubican en este directorio principal, organizadas por el elemento del personaje (Anemo, Pyro, etc.).
   - Cada personaje tiene su propio subdirectorio dentro del directorio de su elemento.

2. **Archivos `.json`:**

   - Contienen las configuraciones a importar en [Genshin Optimizer](https://frzyc.github.io/genshin-optimizer/#/).
   - Su nombre debe describir claramente la configuración (por ejemplo, `C6 On-Field ST.json`).

3. **Archivos `.md`:**
   - Cada personaje tiene un archivo `.md` que documenta todas las configuraciones relevantes de los archivos `.json` dentro de su subdirectorio.
   - Este archivo incluye explicaciones detalladas, como situacion (ST, MT), supuestos y recomendaciones.

---

## Cómo contribuir

### 1. Crear una nueva configuración

Si deseas agregar una configuración nueva, sigue estos pasos:

#### Paso 1: Preparar la configuración

- Asegúrate de que el archivo `.json` incluya:
  - Nombre del personaje y constelación (por ejemplo, `Kaedehara Kazuha C6`).
  - Objetivo de la configuración (por ejemplo, `ST` o `MT`).
  - Detalles técnicos, como rotaciones o supuestos.
  - Equipo sugerido (los personajes recomendados de acuerdo a la configuración).

#### Paso 2: Documentar la configuración

- Actualiza o crea el archivo `.md` correspondiente al personaje:
  - Introduce una descripción de las configuraciones disponibles.
  - Explica los detalles relevantes, como el contexto y las recomendaciones.

> [!TIP]
> Puedes guiarte de la plantilla de [Template.md](TEMPLATE.md) para ayudarte a escribir el archivo.

#### Paso 3: Ubicar los archivos

- Coloca los archivos `.json` y `.md` en el directorio correcto:
  - Ejemplo: Si es una configuración para `Kaedehara Kazuha`, ubícala en `configs/Anemo/Kaedehara Kazuha/`.

---

### 2. Hacer un Pull Request

1. **Fork del repositorio:** Haz un fork del repositorio en tu cuenta de GitHub.
2. **Subir los cambios:** Asegúrate de seguir la estructura definida.
3. **Crear el Pull Request:** Explica brevemente qué cambios realizaste y por qué.

---

## Requisitos para las configuraciones

- **Formato:** Todas las configuraciones deben estar en formato `.json`.
- **Estructura:** Asegúrate de que cada archivo esté ubicado en el directorio correcto.
- **Descripción:** Proporciona explicaciones detalladas en el archivo `.md` correspondiente.

---

## Reportar problemas

Si encuentras un problema con una configuración existente, puedes:

1. **Abrir un reporte:** Utiliza [Bug Report](https://github.com/CesarFlores55/genshin-optimizer-configs/issues/new?labels=bug&template=bug-report---.md).
2. **Incluir detalles:** Describe el problema y, si es posible, sugiere una solución.

---

## Preguntas o sugerencias

Si tienes dudas o sugerencias, puedes:

- Unirte a nuestro servidor de Discord [Excelverso](https://discord.com/invite/excelverso).
- Crear un [Feature Request](https://github.com/CesarFlores55/genshin-optimizer-configs/issues/new?labels=enhancement&template=feature-request---.md).

¡Gracias por contribuir y ayudar a mejorar este proyecto!
