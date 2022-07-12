# Final Grupal 
Final Grupal


# proyectoFinal
Individual final

# Monitoreo de Adultos Mayores
Esta aplicación está pensada como un servicio gratuito de la Municipalidad para sus vecinos. 
Dicho esto, la aplicación permite que cada vecino, pueda ingresar los datos de un adulto mayor, junto a una prescripción médica firmada y nos indique en que horarios se debe tomar los remedios de esta prescripción, de esta forma una persona llama telefónicamente al adulto mayor. <br>

## Comenzando 🚀
Debes descargar el aplicativo de mi github maspee con el nombre final_individual.

### Pre-requisitos 📋
Activar entorno virtual en Visual Studio Code. En caso de no tener instalado un entorno virtual, debes instalarlo y activarlo.
Una vez activo el entorno virtual, ir a la carpeta del aplicativo y ejecutar python.manage.py runserver

### Ejecutando las pruebas ⚙️
La aplicación comienza en la página principal con un mensaje de bienvenida, que nos explica para que sirve y nos da la opción de Ingresar. 
Esto nos lleva a la pagina de prescripciones médicas y nos permite agregar. Es necesario estar registrado para poder ingresar prescripciones. La aplicación nos permite registrarnos como usuarios. 
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

