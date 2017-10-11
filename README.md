Kelly Velez. 201554422
Paula Valencia. 201554041
Descripción de los directorios en este repositorio.

01-socket-utils contiene varios ejemplos básicos de programas de red en Python, e.g. abrir un socket, como redefinir la utilización de un socket, consultar por nombres de servicios, etc. Una descripción de las actividades a hacer en este directorio se describe aquí.
socket-http-client código en python para acceder a un cliente web. Usted debe completar dicho cliente de la siguiente manera. Revise el código y en cada comentario que encuentre la palabra COMPLETE (n) debe introducir el código en Python que le indica el numeral (n). A continuación las pistas de lo que debe poner en el código:
1.Instancie una variable llamada s que es de tipo socket y utiliza el protocolo TCP para la comunicación.
2.Defina una variable llamada port y almacene en ella el valor entero 80.
3.Encuentre el IP del servidor que se encuentra en la variable host y guárdelo en una variable llamada remote_ip.
4.Imprima un mensaje por pantalla que diga el siguiente mensaje La dirección IP de www.google.com es 216.58.192.100. El número IP 216.58.192.100 y www.google.com se deben tomar de las variables remote_ip y host, respectivamente.
5.Defina una tupla llamada endpoint y que consta de los valores en las variables remote_ip y port.
6.Utilice la variable s y su método connect con argumento la variable endpoint para llevar a cabo el proceso de conexión.
7.Utilice un método de la variable s para enviar los datos al servidor.
8.Utilice un método de la variable s para recibir los datos de respuesta del servidor y los almacena en una nueva variable llamada reply.

1.Instancie una variable llamada ss que es de tipo socket y utiliza el protocolo TCP para la comunicación.
2.Defina una tupla llamada endpoint y que consta de los valores en las variables '' y args.port.
3.Utilice los métodos necesarios para asociar el socket a la tupla definia anteriormente e indíquele al sistema operativo el máximo número de conexiones que este debe atender en caso que el servidor web no lo pueda hacer inmediatamente. HINT Los métodos son bind y listen.
