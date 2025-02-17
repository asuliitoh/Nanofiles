# Proyecto Final Redes de Comunicaciones - Nanofiles

## Introducción

Nanofiles se trata de un sistema de compartición y transferencia de ficheros. Está formado por un servidor de directorio (programa Directory) y un conjunto de peers (programa Nanofiles) que se comunican entre sí de la siguiente manera:

* Entre el servidor de directorio y los peers cliente, la comunicación se basa en el modelo Cliente-Servidor mediante el protocolo UDP, con un formato de mensaje textual.
* Entre los peers, la comunicación se basa en el modelo Peer-To-Peer (P2P) mediante el protocolo TCP, con un formato de mensaje binario.

La nota obtenida por este proyecto fue un 10.

## Especificación del proyecto

Para más detalles puede consultar el [enunciado del proyecto](https://github.com/asuliitoh/Nanofiles/blob/bd27aa5a31b2ab8bb3a888137fe7edd58453fca1/EnunciadoNanofiles.pdf) y la [implementación tecnica](https://github.com/asuliitoh/Nanofiles/blob/c8764920ab692015c33d1c37393251cea90f26e2/Redes%20Proyecto.pdf).

1. Los peers que quieran comunicarse con el servidor de directorio deben loguearse. Una vez hecho, el servidor les enviará una clave de sesión única que deben usar en cada solicitud que realicen al directorio, hasta que cierren sesión.
2. Un peer puede actuar como cliente o servidor de ficheros en un momento dado, de forma que acepte conexiones de otros peers para solicitarle descargar alguno de los ficheros que comparte. 
3. Un peer cliente puede descargar de un único servidor especificando IP:Puerto, o puede descargar los datos de múltiples servidores que dispongan del fichero.



## Autores

* Jesús Sánchez - [@asuliitoh](https://github.com/asuliitoh)
* Jiahui Lin - [@JHLumu](https://github.com/JHLumu)


