# Plantilla de configuración

Esta plantilla proporciona una estructura básica para la documentación de una configuración. Puedes utilizarla como guía para crear una nueva configuración.

```md
<br />
<div align="center">
  <img src="https://my-discord-images.s3.us-east-2.amazonaws.com/Repo-Configs-GO/{ELEMENT}/UI_Gacha_AvatarImg_{CHARACTER}.sm.png" 
       alt="{character}" 
       style="max-height: 200px;">

  <h1 align="center">{Character Name}</h1>
</div>

<details>
  <summary><strong>Tabla de Contenido</strong></summary>
  <ol>
    <li><a>{Character Name}</a>
      <ul>
        <li><a href="#{build-1-anchor}">{Build 1 Name}</a></li>
        <li><a href="#{build-2-anchor}">{Build 2 Name}</a></li>
        <!-- Agrega más configuraciones si es necesario -->
      </ul>
    </li>
  </ol>
</details>

## [{Build 1 Name}](Build%201%20Name.json)

**Autor:**  
{Author Name}  
**Explicación:**  
{Descripción breve de la configuración, habilidades o estilo de juego.}  
**Ejemplo de Team:**  
`{Team Members}`

> [!NOTE]
> {Notas importantes o consideraciones especiales para la configuración.}

### Supuestos

- {Puntos clave asumidos en la configuración, como combos específicos, condiciones de habilidad, etc.}
- {Otros supuestos relevantes para la optimización.}

### Personalización

- {Opciones para ajustar la configuración según diferentes escenarios, personajes adicionales, o estilos de juego.}
- {Detalles para optimizar dependiendo del equipo o condiciones externas.}

---

## [{Build 2 Name}](Build%202%20Name.json)

**Autor:**  
{Author Name}  
**Explicación:**  
{Descripción breve de la configuración, habilidades o estilo de juego.}  
**Ejemplo de Team:**  
`{Team Members}`

> [!NOTE]
> {Notas importantes o consideraciones especiales para la configuración.}

### Supuestos

- {Puntos clave asumidos en la configuración, como combos específicos, condiciones de habilidad, etc.}
- {Otros supuestos relevantes para la optimización.}

### Personalización

- {Opciones para ajustar la configuración según diferentes escenarios, personajes adicionales, o estilos de juego.}
- {Detalles para optimizar dependiendo del equipo o condiciones externas.}
```

### Cómo usar:

1. Reemplaza las palabras entre llaves (`{...}`) con la información específica del personaje, configuraciones y notas:
   - `{ELEMENT}`: El elemento (Anemo, Hydro, etc.).
   - `{CHARACTER}`: Nombre interno del personaje (por ejemplo, `Kazuha`).
   - `{Character Name}`: Nombre completo del personaje (por ejemplo, `Kaedehara Kazuha`).
   - `{Build 1 Name}` y `{Build 2 Name}`: Nombres de las configuraciones específicas.
   - `{Team Members}`: Los miembros del equipo sugeridos.
   - `{Author Name}`: Nombre del creador de la configuración.
2. Ajusta las secciones de **Supuestos** y **Personalización** según las necesidades de la configuración.

Con esta plantilla, solo tienes que reemplazar datos y ajustar detalles según el personaje o la configuración. 😊
