
Clase anterior; se habia iniciado el tema de subcapa de acceso medio

ALOHA: accesos satelitales

Como los satelites estan en la orbita, en la tierra se ocupan estaciones base para establecer una linea de vista

Un tema comparten el mismo medio a.k.a. el aire, entonces cuando se quieren conectar las tramas se envian al satelite, y como el satelite no sabe donde es que esta el destinatario, difunde el paquete(Se envia a todos)

![[Pasted image 20260925190436.png]]

Muchos pueden intentar enviar un mensaje usando el mismo canal de comunicacion asi que las tramas chocan y la comunicacion falla por lo que ALOHA puro es muyyyy malo

Para solucionar esto se usan las ranuras

P.d.: Ranura es una apertura temporal

Mientras que requiere sincronizacion y aveces hay desorden, el exito se duplica comparado con el ALOHA puro


Pero eso es con satelites, ahora 
## C a b l e s 
![[Pasted image 20260925191336.png]]

Carrier Sense Multiple access - persistente 1
- Verifica el canal si quiere enviar datos
- Si hay colision se espera un tiempo aleatorio y despues lo intenta de nuevo(tiene el problema del desorden)
- Si el canal esta inactivo se transmite

El mismo pero no persistente
- Si esta activo lo monitorea
- Mejor que el persistente

El mismo pero persistente P
- Usa canales ranurados
- Escucha el canal
- Si esta inactivo se transmite con probabilidad definida por el protocolo
- usa IEE 802.1

CSMA/CD

- Deteccion rapida de colision
- LAN
- Analogico
- Sigue el mismo esquema de el persistente 1
- Existe Tiempo minimo
- Usa Retroceso Exponencial binario con ranuras para un numero definido de colisiones

Metodo de mapa de bits
- Libre de colisiones
- N estaciones(de 0 a N-1)
- Si la estacion 1 tiene que transmitir pone un bit 1 en la ranura 0

Paso de Token
- Como se dice el nombre, se pasa el token entre estaciones, pero el tema es coordinar el paso del token
- Sobrecarga por estaciones
- Un Token ring(circulito donde todos estan conectados como en un circulo)


# Ethernet
La clasica(IEEE 802.3)

No se usa
3-10 Mbps
Cable grueso para conectar computadoras
Ocupa repetidores
Maximo 500 metros
![[Pasted image 20260925194025.png]]
<center>*Trama de la Ethernet clasica circa 1990s or so*
</center>

Como no hay conmutacion, el envio de informacion iba por difusion(todos recibian la trama TODOS)

# Como saben las compus a que info deberian tener acceso? 
 - MAC address lol

Ethernet Conmutada(802.3)
- Ethernet rapidin, autonegociacion
- Cada estacion cuenta con un cable de par trenzado dedicado que llega al hub central
- El hub fue cambiado por un switch
- LA velocidad se limita al elemento mas lento
- Tiene Buffers
- Varias tramas
- Dispositivo caro

<center>Hub VS Switch</center>

<center>No sabe quien esta en cada hueco| Si le sabe</center>

Hub: tenia varios puertos, usa RJ45, Half duplex

Repetidores: Regeneran y amplifican la señal, exteienden el rango de LAN Power over Ethernet

Switch; similar a un bridge, varios segmentos, inteligente para entregar tramas, solo ven paquetes a quienes se le envian, full duplex

	- Al conectar un switch, tecnicamente se monta una LAN
	- Los switches se pueden conectar entre si
	- Pequeño tema; las maquinas en un LAN se pueden descubrir entre si
	- Usualmente los switches traen por definido VLAN = 0 pero se pueden poner otras VLAN