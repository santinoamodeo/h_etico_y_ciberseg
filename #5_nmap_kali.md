# #5_nmap_kali

### Ver mi IP
```
# En este caso 192.168.1.62

ifconfig 
```
### Escaneo general de todos los equipos conectados a la red
```
# se pone la red base/24

nmap 192.168.1.0/24 
```
### Escaneo general con SO de todos los equipos conectados a la red 
```
# se pone la red base/24

nmap 192.168.1.0/24 
```


### Escaneo maquina victima
```
sudo nmap -p- -sVC -sC --open -sS -vvv -n -Pn 192.168.1.51 -oN [nombre_del_fichero]
```