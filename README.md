 Descripción general del proyecto
Este proyecto consiste en una aplicación móvil Android desarrollada para el **Parcial Nº2 de Programación Móvil**, cuyo objetivo es implementar:

- Una **pantalla de Login** con autenticación usando base de datos interna (SQLite).
- Una **pantalla principal**, accesible solo tras un login exitoso.
- La posibilidad de **guardar un registro** en la base de datos desde la pantalla principal.
- Mantener **persistencia de datos** entre ejecuciones.
- Una interfaz simple, funcional y limpia.

Estructura de Pantallas
**1. Pantalla de Login**
Incluye:
- Campo de usuario/email  
- Campo de contraseña  
- Botón para iniciar sesión  
- Validación contra la DB local  
- Mensajes de error cuando las credenciales no coinciden  

 **2. Pantalla Principal**
Accesible solo luego de un login correcto.
Incluye:
- **Título "EduTech Connect"**
- **Barra de búsqueda (solo estética)**
- **Cuatro cards de colores**, centradas en grid  
  Cada card muestra un identificador:
  - MKT → Azul  
  - HTML → Naranja  
  - SCI → Violeta  
  - FIN → Verde  

**Base de Datos – SQLite**
La aplicación usa una base de datos local interna.

Incluye:
- Tabla para usuarios  

Operaciones:
- Insertar usuario (pre-cargado o creado)
- Validar credenciales
