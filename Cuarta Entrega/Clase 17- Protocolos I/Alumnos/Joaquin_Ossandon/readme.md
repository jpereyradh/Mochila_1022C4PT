# Protocolos y redes 📡

## Direccion IP pública

La direccion ip Pública es la designada por el ISP contratado.

para averiguar una IP pública podemos:

- Ingresar el siguiente comando en la consola `nslookup myip.opendns.com resolver1.opendns.com`

- Ingresar a un sitio como http://cualesmiip.es/

## Dirección IP privada

La `direccion IP privada` es aquella otorgada por el DHCP del router local usada para comunicarse internamente en dicha red.

La mascara de subred indica el tamaño de la red, generalmente es 255.255.255.0 siendo una máscara 24

En Windows, se puede acceder a ambas con el comando `ìpconfig`
![](https://i.imgur.com/hGdrQ1x.png)

## Dirección MAC

La MAC es una dirección o identificado único y universal otorgado por el fabricante utilizado para identificar el dispositivo en el mundo.

En Windows se puede obtener con el comando `ipconfig -all`:

![](https://i.imgur.com/3iMCuhq.png)

## ¿La IP pública y privada de qué clase son?

### IP pública
La dirección IP privada por lo general puede ser clase A, B o C.

| clase   | rango                             |
| ------- | --------------------------------- |
| Clase A | `10.0.0.0` a `10.255.255.255`     |
| Clase B | `172.16.0.0` a `172.31.255.255`   |
| Clase C | `192.168.0.0` a `192.168.255.255` |

### IP privada
Las direcciones IP públicas también tienen rangos y se corresponden a aquellos que quedan excluidos de los rangos para las IP privadas, yendo desde «1. …» hasta «191. …». De manera que el rango de la IP públicas estará en:

| clase   | rango                           |
| ------- | ------------------------------- |
| Clase A | `1.0.0.0` a `126.255.255.255`   |
| Clase B | `128.0.0.0` a `191.255.255.255` |
| Clase C | `192.0.0.0` a `223.255.255.255` |

# ¿Qué información puedo obtener de la dirección MAC?
En el sitio [MAC vendors](https://macvendors.com) nos entrega el nombre del fabricante de la placa.

## [Acceso a Paddlet](https://padlet.com/PedagogiaDH/bszr2bcf2qwogr9s)