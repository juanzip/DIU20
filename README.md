# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa) 

Grupo: DIU3_rushB.  Curso: 2019/20 

Proyecto: 

Descripción: 

Logotipo: 

Miembros
 * :bust_in_silhouette:   Juan Nepomuceno Lucena López     :octocat:     

----- 

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil. Utilizaremos herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist) 


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434

>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. 


# Propuesta de aplicación para compartir ocio 

La idea es crear una aplicación que permita a las personas ponerse en contacto para realizar planes de ocio o cultura de forma conjunta, creando grupos con jerarquia y la posibilidad de compartirlo todo en todo momento.


 ## Competitive Analysis

El primer paso a dar es comparar las aplicaciones con un enfoque similar que ya estan en el mercado, en este caso tomamos como referencia "meetup" que es una de las más conocidas en este sector tan poco explorado. 
Tras su estudio llegamos a la conclusión de que esta muy bien pensada pero añadiendole a esa base un sistema de fidelización, por ejemplo, podria mantener m,s a los usuarios, porque en este caso su unica motivación para continuar usando la app es buscar actividades.


 ## Persona

Para ver las necesidades de la aplicación creamos a dos personas ficticias que se adaptan a dos circustancias en las que alguien entraría por primera vez para buscar alguna actividad.

Antonio que por motivos de trabajo esta en otra ciudad que ya conoce con un par de dias libres y Natalia, la cual se ha mudado hace poco a estudiar en otra ciudad y no ha podido conocer a nadie que comparta sus inquietudes. 

![Persona Antonio](img/personaAntonio.png)
![Persona Natalia](img/personaNatalia.png)


 ## User Journey Map

Para ver el recorrido de estas personas hasta que consiguen su proposito creamos sus respectivos journeys maps en los que vemos dos experiencias que podrían ser muy comunes pero tienen motivaciones diferentes. Lo llamativo es que cada uno llega a la página con una recomendación totalmente diferente y consigue su propósito. 

![Journey Antonio](img/journeyAntonio.png)
![Journey Natalia](img/journeyNatalia.png)


  


 ## Feedback Capture Grid

Para ordenar las ideas hemos usado una tabla para organizarlas segun sean cosas positivas, críticas, preguntas o ideas. 

![Tabla feedback](img/grid_tabla.png)

En este caso la idea mas destacable es la que podemos llamar propuesta de valor, que como ya hemos comentado anteriormente es fidelizar a los usuarios de la aplicación con un sistema de niveles y recompensas según las actividades que realicen, como apuntarse a actividades o ser administradores de un grupo.

 ## Tasks & Sitemap 

Para empezar a profuncizar en las caracteristicas especificas de la aplicación usamos un una matriz de tareas donde evaluamos la importancia de cada una en función del tipo de usuario que la vaya a realizar.

![Task](img/sitemap_tabla.png)

A continuación usamos el diagrama llamado sitemap para ordenar la arquitectura de la información, haciendo una jerarquia de todas las páginas que vamos a implementar en un futuro.

![SiteMap](img/sitemap_diagrama.png)

 ## Labelling 

Para dejar claro cual es el significado de todos los terminos usados en el sitemap se definen todos en la siguiente tabla:

![Labelling](img/labeling.png)


 ## Wireframes

Por ultimo 

>>>Leyenda de los numeros en los bocetos:
>>>-1: Grupos  
>>>-2: Buscador  
>>>-3: Menu Principal  
>>>-4: Calendario  
>>>-5: Ayuda  
>>>-6: Perfil  

>>> Boceto de la pagina princial
![Labelling](img/pagina_principal.png = 250x250)

>>> Boceto del perfil de usuario
![Labelling](img/perfil.png)

>>> Boceto del calendario
![Labelling](img/calendario.png)

>>> Boceto de la pagina de uno de los grupos
![Labelling](img/grupos.png)

>>> Boceto del buscador
![Labelling](img/buscador.png)

>>> Boceto del buscador cuando no encuentra resultados
![Labelling](img/buscador_noresultado.png)

>>>La opción de grupos te lleva a una lista de todos los grupos a los que perteneces, en este caso he realizado el boceto de un grupo concreto puesto que pienso que aporta más.

>>>En el buscador se puede dar el caso de no encontrar el grupo que se desea y en ese caso te da la opción de sugerir la creación de ese grupo. Lo propones pero no lo creas tú.


## Paso 3. Make (Prototyping) 


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 

![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


## Paso 4. UX Check (Usability Testing) 


![Método UX](img/ABtesting.png) 4.a A/B Testing
----


>>> Comprobacion de asignaciones para A/B Testing. Asignaciones https://github.com/mgea/DIU19/blob/master/ABtesting.md

>>>> Práctica A: 


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Usuarios para evaluar prácticas 


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


![Método UX](img/usability-report.png) 4.c Usability Report
----

>> Añadir report de usabilidad para práctica B 



## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report
----

>>> Indica qué pretendes evaluar (de accesibilidad) y qué resultados has obtenido + Valoración personal

>>> Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 



## Conclusión / Valoración de las prácticas


>>> (90-150 caracteres) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  







