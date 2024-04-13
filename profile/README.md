# Adoptaunpeludo.com 👋

## Descripción 👩‍💻 

 La web adoptaunpeludo.com crea un punto de encuentro donde protectoras y asociaciones puedan mostrar los animales que han rescatado de la calle para los que buscan una familia y las personas interesadas en adoptar o acoger una mascota puedan conocer sus características y ponerse en contacto con las protectoras.

## Equipo 🙋‍♀️

El proyecto ha sido desarrollado por el grupo {JP:2}, compuesto por alumnos del Bootcamp de Desarrollo Web Full Stack XV de Keepcoding:

- Jose Alberto Delgado ([GitHub](https://github.com/JoseAlbDR) | [LinkedIn](https://www.linkedin.com/in/jalbertodelgado/) | [Web](https://www.jadero.dev/home))
- Juan Manuel Acosta ([GitHub](https://github.com/jmacosta) | [LinkedIn](https://www.linkedin.com/in/juan-manuel-acosta-benitez/))
- Pol Valle ([GitHub](https://github.com/Doplax) | [LinkedIn](https://www.linkedin.com/in/pol-valle-montes/) | [Web](https://doplax.dev/))
- Francisco Suárez ([GitHub](https://github.com/PaquitoGR) | [LinkedIn](https://www.linkedin.com/in/francisco-a-suarez/))


## Características principales

- **Registro de usuarios:** Los usuarios pueden crear cuentas como adoptantes o como asociaciones/protectoras de animales.
- **Listados de animales:** La página principal cuenta con enlaces a listados de gatos y perros disponibles para adopción, así como a un listado de asociaciones participantes.
- **Filtros y búsqueda:** Los listados de animales son paginados y ofrecen opciones de filtrado por nombre, tamaño, edad, género y provincia.
- **Detalle de los animales:** Cada animal en el listado tiene una página de detalle con información detallada, incluyendo raza, características, edad y fotos adicionales.
- **Adopción y favoritos:** Los usuarios pueden solicitar la adopción de un animal directamente desde su página de detalle, y también pueden agregar animales a su lista de favoritos.
- **Mensajería instantánea:** Los adoptantes pueden iniciar un chat con las asociaciones/protectoras que poseen los animales que les interesan, para obtener más información o solicitar la adopción.

## Funcionalidades de usuario

- **Perfil de usuario:** Los usuarios registrados tienen una página de perfil donde pueden editar sus datos personales.
- **Animales favoritos:** Los usuarios pueden ver y gestionar una lista de animales favoritos desde su perfil.
- **Historial de adopciones:** Los usuarios pueden ver un registro de las adopciones que han realizado desde su perfil.

## Funcionalidades de las asociaciones

- **Perfil de asociación:** Las asociaciones tienen una página de perfil donde pueden editar sus datos y dar de alta o baja a los animales que tienen disponibles para adopción.
- **Gestión de animales:** Las asociaciones pueden agregar nuevos animales para adopción, actualizar la información de los animales existentes y retirar animales que hayan sido adoptados.

## Tecnologías utilizadas

- **Frontend:** JavaScript con React.js, React Query, React Router y NextUI para la interfaz de usuario.
- **Backend:** Node.js con Express.js, utilizando TypeScript para un desarrollo más robusto y mantenible.
- **Base de datos:**
  - PostgreSQL para almacenar datos relacionados con usuarios, animales y asociaciones.
  - Supabase como base de datos vectorial para el servicio de asistente.
  - MongoDB como base de datos documental para almacenar el historial de chats del asistente y los logs de error.
- **Mensajería y notificaciones:** Se utiliza un servidor de WebSockets para la mensajería en tiempo real entre usuarios y asociaciones y las notificaciones en tiempo real.
- **Broker de mensajes:** Se utiliza RabbitMQ como broker de mensajes para la comunicacion entre los distintos servicios que conforman la aplicación.

## Links 
- [Front End](https://github.com/Adoptaunpeludo/frontend) 
- Backend:
  - [API](https://github.com/Adoptaunpeludo/backend)
  - [WebSocket Service](https://github.com/Adoptaunpeludo/websocket-service)
  - [Assistant Service](https://github.com/Adoptaunpeludo/chatbot-service)
  - [Email Service](https://github.com/Adoptaunpeludo/email-service)
  - [Monitoring Service](https://github.com/Adoptaunpeludo/noc-service)
    
¡Gracias por tu interés en adoptaunpeludo.com!
