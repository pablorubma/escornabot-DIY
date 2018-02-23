# EN CONSTRUCCIÓN :)

# Basada en la [guía oficial](https://escornabot.org/wiki/index.php/Gu%C3%ADa_de_montaje_(Brivoi))

# Guía Montaje para la versión Escornabot DIY

Los componentes detallados los puedes encontrar [aquí](https://github.com/pablorubma/escornabot-DIY#22-componentes-del-cuerpo) y son estos:

![00-componentes.JPG](imagenes/00-componentes.JPG)

## Ensamblaje motores

Material necesario:
* *Pieza "MotorBracket"*
* *2 Motores paso a paso 28BYJ-48 5V (solo los motores los drivers los usaremos más adelante)*
* *4 Tornillos M3 de 10mm*

![01-motores.JPG](imagenes/01-motores.JPG)

Dependiendo de la calidad de las piezas impresas este paso te costará más o menos.

![03-motores.JPG](imagenes/03-motores.JPG)

>__NOTA: Coloca los motores en la orientación que se muestra en la siguiente imagen, la zona azul en el mismo lado de la pieza donde el agujero central del tornillo tiene una muesca para encajar el tornillo.__

![02-motores.JPG](imagenes/02-motores.JPG)

## Soporte portapilas-batería

Material necesario:
* *Pieza "battery-bracket"*
* *1 Tornillo M3 de 10mm*

>__NOTA: La pieza va colocada al lado contrario donde quedó la parte azul de los motores como puedes ver en las imágenes.__

![04-soporte-bateria](imagenes/04-soporte-bateria.JPG)
![05-soporte-bateria](imagenes/05-soporte-bateria.JPG)

## Soporte placa botonera

Material necesario:
* *Pieza Addon-KeypadBracket-PCB (Ya que estoy utilizando la [placa de XDeSIG](https://github.com/pablorubma/escornabot-DIY#212-versi%C3%B3n-de-xdesig), si fabricamos la [placa totalmente artesanal](https://github.com/pablorubma/escornabot-DIY#211-placa-original-totalmente-artesanal) necesitaremos la pieza Addon-KeypadBracket-5Buttons)*
* *1 Tornillo M3 de 10mm*

>__NOTA: Pondremos solamente el tornillo de la parte trasera como puedes ver en las imágenes__

![06-soporte-placa.JPG](imagenes/06-soporte-placa.JPG)
![07-soporte-placa.JPG](imagenes/07-soporte-placa.JPG)

## Soporte protoboard 170 puntos

Material necesario:
* *Pieza "board-bracket"*
* *2 Tornillos M3 de 10mm*

>__NOTA: La pieza se encaja encima del soporte de la placa botonera y lleva otro tornillo en la parte inferior de los motores (Yo no suelo poner este tornillo porque me queda fijo solo con el superior)__

![08-soporte-proto.JPG](imagenes/08-soporte-proto.JPG)
![09-soporte-proto.JPG](imagenes/09-soporte-proto.JPG)

## Portapilas y bola

Material necesario:
* *Pieza "ballcaster-v2"*
* *2 Tornillos M3 de 10mm*
* *Bola o canica de 14mm*
* *Portapilas AA"
* *4 Pilas AA*

![10-bola.JPG](imagenes/10-bola.JPG)  
>__NOTA BOLA: Puede que la bola se salga, lo puedes solucionar calentando un poco la pieza y ajustando al gusto (con cuidado ^_^).__  

![11-portapilas.JPG](imagenes/11-portapilas.JPG)
>__NOTA PORTAPILAS: En algunos modelos tienen una posición concreta en la que encajan para no forzar la pieza donde va colocado. No utilizo interruptor, así que empalmo unos terminales hembra para después pinchar en la protoboard (puedes ponerlo de otro modo si quieres ^_^)__  

![12-bola-portapilas.JPG](imagenes/12-bola-portapilas.JPG)

>__NOTA PORTAPILAS: Si ves la siguiente imagen en este modelo queda una separación entre las dos piezas y se aprecia un trozo de tornillo. No hace falta ajustar los tornillos a dolor porque te puedes cargar alguna pieza, es suficiente si ajusta y no se mueve.__

![13-bola-portapilas.JPG](imagenes/13-bola-portapilas.JPG)

## Protoboard 170 puntos

Material necesario:
* *Protoboard*

>__NOTA: Al colocar encima el Arduino NANO dejo tres hileras libres en la parte superior y dos en la parte inferior. El único misterio de la protoboard es como todo en la vida, encajarla con cariño ^_^.__

![14-protoboard-nano.JPG](imagenes/14-protoboard-nano.JPG)

## Drivers para controlar los motores

### Colocación de los drivers

Material necesario:
* *2 Drivers ULN2003*
* *2 Tornillos M3 de 10mm (Puedes usar más corticos)*

>__NOTA: Mira en la siguiente imagen como va colacada la placa o te pegará después con las ruedas. Los cuatro pines macho tienen que ir en la parte superior.__

![15-drivers-motores.JPG](imagenes/15-drivers-motores.JPG)

>__NOTA: el de la izquierda (mirando la imagen) te quedará un poquito torcido porque pegarán las soldaduras de la parte trasera en la pieza impresa3D.__

![16-drivers-motores.JPG](imagenes/16-drivers-motores.JPG)

>__NOTA: Un truco para que los cables queden recogidos es pasar el cable por el driver contrario tal y como puedes ver en la siguiente imagen.__

![17-cableado-drivers.JPG](imagenes/17-cableado-drivers.JPG)

### Colocación cableado de los drivers-protoboard

Puedes consultar la [guía de cableado en la web escornabot](https://escornabot.com/web/es/content/cableado) si te quedas con dudas

Material necesario:
* *8 cables arduino macho-hembra de 10cm (me gusta usar de colores pero puedes usar los que quieras)*
* *2 cables arduino macho-hembra de 10cm negros (puedes usar de otro color)*
* *2 cables arduino macho-hembra de 10cm rojos (puedes usar de otro color)*

![18-cableado-drivers.JPG](imagenes/18-cableado-drivers.JPG)

>__NOTA: La conexión es fácil, "mirando de frente los drivers" empezamos por los cuatro conectores de arriba, primero el de arriba a la derecha lo pinchamos en el pin D9 y los otros tres a continuación en orden D8, D7, D6.__

![19-drivers-nano.JPG](imagenes/19-drivers-nano.JPG)  
![20-drivers-nano.JPG](imagenes/20-drivers-nano.JPG)

>__NOTA: Ahora a por el de la izquierda "mirando de frente los drivers" los conectaremos a continuación D5, D4, D3 y D2__

![22-drivers-nano.JPG](imagenes/22-drivers-nano.JPG)

>__NOTA: Vamos a conectar positivo y negativo. Lo tienes marcado en el driver. En este caso el de abajo positivo, el de arriba negativo. Positivo va colocado al pin VIN y el Negativo a GND__

![23-drivers-nano-corriente.JPG](imagenes/23-drivers-nano-corriente.JPG)  
![24-drivers-nano-corriente.JPG](imagenes/24-drivers-nano-corriente.JPG)

>__NOTA: El resultado final debería ser algo así :P__

![25-drivers-nano-corriente.JPG](imagenes/25-drivers-nano-corriente.JPG)

## Placa botonera

Material necesario:
* *Placa botonera (da igual si usas [placa de XDeSIG](https://github.com/pablorubma/escornabot-DIY#212-versi%C3%B3n-de-xdesig) o la [placa totalmente artesanal](https://github.com/pablorubma/escornabot-DIY#211-placa-original-totalmente-artesanal))*
* *3 Cables arduino macho-hembra de 10cm*

>__IMPORTANTE: Primero realiza el Test de la botonera, tienes todos los pasos a seguir en la guía [comprobación y configuración de las lecturas de la botonera](https://escornabot.com/web/es/content/comprobacion-y-configuracion-de-las-lecturas-de-botonera)__

![26-botonera.JPG](imagenes/26-botonera.JPG)

>__NOTA: El pin cercano al botón azul es GND, lo coloco en el GND de la parte inferior.  
El pin central es la conexión de datos, lo coloco en el pin A4 (recuerda revisar el código después para ver que tienes configurado el teclado en este pin).  
El pin exterior es el positivo y lo conectaremos al pin de 5V (en el caso de no ir arcado en el Arduino NANO, tienes que dejar un hueco de separación con GND)__

![27-botonera-cableado.JPG](imagenes/27-botonera-cableado.JPG)

## Buzzer 5V o zumbador

Material necesario:
* *Buzzer 5V*
* *2 Cables arduino macho-hembra de 10cm (me gusta usar uno blanco para negativo y uno amarillo para positivo ^_^)*

>__NOTA: Normalmente el positivo va marcado y suele ser la patilla larga. Yo lo pongo con los cablecicos colgando porque me mola, pero aquí free-style.
Positivo lo conectamos al Pin D10 y negativo al GND que nos queda libre en la parte inferior.__

![30-buzzer.JPG](imagenes/30-buzzer.JPG)

## Ruedas

Material necesario:
* *Pieza "wheel-l"*
* *Pieza "wheel-r"*
* *2 Juntas tóricas 63x60x3mm*
* *2 Tornillos M3 de 10mm*
* *2 Tuercas M3*

>__NOTA: La tuerca debería entrar sin forzar mucho, si ves que no encaja siempre puedes tirar de soldador calentar con cuidado y encajar. Una vez encajada coloca el tornillo sin que asome la punta por la tuerca, así después solo tienes que pretar una vez tengas la rueda montada__

![31-tuerca-ruedas.JPG](imagenes/31-tuerca-ruedas.JPG)

>__NOTA: La junta dependiendo del tamaño te costará un poco ponerla pero no hay mayor problema__

![32-junta-rueda.JPG](imagenes/32-junta-rueda.JPG)

>__NOTA: La rueda lleva la forma del engancha con el motor. Una vez puesta, mueve la rueda para que el tornillo te quede en la parte inferior y lo puedas ajustar con facilidad.__

![33-rueda.JPG](imagenes/33-rueda.JPG)  
![34-rueda-tornillo.JPG](imagenes/34-rueda-tornillo.JPG)  

## Conexión cables corriente pilas

Material necesario:
* *2 Cables arduino macho-macho 10cm*  

*Lo repito, a mi me gusta montarlo así. Puedes ponerle un interruptor o lo que quieras :P*  

>__NOTA: Si has dejado tres huecos en la hilera superior como dije al inicio te quedará sitio para poner el positivo en VIN y negativo en GND como puedes ver en la foto.__  

![35-corriente-pilas.JPG](imagenes/35-corriente-pilas.JPG)  

## Carga el código Arduino  

Solo te quedará cargar el código, lo tienes explicado [aquí](https://github.com/pablorubma/escornabot-DIY#5-instalaci%C3%B3n-ide-arduino-y-descarga-de-la-programaci%C3%B3n)  

# Conecta los cables de corriente con los del portapilas y a JUGAR!!  

![36-escornabot-montado.JPG](imagenes/36-escornabot-montado.JPG)
