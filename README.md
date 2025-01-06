# Proyecto de práctica 4: Pruebas con API para una aplicación de alimentos - Urban Grocers

## Descripción del Proyecto

Crear y enviar solicitudes a la API a través de Postman, hacer informes de errores, leer la documentación de la API y
crear las primeras pruebas de la API.

Urban Grocers es una aplicación para que el cliente pueda realizar compras mediante un catalogo, o kits que ya estan preparados. Al acceder al kit, se ve una lista de posibles artículos de comestibles y cada artículo comestible pertenece a
una categoría específica. En la lista, el usuario o la usuaria ve el nombre, el peso y el precio del artículo.

## Instrucciones para el Desarrollo del Proyecto

La nueva funcionalidad cubre varias áreas: 

Trabajar con los kits en la capacidad de agregar comestibles a un Kit. Usar el endpoint POST /api/v1/kits/{id}/products. Utiliza la parte "Main.Kits" en APIdoc para obtener más información. 
El endpoint devolverá 400 Bad Request (Solicitud no válida) cuando la longitud de la lista de productos resultante sea superior a 30 (no las cantidades acumuladas de cada producto) .

Trabajar con los servicios de entrega en la capacidad de comprobar si el servicio de entrega Order and Go está disponible y cuánto cuesta. El endpoint es POST /order-and-go/v1/delivery. Consulta la parte "Couriers" (Servicios de entrega) de apiDoc y la sección de cálculo del precio de entrega en los requisitos.

  
## Desarrollo del Proyecto

**1. Análisis de requisitos y documentación de la API:** Realicé un análisis minucioso de los requisitos para la nueva funcionalidad del backend de Urban.Grocers, así como de la documentación de la API disponible en Apidoc. Esto me permitió obtener una visión clara de los objetivos y las especificaciones técnicas de la funcionalidad, asegurando que las pruebas se diseñaran de manera alineada con los requisitos esperados.

**2.Diseño de casos de prueba:** Con base en el análisis anterior, diseñé una serie de pruebas organizadas en una lista de comprobación detallada para cubrir todos los aspectos de la funcionalidad del backend. Las pruebas incluyeron tanto escenarios positivos como negativos, asegurando que se validaran todos los posibles flujos de datos y condiciones límite.

**3. Pruebas de las APIs con Postman:** Utilicé Postman para realizar pruebas de las APIs, enviando solicitudes a los puntos finales documentados y verificando las respuestas recibidas. Durante este proceso, identifiqué errores y anomalías que fueron detallados en informes específicos en JIRA para su seguimiento y resolución.

## Herramientas utilizadas:

**JIRA** Para la gestión de errores, seguimiento de incidencias y documentación de los casos "NO APROBADO".

**APIDOC** Para acceder a la documentación de las APIs y comprender los puntos finales y los parámetros necesarios para las pruebas.

**POSTMAN** Para realizar pruebas de las APIs, validar las respuestas y verificar la correcta integración de los servicios backend.

**Documentación de los requisitos** revisión y análisis de los requisitos proporcionados.

**Hojas de calculo** Google sheets. Para la organización y seguimiento de los casos de prueba, así como para la documentación de los resultados obtenidos durante las pruebas.

# CONCLUSIÓN

En este proyecto me he permitido fortalecer y diversificar mis habilidades como QA Engineer, especialmente en el análisis de requisitos, diseño de pruebas y ejecución de pruebas de API. A través de herramientas como JIRA y Postman donde pude detallar de manera eficiente los casos de prueba y los errores. 

************


:sparkles: **GRACIAS** por visitar este proyecto. 

**MUCHAS ESTRELLITAS DE LUZ PARA TI** :star2::star2::star2::star2:

**Si tienes preguntas puedes contactarme en mi Linkedln. :point_right: www.linkedin.com/in/sandrarodriguez461428179**



**************




