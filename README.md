<p align="center"><img src="https://user-images.githubusercontent.com/73592097/152687804-e294d7e9-9e97-4c92-b07d-c681542591d0.png" height="400px"></p>


<hr/>

# Índice #

## - ¿Qué es Travis? ##
## - ¿Cómo usar Travis? ##
## - Ventajas ##
## - Funciones de Travis CI ##
## - Requisitos Previos ##
## - Travis usando: ##
### <img src="https://user-images.githubusercontent.com/73592097/152375522-7d9ee0ad-57af-453e-ba14-9821bf6619c9.png" width="100px" height="30px"/> ###
## - Requisitos Previos ##
<hr/>


***¿Qué es Travis?***

Es un sistema de Integración continua, nos permite crear,probar e implementar código de forma rápida y sencilla. Fundado en 2011 por la comunidad de Travis CI,Idera. Integrado con GitHub 

***¿Cómo usar Travis?***
- Primero nos crearemos una cuenta en [travis](https://www.travis-ci.com/), podremos registrarnos de tres maneras

  * Gmail
  * GitHub
  * Facebook

  <br/>
En la página oficial de travis, vamos a registrarnos en el botón(llamado  **start today**) esquina superior derecha. 
 ![1](https://user-images.githubusercontent.com/73592097/152692062-6c763441-3f10-401b-85c4-9b7fdcddc5fa.PNG)
En esta página nos encontramos con distintas opciones de registro que nos permiten subir proyectos en un momento,en mi caso elegí GitHub.

![2](https://user-images.githubusercontent.com/73592097/152692485-a8a780db-cf08-4ba0-89f2-5d5df4e8c186.PNG)

En el siguiente cuadro aparecera la ventana para autorizar y darle a travis permisos sobre los repositorios de Github

![3](https://user-images.githubusercontent.com/73592097/152692585-c7bea93b-ef7a-49db-8bab-07b28718d065.PNG)

Finalmente ya somos usuarios de Travis CI

<br/>
<br/>


***Ventajas***
Las ventajas de usar travis son las siguientes:
 - **Gratuito** para Proyectos Open Source y de pago para proyectos privados.
 -  **Integración rápida** con GitHub.

![image](https://user-images.githubusercontent.com/73592097/152353373-40d925e8-b3c3-46c6-be1f-0946334018f2.png)

 -  **Testea y construye** aplicaciones que corran en Linux.
 -  **No tiene costos** de mantenimiento.
 -  Intuitiva.
 -  **Verifica la calidad del código**.

***Funciones de Travis CI***

- Tablero de mandos
- Depuración de código
- Gestión de pruebas
- Ofrece soporte para :
  -  Java
  -  Python
  -  Node.js
  -  PHP
  -  Ruby...

***Requisitos Previos <img src="https://user-images.githubusercontent.com/73592097/152683389-1050ea2e-94fd-490b-a62f-ff1b3bd328e2.png" width="50px" height="50px"/>***
- Repositorio GitHub, con permisos de propietario.
- Cuenta en Travis-CI
- Docker configurado (Opcional)

<hr/>

***Travis usando:***


****<img src="https://user-images.githubusercontent.com/73592097/152375522-7d9ee0ad-57af-453e-ba14-9821bf6619c9.png" width="100px" height="30px"/>****

Nos crearemos el repositorio de prueba para desplegar en Travis, la carpeta de configuración de travis se llama .**travis.yml**, que se coloca en el directorio raiz

> - languaje-> indicamos el lenguaje a usar
> - script -> script a lanzar 

> - branches-> ramas a supervisar 
> - notifications-> se pueden hacer notificaciones de las pruebas por correo
> - install -> aplicaciones a instalar

Entre otras secuencias de configuración que se encuentran en el siguiente [enlace](https://docs.travis-ci.com/user/job-lifecycle/)

Configuración de ejemplo

![image](https://user-images.githubusercontent.com/73592097/152694374-070ebf95-9299-4942-b33d-6ca307352106.png)

Fichero .travis.yml

![image](https://user-images.githubusercontent.com/73592097/152694406-82376921-6f33-49c7-9ebe-332a4785c23a.png)

Script python 

![image](https://user-images.githubusercontent.com/73592097/152694422-055b0f6f-04d4-44bd-a21c-eb8b8e18c11c.png)

Ahora que tenemos nuestro repositorio listo para usar con Travis CI, vamos a sincronizarlo, para desplegar el pequeño script
<hr/>


Una vez iniciado travis, los primero que tenemos que hacer es sincronizar nuestro repositorio para ello, vamos a nuestro perfil> configuración

![5](https://user-images.githubusercontent.com/73592097/152693144-a6eda9ac-8b6f-4c9e-8d6a-e560a264bed7.PNG)

Vamos a activar nuestro repositorio para que este supervisado con travis
![6](https://user-images.githubusercontent.com/73592097/152693268-1f3545c5-88f8-4734-997b-919bcb309e8e.PNG)

Nos apareceran todos los repositorios de nuestro GitHub, seleccionamos el repositorio para desplegar la aplicación adecuada.

![7](https://user-images.githubusercontent.com/73592097/152693315-f288ed80-f8cc-40ff-8d14-14d3939e51c7.PNG)

Una vez, seleccionado el repositorio vemos en el tablero de Travis CI, los repositorios activos


![image](https://user-images.githubusercontent.com/73592097/152694879-faf7f5d8-a72c-46fb-b08f-1b28638bc19c.png)










