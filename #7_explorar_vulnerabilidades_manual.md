# #7_explorar_vulnerabilidades_manual
### Comprobar conexion entre una Maquina y la otra
```
ping -c [direccion maquina destino]
ping -c 1 192.168.1.63
```

### Escaneo maquina victima
```
sudo nmap -p- -sVC -sC --open -sS -vvv -n -Pn 192.168.1.51 -oN [nombre_del_fichero]
```