## temat: Routing IP router

### SCHEMAT

### R1
![Alt text](image.png)
![Alt text](image-1.png)
![Alt text](image-2.png)
![Alt text](image-3.png)
![Alt text](image-20.png)

Router(config)#interface GigabitEthernet0/0/0
Router(config-if)#ip address 192.168.0.1 255.255.255.0
Router(config)#interface GigabitEthernet0/0/1
Router(config-if)#ip address 192.168.1.1 255.255.255.0
Router(config)#ip route 192.168.2.0 255.255.255.0 192.168.1.2
Router(config)#ip route 192.168.3.0 255.255.255.0 192.168.1.2
Router(config)#ip route 192.168.1.0 255.255.255.0 192.168.1.1


### R2
![Alt text](image-6.png)
![Alt text](image-7.png)
![Alt text](image-4.png)
![Alt text](image-5.png)

Router(config)#interface GigabitEthernet0/0/1
Router(config-if)#ip address 192.168.1.2 255.255.255.0
Router(config)#interface GigabitEthernet0/0/0
Router(config-if)#ip address 192.168.2.1 255.255.255.0
Router(config)#ip route 192.168.0.0 255.255.255.0 192.168.1.1
Router(config)#ip route 192.168.3.0 255.255.255.0 192.168.2.2

### R3
![Alt text](image-10.png)
![Alt text](image-11.png)
![Alt text](image-8.png)
![Alt text](image-9.png)

Router(config)#interface GigabitEthernet0/0/0
Router(config-if)#ip address 192.168.2.2 255.255.255.0
Router(config)#interface GigabitEthernet0/0/1
Router(config-if)#ip address 192.168.3.1 255.255.255.0
Router(config)#ip route 192.168.0.0 255.255.255.0 192.168.2.1
Router(config)#ip route 192.168.1.0 255.255.255.0 192.168.2.1

### SERWER
![Alt text](image-12.png)
![Alt text](image-14.png)
![Alt text](image-15.png)
![Alt text](image-17.png)
![Alt text](image-16.png)

### STACJA ROBOCZA
![Alt text](image-18.png)
![Alt text](image-19.png)


## testy ping 
![Alt text](image-21.png)
![Alt text](image-22.png)
![Alt text](image-23.png)
![Alt text](image-24.png)
![Alt text](image-25.png)


