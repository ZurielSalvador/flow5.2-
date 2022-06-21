# flow5.2-
Esta actividad es para que otro usuario pueda ver la interfaz del flow5.1 

Para llevar acabo esta actividad, primero se abrio un puerto de nombre: NodeRed con rango: 1880-1880, Protocol: TCP or UDP

Es importante verficar que puedas abrir puertos, en dado caso que no se pueda tiene que contactar a la compañía correspondiente.

Ahora para que otra persona que no este necesariamente en tu red pueda ver la interfaz de tu flow5, tendras que poner la siguiente estructura:

http://192.168.100.33:1880/ui/#!/3?socketid=wUhcDR0dpa7h5vbSAAAB  

*Nota: La ip se obtiene con el comando ifconfig*

Podemos observar que el link tiene la estructura indica anteriormente.

[![flow5-2.png](https://i.postimg.cc/Bny4sYff/flow5-2.png)](https://postimg.cc/68dDfhQM)