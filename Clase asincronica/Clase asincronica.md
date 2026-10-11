
Código CV01.

1. Explica por qué es importante usar rangos de IP (CIDR) que no se solapen al conectar una VPC con una red local u otras VPC.
Esto sucede porque si se sobrelapan puede suceder que no se pueda establecer conexiones


2. Explica la diferencia entre enrutamiento estático y dinámico (BGP) en una conexión AWS Site-to-Site VPN, y qué ventaja da el dinámico.

Enrutamiento dinamico lo que sucede es que usa BGP peering para intercambiar informacion de ruteo, tambien se pueden especificar metricas, y politicas y prioridades de ruteo.


3. Explica qué es AWS Transit Gateway y qué problema resuelve frente a conectar cada VPC por separado.

Es un hub para conectar los VPC, el cual simplifica la tarea de conectarlas VPC por separado, tambien automatizando parte del proceso.


4. Explica qué es AWS Direct Connect, en qué se diferencia de una VPN por internet y cómo se puede proteger el tráfico si no está cifrado por defecto.

AWS Direct Connect es un servicio para conectar una red hacia una VPC.
Hay opciones para proteger las conexiones, como usar MAC Security, o usar tuneles VPN

5. Explica cómo funciona Site-to-Site VPN CloudHub y en qué situación conviene usarlo.

Site-to-Site VPN es un servicio VPN para conectar bases de datos o servicios a los recursos de AWS. Este es conveniente para varias oficinas o conexiones a internet existentes, y se ocupa una forma de conectividad facil y de poco costo para conectividad principal o de respaldo