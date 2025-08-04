# Arquitectura
Integrantes: camilo cometa,santiago cespedes,mateo arrubla
Descripción del Proyecto
El proyecto consiste en el desarrollo de una aplicación móvil que permite a los ciudadanos reportar incidentes de robo directamente a la Policía mediante un formulario automatizado. Además, visualiza en tiempo real un mapa interactivo que muestra las zonas afectadas y la ubicación de los CAIs móviles.

Características
Autenticación de Usuarios:
La aplicación inicia con un sistema de autenticación de usuarios mediante un login seguro, garantizando la protección de datos personales.

Formulario de Reportes Automático:
Un bot se encarga de enviar la información recopilada desde la app al formulario oficial de la Policía, ya sea mediante integración directa o a través de un proceso automatizado.

Mapa Interactivo:
La aplicación muestra un mapa interactivo en tiempo real, utilizando tecnologías como Google Maps o Mapbox, que visualiza los reportes de robos y la ubicación de los CAIs móviles.

Almacenamiento de Archivos:
Los archivos e imágenes asociadas a cada reporte se almacenan de forma segura en AWS S3, asegurando una gestión eficiente de los datos.

Backend sin Servidores:
La lógica de backend será ejecutada sin servidores utilizando AWS Lambda, lo que permite una escalabilidad automática y un bajo costo operativo.

Desarrollo Móvil:
La aplicación será desarrollada utilizando Kotlin, lo que aprovechará sus ventajas sobre Java tradicional, brindando una experiencia moderna y eficiente para los dispositivos Android.

Tecnologías Utilizadas
Frontend (App móvil): Kotlin

Backend: AWS Lambda

Autenticación: Login seguro

Mapas: Google Maps / Mapbox

Almacenamiento de Archivos: AWS S3

Automatización de Reportes: Integración directa o automatización mediante bot
