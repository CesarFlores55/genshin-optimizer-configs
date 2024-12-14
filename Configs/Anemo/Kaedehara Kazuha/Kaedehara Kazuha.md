<br />
<div align="center">
  <img src="https://my-discord-images.s3.us-east-2.amazonaws.com/Repo-Configs-GO/Anemo/UI_Gacha_AvatarImg_Kazuha.sm.png" 
       alt="kazuha" 
       style="max-height: 200px;">

  <h1 align="center">Kaedehara Kazuha</h1>
</div>

<details>
  <summary><strong>Tabla de Contenido</strong></summary>
  <ol>
    <li><a>Kaedehara Kazuha</a>
      <ul>
        <li><a href="#c6-on-field-st">C6 On-Field: ST</a></li>
        <li><a href="#c6-on-field-mt">C6 On-Field: MT</a></li>
      </ul>
    </li>
  </ol>
</details>

## [C6 On-Field: ST](C6%20On-Field%20ST.json)

**Autor:**
mimithiz  
**Explicación:**  
Configuración para Kazuha C6 que utiliza Ataques Normales infundidos con Anemo de manera on-field utilizando su C1. _Esta configuración es sólo para un objetivo (ST)_.  
**Ejemplo de Team:**  
`Kazuha - Faruzan - Zhongli - Bennett`

> [!NOTE]
> La multioptimización es importante debido a los múltiples escalados de Kazuha C6.

### Supuestos

- La configuración usa **Pyro** como el elemento que hace swirl; cámbialo si estás haciendo swirl a otro elemento.
- El combo asumido es `hEP > Q > N1C > tEP > 3xN1C > tEP`.
- Se asume que hay una aplicación inicial de Elemento pero ninguna aplicación fuera de campo durante el tiempo de campo de Kazuha.
- Los 3 Skill Plunges obtienen el daño extra por colisión.

### Personalización

- Si se aplica un Elemento externo (por ejemplo, Xiangling), añade 2 instancias de Swirl para un total de 16.
- Si se usa una Infusión cuerpo a cuerpo externa (por ejemplo, C6 Bennett), cambia los modificadores de Infusión cuerpo a cuerpo del equipo a ese Elemento y elimina 2 instancias de daño de Swirl para un total de 12.

## [C6 On-Field: MT](C6%20On-Fielf%20MT.json)

**Autor:**
mimithiz  
**Explicación:**  
Configuración para Kazuha C6 que utiliza Ataques Normales infundidos con Anemo en un estilo de juego en el campo utilizando su C1. _Esta configuración es sólo para multiobjetivo (MT)_.  
**Ejemplo de Team:**  
`Kazuha - Faruzan - Zhongli - Bennett`

> [!NOTE]
> Optimizar Kazuha C6 en multiobjetivo es complicado debido a que el daño de los Swirls tienen un gran impacto en su DPS general.

### Supuestos

- La configuración usa **Pyro** como el Elemento que hace Swilr; cámbialo si estás haciendo Swirl a otro Elemento.
- El combo asumido es `hEP > Q > tEP > 3xN1C > tEP`.
- Mínimo 2 objetivos.
- Se asume que hay una aplicación inicial de Elemento pero ninguna aplicación fuera de campo durante el tiempo de campo de Kazuha.

### Personalización

- Si se usa una Infusión externa cuerpo a cuerpo (por ejemplo, C6 Bennett), cambia los modificadores de Infusión cuerpo a cuerpo del equipo a ese Elemento y elimina 6 instancias de daño de Swirl para un total de 24.
- Si el elemento al que se hace Swirl es **Hidro**, divide las instancias de Remolino a la mitad (15 con Infusión Anemo, 12 con Infusión externa cuerpo a cuerpo).
