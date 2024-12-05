# BookFlow

BookFlow es una aplicación web diseñada para la administración eficiente de bibliotecas. Proporciona herramientas para gestionar transacciones, movimientos y usuarios con roles diferenciados. Con un diseño moderno e intuitivo, facilita la organización del inventario y las operaciones de préstamo y devolución de materiales.

## Link demostración de la aplicación
[Demostración: Gestión de bibliotecas - Oswald Gutiérrez](https://drive.google.com/file/d/16s6KX78KtHQ1uy17Al6e90cpwG9YeA8C/view?usp=drive_link "Demostración: Gestión de bibliotecas - Oswald Gutiérrez")

## Características

### Funcionalidades principales
- **Autenticación de usuarios**:
  - Implementada con [Supabase](https://supabase.com/).
  - Inicio de sesión seguro con gestión de roles y sesiones.
- **Página de Landing**: Página inicial atractiva con opción para iniciar sesión.
- **Sidebar**: Navegación intuitiva con enlaces a las diferentes secciones de la aplicación:
  - Inventarios
  - Transacciones
  - Usuarios
- **Gestión de transacciones**:
  - Visualización de movimientos.
  - Visualización de préstamos de libros.
  - Creación, edición y eliminación de registros (Solo administradores).
- **Gestión de usuarios**:
  - Roles diferenciados: **ADMIN** y **USARIO**.
  - Administración de permisos según el rol.
  
### Roles de usuario
- **ADMIN**:
  - Acceso completo a todas las funcionalidades.
  - Gestión de usuarios y creación de nuevos libros.
- **USER**:
  - Acceso a la gestión de transacciones y libros.
  - Sin permisos para administrar usuarios o crear nuevos libros.

## Tecnologías utilizadas

- **Frontend**: 
  - [Next.js](https://nextjs.org/) - Framework de React para aplicaciones web modernas.
  - [React](https://reactjs.org/) - Biblioteca para construir interfaces de usuario.
  - [TailwindCSS](https://tailwindcss.com/) - Framework CSS para diseño responsivo y moderno.
  
- **Backend**:
  - [Supabase](https://supabase.com/) - Base de datos, autenticación y servicios de backend.

## Instalación

### Requisitos previos
- Node.js (v16 o superior).
- npm o yarn.
- Una cuenta en [Supabase](https://supabase.com/).

## Pasos de instalación

### 1. Clonar el repositorio
1. Clona el repositorio en tu máquina local ejecutando el siguiente comando:  
```bash
git clone https://github.com/20242-Ingenieria-Web-Udea-MJ/Oswald-Gutierrez-Biblioteca
```
2. Instalar dependencias del proyecto
```bash
npm install ó npm install --force
```
3. Configuración de credenciales de Supabase
```bash
Crear un .env en la raíz del proyecto con las credenciales de Supabase.
```
4. Ejecutar la aplicación
```bash
npm run dev
```
5. Abrir el servidor de la aplicación localmente
```bash
http://localhost:3000
```

