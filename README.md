Desarrollo Web Full Stack - Acamica 2020

Proyecto: Delilah Resto

Grupo: dwfs-cor-10 (Cordoba)

Alumno: Moreno Matias Javier

Email: elmatiasmoreno@hotmail.com

https://github.com/matiasjmoreno/delaila

Pasos para inicializar el servidor y la base de datos, esto le permitira interactuar con la API desde su propia computadora.

Archivos que componen el proyecto :

openapi.yaml y documentacion.html: Son los archivos en los que encuentra las instrucciones de como usar cada uno de los endpoints correctamente. Los parametros que espera recibir y lo que obtendra como respuesta de cada uno de ellos.

estilos.css: contiene los estilos correspondientes al archivo documentacion.html

package.json: es el archivo que contiene la informacion de los modulos que debera importar para poder usar la api correctamente.

queries bd: Posee los queries para que pueda crear la estructura de las tablas requeridas para el funcionamiento de la api. Una vez ejecutados, en su motor de base de datos deber�a tener una nueva base de datos llamada delilah, con 4 tablas: usuarios, productos, pedidos y pedidos_productos. La tabla usuarios deber�a tener un registro, que sera el que usara para las funcionalidades de administrador. Las otras 3 estaran vaci�as.

serverdelilah.js: es el archivo de la api.

Como inicializar la API:

1.  Lo primero que debes hacer es abrir el archivo serverdelilah. Asegurese que en la terminal tengas abierta la carpeta en la que se encuentra el archivo.

2.  Luego, en la consola, corra el comando npm install. Esto instalara los modulos necesarios para que la api funcione en su computadora. (Asegurese de tener node instalado)

3.  El siguiente paso es configurar la base de datos para conectarlo con nuestro proyecto. Para eso en la li�nea numero 12 del archivo serverdelilah, reemplaza en ("mysql://root:@localhost:3306/delilah") el segmento "root:" por su usuario y contrase�a de la base de datos de la siguiente manera --> usuario:contrase�a

4.  Ahora solo falta ejecutar el archivo y ya esta listo para usar la api desde el puerto 3000 de su computadora, para empezar a usar la api puede crear un nuevo usuario desde el endpoint post usuarios y para probar las funcionalidades de administrador, aca le dejo el usuario y contrase�a necesario para ello:

nombreusuario: delilahAdmin
contrase�a: administrador56

En la documentacion tiene todos los endpoints explicados detalladamente.
