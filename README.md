\# Reto Técnico - Simple Books API



\## Objetivo



Automatizar pruebas API sobre la Simple Books API utilizando Postman y Newman.



\## Herramientas utilizadas



\- Postman

\- Newman

\- Git

\- GitHub



\## Casos de prueba implementados



\### Casos positivos



\- Registrar Cliente

\- Consultar Estado API

\- Listar Libros

\- Listar Libros por Tipo

\- Consultar Libro por ID

\- Crear Orden

\- Consultar Todas las Órdenes

\- Consultar Orden

\- Actualizar Orden

\- Validar Actualización

\- Eliminar Orden



\### Casos negativos



\- Crear Orden sin autenticación

\- Consultar libro inexistente

\- Cliente duplicado



\## Ejecución



```bash

newman run "Reto\_Técnico\_SimpleBooks\_API.postman\_collection.json" -e "Ambiente-SimpleBooks.postman\_environment.json"

```



\## Archivos incluidos



\- Reto\_Técnico\_SimpleBooks\_API.postman\_collection.json

\- Ambiente-SimpleBooks.postman\_environment.json

\- Reportes de ejecución Newman



\## Autor



Alan Eduardo Diaz Arosemena



Analista de Pruebas en Formación

