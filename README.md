# DebAPoint
Linux Debian Access Point hostapd, mode NAT or mode Bridge

DebAPoint está diseñado para ejecutarse sobre una instalación NUEVA/FRESCA de Debian *7(Wheezy)* o Debian *8(Jessie)*. Ponga atención a esta nota, ya que este script MODIFICARA dos archivos importantes del sistema: /etc/apt/sources.list y /etc/network/interfaces

# Instalación

```sh
 $ su -
 
 # wget --no-check-certificate https://raw.githubusercontent.com/joseccnet/DebAPoint/master/DebAPoint.sh
 
 # bash DebAPoint.sh
 
 # reboot
```

Reinicie el servidor virtual y cuando este arriba, conecte la(s) interfaz de red USB, en unos segundos podra utilizar el Access Point.
