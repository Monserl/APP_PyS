# APP_PyS
Será una plataforma de exploración y gestión de películas y series, donde los usuarios podrán crear una cuenta, iniciar sesión y acceder a una base de datos con información de títulos, incluyendo imagen, sinopsis y puntuación promedio. Funcionalidades principales :
1. Gestión de cuenta de usuario 
    * Registro de cuenta mediante correo electrónico y contraseña. 
    * Inicio de sesión con autenticación segura (JWT).
2. Exploración de películas y series
    * Visualización de sinopsis, imagen y título. 
    * Consulta de opiniones y valoraciones de otros usuarios. 
    * Ranking general de cada película basado en puntuaciones globales.
3. Interacción con películas
    * Marcar películas como “vista”. 
    * Asignar puntuación mediante estrellas. 
    * Escribir y publicar reseñas.
4. Listas personalizadas
    * Crear listas con nombre personalizado (ej. “Mis pelis de terror fav”). 
    * Agregar y eliminar películas de dichas listas. 
    * Lista automática de películas vistas, con opción de filtrado por calificación otorgada

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
