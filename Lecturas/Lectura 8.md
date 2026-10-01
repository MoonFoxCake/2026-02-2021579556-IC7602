Explique el funcionamiento de ICMP.
Internet Control Message Protocol

Este se envia usando el header basico de IP, el primer octeto es para el tipo de ICMP
Este lo que hace es que se tiene asi:
![[Pasted image 20260918115200.png]]
Entonces, el tipo del mensaje es el que define para que es entonces si en el tipo es 3 es porque no se puede llegar al destino el codigo son como subcategorias del destino, con 11 es de tiempo expirado, ya despues hay variaciones como este:

![[Pasted image 20260918144820.png]]

Este es tipo 5, de redireccion.

Comente las aplicaciones de este protocolo en las comunicaciones.

Se usa para dar mensajes sobre errores o informacion, entonces se usa para que las aplicaciones tengan algo de informacion sobre temas que suceden O cuando no se llega al destino, o no se tiene la capacidad de pasar el datagrama. En resumen es para dar informacion sobre detalles o temas en el ambiente de operacion