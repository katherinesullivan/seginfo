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

Investigue sobre las características de AppArmor en Ubuntu para proveer seguridad del tipo MAC




