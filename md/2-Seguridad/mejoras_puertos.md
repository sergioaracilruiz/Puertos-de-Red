## Mejoras en los puertos TCP/UDP

Como puedes ver, los puertos TCP y UDP son una parte fundamental en Internet hoy en día. Estos se han utilizado ampliamente para las comunicaciones, durante décadas. Pero a pesar de que se ha demostrado que son eficaces y confiables para tal efecto, es muy importante que continúen evolucionando para poder adaptarse a los cambios y demandas actuales. Esto se debe al aumento exponencial de las aplicaciones que los requiere, así como para los servicios en línea que también son cada vez más.

En el caso de **TCP, alguna evolución puede pasar por las mejoras en la eficiencia y velocidad de transferencia de los datos**. Para ello muchos desarrolladores exploran diferentes técnicas como puede ser la segmentación y la multiplexación. Estos mejoran los flujos de datos, para así optimizar la transmisión cuando se trata de grandes volúmenes de datos. Por otro lado, también se trabaja en mecanismos para poder controlar la congestión de la red. De forma que esta se hace más efectiva, y garantiza un rendimiento lo más óptimo posible en todos los casos.

En el caso del protocolo **UDP, este se ha utilizado mucho en aplicaciones donde se requiere una comunicación muy rápida**. Pueden ser videojuegos o transmisiones en tiempo real. **En cambio, está falto de mecanismos de control para prevenir errores**, y la retransmisión de paquetes limita sus aplicaciones en algunos contextos. Por lo cual una posible evolución en este aspecto, podría ser el implicar la incorporación de mecanismos más selectivos para el control de errores y retransmisión. Lo cual puede permitir que se utilice en aplicaciones donde es muy importante mantener una integridad muy alta en los datos.

Por otro lado, algo en lo que siempre se está evolucionando y mejorando es la seguridad. En los tiempos que corren los datos que se manejan en Internet son más privados que nunca, por lo cual la seguridad es un aspecto que no se puede olvidar nunca. Pero esto es algo que ya se aplica a prácticamente cualquier sistema ya en uno, o en desarrollo.

 
## Diferentes estados de los puertos

Para determinar el estado de los puertos, podemos utilizar tres términos los cuales varían en función de la configuración de los mismos.

+ **Puertos cerrados**: Cuando la comunicación es rechazada completamente, por lo cual no generan ningún tráfico entrante o saliente.
+ **Puertos filtrados**: Todo el tráfico que transcurre por estos, es filtrado por aplicaciones de seguridad como los firewall.
+ **Puertos abiertos**: Cuando un servicio está escuchando en este puerto, y es accesible desde el exterior.

 
## Diferencias de rendimiento

Con TCP estamos ante un protocolo orientado a la conexión. Esto quiere decir que establece la conexión entre dos dispositivos, previamente a enviar los datos. Una vez esta está creada, TCP utiliza procesos de confirmación para poder garantizar que todos los datos se entreguen sin errores y en el orden correcto. Por lo cual es un protocolo confiable y seguro que se utiliza para la transmisión de datos críticos y sensibles, como la información financiera o los correos electrónicos. En cambio, estos procesos de confirmación y verificación de errores tienen un impacto significativo en el rendimiento de la red.

Por lo general, **TCP es más lento que UDP y requiere más ancho de banda**. Esto ocurre porque cada paquete debe ser confirmado antes de que se envíe el siguiente, aumentando así la cantidad de tiempo que se tarda en realizar los envíos. Al cual tendremos que sumar, los procesos de confirmación.

Por otro lado, con UDP estamos ante un protocolo sin conexión que no requiere una conexión previa entre los dispositivos antes de enviar datos. Esto quiere decir que los paquetes se envían inmediatamente y sin confirmación de recepción.

Esto hace que estemos ante un protocolo rápido y eficiente que se utiliza para aplicaciones en tiempo real, como el streaming de video y audio, videojuegos o videollamadas. Pero a pesar de su rapidez, se trata de un sistema que es menos confiable que TCP. Esto ocurre porque no dispone de una confirmación de recepción, y tampoco contienen mecanismos de corrección de errores. Estos paquetes, se pueden perder o incluso llegar en un orden que no es el adecuado al envío que se ha realizado. Por lo cual puede afectar a la calidad de los datos que se han transmitido, siendo este el motivo por el cual se descarta para otro tipo de comunicaciones.

En definitiva, hay que tener claro que, en términos de rendimiento puro, lo cierto es que los puertos UDP son los que ofrecen una mayor eficiente, siempre en comparación con los puertos TCP. Y todo porque este no pone una conexión antes de la transmisión en sí, por lo que los paquetes se envían de una forma más rápida y con una mejor latencia. Esto hace que, en servicios como los de almacenamiento en la nube en tiempo real, se use más el otro protocolo. Al igual que en otras opciones como videojuegos o transmisiones de vídeo en directo.

 
## Por qué es importante abrir puertos

Hemos mostrado los principales puertos tanto TCP como UDP. Ahora vamos a hablar de por qué en ocasiones es importante abrir determinados puertos. Lo es para que la conexión pueda pasar correctamente y lograr así una buena velocidad, evitar cortes y no tener problemas para acceder a ciertos servicios.

 
### Jugar por Internet

Un ejemplo claro es para jugar por Internet. Los juegos utilizan determinados puertos para poder establecer una conexión. Para que esa conexión sea veloz y no aparezcan cortes, es necesario saber qué puertos utiliza cada juego y abrirlos en el router. Esto evitará problemas o que incluso no puedas entrar en una partida determinada. Esto es algo que puede ser necesario tanto a la hora de jugar en ordenador como también a través de videoconsolas. Debes informarte bien sobre qué puertos utiliza cada juego y si es necesario o no abrirlos. En algunos routers incluso verás puertos predeterminados en la configuración para abrirlos fácilmente para determinados juegos populares.

Videoconsolas como la PS4, PS5 o xBox pueden requerir de abrir un rango de puertos específico para poder jugar a determinados juegos sin que haya problemas. Podrás encontrar mucha información en Internet, en foros especializados o en la propia página de los videojuegos, donde verás cuáles debes abrir y así poder configurar correctamente tu router.

En cuanto al puerto que los videojuegos van a utilizar, la elección es un proceso crítico. Y lo cierto es que de forma constante es muy incomprendido ante la creación de un videojuego online. En muchos casos, **los desarrolladores tienen la capacidad y libertad de poder seleccionar los puertos que van a utilizar** para sus servicios online y poder sacar el juego a la comunidad. A menudo, se eligen puertos muy específicos por diferentes razones. Algunos de ellos son bien conocidos y están asociados con un tráfico muy particular de la red. Como puede ser el puerto 80 o el 443. En cambio **para evitar todo tipo de conflictos con otros servicios, suelen elegir puertos en rangos de entre 1024 y 49151**. Lo cuales ***se conocen como puertos registrados***.

La elección de este puerto, también puede estar muy dictada por diferentes razones, como las convenciones de la industria del videojuego. Algunos juegos multijugador, pueden usar los mismos puertos para que la configuración sea mucho más sencilla para las redes de los jugadores. Y por supuesto, a la hora de resolver problemas también tendremos muchos videojuegos en el mismo puerto. Por lo cual sabemos más o menos hacia donde apuntar en todo caso.

Cabe destacar, que los desarrolladores tienen capacidades para elegir el puerto. Pero es posible que no todos los juegos permitan a los jugadores modificar este parámetro para cambiar de puerto. Esto por lo general tiene sus razones, como puede ser la seguridad, la simplicidad de la conexión, o simplemente que el jugador tenga la experiencia de juego tal cual fue diseñada. Existen varias formas en las cuales los jugadores pueden configurar el router para que en juego funcione mejor. Pero lo más sensato en estos casos, es acudir a la página oficial de la desarrolladora, donde encontraremos en muchas ocasiones la información necesaria con respecto al puerto que utilizan sus videojuegos.

 
### Descargas P2P

Algo similar ocurre al utilizar aplicaciones de **descargas P2P**. Estos programas van a conectarse a determinados puertos para establecer la conexión. Si esos puertos están cerrados, se produciría un cuello de botella y la velocidad de las descargas sería muy limitada y podrías tener problemas para bajar archivos correctamente.

Por ejemplo para usar BitTorrent o uTorrent será necesario tener los puertos abiertos correctamente. En algunos casos no será necesario y no notarás diferencia, pero en otras ocasiones sí que podrás ver que los archivos se descargan mucho más rápido. Aplicaciones de descargas P2P clásicas como eMule incluso mostraban una señal que indicaba que los puertos estaban cerrados y la velocidad de descarga muy limitada.

Especialmente en la descarga de archivos es cuando más interesa que la aplicación aproveche al máximo la capacidad que tiene nuestra conexión. Esto puede ser determinante de cara a que una descarga tarde más o tarde menos en completarse.