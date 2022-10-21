# MANUAL TÉCNICO DE DESPLIEGUE APLICACIÓN WEB SHOPIFY
## Proyecto: Prueba Técnica Gradiweb 2022 Front-End Developer
 
 ### Versión: 1.0 
 21/10/2022
 
 
 ### Contenido
 1.	Objetivo
2.	Prerequisitos
3.	Descripción técnica de la Solución tecnológica
4.	Información de ambientes y usuarios
5.	Tabla de componentes para instalar
6.	Pasos para el despliegue
7.	Plan de retorno
8.	Condiciones de mantenimiento
9.	Anexos

### 1.	Objetivo

Informar los requerimientos y pasos a seguir para realizar el despliegue de los componentes para dar cumplimiento al requerimiento realizado por la compañía Gradiweb como parte del proceso de aplicación a la vacante de desarrollador Front-End.
### 2.	Prerrequisitos
•	Tener una cuenta de desorrallor en Shopify Developers Platform
https://shopify.dev/
•	Tener una tienda de prueba para aplicar el tema desarrollado. 
•	Tener productos, colecciones y blogs posteados en dicha tienda demo. 
•	Poseer todos los permisos y acceso a la tienda de prueba. 


### 3.Descripción técnica de la Solución tecnológica

Aplicación web desarrollada con lenguajes como HTML5, CSS y JAVASCRIPT. Con arquitectura y compatibilidad en la plataforma de e-commerce Shopify. La aplicación ha sido desarrollada siguiendo los lineamientos y estructuras de un proyecto de Shopify, a través del uso de lanzadores JSON y Templates en Liquid. La tienda de prueba tiene interacción entre usuario (log-in and sign-in), los productos de la tienda, el carrito y pasarela de pagos; además de mostrar información a través de blogs personalizables a través de bloques pertenecientes al esquema liquid. 
### 4.	Información de ambientes y usuarios
	Ambiente	IP / Hostname / URL
Origen	Desarrollo	https://teststorebrianvalencia.myshopify.com/ or https://ckhs9g7qsoitjdkh-62655594654.shopifypreview.com (contraseña: Gradiweb)
Destino	QA	Por definir


### 5.	Tabla de componentes a instalar

Fuente	Nombre	Tipo 

layout	theme	liquid

section	featured-product	liquid

section	main-blog	liquid

section	main-cart-items	liquid

section	header	liquid

section	main-404	liquid

section	main-article	liquid

section	main-blog	liquid

section	main-collection	liquid

section	main-product	liquid

section	main-order	liquid

snippet	Icon-company	liquid

snippet	Icon-account	liquid

snippet	Icon-cart-mine	liquid
template	404	json

template	article	json

template	blog	json

template	cart	json

template	collection	json

template	product	json

template	index	json


### 6.	Pasos para el despliegue
a)	Descargar o clonar el código desde el repositorio de GitHub:
https://github.com/ervysad/https---github.com-ervysad-gradiweb_test_2022
b)	Iniciar sesión de Shopify.dev
c)	Ingresar a alguna tienda disponible para realizar pruebas del front desarrollado.
d)	Una vez dentro de la tienda ir a la sección “Temas”.
 

e)	En la sección “Theme Library” hacer clic en agregar tema.
 

f)	Conectar el tema con el repositorio en GitHub compartido o subir el archivo del repositorio completo en .zip. 
g)	Finalmente acceder al tema aplicado a la tienda publicándolo para pruebas o a través de la vista previa. (publish o preview)
  
 

h)	Realizar las pruebas y verificaciones correspondientes.

### 7.	Plan de retorno
En caso de presentarse algún problema durante el despliegue favor realizar nuevamente el procedimiento de vinculación del repositorio o subir nuevamente el código del tema. En caso de persistencia comunicarse con el correo electrónico bcvalenciap@unal.edu.co para mayor asistencia.
### 8.	Condiciones de mantenimiento
Dependiendo del resultado de la evaluación de desempeño y errores se programarán los mantenimientos requeridos al proyecto con el fin de superar la fase de pruebas y dado caso llevarlo a operación. Dependiendo del equipo de desarrollo se acordarán las medidas a tomar teniendo en cuenta la retroalimentación del estado del proyecto. 
### 9.	Anexos

Demostración en vivo del funcionamiento del proyecto.

https://drive.google.com/file/d/129dqJg-J_K87KyHEuynH8cuUuhuRnBRf/view?usp=sharing
###
