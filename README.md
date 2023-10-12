GUIA DE INSTALACION DEL FACTURADOR:

PASO 1:
Lo primero que haremos sera instalar LARAGON, para ello entraremos a https://laragon.org/download/index.html
Aqui lo que haremos es darle Clic en la parte de EDITOR donde diga DOWNLOAD LARAGON - FULL (173MB)

![image](https://github.com/Luiston26/Guia/assets/141371960/4539c00a-fb56-4ae2-90b3-c4e2f31d707e)

Al a ver hecho eso instalaremos LARAGON, la instalacion puede durar algunos minutos depende de su PC
Mientras que instalamos LARAGON tambien vayamos instalando VISUAL CODE STUDIO (esto ya la mayoria lo debe tener instalado).

PASO 2:
Lo que haremos aca es configurar nuestro Laragon, para ello iremos a Menu, luego en las opciones que nos aparecere escogemos PHP, luego en extensiones y finamente luego nos saldra una lista llena de opciones, pero nosotros macaremos la opciones que dice, SOAP.

![image](https://github.com/Luiston26/Guia/assets/141371960/2979af0c-0082-4cc3-aaf8-7db24690dbe9)

Luego de eso iremos a la tuerquita que esta en la misma interfaz de Laragon en la cual lo que haremos es darle la ruta de la instalcion del facturador en nuestra PC, para ellos luego de darle en la tuerquita, se nos va presentar un cuadro donde iremos a la opcion que diga ROOT DOCUMENTOS, en la cual escogeremos la ruta de LARAGON y la carpeta de nombre WWW y finalmente le cambios lo que es el HOSTANAME, solo agregaremos al final .pe 

![image](https://github.com/Luiston26/Guia/assets/141371960/7279cef4-fb48-4c3e-83a7-7f4a57aacc27)

PASO 3:
Ahora entraremos a la terminal desde LARAGON, para esto le damos a Iniciar Todo y luego le dan en el boton de terminal.

![image](https://github.com/Luiston26/Guia/assets/141371960/bb83003a-aea8-4587-81df-1936540c7c12)

Ya una vez entrado a la terminal vamos a poner algunos comando, primero vamos a clonar nuestro repositorio, para esto pondremos git clone y el link de nuestro repositorio que creemos en GitHub, luego nos saldra ahi mismo en la terimnal que pongamos nuestro nombre de usuario en GitHub y ya luego esperemos a que siga cargando.

![image](https://github.com/Luiston26/Guia/assets/141371960/c372e662-2214-4ddf-b4f8-ced4555fc9f3)


PASO 4:
Despues que haya cargado, aun no saldremos de la terminal y sigamos con los comandos, pondremos cd facturadorpro4, luego ponemos composer install, esperamos a que los codigos carguen en su curso y luego cuando en la terminal ya nos deje escribir actualizamos composer con update composer, esto puede tarder unos minutos.

![image](https://github.com/Luiston26/Guia/assets/141371960/a5e21685-eb4e-4940-a01b-3db8d4d95c9b)

![image](https://github.com/Luiston26/Guia/assets/141371960/db926ec8-1ec8-492a-aa50-110cbbf41a54)

PASO 5:
una vez que haya terminado de cargar todo, seguimos con la onstalacion, para ellos vamos a poner los siguentes comandos, composer self.update, luego vamos a poner rm composer.lock, luego composer install y luego pondremos git checkout

![image](https://github.com/Luiston26/Guia/assets/141371960/87a5d6a4-e070-411c-bb01-da1446175742)

Paso 6:
Lo que haremos ahora es crear una Base de Datos y le pondremos como nombre tenancy, para ellos abrimos Laragon, luego le damos donde dice Bse de Datos, ponemos en nueva, abrimos, luego clic derechi en el panel del lado izquierdo y eligimos la opcion crear nueva Base de dato y le ponemos el nombre tenancy.

![image](https://github.com/Luiston26/Guia/assets/141371960/1b400cf7-8206-4e4d-8513-3a6a3e952380)

Luego volvemos al menu de inicio de Lagaron y elegimos la opcion que dice Root, se nos abrira nuestra caperta, entramos a la carpeta que dice facturadorpro4, luego buscamos el archivo que se llama .env.example y lo copiamos y pegamos ahi mismo el archivos que copiamos pero le vamos a cambiar el nombre, el cual sera .env y luego clic derecho al archivo y lo editamos en la opcion Edit With Notepad++ una vez adentro lo unico que haremos es ir a la linea 5 del codigo y cambiar la palabra facturador a facturador4.pe y le damos en guardar 

![image](https://github.com/Luiston26/Guia/assets/141371960/640571bc-1da3-49ba-8013-bdb8e55ad41b)

![image](https://github.com/Luiston26/Guia/assets/141371960/698f7ef4-3a0c-404d-b73d-84e7be2d14ce)

Paso 7:
Ya lo que haremos ahora es seguir copiando y pegando codigos, los siguientes codigos seran php artisan key:generate, composer dump-autoload, php artisan migrate --seed y luego php artisan  storage:link 

![image](https://github.com/Luiston26/Guia/assets/141371960/08d126f7-f784-4de1-8e5e-14f435507da3)

Paso 8: 
Ya por ultimo lo que haremos es abrir otra vez el Laragon donde vamos a detener el programa y luego a iniciar para actulizar todo lo que hemos agregado, lueho le damos clic en ka opcion H que sale arriba para ver si se ha guaradado los cambios, luego vamos a buscar la siguiente ruta en nuestra expolador de archivos, disco C, Windows, es-ES, System 32, Drivers, etc y luego host, aqui le damos en clic derecho luego en propiedades, le desactivamos la opcion que dice solo lectura y le damos en continuar, lueego cerramos y volvemos al Laragon donde le vamos a volver a entrar en H y tenemos que tenemos lo siguientes codigos 

![image](https://github.com/Luiston26/Guia/assets/141371960/d474b471-e1f9-4921-83af-9e54b75162fe)

![image](https://github.com/Luiston26/Guia/assets/141371960/5813c3c3-ad8d-4ad7-9294-4f2111152ab4)

Ya por ultimo si lo hicimos tal cual vamos a nuestro explorador de internet favorito y escribiremos facturadorpro4, nos saldra un login donde nos registraremos el cual pondremos de nombre de usuario admin y la contraseña sera 123456 y asi lograremos ingresar al facturador.

![image](https://github.com/Luiston26/Guia/assets/141371960/fadba522-8bba-4bf1-b995-d43dfa324e0e)









