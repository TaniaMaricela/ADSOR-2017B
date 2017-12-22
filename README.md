# Escuela Politécnica Nacional

### Materia : `Administración de Sistemas Operativos y Redes`

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Escudo_de_la_Escuela_Polit%C3%A9cnica_Nacional.png"  height="200">
</p>

### Tema : `Manuales de Prácticas de Laboratorio` 
### Fecha : `2017-12-21`
### Estudiante : `Tania Maricela Guamushig Aimacaña`
### Profesor : `Iván Carrera`
### Corresponde a : `I Bimestre`

<a name="cabecera"></a>
## Índice de contenidos


- <a href="#virtualizacion">Virtualización</a>
- <a href="#dhcp">DHCP</a>
- <a href="#ftp">FTP</a>
- <a href="#mysql">MYSQL</a>
- <a href="#dns">DNS</a>
- <a href="#http">WEB - HTTP</a>
- <a href="#smtp">SMTP</a>

<a name="virtualizacion"></a>
## Virtualización
`OBJETIVOS`

- Conocer el funcionamiento de las máquinas virtuales de VMware Y virtualbox
- Realizar configuraciones necesarias para que las máquinas virtuales naveguen en el internet por medio de la máquina física, tanto para VMware como virtualbox.
- Realizar la parametrización de memoria virtual, espacio físico y procesador.
- Configurar la red para la máquina física y para las máquinas virtuales de manera que se pueda realizar ping entre ellas.
- Importar, exportar, clonar y snapshots para una máquina virtual tanto en vmware como en virtual box.
- Compartir carpetas entre máquinas virtuales, tanto en vmware como virtualbox.

`Virtualizacion`
<p>Virtualizar aporta ventajas y posibilidades únicas en la actualidad. Permite reducir costes en prácticamente todos los campos de actuación de la administración de sistemas; desde la instalación y configuración de equipos hasta los procesos de copias de seguridad, monitorización, gestión y administración de la infraestructura. Disminuye el número de servidores físicos necesarios y el porcentaje de desuso de los recursos de los que disponen, aumentando su eficiencia energética. 
También nos brinda la posibilidad de centralizar y automatizar procesos cuya administración normalmente consume mucho tiempo, pudiendo aprovisionar y migrar máquinas virtuales de una manera rápida y fiable, manteniendo alta la calidad del servicio y bajo el tiempo de respuesta ante una caída del mismo.</p>

<p>Las técnicas de virtualización unidas a otras herramientas disponibles pueden garantizar requerimientos que de otro modo serían difíciles de cubrir, al menos de manera tan sencilla, como son por ejemplo alta disponibilidad y alto rendimiento. En nuestro caso serán aplicadas a servicios de telefonía IP, por lo que es también de vital importancia revisar el estado actual de este tipo de servicios y más concretamente de Asterisk. Asterisk, desde su aparición, ha revolucionado por completo el concepto de servicios de telefonía IP debido a sus ventajosas prestaciones proporcionando características telefónicas que lo dotan de un gran potencial, como escalabilidad, portabilidad y flexibilidad, o su integración con Internet y redes locales.</p>

<p align="center">
<img src="http://www.pcactual.com/medio/2010/07/07/virtualizacion3_618x352.jpg">
</p>

(Documento completo en: (https://raw.githubusercontent.com/TaniaMaricela/ADSOR-2017B/master/Manual%201%20-%20Virtualizaci%C3%B3n.docx))

<a href="#cabecera">A la cabecera</a>

<a name="dhcp"></a>
## DHCP
`OBJETIVOS`

- Conocer el funcionamiento de DHCP cliente y servidor
-	Configurar DHCP en WINDOWS SERVER Y LINUX.
-	Realizar la configuración de DHCP en IPv4 para una red conmutada.
-	Definir rangos de funcionamiento de DHCP 
-	Capturar los logs del servidor en cada plataforma: Windows Server y Linux en cada instanciación de asignación de direcciones IP


`DHCP`
<p>El protocolo DHCP (Dinamic Host Configuration Protocol) proporciona un mecanismo para intercambiar información de configuración a los distintos clientes en una red TCP/IP. DHCP tiene dos componentes principales: un protocolo para entregar los datos de configuración a los distintos clientes desde un servidor DHCP, y un mecanismo para almacenar las direcciones de red servidas a los distintos clientes.</p>

<p>El protocolo DHCP sirve principalmente para distribuir direcciones IP en una red, pero desde sus inicios se diseñó como un complemento del protocolo BOOTP (Protocolo Bootstrap), que se utiliza, por ejemplo, cuando se instala un equipo a través de una red (BOOTP se usa junto con un servidor TFTP donde el cliente encontrará los archivos que se cargarán y copiarán en el disco duro). Un servidor DHCP puede devolver parámetros BOOTP o la configuración específica a un determinado host.</p>

<p align="center">
<img src="https://tecadmin.net/wp-content/uploads/2013/03/dhcp.png">
</p>

(Documento completo en: (https://raw.githubusercontent.com/TaniaMaricela/ADSOR-2017B/master/Manual%202%20-%20DHCP.docx))

<a href="#cabecera">A la cabecera</a>

<a name="ftp"></a>
## FTP
`OBJETIVOS`

- Conocer el funcionamiento de FTP cliente y servidor
- Configurar FTP en WINDOWS SERVER Y LINUX.
- Realizar la configuración de FTP en IPv4 
-	Definir rangos de funcionamiento de FTP

`FTP`
<p>El FTP es uno de los sistemas de almacenamiento y distribución de archivos más populares de Internet. La sencillez con la que se realizan el montaje y el acceso, permiten a cualquier usuario acceder a archivos y carpetas remotas, casi como si se tratara de su propio disco duro.</p>

<p>Para resolver estos problemas, se desarrolló el protocolo de transferencia de archivos (File Transfer Protocol). FTP es un programa muy básico para la transferencia de archivos entre ordenadores, pero a la vez es muy sencillo y fácil de usar, permitiendo ser utilizado de forma interactiva por un usuario, o bien, desde cualquier otra aplicación.</p>

<p>En FTP, un cliente de FTP establece una conexión con un servidor de FTP a través de lo que se conoce como conexión de control, siendo esta conexión de control una sencilla sesión de NVT1. El cliente envía los comandos al servidor a través de la conexión de control y el servidor envía respuestas al cliente a través de la misma.</p>

<p align="center">
<img src="http://www.ftpclientserversites.com/wp-content/uploads/2016/08/FTP-Setup.png">
</p>

(Documento completo en: (https://raw.githubusercontent.com/TaniaMaricela/ADSOR-2017B/master/Manual%203%20-%20FTP.docx))

<a href="#cabecera">A la cabecera</a>
<a name="mysql"></a>
## MYSQL
`OBJETIVOS`

- Describir la configuración Básica del servicio MySQL.
- Aplicar los conocimientos de virtualización en herramientas de virtualización correspondiente.
- Probar con el diseño cliente servidor el funcionamiento del servicio y su conexión.

`MYSQL`
<p>MySQL es un sistema de gestión de bases de datos de código abierto, comúnmente instalado como parte de la popular pila LEMP (Linux, Nginx, MySQL / MariaDB, PHP / Python / Perl). Utiliza una base de datos relacional y SQL (Structured Query Language) para administrar sus datos.</p>

<p>CentOS 7 prefiere MariaDB, una bifurcación de MySQL administrada por los desarrolladores originales de MySQL y diseñada como un reemplazo para MySQL. Si ejecuta yum install mysqlen CentOS 7, es MariaDB que está instalado en lugar de MySQL. Si te estás preguntando sobre MySQL vs. MariaDB, MariaDB generalmente funcionará perfectamente en lugar de MySQL , así que a menos que tengas un caso de uso específico para MySQL, mira la guía Cómo instalar MariaDB en Centos 7 .</p>

<p align="center">
<img src="https://mariadb.com/sites/default/files/2017-08/MariaDB-TX-high-resolution.png">
</p>

(Mayor Información en: (https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-centos-7))

<a href="#cabecera">A la cabecera</a>
<a name="dns"></a>
## DNS
`OBJETIVOS`

- Conocer el funcionamiento básico de DNS.
-	Instalar paquetes básicos en un servidor con Linux.
-	Configuraciones de Archivos para su fucnionamiento.
-	Probar su funcionamiento con diversas pruebas de usuario.

`DNS`
<p>Los archivos de configuración DNS son almacenados en el directorio /etc/bind. El archivo de configuración primario es /etc/bind/named.conf.

la linea include especifica el nombre de archivo que contiene las opciones DNS. La linea directory en el archivo /etc/bind/named.conf.options le dice a DNS donde buscar archivos. Todos los archivos que BIND usa seran relativos a este directorio.</p>

<p>El archivo de nombre /etc/bind/db.root describe los servidores de nombres raíz para todo el mundo. Los servidores cambian con el tiempo, por lo que /etc/bind/db.root debe actualizarse de vez en cuando. Esto se hace habitualmente mediante actualizaciones del paquete bind9. La sección zone define un servidor maestro, que es almacenado en el archivo indicado por la opción file.</p>

<p>Es posible configurar el mismo servidor para que actúe como servidor de caché de nombres, maestro primario y maestro secundario. Un servidor puede ser el Start of Authority (SOA) de una zona, al tiempo que proporciona servicio secundario para otra zona. Y todo al mismo tiempo que proporciona servicios de caché para equipos de la LAN local.</p>

<p align="center">
<img src="https://moodle2016-17.ua.es/moodle/pluginfile.php/62199/mod_resource/content/6/navegadores/images/pic006.jpg">
</p>

(Configuración Oficial en: (https://help.ubuntu.com/lts/serverguide/dns-configuration.html))

<a href="#cabecera">A la cabecera</a>
<a name="http"></a>
## WEB - HTTP
`OBJETIVOS`

- Realizar una investigación bibliográfica sobre HTTP, con su definición y características principales.
-	Instalar un servidor apache para Linux y configurar, crear un sitio web con página principal y probar desde maquina clientes con diferente IP. El sitio creado deber tener 3 paginas linkeadas 
-	Probar la navegación al sitio definido navegando en las distintas páginas y retrocediendo
-	Instalar un servidor IIS para Windows y configurar, crear un sitio web con página principal y probar desde maquina clientes con diferente IP. Utilizando las paginas ASP, ASPX.
-	Probar la navegación por dirección IP desde otra máquina virtual o física apuntando a la dirección IP y el nombre del sitio virtual.

`HTTP`
<p>HTTP son las siglas en inglés de HiperText Transfer Protocol (en español, protocolo de transferencia de hipertexto). Es un protocolo de red (en informática un protocolo se puede definir como un conjunto de reglas a seguir) para publicar páginas de web o HTML. HTTP es la base sobre la cual está fundamentado Internet, o la WWW.</p>

<p>HTTP fue desarrollado por el World Wide Web Consortium y la Internet EngineeringTaskForce, colaboración que culminó en 1999 con la publicación de una serie de RFC, el más importante de ellos es el RFC 2616 que especifica la versión 1.1. HTTP define la sintaxis y la semántica que utilizan los elementos de software de la arquitectura web (clientes, servidores,proxies) para comunicarse.</p>

<p align="center">
<img src="https://moodle2016-17.ua.es/moodle/pluginfile.php/62199/mod_resource/content/6/navegadores/images/pic004.jpg">
</p>

(Documento completo en: (https://raw.githubusercontent.com/TaniaMaricela/ADSOR-2017B/master/Manual%206%20-%20HTTP.docx))

<a href="#cabecera">A la cabecera</a>
<a name="smtp"></a>
## SMTP
`OBJETIVOS`

- Instalar un servidor de correo electrónico no webmail (en plataforma Windows y otro en plataforma Linux)
-	Configurar el dominio del servidor: adsor2017AGxx (xx: número de grupo)
-	Crear tres usuarios para el servicio (usr1, usr2, usr3) nombre de cada estudiante del grupo
-	Configurar un software de cliente de correo para usr1, con el mismo software configurar el usr2.
-	Probar envío de correo de usr1 para usr2 y viceversa.
-	Probar la opción de llegada de correo y lectura del mensaje cuando envía mensaje de usr1 a usr2.
-	Probar un envío de correo desde usr3 a usr2, pero usr3 desde línea de comandos.
-	Configurar un servidor de correo webmail con el dominio adsor2017AWg3, generar 2 usuarios (nombres de los estudiantes del grupo) y probar envío y recepción de mensajes. El dominio de este servidor debe ser: adsor2017AG3
-	La prueba del cliente debe ser a través de un navegador web.
-	En cada caso capturar la configuración de cliente y del servidor.
-	Configurar un cliente con PoP3 y otro con IMAP4.


`SMTP`
<p>VEl correo electrónico de Internet se implementó originalmente como una función del protocolo FTP. En 1980 Suzanne Sluizer y Jon Postel realizaron trabajos con un protocolo que posteriormente se denominaría SMTP ("Simple Mail Transfer Protocol"). Hoy en día se sigue utilizando este protocolo, con los avances lógicos que requiere el tipo de transferencia actual.</p>

<p>El protocolo SMTP fue desarrollado pensando en que los sistemas que intercambiarían mensajes, eran grandes computadores, de tiempo compartido y multiusuario conectados permanentemente a la red Internet. Sin embargo, con la aparición de los computadores personales, que tienen una conectividad ocasional, se hizo necesaria una solución para que el correo llegase a estos equipos. Para solventar esta limitación, en 1984 surge POP.</p>

<p>Este protocolo, en su especificación inicial, solo permite funciones básicas como recuperar todos los mensajes, mantenerlos en el servidor y borrarlos. En sucesivas versiones del protocolo (POP2 y POP3) se han ampliado las funciones, permitiendo una mejor gestión del correo.</p>

<p>Por lo tanto, podemos discriminar dos tipos de agentes que están involucrados en la transferencia de correo, MUA y MTA: </p>

- Agente de usuario (MUA), interfaz para leer y escribir los mensajes. (POP).
- Agente de transporte (MTA o estafeta), encargado del transporte de los mensajes. (SMTP).

<p align="center">
<img src="https://networkcata.files.wordpress.com/2010/02/16.jpg">
</p>

(Documento completo en: (https://raw.githubusercontent.com/TaniaMaricela/ADSOR-2017B/master/Manual%207%20-%20SMTP.docx))

<a href="#cabecera">A la cabecera</a>
