# Tienda de Ropa Online - Proyecto en Angular con MySQL

## Descripción del Proyecto

Este proyecto es una aplicación web desarrollada en Angular que simula una tienda de ropa online. La información sobre los productos, usuarios y transacciones se almacena en una base de datos MySQL. La aplicación permite a los usuarios navegar por la tienda, ver detalles de productos, realizar compras y gestionar sus perfiles.

## Funcionalidades Principales

1. **Catálogo de Productos:**
   - Muestra una amplia gama de productos de moda organizados por categorías.

2. **Detalles del Producto:**
   - Permite a los usuarios ver detalles específicos de cada producto, como descripción, precio y disponibilidad.

3. **Carrito de Compras:**
   - Los usuarios pueden agregar productos a su carrito de compras y realizar compras seguras.

4. **Gestión de Usuarios:**
   - Registro de nuevos usuarios y autenticación para acceder a perfiles personales.

5. **Historial de Compras:**
   - Los usuarios registrados pueden revisar su historial de compras y realizar un seguimiento de sus pedidos.

6. **Base de Datos MySQL:**
   - Almacena la información esencial, como productos, usuarios y transacciones, en una base de datos MySQL.

7. **Interfaz Responsiva:**
   - Diseño responsive para garantizar una experiencia de usuario consistente en diferentes dispositivos.

## Requisitos del Sistema

- **Node.js y npm:** Asegúrate de tener Node.js y npm instalados en tu sistema.

- **Angular CLI:** Se necesita Angular CLI para compilar y ejecutar la aplicación.

- **MySQL:** Es necesario tener un servidor MySQL para la gestión de la base de datos.

## Configuración y Uso

1. Clona o descarga el repositorio en tu máquina local.

2. Navega hasta el directorio del proyecto y ejecuta `npm install` para instalar las dependencias.

3. Configura la conexión a la base de datos MySQL en el archivo de configuración.

4. Crea la base de datos y las tablas utilizando scripts SQL proporcionados en la carpeta correspondiente.

5. Ejecuta `ng serve` para iniciar el servidor de desarrollo de Angular.

6. Abre el navegador y accede a `http://localhost:4200` para utilizar la aplicación.

## Estructura del Proyecto

- **src/app/components:** Contiene los componentes de Angular, como catálogo, detalles del producto, carrito de compras, etc.

- **src/app/services:** Define los servicios que interactúan con la base de datos y gestionan la lógica de la aplicación.

- **src/app/models:** Contiene las clases de modelos para representar productos, usuarios, transacciones, etc.

- **src/app/database:** Incluye scripts SQL para la creación de la base de datos y las tablas.

## Contribuciones y Problemas

Si encuentras problemas, tienes sugerencias o deseas contribuir al proyecto, por favor, abre un issue en el repositorio. ¡Las contribuciones son bienvenidas!

