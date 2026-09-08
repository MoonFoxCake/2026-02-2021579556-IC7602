

### Capas de OSI

![[Pasted image 20260904190115.png]]

Son informativas(Para saber que existen pero no se manipulan en el dia a dia)
#### Capa fisica

- Interactua con el hardware
- Define el equipo de hardware, cableado, frecuencia y pulsos
- Mecanismo de señalizacion(como una computadora se va a comunicar)
- La capa de datos envia frames, la capa fisica agarra el array de bytes y los convierte a pulsos electricos
- Wired o wireless

##### Bandwith

El medio tiene un rango de pulsos

![[Pasted image 20260904190543.png]]

Puede ser digital o analogica

La amplitud dice en el momento del eje


Potencia constante: todas las frecuencias se mandan con la misma potencia

La señal se puede ir degradando, es decir pierde Hz o su amplitud

Frecuencia de corte del material: Frecuencia en la cual se degrada y cae mas de 50%
En ese punto es donde se encuentra el ancho de banda.

De aca sale que el repeater no ayude, porque no significa que vaya a quitar la degradacion o que ayude al ancho de banda

Si la señal mide por ejemplo 1km, para poder capturarla se ocupa 1/4 parte de la señal, por lo cual seria minimo 250 metros de antena.


Para un ejemplo mas practico, con un ancho de banda de 500 MHz, si se conecta una laptop se deberia de poder usar todo, pero como es costoso darle todo el ancho a un dispositivo, se subdivide, por lo cual el ancho de banda se divide en canales, se asigna un canal a cada dispositivo

*Importante:* Solo porque tengan la misma capacidad, no significa que tengan las mismas capacidades, puede que algunos por ejemplo pierdan mas amplitud en menor distancia o viceversa.

**Esto explica por ejemplo porque los servicios se pelean ciertos rangos de frecuencia**


Nunca se usa el canal completo, hay unas "Barreras" para evitar interferencia

Hay formas de dividir el canal, por ejemplo, multiplexion por tiempo, que es por ejemplo 10 segundos por usuario.

En uso real se usan varios metodos de multiplexion a la vez, entonces se usa multiplexion por frecuencia **y** por tiempo.

![[Pasted image 20260904193935.png]]



##### Señales electormagneticas

- Es cuando los datos son enmiados por el medio fisico
- Pueden ser analogos o digitales
- Las señales digitales son discretas, llevan informacion binaria y son cuadradas(Como el signaling)
- Las analogicas son continuas


![[Pasted image 20260904194403.png]]

Fase: Relacion entre 2 o mas señales pero que no estan alineadas a pesar de estar en la misma frecuencia, que se hace? se usan los angulos para distinguir entre frecuencias

**Asi se ve la onda, se desfasa**
![[Pasted image 20260904195226.png]]


Usualmente las ondas rebotan y no salen de la tierra, pero cuando salen, como no tienen donde rebotar si pueden viajar infinitamente

**Analisis de Fourier(jaja la tarea)**

Cualquier funcion periodica se puede construir como la suma de un numero de senos y cosenos


***Deterioro de la transmicion***

Distorcion, limitacion de ancho de banda, o Ruido


Medios:

- Se caracterizan por el ancho de banda o la distancia que puede mover la transmision(mini resumen basicamente)

Medios magneticos, se almacena en una cinta magnetica(es metodo)

Snowcone AWS; ok, esta curioso para transferir datos