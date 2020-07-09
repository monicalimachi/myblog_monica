+++
authors = [
    "Monica Limachi"
]
title = "The Phoenix Project"
date = "2020-03-01"
description = "The Phoenix Project es un bestseller que analiza como los equipos de trabajo del area de desarrollo pueden mejorar con comunicacion y coordinacion."
images = [
    "developer1.png",
]
+++

The Phoenix Project es un bestseller que analiza como los equipos de trabajo del area de desarrollo pueden mejorar con comunicacion y coordinacion. 

<!--more-->

## INTRODUCCION

En el año 1975, fue Steve Sasson quien presento su prototipo de la primera maquina fotográfica sin película a los administrativos de la empresa Kodak, quienes quedaron cautivados pero inmediatamente desecharon la idea. Fue así como la primera cámara digital quedo en el olvido por varios años y fue así como años después se darían cuenta de el mayor error cometido.
Hoy en día el mercado de las cámaras digitales ha sido absorbido por empresas tecnológicas, donde la mayor participación la tienen aquellos enfocados en teléfonos móviles.

![Steve Sasson!](/images/camaradigital1.jpg "Steve Sasson con la primera camara digital")

Las empresas que venían de un proceso y pensamiento tradicional y que hasta los 90's podrían haber sido consideradas como las empresas mas grandes del mundo, fueron sobrepasadas por empresas innovadoras, que comenzaron a aparecer, nuevas ideas y nuevas formar de trabajo aparecieron.

Podemos ver una evolución e incluso una reinvención y fusión en varias empresas, aquellas como Toyota que tuvieron que mejorar su sistema de producción **(Toyota Kata)**, o el caso de Microsoft donde David J. Anderson y Dragos Dumitriu identificaron los problemas en su departamento de IT e implementaron mejoras en los procesos para desarrollar sus productos, adicionando tableros Kanban y un campo **"Waiting for Dragos"** para identificar el lugar de bloqueo de una tarea.. 

# LA CULTURA DEVOPS 

## Antecedentes

Con la creciente demanda, la oferta de nuevos productos, los procesos de comercialización, las compañias retailer, la oferta de servicios y soluciones tecnológicas **(como la virtualización)** a empresas que buscaban permanecer y crecer, conllevo al posicionamiento del e-commerce y a nuevo mercados digitales, que se continuan expandiendo debido a un mayor acceso para las personas alrededor del mundo.

![Agile!](/images/LeanAgile.png "Agile en Desarrollo")

Las empresas necesitan analizar el tiempo que les toma su producción, las herramientas tecnológicas, metodologías, que están surgiendo. Pero también analizar el factor humano, el trabajo en equipo y el crecimiento individual.

DevOps **(Developers + Operations)** simplemente buscaba en un inicio mejorar la cooperación entre desarrolladores y equipos de Operación, recopilando y armando los procesos y principios, socializados en eventos, aprendiendo de empresas que comenzaron a implementar algunos principios de Lean y Agile enfocadas a incrementar su producción, implementando la automatización, llegando a convertirse con el tiempo  en una Cultura que fácilmente se puede implementar en cualquier empresa.

## Principios

**First Way: Business > Desarrollo > Operaciones > Cliente**

{{< highlight html >}}
Identificar los requerimientos
- Realizar CI/CD
- Limitar el WIP
- Verificar los cambios
- La seguridad no debe afectar al consumidor final.
{{< /highlight >}}

**Second Way: Fast Feedback**

{{< highlight html >}}
Una buena retroalimentación  en cada punto de producción: 
- Business
- Desarrollo
- Operaciones
- Cliente
Puede prevenir problemas o habilitar la detección rápida y la recuperación de entornos si fuera necesario.
{{< /highlight >}}

**Third Way: Aprendizaje y experimentacion continua**

{{< highlight html >}}
Crear una cultura en la cual busquemos aprendizaje y experimentacion continua:
- Tomar riesgos, experimentar nuevas herramientas, mejorar.
- Repetir ciertas tareas mejora nuestras habilidades.
- Celebrar las mejoras.
{{< /highlight >}}

## Categorias del trabajo

Identificarlos te ayudan a medir y mejorar tu trabajo

**Categoria 1: Trabajo Planificado**

Esta tarea recae principalmente en el equipo de `Project Managers` o `PMs`, pero es una tarea que suele ser compartida junto a los equipos, al necesitar coordinar.
- Generar los requerimientos.
- Crear las tareas y la documentacion.
- Administrar los tiempos de las tareas.
- Revisar el progreso de los equipos.
Son solo algunas de las tareas que realizan.

**Categoria 2: Proyectos internos**

Esta tarea recae en los equipos de `Infraestructura`, `IT`, `Operaciones` y son quienes se encargan de coordinar e implementar proyectos internos:
- Crear nuevos entornos
- Automatizar el despliegue de los entornos
- Coordinar con los equipos de desarrollo, base de datos, QA, entre otros e identificar requerimientos
- Este punto podria transformarse en un `cuello de botella` si existen demasiados proyectos internos y poco tiempo o poco personal.

**Categoria 3: Cambios Operacionales**

Los cambios estan presentes casi siempre, se debe tomar en cuenta que suelen provenir de las categorias previas, existen herramientas que ayudan a administrar el trabajo:
- Tener un sistema de tickets para visibilizar el trabajo de cada miembro
- Utilizar herramientas de Agile o Kanban o un mix con acceso a los lideres de equipos, de proyectos y los miembros
- Tener un sistema para el uso de todos los miembros
- El manejo de tareas que se encuentran en reserva o `backlog` se facilita al tener un mismo sistema.

**Categoria 4: Trabajo no Planificado**

Puede incluir dos tipos
- Problemas de tipo operacional: Errores no planificados, casos sin analizar
- Incidentes: Resultado de alguna categoria de trabajo previa.




<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>



***


{{< css.inline >}}
<style>
.emojify {
	font-family: Apple Color Emoji,Segoe UI Emoji,NotoColorEmoji,Segoe UI Symbol,Android Emoji,EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
    .nowrap {
	display: block;
	margin: 25px 0;
}
}
</style>
{{< /css.inline >}}
