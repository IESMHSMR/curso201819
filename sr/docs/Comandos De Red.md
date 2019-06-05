#Configuracion TCP/IP
##Windows
###ipconfig
Muestra la información de nuestro equipo como:
>**Descripción** - Nombre del adaptador o tarjeta de red utilizado en la conexión.

>**Dirección IPV4** - Es la dirección IP asignada al equipo en la red local.

>**Puerta de enlace predeterminada** - Es la dirección IP del equipo que funciona como servidor y que tiene acceso a internet.

![](../img/Captura1.PNG)

###ipconfig /all
Muestra la información de nuestro equipo como:
>**Descripción** - Nombre del adaptador o tarjeta de red utilizado en la conexión.

>**Dirección IPV4** - Es la dirección IP asignada al equipo en la red local.

>**Puerta de enlace predeterminada** - Es la dirección IP del equipo que funciona como servidor y que tiene acceso a internet.

>**Servidores DNS** - Son los servidores con los cuales el equipo anterior gestiona en la red la relación nombre de dominio/Dirección IP de las paginas solicitadas.

>**Estado de DHCP** - Configuración dinámica de host, eso significa que siempre se utilizara una dirección IP estática o fija entre el equipo y el host.

![](./curso201819/sr/Captura2.png)
###getmac
Este comando habilita al administrador para poder mostrar la dirección MAC de uno o mas adaptores de red de un equipo.

![](./curso201819/sr/Captura3.png)
##Linux
###ifconfig
La orden ifconfig se utiliza para configurar y mostrar los interfaces de red de Linux. Se indican varios parámetros:

* La dirección IP de la maquina.
* La mascara de la red local.
* La dirección de broadcast.
* La dirección Mac.

![](./curso201819/sr/Captura4.png)
###ifconfig -a
La orden ifconfig -a se utiliza para configurar y mostrar los interfaces de red en Linux incluyendo las interfaces que no están activas.

![](./curso201819/sr/Captura5.png)
###ip address show
La orden ip address show se utiliza para configurar y mostrar los interfaces de red de Linux incluyendo las que no están activas. Se indican varios parámetros:

* La dirección IP de la maquina.
* La mascara de la red local.
* La dirección de broadcast.
* La dirección Mac.

![](./curso201819/sr/Captura6.png)
##Mikrotik
###interface print
![](./curso201819/sr/Captura8.png)
###ip address print
![](./curso201819/sr/Captura9.png)
#Enrutamiento/Tabla de rutas
##Windows
###route print
![](./curso201819/sr/Captura10.png)
##Linux
###netstat -r
![](./curso201819/sr/Captura11.png)
###route -n
![](./curso201819/sr/Captura12.png)
###ip route show
![](./curso201819/sr/Captura13.png)
##Mikrotik
###ip route print NUEVO NUEVO
![](./curso201819/sr/Captura14.png)
