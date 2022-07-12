# Final Grupal 
Final Grupal

# APPFARM
Esta aplicación es una farmacia en linea, la que permite la venta de remedios. 
Tiene un formulario para que el administrador cargue productos y un carro de compra para la venta.

## Comenzando 🚀
Debes descargar el aplicativo del github Patricio90 con el nombre tlv_final.

### Pre-requisitos 📋
Activar entorno virtual en Visual Studio Code. En caso de no tener instalado un entorno virtual, debes instalarlo y activarlo.
Una vez activo el entorno virtual, ir a la carpeta del aplicativo y ejecutar python.manage.py runserver

### Ejecutando las pruebas ⚙️
La aplicación comienza en la página principal donde se indica que se trata de una farmacia virtual. 
La aplicación nos permite registrarnos como usuarios. 
Pasos para prueba:
En el archivo settings.py, se debe modificar la contraseña de la base de datos farmbd. La contraseña es 12345678.
Ingrese a http://127.0.0.1:8000/ y logearso con super usuario farmacia, contraseña farmacia.
En la opción productos, agregar producto. 
En la opción listado productos, puede ver los productos agregados. 
Puedes agregar usuarios en la opcion login, registro. 

### Analice las pruebas end-to-end 🔩
El sistema graba nuevos usuarios.
Valida que el formulario de creación de usuarios trabaja correctamente.
El sistema permite agregar, modificar, actualizar y eliminar productos.
Valida que el formulario trabaja correctamente. 

### Construido con 🛠️
El aplicativo esta desarrollado con en el framework Django versión 4.0.5, desarrollado en Python versión 3.10.4.
Utiliza una base de datos PostgreSQL, administrada con pgAdmin..
Para el desarrollo se ha utilizado el editor Visual Studio Code versión 1.69.0.
El aplicativo ha sido probado con Google Chrome

### Autores ✒️
En este proyecto individual participaron activamente: 
•	Yaruska Diaz - Alumna - yarudv
•	Mauricio Aspeé Ramos - Alumno - maspee 
•	Patricio Pinto - Alumno - Patricio90
•	Joshua Olave - Profesor - jm-olave 

