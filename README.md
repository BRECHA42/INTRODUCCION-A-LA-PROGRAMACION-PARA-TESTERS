# Introducción a la programación para testers - CES

## Descripción

Funcionaldiades sitio web http://cestore.ces.com.uy/adminces/.

---

## Funcionalidades (Sin Loguearse)
---
- Iniciar sesión Administrador: Permite que los administradores ingresen al sistema mediante credenciales válidas.
  ### Datos requeridos
- Email
- Contraseña
---  
- Crear cuenta Administrador: Permite crear una nueva cuenta con Rol Administrador de usuario en el sistema.
  ### Datos requeridos
- Nombre
- Apellido
- Email
- País de nacimiento
- Contraseña
---  
- Reiniciar Contraseña: Permite recuperar o restablecer la contraseña de acceso.
### Datos requeridos
- Email
- Contraseña
---
## Funcionalidades (Loguearse)
---
- Editar perfil: Permite modificar la información personal del usuario.
### Datos requeridos
- Nombre
- Apellido
- Email
- País de nacimiento
- Contraseña
---  
- Cerrar sesión: Permite finalizar la sesión activa del usuario.
---  
- Crear Nuevo usuario: Permite registrar nuevos usuarios dentro del sistema.
### Datos requeridos
- Nombre
- Apellido
- Email
- País de nacimiento
- Contraseña
- Rol
---  
- Eliminar Uusario (Solo accesible a Usuarios Administradores): Permite eliminar usuarios registrados.
### Datos requeridos
- ID de usuario
- Nombre de usuario
---  
- Visualziar usuarios: Permite visualizar el listado de usuarios registrados en el sistema.
### Datos visualizados
- Nombre
- Apellido
- Email
- Rol
- Estado del usuario

---

---

## Estructura del proyecto

src/
└── Usuario.java

---

## Autor

Carlos Bredo
