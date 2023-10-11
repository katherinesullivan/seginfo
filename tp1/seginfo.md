# Ejercicio 1: Diferencia entre datos e información

- Datos: hechos, eventos, transacciones, etc., que han sido registrados. Es la entrada sin procesar de la cual se produce la información. No hay organización en ella. 

- Información:  datos que han sido procesados y comunicados de tal manera que pueden ser entendidos e interpretados por el receptor. Poseen valor, contexto y sentido. Es algo que se deriva de los datos o metadatos o características de los mismos al ser analizados en conjunto.

Uno generalmente quiere proteger la información, eso probablemente implique también la protección de los datos, además de otras cosas.

# Ejericcio 2: e-mails restringidos en empresas

Las empresas usualmente restringen a sus empleados el uso de e-mail para fines laborales, pero permiten un mínimo uso para razones personales

1. Cómo podría una empresa detectar un uso excesivo de e-mails personales, sin tener que leerlos?

Con un firewall, contando la cantidad de mails personales (verificando remitentes para ver si son personales)

2. Intuitivamente, parece razonable evitar TODO uso personal de e-mail. Explique por qué la mayoría de las empresas no hacen esto.

Una razon podria ser para no inteferir con comunicación que sirva al progreso de la empresa, mantener la usabilidad de las computadoras, no hacerle perder el tiempo a los empleados buscando técnicas alternativas para comunicación y obtención de información.

# Ejercicio 3: cómo las políticas de seg afectan comercialmente

- restricciones en mails podrian trabar una comunicación mas fluida con clientes o entre empleados

- restringiendo sitios de internet, podrian dificultarle el acceso a informacion importante a los empleados

- restrngiendo copiar y pegar en entornos remotos pueden llevar a pérdida de tiempo al tener que reescribir cosas

- podrían restringir el acceso a aplicaciones que harían el trabajo más fácil

# Ejercicio 4: dif entre amenazas internas y externas

- Amenazas externas: Ocurre cuando una entidad no autorizada fuera del dominio de seguridad tiene el potencial de dañar un sistema de información a través de la destrucción, divulgación, modificación de datos y/o la denegación de servicio. Una amenaza externa se refiere al riesgo de que una persona externa o ajena a la organización intente explotar las vulnerabilidades de un sistema para obtener acceso no autorizado a la red objetivo.

Malware, phishing, ataques de denegación de servicio o ransomware son solo algunos de los métodos que los ciberdelincuentes utilizan para tratar de obtener acceso a un sistema. Una vez lo consiguen pueden permanecer dentro durante meses sin ser detectados.

- Amenazas internas: as amenazas internas son las que tienen origen dentro de la propia organización. Son producidas por usuarios con acceso legítimo a los activos de la empresa, por ejemplo, empleados actuales o antiguos, colaboradores externos, proveedores o socios comerciales. Las amenazas internas son muy variadas en cuanto a conocimiento, motivación, intención y nivel de acceso.

Es importante diferenciar entre insiders y amenazas internas. Un insider es una persona que tiene un gran conocimiento de una empresa porque trabaja o trabajó en ella, y que, por su situación actual en relación con la empresa, busca resarcimiento o venganza. Esta persona puede realizar acciones maliciosas como el cambio de credenciales importantes, un uso inadecuado de dispositivos, etc.

Otro ejemplo de amenaza interna puede ser una entidad que tiene algún vínculo con la organización, por ejemplo, un empleado que no pertenece a la empresa pero que tiene acceso a la misma por algún motivo, un empleado de una subcontrata, personal de mantenimiento, etc.; esa persona podría ejecutar acciones que perjudicasen a la empresa, como introducir malware dentro de la red o cambiar credenciales.

La motivación de los ataques, tanto de empleados descontentos como de amenazas internas, puede ser económica, de espionaje industrial, venganza, distracción para realizar otras actividades maliciosas o desconocimiento (fallo involuntario).

Cual es la importancia relativa de las amenazas internas?

Tiene mas fortaleza una amenaza interna al tener un camino más allanado, al ser necesario el confiarle información a los internos.

Para los equipos de seguridad no es fácil detectar amenazas internas, ya que las medidas de seguridad técnicas, como firewalls o antivirus, suelen estar centradas en amenazas externas y no siempre son capaces de identificar las amenazas que proceden de dentro de la organización, especialmente porque muchas se cuelan a través de ataques de ingeniería social que consiguen engañar a los empleados para que revelen información confidencial o realicen acciones que comprometan su seguridad. Por eso, para identificar y esquivar esta amenaza, es fundamental la formación y concienciación de los empleados en materia de ciberseguridad.

Es importante restringir el acceso a los empleados a lo mínimo indispensable para evitar amenazas que podrían ser más graves.

Fue adapatada a medida que la tecnología fue progresando?

Sí


# Ejercicio 5: qué medidas de seg podrían afectar estas cualidades

- Performance: el uso de conexiones remotas o vpns o muchas verificaciones/consultas ralentizan el uso del sistema. 

- Usabilidad: no permitir tener dos archivos abiertos con distinto nivel de seguridad hace que se deban cerrar lo que restringe la usabilidad

- Mantenibilidad: agregando código que verifique condiciones de seguridad, como firewalls, resulta en algo nuevo para tener en cuenta sobre la mantenibilidad del código y los distintos softwares usados necesitan estar siempre al día para evitar vulnerabilidades.

- Reusabilidad: la arquitectura con mucha seguridad se puede volver compleja, el agregado de requisistos de seguridad específicos, el peligro que implica tener el mismo código en dos sistemas, en seguridad se puede llegar a necesitar dependencias de terceros

- Otras cualidades: flexibilidad, portabilidad y testeabilidad

https://www.geeksforgeeks.org/measuring-software-quality-using-quality-metrics/

# Ejecicio 6: clasificación violación de confidencialidad, de integridad, de disponibilidad, o una combinación de ellas:

* v. de confidencialidad: acceden a datos usuarios que no deberían. Ej: fugas de datos sobre decisiones empresariales

* v. de integridad: datos corrompidos o alterados. Ej: manipulación de datos financieros

* v. de disponibilidad: datos no disponibles cuando se los necesita. Ej: ataque DoS

1. Juan se copia de la tarea de María: confidencialidad

2. Pablo le rompe el sistema a Jimena: disponibilidad/integridad

3. Carolina cambia el monto del cheque de Diego de $100 a $1000: integridad

4. Mirta falsifica la firma de Rodrigo en una escritura: integridad

5. Esteban registra el nombre de dominio “AddisonWesley.com” y se rehusa permitir a la editorial comprar o usar ese nombre de dominio: disponibilidad

6. Manuel obtiene el número de tarjeta de crédito de Pedro y logra que la empresa cancele la tarjeta y la reemplace por otra tarjeta con un número diferente: integridad/confidencialidad menos

# Ejercicio 7: ejemplo de una situación en la cual un compromiso de confidencialidad conduce a un compromiso de integridad

Proteger datos como tarjetas de crédito en una base de datos.

Proteger datos como votos en una elección.

?

# Ejercicio 8: ejemplos problemas safety - security

security: prevención de ataques

safety: ejecución correcta

- Problema de security que también es de safety: software para vehículos automáticos. Si alguien puede tomar control del vehículo (efectuando así un ataque de security) no se cumplen los requerimientos expresados del sistema (safety) (parece que está más relacionado con sistemas críticos)

- Problema de security que NO es de safety: filtrado de datos de una red social (parece que está más relacionado con sistemas no críticos) 

- Problema de safety que NO es de security: un requerimiento mal codeado. Un if que iba al revés. problema de hardware?

# Ejercicio 9: seguridad a través de oscuridad (security by obscurity)

Dé un ejemplo de alguna situación en que el ocultamiento de información no agrega apreciable seguridad a un sistema. Luego dé un ejemplo en que sí.

Ocultamiento no agrega seguridad: contraseñas débiles, aunque nunca se divulgen pueden ser adivinadas.

Ocultamiento agrega seguridad: usar puertos personalizados y mantenidos cuáles ocultos para evitar ataques que se hacen a los puertos conocidos.

# Ejericicio 10: flujo de información médica

En un sistema de información médica que controla el acceso a los registros de los pacientes
y las recetas:

* Los doctores pueden leer y escribir registros de pacientes y recetas.

* Las enfermeras pueden leer y escribir recetas pero no pueden saber nada sobre los registros.

¿Cómo puede capturar esta política en un modelo de látices que prevenga flujo de información de
los registros a las recetas?

Tiene que ser sobre procesos? Entenderiamos como procesos a doctores y enfermeras? y los objetos que onda
O es sobre objetos por como esta redactada la consigna?

    Registros Recetas Doctores Enfermeras

    Doctores
       +
       |
       |
    Enfermeras

# Ejercicio 11: revelación, alteración, engaño y usurpación

1- Busque y discuta sobre la definición de: disclosure (revelación), disruption (alteración), deception (engaño), usurpation (usurpación).

https://people.cs.rutgers.edu/~pxk/419/notes/intro.html 

A threat is how we refer to the potential adversary (person or thing) who has the potential to attack the system. A threat may attack. The key point is that a threat refers to the possibility of an attack rather than the attack itself. An attacker was a threat. A threat will not necessarily attack.

Threats fall into four broad categories:

* Disclosure: Unauthorized access to data, which covers exposure, interception, interference, and intrusion. This includes stealing data, improperly making data available to others, or snooping on the flow of data.

* Deception: Accepting false data as true. This includes masquerading, which is posing as an authorized entity; substitution or insertion of includes the injection of false data or modification of existing data; repudiation, where someone falsely denies receiving or originating data.

* Disruption: Some change that interrupts or prevents the correct operation of the system. This can include maliciously changing the logic of a program, a human error that disables a system, an electrical outage, or a failure in the system due to a bug. It can also refer to any obstruction that hinders the functioning of the system.

* Usurpation: Unauthorized control of some part of a system. This includes theft of service or theft of data as well as any misuse of the system such as tampering or actions that result in the violation of system privileges.


2- Muestre que los tres servicios de seguridad: confidencialidad, integridad y disponibilidad; son suficientes para lidiar con esas cuatro amenazas

Disclosure - Confidenciality

Deception and Disruption - Integrity

Usurpation - Availability

Integrity is ensuring that data and all system resources are trustworthy por eso tmb implica disruption

# Ejercicio 12: AppArmor en Ubuntu - MAC

Investigue sobre las características de AppArmor en Ubuntu para proveer seguridad del tipo MAC.

Es un módulo de seguridad del kernel Linux que permite al administrador del sistema restringir las capacidades de un programa. Para definir las restricciones asocia a cada programa un perfil de seguridad. Este perfil puede ser creado manual o automáticamente. Complementa el modelo tradicional de control de acceso discrecional de Unix (DAC) proporcionando el control de acceso obligatorio (MAC). Está implementado utilizando el framework del núcleo Linux Security Modules. 

AppArmor is a Mandatory Access Control (MAC) system which is a kernel (LSM) enhancement to confine programs to a limited set of resources. AppArmor's security model is to **bind access control attributes to programs rather than to users**. AppArmor confinement is provided via profiles loaded into the kernel, typically on boot. AppArmor profiles can be in one of two modes: enforcement and complain. Profiles loaded in enforcement mode will result in enforcement of the policy defined in the profile as well as reporting policy violation attempts (either via syslog or auditd). Profiles in complain mode will not enforce policy but instead report policy violation attempts.

AppArmor differs from some other MAC systems on Linux: it is path-based, it allows mixing of enforcement and complain mode profiles, it uses include files to ease development, and it has a far lower barrier to entry than other popular MAC systems. 

Example at https://wiki.ubuntu.com/AppArmor

# Ejericicio 13: modelo Biba para integridad
a) Lea sobre el modelo de Biba para integridad.

The Biba Model or Biba Integrity Model developed by Kenneth J. Biba in 1975,[1] is a formal state transition system of computer security policy describing a set of access control rules designed to ensure data integrity. Data and subjects are grouped into ordered levels of integrity. The model is designed so that subjects may not corrupt data in a level ranked higher than the subject, or be corrupted by data from a lower level than the subject.

In general the model was developed to address integrity as the core principle, which is the direct inverse of the Bell–LaPadula model which focuses on confidentiality.

b) ¿Es posible usar los modelos de Bell-LaPadula y de Biba para modelar confidencialidad e integridad simultáneamente? ¿Se pueden usar las mismas categorĺas de seguridad para ambas políticas?

Si tienen las mismas categorias de seguridad: The Strong Star Property is an alternative to the *-Property, in which subjects may write to objects with only a matching security level. Thus, the write-up operation permitted in the usual *-Property is not present, only a write-to-same operation. The Strong Star Property is usually discussed in the context of multilevel database management systems and is motivated by integrity concerns.[8] This Strong Star Property was anticipated in the Biba model where it was shown that strong integrity in combination with the Bell–LaPadula model resulted in reading and writing at a single level. 

Si tienen distintas categorias de seguridad podria suceder que no sea tan restrictivo.

De hecho, si las inviero a las categorías estoy yendo para el mismo lado.

This security model is directed toward data integrity (rather than confidentiality) and is characterized by the phrase: "read up, write down". This is in contrast to the Bell-LaPadula model which is characterized by the phrase "read down, write up".

En Bell-LaPadula tenemos que todos los objetos abiertos en mode de lectura tienen que tener una clase dominada por la de cualquiera de los objetos abiertos en modo escritura.

In the Biba model, users can only **create content at or below** their own **integrity level** (a monk may write a prayer book that can be read by commoners, but not one to be read by a high priest). Conversely, users can only **view content** at or above their own **integrity level** (a monk may read a book written by the high priest, but may not read a pamphlet written by a lowly commoner). Another analogy to consider is that of the military chain of command. A General may write orders to a Colonel, who can issue these orders to a Major. In this fashion, the General's original orders are kept intact and the mission of the military is protected (thus, "read up" integrity). Conversely, a Private can never issue orders to his Sergeant, who may never issue orders to a Lieutenant, also protecting the integrity of the mission ("write down").

The Biba model defines a set of security rules, the first two of which are similar to the Bell–LaPadula model. These first two rules are the reverse of the Bell–LaPadula rules:

The Simple Integrity Property states that a subject at a given level of integrity must not read data at a lower integrity level (no read down).
The * (star) Integrity Property states that a subject at a given level of integrity must not write to data at a higher level of integrity (no write up).[3]
Invocation Property states that a process from below cannot request higher access; only with subjects at an equal or lower level.

# Ejercicio 14: Bell-LaPadula en Z

a) Codifique en Z el modelo de Bell-LaPadula, definiendo operaciones de lectura y escritura con
condiciones de disparo de acuerdo a niveles de seguridad.

b) Pruebe usando Z/EVES que las operaciones preservan las propiedades definidas del modelo
(security condition y *-property).

# Ejercicio 15: permisos en Haskell

a) Implemente en Haskell una función:

```
    grant :: User -> File -> Access -> Bool
    grant user file rm = HaveSecurityClasses(user) && HaveSecurityClass(file) && (not isOpened(file)) && secClass(user) dominates secClass(file) && openedWriteObjects() dominates secClass(file) && addOpenedReadObj(file)
    grant user file wm = HaveSecurityClasses(user) && HaveSecurityClass(file) && (not isOpened(file)) && secClass(user) == secClass(file) && secClass(file) dominates openedWriteObjects() && addOpenedWriteObj(file)

```

Que, dado un usuario (sujeto), un archivo (objeto) y un tipo de acceso (lectura, escritura), devuelva un booleano indicando si se puede llevar adelante el acceso, siguiendo la política del modelo Bell-LaPadula.

Obs: Puede agregar parámetro(s) adicional(es) con la información necesaria para poder devolver lo que corresponda.

b) Si no lo hizo en el inciso anterior, modifique la función de manera que mantenga el estado de
archivos accedidos (abiertos), para tener en cuenta también la propiedad *.

# Ejercicio 16: ACL
a) Investigue el sistema de permisos clásico de Linux.

https://www.redhat.com/sysadmin/linux-file-permissions-explained

    $ ls -l
        drwxr-xr-x. 4 root root    68 Jun 13 20:25 tuned
        -rw-r--r--. 1 root root  4017 Feb 24  2022 vimrc

    File type: -
    Permission settings: rw-r--r--
    Extended attributes: dot (.)
    User owner: root
    Group owner: root

How to read permissions?

rw-r--r–

This string is actually an expression of three different sets of permissions:

    rw-
    r--
    r--

The first set of permissions applies to the owner of the file. The second set of permissions applies to the user group that owns the file. The third set of permissions is generally referred to as "others." All Linux files belong to an owner and a group.

When permissions and users are represented by letters, that is called symbolic mode. For users, u stands for user owner, g for group owner, and o for others. For permissions, r stands for read, w for write, and x for execute.

Como chequea?

When the system is looking at a file's permissions to determine what information to provide you when you interact with a file, it runs through a series of checks:

1. It first checks to see whether you are the user that owns the file. If so, then you are granted the user owner's permissions, and no further checks will be completed.

2. If you are not the user that owns the file, next your group membership is validated to see whether you belong to the group that matches the group owner of the file. If so, then you're covered under the group owner field of permissions, and no further checks will be made.

3. "Others" permissions are applied when the account interacting with the file is neither the user owner nor in the group that owns the files. Or, to put it another way, the three fields are mutually exclusive: You can not be covered under more than one of the fields of permission settings on a file.

O sea, se mantiene un mapeo por archivos de quienes tienen permiso a ellos.

Leer sobre octal values.


b) Instale y configure alguna ACL. Discuta sus descubrimientos.

# Ejercicio 17: permisos en /tmp
Explicar qué hace el bit t en los permisos de la carpeta /tmp.

When running the command ls -ld /tmp, the output would be:

    drwxrwxrwt 30 root root 20480 Mar 11 14:17 /tmp


**So what is the sticky bit?**

A sticky bit is a permission bit that is set on a directory that allows only the owner of the file within that directory, the owner of the directory or the root user to delete or rename the file. No other user has the needed privileges to delete the file created by some other user.

This is a security measure to avoid deletion of critical folders and their content (sub-directories and files), though other users have full permissions.

**Why does /tmp have the t sticky bit?**

The /tmp directory can be used by different Linux users to create temporary files. Now, what if a user deletes/renames a file created by some other user in this directory?

Well, to avoid these kind of issues, the concept of sticky bit is used. So for that a 777 is given but preserving the sticky bit is not a bad idea.

**How can I set up the sticky bit for a directory?**

I'll set a sticky bit on a directory called test on my Desktop.

Using symbolic notation (t represents the sticky bit):

chmod o+t ~/Desktop/test

or

chmod +t ~/Desktop/test

Using octal notation (1 in the first position represents the sticky bit):

chmod 1757 ~/Desktop/test

Now let us test the results:

ls -li ~/Desktop/test

1551793 drwxrwxrwt 45 hadi hadi 20485 Mar 11 14:35 ~/Desktop/test

To delete/Remove a sticky bit

chmod o-t ~/Desktop/test

Now let us test the results:

ls -li ~/Desktop/test

1551793 drwxrwxrwx 45 hadi hadi 20485 Mar 11 14:35 ~/Desktop/test

Source: “What is a sticky Bit and how to set it in Linux?” at The Linux Juggernaut


# Ejercicio 18: 
Cuando no hay ACLs disponibles, una alternativa para dar determinado acceso a un grupo de usuarios es crear un grupo ad hoc para ese archivo, y cambiar con chgrp al grupo creado, dándole los permisos buscados al grupo. 

Explicar qué inconvenientes trae esto, y dar un caso donde, aunque se usen grupos ad hoc, no alcance el sistema de permisos de Linux para especificar todos los permisos que se desean dar.

# Ejericicio 21:

Determinar si en los siguientes programas hay flujo indebido de información:

    -- Prog 1
    magic = readL();
    if (magic == 0xdeadbeef)
    writeH("hey");
    else
    writeH("ho");

Tenemos un archivo low abierto pero solo en modo lectura y solo escribimos en un archivo high. No hay flujo indebido.

    -- Prog 2
    x = readH();
    writeL("Loading...");
    writeH(x);

Tenemos un archivo high abierto y escribimos en un archivo low. Hay posible flujo indebido. (Puede haber un timing channel. Me fijo cuanto tarda en aparecer Loading en el archivo low. Pero si no medio que SME no podria ni funcionar. Podria ser que no ejecute tmp el readH). Preguntar a maxi como iria esto en SME (en que estado queda la varia x en el proceso L, se rompe el prog? para 22 je). El fork lo hace cuando empieza a ejecutar el read de H o cdo termina el read

    -- Prog 3
    x = readH();
    writeL("Loading");
    while (x-- > 100)
    writeL(".");
    writeH(x);

Tenemos un archivo high abierto y escribimos en un archivo low. Escribimos en el archivo low dependiendo de lo que hay en el archivo high. Hay flujo indebido.

    -- Prog 4
    user = readL();
    pass = readL();
    if (user == "root" && pass == "1234")
    msg = "Bienvenido";
    else
    msg = "Usuario/password incorrecto";
    writeL(msg);

Creeria que no. No hay algo high en juego?

    -- Prog 5
    db_pass = readPassFromDBH();
    db_user = readUserFromDBH();
    user = readL();
    pass = readL();
    if (user == db_user && pass == db_pass)
    msg = "Bienvenido";
    else
    msg = "Usuario/password incorrecto";
    writeL(msg);

Tenemos que db_pass y db_user son archivos high y tenemos un archivo low abierto en el que escribimos también. Escribimos condicionadamente del archivo high. Hay flujo indebido.

# Ejercicio 23:

Step 1
l = h

Step 2
if (h) {l=true;} else {l=false;}
https://ifc-challenge.appspot.com/steps/codfish#

Step 3
hatch = h;
l = declassify(hatch);
https://ifc-challenge.appspot.com/steps/joystick#

Step 4
let (lou = h) in l = lou;
https://ifc-challenge.appspot.com/steps/graphite#

Step 5
try {
  l = true;
  if (h) {throw;} else {skip;}
  l = false;
}
catch skip;
https://ifc-challenge.appspot.com/steps/allergy#

Step 6
https://ifc-challenge.appspot.com/steps/collect

step 1 flujo explicito.
step 2 flujo implicito por la estructura.