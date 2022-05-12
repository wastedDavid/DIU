# DIU22
Prácticas Diseño Interfaces de Usuario 2021-22 (Tema: Hostels) 

Grupo: DIU9_LargoSobreCongo.  Curso: 2021/22 
Updated: 12/5/2022

Proyecto: 
Menú Gastronómico de Granada - 4U Hostel

Descripción: 

Decidimos desarrollar un  menú gastronómico de la comida típica de la provincia para sacarle su 
máximo potencial y atraer a más clientes a visitar Granada. El microsite ofrece
los servicios típicos: reserva, consultar carta, además de poder conocer un poco
más la cultura e historia de los platos.

Logotipo: 
Logo:
![Método UX](img/logo.drawio.png)


Miembros
 * :bust_in_silhouette:  Álvaro Vega Romero     :octocat:     
 * :bust_in_silhouette:  David Correa Rodríguez     :octocat:

----- 



# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

Seleccionamos aquellos hostels que eran similares al 4U Hostel (respecto a valoración) y ubicación, pero que tuvieran
ciertas diferencias de diseño y servicios.
Elegimos: Broz Hostel, Oh! My Hostel y 4U Hostel.
Podemos destacar que:
- Broz Hostel tiene más facilidades y servicios que 4U
- Oh! My Hostel presentaba dificultades e inconsistencias en la navegación,
además de un diseño visual mejorable.
- 4U presenta algunos bugs visuales y el despliegue de los servicios que ofrece no están
en un sitio adecuado. No dispone de seccion FAQs.



![Método UX](img/Persona.png) 1.b Persona
-----

Quisimos seleccionar personas con perfiles diferentes para poder abarcar más posibilidades
en la experiencia de usuarios del hostel.
- Cristian: estudiante, vividor, sociable.
- Paco: anciano, inexperto, ganas de viajar.

![Método UX](img/Cristian_P.JPG)
![Método UX](img/Paco_P.JPG)


![Método UX](img/JourneyMap.png) 1.c User Journey Map
----


Decidimos jugar con ese concepto de que eran usuarios diferentes:
- Crisitan es joven y está acostumbrado a las tecnologías y a este tipo de aventuras, por lo
que su experiencia de usuario sería previsiblemente buena.
- Paco es un anciano inexperto y torpe con las tecnologías, por lo que previsiblemente iba a tener
una experiencia de usuario mala.

Cristian es un usuario bastante común en estas situaciones (vacaciones, escapada). Paco es menos común, aunque
es cierto que la tercera edad es cuando más tiempo disponible se tiene para hacer otras actividades como,
por ejemplo, viajar y hospedarse.

![Método UX](img/usabilityReview.png) 1.d Usability Review
----

- Enlace al documento: https://github.com/wastedDavid/DIU/blob/master/P1/Usability-review-template.xls
- Valoración final (numérica): 82
- Comentario sobre la valoración:  En general, es accesible para todos los tipos usuarios, pero un poco
tosca para aquellos con conocimientos básicos de web. Interfaz atractiva aunque con algunos defectos
de tamaños y cambios de pantalla / zooms.


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid / EMpathy map / POV
----



Interesantes | Críticas
------------ | ----------------
| Instalaciones visualmente atractivas. | Las habitaciones podrían ser un poco más grandes y disponer de una pequeña cocina para cocinar. |
| Habitaciones rústicas bonitas. | Tardaron en responder al teléfono, podrían estar más atentos o disponer de varios teléfonos (en la web solo aparece 1) |
| Facilidad de reserva y de ver las posibles habitaciones para esta. | No se puede pagar en efectivo (en la reserva se pide una tarjeta) ni tampoco después de la estancia. |
| Página más bonita y completa que la competencia. |
| Situado en pleno centro de Granada. |

Preguntas | Nuevas ideas
------------ | ----------------
| ¿Hay aparcamiento? | Que las secciones de la página  no aparezcan cortadas por el encabezado. |
| ¿Algún lugar que describa las actividades que tienen? | Tener habitaciones sin literas (pareja de ancianos no se ven capaces de subir a una litera) e individuales. |
| ¿Qué tiene alrededor? Hay paradas de autobús, tiendas, monumentos? | Poder pagar después de la estancia y en efectivo. |
| ¿Se puede ir con mascotas? |
| ¿Hay zonas de ocio cercanas? |



  
    
El problema que planteamos es que 4U Hostel no ofrecía un lugar de comida
o restaurante formal en donde sus huéspedes tomaran o comieran durante su estancia.

Planteamos la hipótesis de que, si se incluyera este servicio, incentivaría más
a querer hospedarse en el local, quedarse más tiempo, no depender de otros servicios
externos además de ofrecerle a los clientes conocimientos y cultura general de la 
gastronomía de Granada, haciéndolo emblemático y exclusivo.



![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----

![Método UX](img/canvas.JPG)


![Método UX](img/Sitemap.png) 2.b Tasks analysis 
-----

![Método UX](img/user_map.JPG)


![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----

![Método UX](img/site_map.JPG)


Término | Significado     
------------ | ----------------
| Menú | Redirige a una página de información general acerca del restaurante y del menú |
| Sobre nosotros | Redirige a la página de información de la empresa / negocio |
| Contactar | Redirige a la página de contacto de la empresa / negocio |
| Carta | Redirige a la página de los platos ofertados con su información asociada, como alérgenos, precios, ingredientes y fotos (mediante categoría Carta y mediante galería de fotos)|
| Reservar | Redirige a la página para hacer una reserva en el restaurante (botón Reservar y categoría Reservas) |
| Opiniones | Redirige a una página con las opiniones escritas acerca del restaurante, además de poder redactar (categoría Opiniones) |


![Método UX](img/Wireframes.png) 2.d Wireframes
-----


Hicimos un planteamiento para Web, pero en la práctica 3 reflexionamos sobre ello
y llegamos a la conclusión de que iba a ser un servicio más accedido a través de movil
por su rapidez y comodidad de hacerlo por teléfono.

Inicialmente se mostraría la portada. Desde ahí, se podría acceder a la reserva
o a la carta, además del resto de términos explicados en el Labelling.
Se accedería mediante los botones/enlaces explicados en el Labelling.

Un ejemplo de navegación sería: Portada -> Carta -> Volver a Portada -> Reservar

Parte de la portada
![Método UX](img/menu_gastronomico.drawio.png)

Parte de la carta
![Método UX](img/carta.drawio.png)

Parte de la reserva
![Método UX](img/reserva.drawio.png)


## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo
>>> Si diseña un logotipo, explique la herramienta utilizada y la resolución empleada. ¿Puede usar esta imagen como cabecera de Twitter, por ejemplo, o necesita otra?


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 
>>> Tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto en forma de video de 90 segundos aprox


## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 


>>> ## Paso 5. Evaluación de Accesibilidad  (no necesaria)


>>> ![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report 
>>>> ----

>>> Indica qué pretendes evaluar (de accesibilidad) sobre qué APP y qué resultados has obtenido 

>>> 5.a) Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 
>>> 5.b) Uso de simuladores de accesibilidad 

>>> (uso de tabla de datos, indicar herramientas usadas) 

>>> 5.c Breve resumen del estudio de accesibilidad (de práctica 1) y puntos fuertes y de mejora de los criterios de accesibilidad de tu diseño propuesto en Práctica 4.



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













