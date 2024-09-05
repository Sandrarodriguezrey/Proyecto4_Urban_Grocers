# Proyecto 4: Pruebas con API para una aplicación de alimentos  Urban Grocers

## Descripción del Proyecto

Crear y enviar solicitudes a la API a través de Postman, hacer informes de errores, leer la documentación de la API y
crear las primeras pruebas de la API.

Urban Grocers es una aplicación para que el cliente pueda realizar compras mediante un catalogo, o kits que ya estan preparados. Al acceder al kit, se ve una lista de posibles artículos de comestibles y cada artículo comestible pertenece a
una categoría específica. En la lista, el usuario o la usuaria ve el nombre, el peso y el precio del artículo.

## Instrucciones para el Desarrollo del Proyecto

La nueva funcionalidad cubre varias áreas: 

Trabajar con los kits: la capacidad de agregar comestibles a un kit. El endpoint es POST /api/v1/kits/{id}/products. Utiliza la parte "Main.Kits" en apiDoc para obtener más información. El endpoint devolverá 400 Bad Request (Solicitud no válida) cuando la longitud de la lista de productos resultante (no las cantidades acumuladas de cada producto) sea superior a 30.

Trabajar con los servicios de entrega: la capacidad de comprobar si el servicio de entrega Order and Go está disponible y cuánto cuesta. El endpoint es POST /order-and-go/v1/delivery. Consulta la parte "Couriers" (Servicios de entrega) de apiDoc y la sección de cálculo del precio de entrega en los requisitos.

  
## Desarrollo del Proyecto

1. Analice los requisitos para la nueva funcionalidad del back-end de Urban.Grocers y la documentación de la API en Apidoc.
2. Diseñe varias pruebas en una lista de comprobación para cubrir la funcionalidad.
3. Probe las APIs a través de Postman y detalle los informes de errores en el Jira.


