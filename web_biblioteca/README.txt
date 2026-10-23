SISTEMA BIBLIOTECARIO UTNG - VERSIÓN WEB
========================================

Esta carpeta contiene una conversión de interfaz del proyecto JavaFX a una estructura web:
- HTML: index.html, estructura de las vistas.
- CSS: css/styles.css, estilos y diseño adaptable.
- JavaScript: js/app.js, navegación y comportamiento interactivo.
- assets/: imágenes y logotipos recuperados del proyecto original.

CÓMO EJECUTAR
-------------
1. Descomprime el ZIP.
2. Abre la carpeta "web_biblioteca".
3. Haz doble clic en index.html para abrirlo en tu navegador.

También puedes abrir la carpeta en VS Code y usar la extensión Live Server para recargar los cambios automáticamente. No requiere npm ni instalar dependencias.

VISTAS INCLUIDAS
----------------
Inicio, Consulta del catálogo, Gestión de materiales, Préstamos, Reportes y Usuarios.
Incluye navegación, búsqueda, filtros, formularios de alta/edición, eliminación de usuarios/préstamos,
cambio de disponibilidad, registro de devolución y exportación CSV de reportes.

IMPORTANTE: ALCANCE DE ESTA CONVERSIÓN
--------------------------------------
Esta es una demostración frontend. Los registros de ejemplo y cambios se guardan en localStorage
del navegador; no se conecta a la base de datos SQL Server del proyecto Java original. Los datos
pueden variar según el navegador/equipo y no se comparten con otros usuarios. El inicio de sesión
es simulado y acepta cualquier correo y contraseña.

Para tener una aplicación web real conectada a SQL Server, hace falta crear un backend/API
(por ejemplo, Java con Spring Boot, .NET o Node.js), configurar la conexión segura a la base
de datos y reemplazar las operaciones de localStorage por llamadas a esa API. No es seguro
conectar el navegador directamente a SQL Server.
