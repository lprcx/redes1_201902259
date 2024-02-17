# Manual Técnico
#### Universidad de San Carlos de Guatemala 
#### Facultad de Ingeniería 
#### Escuela de Ciencias y Sistemas 
#### Redes de Computadoras 1 “N”
#### Catedrático: Ing. Pedro Pablo Hernández Ramírez 
#### Auxiliar: Melani López

### Objetivos
• Demostrar el conocimiento adquirido respecto a los protocolos Ethernet, IP, ARP e ICMP. 
• Demostrar el conocimiento requerido para la configuración de máquinas virtuales 
VPC y switches de capa 2. 

• Emplear la herramienta Packet Tracer para desarrollar la topología de acuerdo con 
las especificaciones dadas. 

• Emplear el modo simulación de Packet Tracer para la captura de paquetes. 


## Configuración de las VPCs
### Primer Nivel
#### VPC del área de Administración
![VPC del área de administración](/capturas/3.png)
ip: 192.168.59.10
#### VPC del área de Gerencia
![Descripción de la imagen](/capturas/4.png)
ip: 192.168.59.11
#### VPC del área de Atención al Cliente
![Descripción de la imagen](/capturas/5.png)
ip: 192.168.59.12
#### VPC del área de Recursos Humanos
![Descripción de la imagen](/capturas/6.png)
ip: 192.168.59.14
### Segundo Nivel
#### VPC del área de la Oficina A
![Descripción de la imagen](/capturas/7.png)
ip: 192.168.59.20
#### VPC del área de la Oficina B
![Descripción de la imagen](/capturas/8.png)
ip: 192.168.59.23
#### VPC del área de la Oficina C
![Descripción de la imagen](/capturas/9.png)
ip: 192.168.59.29

## Pings entre los hosts

#### Ping desde el equipo con ip 192.168.59.10 (Administración) a los equipos con ips:
- 192.168.59.11 (Gerencia)
- 192.168.59.12 (Atención al Cliente)
- 192.168.59.14 (Recursos Humanos)
![Descripción de la imagen](/capturas/2.png)

## Paquete ARP/ICMP
### Envío de un paquete ARP/ICMP desde el equipo con ip 192.168.59.10 (Administración) al equipo 192.168.59.20 (Oficina A)

![Descripción de la imagen](/capturas/10.png)
![Descripción de la imagen](/capturas/11.png)

