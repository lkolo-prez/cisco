# lekcja 9-3routery-ospf

## SCHEMAT
![Alt text](image-4.png)


## R1
![Alt text](image-2.png)
![Alt text](image-3.png)


Router> enable
Router# configure terminal
Router(config)# router ospf 1
network 192.168.0.0 0.0.0.255 area 0
network 192.168.1.0 0.0.0.255 area 0
network 192.168.2.0 0.0.0.255 area 0
network 192.168.3.0 0.0.0.255 area 0
exit


## R2
![Alt text](image-11.png)
![Alt text](image-12.png)

enable
configure terminal
router ospf 1
network 192.168.0.0 0.0.0.255 area 0
network 192.168.1.0 0.0.0.255 area 0
network 192.168.2.0 0.0.0.255 area 0
network 192.168.3.0 0.0.0.255 area 0
exit

## R3
![Alt text](image-13.png)
![Alt text](image-14.png)
enable
configure terminal
router ospf 1
network 192.168.0.0 0.0.0.255 area 0
network 192.168.1.0 0.0.0.255 area 0
network 192.168.2.0 0.0.0.255 area 0
network 192.168.3.0 0.0.0.255 area 0
exit

## SERVER DNS
![Alt text](image-5.png)
![Alt text](image-6.png)
![Alt text](image-7.png)

## SERVER HTTP
![Alt text](image-8.png)
![Alt text](image-9.png)
![Alt text](image-10.png)

## STACJA ROBOCZA
![Alt text](image.png)
![Alt text](image-1.png)

## PINGI 
![Alt text](image-15.png)
![Alt text](image-16.png)

## FINAL WP.PL
![Alt text](image-17.png)
![Alt text](image-18.png)
