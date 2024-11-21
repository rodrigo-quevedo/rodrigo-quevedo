# Proyectos personales

Estos son proyectos en los que no seguí ninguna guía o tutorial. Solamente usé Google para soluciones espefícias, y la documentación oficial de las tecnologías del proyecto.

### Gest (en construcción)

- Live demo: [gest-rodrigo-quevedo.onrender.com](https://gest-rodrigo-quevedo.onrender.com/)
- Source code: [/rodrigo-quevedo/Gest](https://github.com/rodrigo-quevedo/Gest)
  
![Gest website icon](https://github.com/rodrigo-quevedo/Gest/blob/master/frontend/src/media/website_icon.png) 

Es una aplicación web fullstack pensada para un negocio que vende productos: se puede cargar la compra de productos de los proveedores, cargar las ventas a los clientes, tener un historial de compras y ventas, y también tener una lista de productos disponibles.

#### Aspectos técnicos
- Frontend: HTML, CSS (sin librerías), CSS Modules, JavaScript, React, creación de componentes reutilizables, UI responsive (versión desktop y versión mobile), fetch a la API backend, variables de entorno en React.
- Backend: NodeJS, Express, MongoDB, Mongoose, manejo de cookies, JSON Web Token (JWT), bcrypt (para encriptar contraseñas de los usuarios en la DB), configuración de CORS (sin librerías, solo middleware), manejo de variables de entorno en NodeJS.
- Database: Mongo DB.
- Despliegue: El frontend y el backend están desplegados por separado en [Render](https://render.com/) . La database está desplegada en [Mongo DB Atlas](https://www.mongodb.com/products/platform/atlas-database) .

