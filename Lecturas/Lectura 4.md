
¿En qué consiste ARP?

ARP es un protocolo el cual pasa una IPv4 a MAC, es decir de una direcion logica de 32 bits a una fisica de 48 bits, todo esto para encontrar la direccion MAC de un dispositivo en una LAN

¿Cómo funciona ARP?

El ARP es un proceso complicado el cual lleva varios pasos

Primero, se sabe la IP de a quien se quiere llegar, por lo cual se pide el ARP, enviando su IP, la IP del destinatario y el MAC en puros 0, se pasa la informacion donde el MAC de quien lo envia es la direccion fuente, entonces todos reciben esos datos, pero quien responde es la maquina que se da cuenta que el mensaje es para ella entonces envia su ARP de vuelta, por lo cual la maquina original ahora si puede enviar el mensaje a quien le toca.

¿Cuáles considera son las ventajas y desventajas de Static y Dynamic Mapping?

Desventajas de Static Mapping
	Las direcciones cambian varias veces y se tiene que actualizar, haciendo que afecte el rendimiento

Desventajas de Dynamic Mapping
	Requiere mas protocolos para mapear las direcciones

Ventajas de cada uno

Para Static Mapping es tecnicamente mas sencillo, ya que solo se requieren las tablas para guardar las direcciones

Para Dynamic mapping como no se tiene que actualizar nada tiene mejor rendimiento


¿Cuáles son las aplicaciones de un Proxy ARP?

Se puede usar para por ejemplo hacer una comunicacion entre distintas redes o para facilitar la comunicacion del ARP cuando se trabaja con subredes.


¿Cómo funciona el ARP spoofing? Puede usar otros recursos para dar respuesta a esta pregunta.

ARP spoofing es una tecnica donde se envian mensajes ARP falsos y esto puede interrumpir la comunicacion en una red LAN. Este metodo usualmente funciona enviando mensajes ARP con direcciones falsas entonces en este momento se vuelve peligroso porque pueden redireccionar donde se envia la comunicacion o hacer un desorden de redes, atacando de varias formas como robar datos o impedir conecciones.

#### Citas usadas:

Veracode. (2026, 20 julio). _ARP Spoofing explained: How it impacts networks_. https://www.veracode.com/security/arp-spoofing/

Masas, R. (2023, 20 diciembre). _What is ARP Spoofing | ARP Cache Poisoning Attack Explained | Imperva_. Learning Center. https://www.imperva.com/learn/application-security/arp-spoofing/

Jajodia, S. (2005b). _Information Systems Security: First International Conference, ICISS 2005, Kolkata, India, December 19-21, 2005, Proceedings_. Springer Science & Business Media. https://books.google.co.cr/books?id=4LmERFxBzSUC&pg=PA239&redir_esc=y#v=onepage&q&f=false
