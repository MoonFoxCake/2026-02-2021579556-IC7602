¿Qué es un firewall? Comente los tipos existentes en capa 3/4

Es un control sobre que maquinas se pueden ver y que se puede ver hacia afuera, se podria describir un peaje entre la compu y el internet, limita por donde se puede pasar y quienes pueden pasar, bueno mejor que un peaje un punto de control

Filtrado de paquetes

¿Qué es un bastion host?

Es un host que usa packet filtering junto con otras tecnicas y comparado a otros sistemas es un host unico por lo cual es mas facil de configurar y mantener

¿En qué consiste un DMZ?

Es un area de buffer entre 2 routers(usualmente con el bastion host en medio) Entonces lo que se puede hacer es por ejemplo deshabilitar trafico que entre o trafico que salga.

¿Qué es un Proxy server?

Tipo de bastion host que usa software especializado que se hace pasar como una maquina interna para una externa el cual protege de trafico no deseado, el tema es que el proxy no es como una firewall, es un poco como una computadora

Explique los diferentes protocolos de VPN

Una VPN es una interconeccion de 2 o mas redes desconectadas

IPSec
Es la respuesta a la pregunta sobre por que TCP/IP no soportaba autenticacion y encriptacion este protocolo lo que es, es un protocolo de seguridad, tiene 2 modos, transporte y tunel, entonces con una llave comun entre los dispositivos pueden hacer la autenticacion y encriptacion de la informacion

ESP

ESP es un protocolo el cual encapsula el payload entonces funciona con otros tipos de seguridad/encriptacion simetrica y como dice el nombre encapsula el payload

AH

Protocolo el cual se encarga de la autenticacion, se usa solo o con otros protocolos este solo se preocupa de la informacion del header.

ISAMKP

Este protocolo es el procotolo por el cual se intercambian las llaves, en este da autenticacion a todos los que estan incluidos, maneja las politicas de seguridad, y maneja el intercambio de llaves.

ISO X.509

Da un nivel de acceso de control, se pone para manejar los certificados y autenticacion.

LDAP

Es muy similar al X.509, se usa para dar autenticacion y proveer manejo de certificados

Radius

Este sistema es para autenticar dentro de organizaciones.

PPTP

Servicio que va por encima de la IP, paraa comunicaciones seguras entre host y host.
