# Blog CRUD con Laravel y AdminLTE

## Descripción
Proyecto de un sistema de blog implementado en Laravel 11 con un panel de administración usando AdminLTE. Permite a los administradores crear, leer, actualizar y eliminar entradas de blog, gestionando categorías y etiquetas de forma sencilla.

### Funcionalidades
- CRUD completo para entradas de blog.
- Administración de categorías y etiquetas.
- Visualización de entradas con paginación.
- Panel de administración amigable basado en AdminLTE.

### Requisitos
- PHP >= 8.1
- Composer
- Node.js y npm (para compilación de assets)
- Base de datos MySQL o PostgreSQL

### Instrucciones de instalacion

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Daber98/Blog_crud_Final_Desarrollo_Web.git
   cd blog_crud

2. **Instala las dependencias del proyecto:**
   ```bash
   composer install
   
3. **Copia el archivo de entorno de ejemplo y renómbralo:**
   ```bash
   cp .env.example .env

4. Configura tu archivo .env con las credenciales de tu base de datos.

5. **Genera la clave de la aplicación:**
   ```bash
   php artisan key:generate

6. **Ejecuta las migraciones y seeders para crear las tablas en la base de datos y sus registros:**
   ```bash
   php artisan migrate --seed

7. **Inicia el servidor:**
   ```bash
   php artisan serve
