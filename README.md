# Date 07/10/2026 Ataque de denegacion de servicio

Ataques a Servidores, routers e impresoras.
<span style="color: red;">Ataque masivo:</span>
Mensaje a un equipo promt, XP.

Que se hace
    Vulnerabilidad
            Soluccion

Ataques espía, bucle con pin hacia una máquina o varias con un .but
IPS: Intentos recurrentes.

# Date 07/10/2026 Ejercicio del día 

Version a descargar: Virtual box. 6 5 1
<br> Muestra todos los servicios de la maquina: Net start
<br> Sistema operativo - XP Profesional

# Date 08/10/2026

Lo primero para certificar una empresa se necesita una “metodología”. Vale cualquier metodología pero es obligatorio una, aunque sea inventada.

Octava metodología, muy usada en Sudamérica
Magerit metodología muy usada en Europa.

Ejercicio práctico de encriptación.	
Practica: Informes, para Windows, un Linux, un xp y un servidor.
Modelo de ataques.

# Date 9/10/2026 Clases de contraseñas

Clientes de usuario <br>
Grupos especiales (windows) <br>
Políticas de contraseñas <br>
Conexión remota <br>

<strong> Segunda maquina en Windows </strong>
Ejercicios practico.
Una empresa, selección gestionada un SGSI la creación de dos cuentas de usuario 1 diurno, 2 tarde. Necesita además una tercera cuenta llamada técnico esta cuenta tendrá permisos de administración y debe poder conectarse por remoto a otras maquinas.
La contraseña en principio será de carácter local, ver diferentes con controlador de dominio. La conexión remota debe de ser con telnet o escritorio remoto.

<strong> Contraseña de Clase A </strong> <br>
Minúsculas
<strong> Contraseña de Clase B </strong> <br>
Minúsculas + Números
<strong> Contraseña de Clase C </strong> <br>
Minúsculas + Mayúsculas + Números

<br>

El usuario debe de cambiar la contraseña al iniciar la sesión <br>
Contraseña asignada obligatoria
La contraseña nunca caduca <br>
Escalada de privilegios, de menor a mayor <br>
1. Creación de un usuario en MiPC, desde la administración, herramientas administrativas <br>
2. Creación por comando, net user diurno <br>
Comando: net user nombre_de_usuario contraseña /add
-----
# Date 9/10/2026 Código de ética auditoria.

Se basan en 7 puntos, como conducta de Auditoria.
1.	Apoyar la implementación y el cumplimiento de los estándares, procedimientos, normas y controles de los sistemas informáticos y de la empresa.
2.	Ejecutar las tareas con objetividad, diligencia y rigo profesional. Basado en el estándar.
3.	Actuar en el interés de las partes, empleados y clientes, de un modo diligente y leal. Siempre y cuando no incurran en ISACA.
4.	Mantener la confidencialidad de la información que obtenga en el desarrollo de la auditoria salvo que queja exigida Motivada por la autoridad legal, esta no se puede usar en beneficio propio.


# Date 23/10/2026 Ejercicio continuación, más sistemas RAID (Marco técnico/practico) RAID 5

Proceso de inicio, de ejecución.
1)	Levantar el server_2003_dominio
2)	Levantar el server_2003_independiente
3)	Levantar el cliente WindowsXPPro2
La cuenta de administrador, no se usa nunca (Buenas prácticas). Se usará la de TECNICO.

Uniremos WindowsXPPro2, a nuestro dominio control017 (nos loguemos con TECNICO)

Una vez unido al dominio, escribimos un usuario creado, ejemplo Usuario RRHH y contraseña Clase123
Para cambiar la contraseña por cmd, rápidamente en el Server_2003_dominio
Net user: muestra todas las cuentas
Net user RRHH2 * : Cambia la contraseña del usuario RRHH2, escribimos la contraseña Clase1234
Realizar segmentación lógica, no por hardware, realizar un cambio de grupo. Pero se debe de realizar una segmentación lógica por hardware.
Pero tenemos un problema de latencia, por una red del centro que esta saturada, router “tonto” el router no limpia las tablas de conmutación y da conflictos de IP duplicadas.



