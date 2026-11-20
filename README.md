# Estética Bella Studio

Panel administrativo en PHP y MySQL para una estética.

## Código fuente completo

Descarga **Estetica-Bella-Studio-Codigo-Fuente.zip** desde la lista de archivos. El archivo contiene el código íntegro y editable, conservando la estructura de carpetas de la aplicación.

1. Descomprime el archivo y entra en `Codigo-fuente`.
2. Copia la carpeta `bella-studio` a `C:\AppServ\www`.
3. Inicia Apache y MySQL y abre `http://localhost/bella-studio/`.
4. Completa el instalador con tus datos locales de MySQL y crea tu cuenta administradora.

No necesitas importar el SQL para una instalación limpia. No hay contraseña administradora predefinida. En XAMPP usa `C:\xampp\htdocs`.

## Funciones

Clientes, servicios, personal, agenda, cobros, inventario, gastos, reportes, usuarios y configuración. El campo Cliente permite escribir el nombre conservando la estructura original del formulario. Las citas validan superposición por profesional y el cobro es único por cita.

Administración gestiona todos los módulos. Recepción gestiona clientes, citas y cobros y consulta catálogos e inventario.

## Base de datos y modelo

El repositorio incluye `estructura.sql`, con diez tablas y ocho relaciones, y el diagrama entidad relación.

## Requisitos

Apache 2.4, PHP 7.3+ con PDO MySQL y mbstring, MySQL 5.7+ o MariaDB 10.4+. Uso en localhost. La copia no incluye credenciales reales, config.php ni registros privados de la instalación.

## Equipo y roles

- Bartolo Vaquero Ximena: coordinación y documentación.
- Chávez Beltrán Noe: lógica y módulos.
- Gómez Angeles Evelin: base de datos e instalación.
- Hernández Rafael Adán: diseño y pruebas.

## Alcance

El panel es una aplicación web independiente. La app móvil y su API de integración son mejoras futuras. No procesa pagos bancarios ni emite CFDI.

