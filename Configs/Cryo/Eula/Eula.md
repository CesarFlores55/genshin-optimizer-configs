<br />
<div align="center">
  <img src="https://my-discord-images.s3.us-east-2.amazonaws.com/Repo-Configs-GO/Cryo/UI_Gacha_AvatarImg_Eula.sm.png" 
       alt="kazuha" 
       style="max-height: 200px;">

  <h1 align="center">Eula</h1>
</div>

<details>
  <summary><strong>Tabla de Contenido</strong></summary>
  <ol>
    <li><a>Eula</a>
      <ul>
        <li><a href="#standard-burst-rotation">Standard Burst Rotation</a></li>
      </ul>
    </li>
  </ol>
</details>

## [Standard Burst Rotation](Standard%20Burst%20Rotation.json)

**Autor:**
twce\_  
**Explicación:**  
La configuración cubre la rotación típica de la Definitiva (Burst) de Eula utilizando el conjunto de 4 piezas de Llamas Albinas (su mejor set de artefactos).  
**Ejemplo de Team:**  
`Eula - [Electro] - Rosaria - Bennett`

> [!NOTE]
> La optimización para múltiples objetivos permite una optimización más integral de los Ataques Normales y la Definitiva de Eula, ya que ambos infligen un daño significativo.

### Supuestos

El conjunto de artefactos equipado es el de 4 piezas de Llamas Albinas (Pale Flame), el mejor set para Eula. Esta rotación es generalmente óptima y casi siempre debería usarse, con muy pocas excepciones.

> [!CAUTION]
>
> - Superconductor está incluido en la configuración, por lo que no debe activarse de forma predeterminada.
> - El bono de ATK% de Eula derivado del efecto de las 4 piezas de Llamas Albinas se calcula dinámicamente, por lo que tampoco debe activarse de forma predeterminada. Lo mismo ocurre con la reducción de RES de su Habilidad Elemental (Skill) mantenida, que también se calcula dinámicamente y no debe habilitarse por defecto.

- El combo asumido en `Eula` es `E > Q > N4 > Hold E > N4 > Explosion`.
- El nivel de talento asumido para la Habilidad Elemental es **9**, por lo que debes ajustar la reducción de RES según el nivel que tengas.
- No se asume que la resonancia Cryo esté activa, ya que depende del equipo, el momento y, a menudo, el aura elemental del enemigo.

> [!TIP]
> **Restricciones mínimas de construcción** (Minimum Build Constraints):
>
> > - Crit, Rate: 70%
> > - Energy Recharge: 120% (dependiendo del equipo, puede llegar hasta 140% sin Raiden).
> >
> > Acumulaciones de Espada Luminosa (Lightfall Stacks):
> >
> > > - 26 en C6.
> > > - 14 con Oda de los Pinos (Song of Broken Pines).
> > > - 13 en otros casos (elige esto en la pestaña de Talentos de Eula).

### Personalización

- Si no estás usando el conjunto de 4 piezas de **Llamas Albinas** (Pale Flame), elimina el bono de 25% de Daño Físico y el aumento de 18% ATQ que se obtienen después de usar la Habilidad Elemental mantenida (Hold Skill).
- Si estás utilizando armas con pasivas dinámicas, como **Oda de los Pinos** (Song of Broken Pines), estas deben considerarse individualmente. Por ejemplo, la pasiva de Pinos no se activará hasta después del primer combo N4 (cuatro Ataques Normales).
- Si Eula tiene Constelación C1+, agrega el bono de 30% de Daño Físico para los Tarjets a partir de `Escarcha turbulenta` en adelante.
