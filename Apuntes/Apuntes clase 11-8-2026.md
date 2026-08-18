
```
SAMPLE_RATE = 44100  # Hertz
DURATION = 5  # Seconds
MULT = 1.0

def generate_sine_wave(freq, sample_rate, duration):
    x = np.linspace(0, duration, sample_rate * duration, endpoint=False)
    frequencies = x * freq
    y = np.sin((2 * np.pi) * frequencies)
    return x, y



```
En este trozo de codigo es ideal para ver como sirven las señales, y propiedades que tienen como que se pueden demostrar mediante Senos(matematicos)



![[Pasted image 20260813205150.png]]

La importancia de esta imagen es que muestra como las ondas pueden cambiar dependiendo del pitch y la amplitud de estas. 

Se habla de la diferencia entre AM y FM, no es que una sea mejor que la otra, pero la diferencia es como se transfiere la informacion

Con AM la profundidad define si es un 1 o 0 mientras tanto con FM la informacion la define la cantidad de crestas.

Otro tema del que se discute es la calidad de audio; temas como los discos de acetato(viniles? ni idea, nunca habia escuchado del material), como es que varia la calidad de audio entre formatos(aunque los .wav deberian de deshacerse un poco de esa perdida de calidad). Pero no es solo eso, tambien hay factor humano, hay gente que puede tener un oido mejor refinado por lo cual si escuchan ciertos elementos extra por lo cual cuando se comprime por ejemplo con un mp3 se pierde la calidad.

Otro tema de habla es la relacion entre las distintas frecuencias, como que 2.4GHz tiene mejor penetracion contra 5GHz que tiene mejor ancho de banda, y su relacion con la energia, que de forma muy resumida, mientras mas watts se les da a las antenas y dispositivos.

![[Pasted image 20260818144409.png]]


Otro tema discutido es Fourier, que la fundamental de Fourier es el elemento de frecuencia que es el mas predominante.

Finalmente unos datos curiosos de la clase: los tubos de metal por donde van los cables en las aulas es por un estandar antiguo donde los cables de corriente generaban mucha interferencia por lo que los tubos eran necesarios. Todas las grabaciones de audio tienen 2 canales. Otro tema curioso de que se ocupa capturar por lo menos un cuarto de una señal para que se pueda reconstruir matematicamente, bajo este tema por ejemplo es que antes los telefonos ocupaban audifonos para que la radio funcione.

Finalmente; se deja la tarea, con un tiempo aprox de 2 semanas, donde hay varios criterios como documentacion, un reporte semanal y otros. La tarea en si es hacer un analizador de espectros sencillo para audio, de 3 elementos principales, analizador, reproductor y un comparador.
