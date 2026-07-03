# medina-hub-pipeline-analysis
Análisis del pipeline de ventas B2B para identificar cuellos de botella, mejorar tasas de conversión y optimizar Revenue Operations. Proyecto Capstone desarrollado con Python, SQL y Tableau. Incluye limpieza de datos, visualizaciones y recomendaciones accionables.


Este proyecto analiza el embudo de ventas de Medina Hub, una empresa ficticia de servicios tecnológicos B2B. El objetivo principal fue identificar los principales cuellos de botella en el pipeline comercial y proponer mejoras concretas para aumentar la eficiencia y los ingresos.

Sobre el Proyecto

Trabajé con más de 3,000 registros de leads, generados y limpiados por mí mismo. Utilicé Python para crear los datos, SQL para la limpieza y Tableau para las visualizaciones. 

El enfoque esta orientado a Revenue Operations (RevOps): entender cómo fluye el pipeline, dónde se pierden oportunidades y cómo se puede mejorar el proceso de ventas.


 Hallazgos Principales

- La mayor pérdida de oportunidades ocurre en la etapa de Closed Lost (1,085 leads).
- Existe un claro cuello de botella entre Technical Demo y Negotiation & ROI.
- El canal Referral tiene mejor tasa de cierre y velocidad, mientras que Outbound genera volumen pero con menor eficiencia.
- El tiempo promedio de cierre varía mucho según el canal de adquisición.

 Tecnologías Utilizadas

- Python – Generación de datos
- SQL – Limpieza y transformación
- Tableau – Dashboard interactivo y visualizaciones
- GitHub – Control de versiones y portafolio

Dashboard
[Haz clic aquí para ver el Dashboard en Tableau Public](<div class='tableauPlaceholder' id='viz1783045839023' style='position: relative'><noscript><a href='#'><img alt='Medina Hub - Revenue &amp; Pipeline Performance ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MedinaHub-V1&#47;MedinaHub-RevenuePipelinePerformance&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MedinaHub-V1&#47;MedinaHub-RevenuePipelinePerformance' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MedinaHub-V1&#47;MedinaHub-RevenuePipelinePerformance&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='es-ES' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1783045839023');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1027px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>) (<div class='tableauPlaceholder' id='viz1783045950448' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TR&#47;TR2XMS66C&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;TR2XMS66C' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TR&#47;TR2XMS66C&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='es-ES' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1783045950448');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1377px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>)

Recomendaciones

Basado en el análisis, propongo:

- Implementar un seguimiento más estructurado después de la demostración técnica.
- Mejorar la calificación de leads en el canal Outbound.
- Fortalecer el programa de referidos, ya que muestra los mejores resultados.
- Crear alertas para oportunidades que se estanquen en etapas críticas.


Estructura del Repositorio

- `/data` → Archivos CSV (crudos y procesados)
- `/notebooks` → Scripts de Python y consultas SQL
- `/dashboard` → Archivo de Tableau y capturas
- `/reports` → Reporte Ejecutivo en PDF

 Habilidades Demostradas

- Análisis completo del proceso de ventas B2B
- Limpieza y preparación de datos
- Creación de visualizaciones claras y accionables
- Pensamiento orientado a negocio y Revenue Operations

Autor: Edgar Alexis Medina Valencia  
Fecha: Julio 2026  
Certificación:Google Data Analytics Professional Certificate
