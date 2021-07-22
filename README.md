Prueba de desarrollo web PHP - Joomla
====================================

¡Hola! Queremos saber si estás list@ para hacer parte de nuestro equipo.
---------------------------------

### Descripción
Nuestro cliente requiere contar con un sitio web para identificar el personaje más influyente actualmente. Para esto, requiere que Emerald Studio realice un sitio web que permita a los visitantes votar por los personajes disponibles y mostrar los resultados de la votación.

> **El reto**: Construir un sitio web responsive que permita la visualización de los candidatos y a su vez votar por cada uno guardando un registro de cada voto.

## Requerimientos generales:

[ ] Crear un repositorio en tu cuenta de Github para almacenar el proyecto
[ ] Crea una rama por cada fase, ejemplo: maquetacion, interaccion, integracion, etc
[ ] Realizar comentarios en tu código cuando creas que se requiere una aclaración importante en tu desarrollo
[ ] Crea un archivo readme en donde indiques los pasos para replicar tu proyecto

### Fase 1 - Maquetación
En esta fase deberás realizar el corte y maquetación del sitio web. Para esto cuentas con varios recursos:
- Plantilla en formato png [pngTemplate](https://drive.google.com/file/d/1Mla5vJJIPrDODWXDfuvWheRq28UFq-kL/view?usp=sharing)
- Plantilla en formato psd [psdTemplate](https://drive.google.com/file/d/1zSruxXa3xoLDHKPswJNjCr2DQf_mkpPg/view?usp=sharing)
- Tipos de resolución:
    - [Móviles](https://www.figma.com/proto/EgWspZWTzvX0MpPIjLDwhB/Votación-Layouts?node-id=6%3A43&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=6%3A43)
    - [Tabletas](https://www.figma.com/proto/EgWspZWTzvX0MpPIjLDwhB/Votación-Layouts?node-id=84%3A1033&scaling=min-zoom&page-id=84%3A1032&starting-point-node-id=84%3A1033)
    - [Escritorio](https://www.figma.com/proto/EgWspZWTzvX0MpPIjLDwhB/Votación-Layouts?node-id=84%3A2401&scaling=min-zoom&page-id=84%3A1031&starting-point-node-id=84%3A2401)

## Requerimientos:
[ ] Debes crear el archivo html del home del sitio web
[ ] Debes utilizar media queries para cumplir con los tipos de resolución
[ ] Puedes utilizar procesadores como SASS/LESS para optimizar y ahorrar trabajo en tus estilos CSS
[ ] El menú principal debe direccionar a otras páginas internas. Aunque sólo te indicamos cómo se debería ver el home, puedes crear páginas vacías con los títulos de cada sección.

### Fase 2 - Interacción con Javascript
Para esta fase debes agregar alguna interacción con Javascript al home creado en la fase 1.

## Requerimientos:
[ ] Crear un archivo en formato JSON que contenga la información sobre los personajes para votar
[ ] Consulta y muestra los personajes almacenados en el archivo JSON en el home
[ ] Agregar un mensaje (estilo toast) cuando un visitante realice un voto, debe contener el siguiente texto: "Gracias por tu voto"
[ ] Si el voto es positivo, el mensaje debe tener un estilo verde (o similar), de confirmación, de lo contrario, debe ser rojo (o similar)
[ ] No debe existir restricción por la cantidad de votos por usuario

### Fase 3: PHP y Joomla
En esta fase podrás demostrar tus habilidades con Joomla y PHP, para esto debes cumplir con los siguientes requerimientos:

## Requerimientos:

[ ] Debes crear una instalación limpia de Joomla
[ ] Crea y configura por defecto la plantilla que creaste en la fase 1
[ ] Vincula el link de "Log In / Sign Up" del menú principal a la pantalla de Inicio de sesión de Joomla para que los usuarios puedan registrarse o ingresar a su cuenta
[ ] Crea un componente que permita gestionar los personajes a votar, debes permitir crear, editar y eliminar los personajes desde el panel de control de Joomla (Dashboard).
[ ] Crea una cuenta gratuita en algún proveedor de hosting y publica el sitio que acabas de crear. Indícanos el link en el readme de tu repositorio.


### Entrega

[ ] En el readme de tu repositorio indícanos en un breve resumen qué fue lo que más te gustó y se te dificultó de esta prueba.
[ ] Aparte de las tecnologías usadas en esta prueba, qué más te gusta hacer o te sientes más hábil
[ ] Incluye el link donde alojaste el sitio web resultante de la fase 3
[ ] Envía un correo a daniel.alvarez@emerald.studio con el asunto "Prueba de desarrollo web PHP-Joomla" en donde indiques el link de tu repositorio. Asegúrate de que sea público para que podamos visualizarlo sin restricciones.
