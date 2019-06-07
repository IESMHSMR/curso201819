	TCP/IP Windows 
Para configurar la configuración TCP/IP de windows de hace gráficamente, de tal forma que iríamos a la zona inferior derecha y en la pantalla con un cable de Internet (rj45)
![](https://csirc.ugr.es/opencms/export/sites/default/informatica/Galerias/Imagenes/ImagRedes/tcp_w10_1_1.png)

Le daremos click derecho y abrimos el centro de redes y recursos compartidos.

![](https://lh3.googleusercontent.com/h74CoWTUJKSwU29w5vu39GtWWUzfzVwkhwfbrWv8Gwb23gMmUdKWq2Y9jjy8q2xMt1-6=s168)

Se nos abrirá una pantalla en la cual tendremos que darle a propiedades en la zona inferior izquierda y buscaremos el Protocolo de Internet versión 5 (TCP/IPv4)

![](https://lh3.googleusercontent.com/Fcia7ZRknX7H0btnR3GNq-mOcFcM6l6aoMiYthXqeUacyDIP-zkW7ToKGyn7JPkY2sxSSXA=s85)

Dentro de esta pantalla, en primer lugar podremos poner la IP de forma automática (DHCP), la opción de usar la siguiente dirección IP: podremos configurar la IP estática que queremos, la Máscara de subred y la puerta de enlace, por si tenemos una ip privada asignada para el equipo y continuación pondremos la DNS como anteriormente, si automática o estática.

En la configuración avanzada de hace lo mismo añadiendo el WINS.

-Comandos de windows de comprobación:

ipconfig

![](https://lh3.googleusercontent.com/HA_ie9ePra0n74O_OZHgJgGMMBkLe_JiHRadtf-amC4pSWFhiyaKyG-l4vvLo2NZJptulA=s167)

En el cual nos aparecerá, El sujido  DNS,Direcion IPv6 Local, IPv4, mascara de subred y puerta de enlace. como cosas importantes.

ipconfig/all

![](https://lh3.googleusercontent.com/tvStWxEVOEduaeSDeufS4X8y1C0p9dT8p41DWpKuWpf3_fCZts41GsAhdiJcpEPxoe-Iag=s102)

Viendo el comando ya podréis entender que es una extensión del anterior, entonces nos saldrá lo mismo que anteriormente mas, el nombre de host, sufijo DNS, servidor dhcp, direccion fisica y los DNS, como lo mas importante

getmac

![](https://lh3.googleusercontent.com/xxkjwPQH8f5YTYFlE9NXkJvXZ3dLI3-atA178DLiwIpEu0hrQw9nGF2qTNkk9SkwiEBZwUs=s170)

Con este comando veremos la Dirección física (MAC) y el nombre del transporte 

	TCP/IP Linux

En la parte superior derecha encontraremos este icono:

![](https://lh3.googleusercontent.com/PJ-40hU_ZNUJ1wMRoW40tqUeY35miEHBTWzcoxedG902rocTRHqUXWUbLQ83bpX5g7Fi=s24)

Le daremos click  y editar conexiones.

Cuando se nos abra este meno:

![](https://csirc.ugr.es/opencms/export/sites/default/informatica/Galerias/Imagenes/ImagRedes/Imagen_4.png_130534248.png)

elegiremos la red y le daremos a editar, se nos abrirá un menu y nos vamos a la pestaña IPV4.

![](https://csirc.ugr.es/opencms/export/sites/default/informatica/Galerias/Imagenes/ImagRedes/Imagen_7.png)

Aqui podremos como en windows. en Método elijemos DHCP o Static, si ponemos static configuraremos la direción, mascara de red y puerta de enlace. abajo podremos elegir la DNS.

-Comandos de linux para ver la configuracion


Ifconfig

Igual que el ipconfig de windows, te muesta cada una de las tarjetas con su nombre, su ip,mascara...

![](https://4.bp.blogspot.com/-PwxD0WbFFlo/WounRppdDLI/AAAAAAABnhc/fONOjNViCMQGRa7D_K_O6rdffv02Xv0-ACLcBGAs/s1600/Captura.PNG)

ip address show

Te muestra la ip con la que estas trabajando.

![](https://static.makeuseof.com/wp-content/uploads/2018/05/linux-ip-addr-show.jpg)

ip address list

Con este comando puedes encontrar la ip y la MAC


	Comandos Mikrotik

-ip address print

Este comando nos enseña las conexiones que tenemos, tanto la ip con su mascara, como el network y la interface.

![](https://lh3.googleusercontent.com/kopqounkqpVsGxgIuzwBIgSdnxkeZLOm8AbcRxefisXVUCToOvlFvUq8oxVAosOk4SrLuT4=s170)

-interface print 

Nos muestra los nombres de las redes que tenemos

![](https://lh3.googleusercontent.com/xckiJau0HSVugTMBHeXIUggC4U4jQR6vSMV2kclq97TIRHpNUeQbXMlgxK_F4uHvnXQDZy8=s170)


	Enrutamiento / tabla de rutas	

	Comandos Windows

-Route print

Este comando se utiliza para imprimir rutas y también poder ver las rutas activas.
![](https://lh3.googleusercontent.com/zgAyYmAc-gt5aDfNrV8P8GsLG1-rmoRIQjkJ36I7uwqtYZbBJZ9x39yoHefheP5c_Gj5OTg=s85)

	Comandos Linux

-netstat -r

Te enseña las tablas de rutas y el -r las principales.

![](https://lh3.googleusercontent.com/ql6yCOshspmWYdBEj1xc4nwpdqZ7gJZD4BwctYmQIrjJeX13RVTwuES0sm4iAvd--D6-ag=s170)

-route - n

Te enseña las posibles rutas y con -n las principales, es un comando parecido a netstat


![](https://lh3.googleusercontent.com/849KYoK68xrskHPCEjatCb2A_x6xe7hJq5ZbHC5cT_wmTdDeMre7aD3WfoVVIpXPByylReE=s170)


-ip route show

Te enseña cada tarjeta de red con su configuración básica

![](https://lh3.googleusercontent.com/Ib-ttVy1Qt915nRJ4-xnXXWhps-FyJCIE4M-_toeUtEV94qhDEyFjyMCk-uPqIt-CtcRt9s=s170)

	Comandos Mikrotik

-ip route print 

Te enseña la configuración básica de las tarjetas de red

![](https://lh3.googleusercontent.com/9-aD25MFvUSnPKUCevLfJ0kMRwCTQFbFvXh3tOdeWS8dABPBbCvtWOBOMIdpYzat758--cg=s170)


Hecho por: Ivan