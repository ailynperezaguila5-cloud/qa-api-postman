# Proyecto QA — Pruebas de API REST con Postman

## Descripción
Proyecto práctico de testing de API REST para validar respuestas HTTP, estructura de datos JSON, tipos de datos, variables de entorno, autenticación y gestión de errores.

## Herramientas
- Postman
- JavaScript para tests automatizados
- JSONPlaceholder y httpbin para practicar con APIs públicas

## Pruebas realizadas
- GET: consulta de usuarios existentes y no existentes.
- POST: envío de datos para simular la creación de un usuario.
- PUT: simulación de actualización completa.
- PATCH: simulación de actualización parcial.
- DELETE: simulación de eliminación.
- Validación de códigos HTTP y campos obligatorios.
- Validación de tipos de datos y formato de email.
- Validación del tiempo de respuesta.
- Pruebas negativas y uso de variables de entorno.

## Resultados
Última ejecución registrada:
- Tests ejecutados: 18
- Tests aprobados: 18
- Tests fallidos: 0

## Cómo ejecutar las pruebas
1. Importar la colección de Postman.
2. Crear o importar el entorno `QA-Practica`.
3. Configurar la variable `baseUrl` con `https://jsonplaceholder.typicode.com`.
4. Seleccionar el entorno.
5. Ejecutar la colección desde Collection Runner.

## Limitaciones
JSONPlaceholder simula las operaciones de escritura. Los datos creados, modificados o eliminados no se conservan como en una API de producción.

## Objetivo
Demostrar conocimientos prácticos de testing de API, automatización de aserciones y análisis de respuestas HTTP.
