# 📘 Manual Técnico de Configuración de Red

## 📋 1. Tabla de Direcciones IP

| Switch / Dispositivo          | IP de Gestión      |
|--------------------------------|--------------------|
| **SW_L1**                     | 192.168.91.100     |
| **SW_L1_RECEPCION**           | 192.168.91.101     |
| **SW_L1_CONTABILIDAD**        | 192.168.91.102     |
| **SW_L1_LEGAL**               | 192.168.91.103     |
| **SW_L1_REUNIONES**           | 192.168.91.104     |
| **SW_L2**                     | 192.168.91.110     |
| **SW_L2_ARQUITECTURA**        | 192.168.91.111     |
| **SW_L2_URBANISMO**           | 192.168.91.112     |
| **SW_L2_REUNIONES**           | 192.168.91.113     |
| **SW_L3**                     | 192.168.91.120     |
| **SW_L3_DIRECCION**           | 192.168.91.121     |
| **SW_L3_INGENIERIA**          | 192.168.91.122     |
| **SW_L3_SERVIDORES**          | 192.168.91.123     |

---

## ⚙️ 2. Comandos para Configurar Switches

A continuación, se muestran los comandos para cada switch.  
**En Packet Tracer, usar en CLI:**

```bash
# SW_L1
enable
configure terminal
interface vlan 1
ip address 192.168.91.100 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L1_RECEPCION
enable
configure terminal
interface vlan 1
ip address 192.168.91.101 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L1_CONTABILIDAD
enable
configure terminal
interface vlan 1
ip address 192.168.91.102 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L1_LEGAL
enable
configure terminal
interface vlan 1
ip address 192.168.91.103 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L1_REUNIONES
enable
configure terminal
interface vlan 1
ip address 192.168.91.104 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L2
enable
configure terminal
interface vlan 1
ip address 192.168.91.110 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L2_ARQUITECTURA
enable
configure terminal
interface vlan 1
ip address 192.168.91.111 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L2_URBANISMO
enable
configure terminal
interface vlan 1
ip address 192.168.91.112 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L2_REUNIONES
enable
configure terminal
interface vlan 1
ip address 192.168.91.113 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L3
enable
configure terminal
interface vlan 1
ip address 192.168.91.120 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L3_DIRECCION
enable
configure terminal
interface vlan 1
ip address 192.168.91.121 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L3_INGENIERIA
enable
configure terminal
interface vlan 1
ip address 192.168.91.122 255.255.255.0
no shutdown
exit
exit
write memory

# SW_L3_SERVIDORES
enable
configure terminal
interface vlan 1
ip address 192.168.91.123 255.255.255.0
no shutdown
exit
exit
write memory

```

## 🖥️ 3. Configuración de las VPCs (10 áreas)
![VPC 1](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img42.jpg?raw=true)  
![VPC 2](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img43.jpg?raw=true)  
![VPC 3](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img46.jpg?raw=true)  
![VPC 4](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img47.jpg?raw=true)  
![VPC 5](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img50.jpg?raw=true)  
![VPC 6](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img51.jpg?raw=true)  
![VPC 7](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img54.jpg?raw=true)  
![VPC 8](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img55.jpg?raw=true)  
![VPC 9](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img58.jpg?raw=true)  
![VPC 10](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img59.jpg?raw=true)  





## 🖥4. Pruebas de Conectividad (Ping entre áreas)

> se Coloco aquí 10 capturas de pantalla demostrando comunicación entre PCs de distintas áreas.  
![Ping 1](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img22.jpg?raw=true)  
![Ping 2](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img23.jpg?raw=true)  
![Ping 3](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img26.jpg?raw=true)  
![Ping 4](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img27.jpg?raw=true)  
![Ping 5](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img30.jpg?raw=true)  
![Ping 6](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img31.jpg?raw=true)  
![Ping 7](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img34.jpg?raw=true)  
![Ping 8](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img35.jpg?raw=true)  
![Ping 9](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img38.jpg?raw=true)  
![Ping 10](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img39.jpg?raw=true)  


## 🖥5. Captura de Paquetes ARP y ICMP

> se realizo un ping en modo simulación y captura la secuencia de paquetes ARP e ICMP.  
> 

![Descripción de la imagen](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img14.jpg?raw=true)
![Descripción de la imagen](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img19.jpg?raw=true)
![Descripción de la imagen](https://github.com/luisyoupi1/Redes1_2S_2025_201801391/blob/main/imagenes/img18.jpg?raw=true)

