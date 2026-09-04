¿Cómo funciona el Port-Based Authentication?

Port-Based authentication consiste de un supplicant, autenticador y un servidor de autenticacion

Estos 3 elementos son los que conforman 

Supplicant

El supplicant es un cliente desconocido y no se les confia hasta que se puedan autenticar,  y para ser valido se tienen que implementar ciertos estandares como EAP o  802.1X. Entonces si es valido se comunica con el servidor usando EAP.

Autenticador

El autenticador es la segunda capa, sirve como el traductor entre el supplicant y el server de autenticacion(agarrando la solicitud del supplicant, metiendola en un EAPOL y enviandola), tambien es el porton entre quienes quieren entrar y la red, quien dice quienes si pueden y quienes no pueden entrar.

Server de autenticacion

Ya este ultimo elemento es el mas importante ya que tecnicamente es el que dice si si o si no pasa, con RADIUS que es el metodo que se utiliza. A veces solicitandole varias veces info al user.


Defina los componentes principales de 802-1x.

Puede que me equivoque, pero creo que son los mismos que los elementos de port-based authentication(Supplicant, autenticador, y server)


¿Por qué considera que este tipo de autenticación es relevante?

La autenticacion en si es importante para impedir que actores maliciosos entren o que puedan hacer algun daño al servidor o lo que sea que se desee proteger, aun mas, para evitar que clientes externos o que varios tipos de ataque logren llegar.