Comente de acuerdo a la lectura las principales características de WEP, WPA y WPA2

WEP(Wired Equivalent Privacy): Protocolo de seguridad introducido por la IEEE, hecho para dar encripcion a la transmision de  los dispositivos de red.
Hecho originalmente en 1987 e implementado en 1997
La autenticacion es un sistema y llave abierta.(cualquiera se puede unir, pero hay un proceso de autenticacion)
Se usa Rivest Cipher 4
Se comparte 1 llave entre todos los dispositivos de la red, se refiere como la "Root Key"
Alto grado de manipulacion y perdida de datos, y la llave se puede decodificar capturando los datos

WPA(Wifi Protected Access):

Introducido en 2003
Hecho para reemplazar WEP
Para WPA  personal se usa PSK para autenticacion
Para WPS  de empresa se usa EAP
Se usa una llave pre-compartida para la seguridad, se recibe con una contraseña
El acceso a la red se obtiene a traves se un servidor de acceso.
Se usa un protocolo de integridad de llave temporal, llaves distintas para distintos periodos de tiempo.
Estas llaves se generan en el servidor de autenticacion y se pasan(usual mente pre compartidas)
Usa un codigo de integridad para evitar ataques
Por como se generan las llaves es vulnerable a ataques de fuerza bruta

WPA2(Sames)
Es una mejora del WPA
Mejora del estandar de encriptacion
Mejora en el proceso de autenticacion(Se pasa del TKIP es decir llave temporal a CCMP)
Aun usa Servidor de autenticacion y llave pre-compartida
Usa el AES para encriptar y desencriptar
Se usa PTK para generar las llaves
Vector de inicializacion largo
Fuerte contra ataques de fuerza bruta
Mejora de velocidad
Debilidades menores como que el PTK depende de PSK para su seguridad