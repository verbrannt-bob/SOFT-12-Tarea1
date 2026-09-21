# Tarea 1
 
Tarea 1 SOFT-12
 
**Estudiante:** Roberto González Castillo
**Sección:** SCV2    **Periodo:** III cuatrimestre 2026
**Docente:** Alvaro Cordero Peña
**Fecha de Entrega** 20/09/2026

## Caso 1
 
Aplicación web de una expedicion científica que permite a los participantes mantenerse informado acerca del estado,  las misiones, actividades y alertas relavantes de la expedición.

## Caso 2
 
Aplicación web con enfoque en dispositivos móbiles para informar a los visitantes de las actividades del festival. Los usuarios podran desde sus celulares ver los horarios, lugaras y más información acerca de las actividades, así como que servicios están disponibles.

## Estructura del repositorio
 
- `/SOFT-12-Tarea1` — root
  - `caso1/` — Expedicion Tortuga 2026
    - `css/` — Hojas de Estilo
  - `caso2/` — Festival C
    - `css/` — Hojas de Estilo
    - `img/` — Imagenes

 ## Ejecutar Caso 1
 Abrir `caso1/index.html` en el navegador. No requiere instalación.  
 ## Ejecutar Caso 2
 Abrir `caso2/index.html` en el navegador. No requiere instalación. 

 ## Desiciones de diseño
 **Etiquetas:** Utilicé principalmente etiquetas para definir las diferentes areas del la página. Header y Main para los encabezados y el contenido. Además dentro del contenido pricipal dividí con la etiqueta Section las diferentes partes y la etiqueta article para los elementos individuales dentro de cada sección \
 **Jerarquía:** Empezando con el titulo principal de la pagina con h1, un h2 para cada seccion y si fuera necesario h3 para partes dentro de las secciones\
 **Accesibilidad:** Se declaro el idioma español mediante la propiedad lang, se respeto la jeranquia de encabezados. Se aplico un filtro de opacidad para permitir leer el texto sobre las imagenes en el caso 2. Los estados de las alertas estan esplicitamente escritos ademas de estar identificados por colores.\
 **Modelo de cajas:** El modelo de cajas considera cada elemento como una caja formada por contenido, padding, border y margin.\
 **Posicionamiento:** Utilice position para colocar el simbolo de alerta en la esquina de las tarjetas de alerta con el valor relativ en la tarjeta y absolute en el span con el !. De esta manera el simbolo puede referenciar a la tarjeta y con las propiedades top y right colocarce en la esquina superior derecha. Ademas utilice sticky en el caso 2 para mantener el header visible cuando el usuario baja en la pagina.\
 **Prioridad de Estilos:** Por la especificidad, gracias a la combinacio de selectores de clase y etiqueta puedo seleccionar uno o varios elementos con alta especificidad para asegurar de que el estilo se aplique correctamente \
 **Flexbox:** Principalmente en la organizacion de las secciones internamente, ya que en muchas ocaciones una solo dimencion era suficiente\
 **CSS Grid:** En algunas ocaciones para acomodar partes internas de ciertas secciones, pero primordialmente para acomodar todo el contenido en las paginas diseñadas para tablet y desktop.\
 **Responsibidad:** En la versiones mobiles se acomoda todo en una sola columna con el objetivo de que el usuario pueda scrollear con facilidad. Al crecer el ancho de las pantallas las diferentes secciones se acomodan en varias columnas, para aprovechar mejorel espacio horizontal, tambien algunas secciones cambian su forma de acomodarse internamente para poder compartir el ancho más eficientemente con otras secciones.\
 **Breakpoints:** Los puntos de quiebre seleccionados fueron 48rem y 64rem. Estos puntos los saque del desafio de diagramacion adaptable visto en clase \
 **Unidades Relativas:** Principal mente rem\
 **Variables CSS:** Las variables se utilizaron para definir una paleta de colores y reutilizarlos con mayor facilidad. ademas tambien se definieron los fonts para cada caso de esta manera.

 ## Resumen de commits
 
| # | Fecha      | Hash    | Mensaje                  | Caso   | Cambio        |
|---|------------|---------|--------------------------|--------|---------------|
| 1 | 2026-09-18 | d46205c | Creacion de estructura del repositorio, README, html y estilos basicos del caso1 | 1 | Estructura|
| 2 | 2026-09-18 | b8fd89c | Header Estilo Basico Mobile-First | 1 | Header |
| 3 | 2026-09-19 | fde0045 | Ajustes al header, completar diseño para tablet y desktop | 1 | Header |
| 4 | 2026-09-19 | 1bccb25 | [Caso 1] Menu de navagacioncompleto | 1 | Nav |
| 5 | 2026-09-20 | 29c74b0 | [caso 1] Inicio de diseño del resumen de operaciones | 1 | Resumen Operaciones |
| 6 | 2026-09-20 | a4ca7f1 | [caso 1] Diseño de resumen de opraciones completado | 1 | Resumen Operaciones |
| 7 | 2026-09-20 | 73d45b4 | [caso 1] Seccion de Misiones version Mobile | 1 | Misiones |
| 8 | 2026-09-20 | 03e40de | [caso 1] Seccion de Equipos version Mobile | 1 | Equipos |
| 9 | 2026-09-20 | 5984320 | [caso 2] Header + Menu de navegacion completo | 2 | Header + Nav | 
| 10 | 2026-09-20 | 99ca861 | [caso 2] Secciones Ahora y Proximamente para Mobile | 2 | Ahora + Proximamente |
| 11 | 2026-09-20 | 0367571 | [caso 2] Seccion de escenarios y responsibidad de la pagina hasta este punto | 2 | Escenarios |
| 12 | 2026-09-20 | 5d86076 | [caso 1] Agenda de actividades y ajustes de responsividad | 1 | Actividades |
| 13 | 2026-09-20 | 3ec104c | [caso 2] Secciones de Camibios y Servicios | 2 | Cambios + Servicios |
| 14 | 2026-09-20 | 5f25ef5 | Estructura del README | N/A | README |