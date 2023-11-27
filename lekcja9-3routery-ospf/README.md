# lekcja 9-3routery-ospf

## SCHEMAT
![Alt text](image-4.png)


## R1
![Alt text](image-2.png)
![Alt text](image-3.png)


R1#conf t
Enter configuration commands, one per line. End with CNTL/Z.
R1(config)#
R1(config)#router ospf 10
R1(config-router)#network 192.168.5.0 ?
A.B.C.D OSPF wild card bits
R1(config-router)#network 192.168.5.0 0.0.0.255 ?
area Set the OSPF area ID
R1(config-router)#network 192.168.5.0 0.0.0.255 area ?
OSPF area ID as a decimal value
A.B.C.D OSPF area ID in IP address format
R1(config-router)#network 192.168.5.0 0.0.0.255 area 0
R1(config-router)#network 10.1.1.0 0.0.0.3 area 0
R1(config-router)#end

## R2

## R3

## SERVER DNS
![Alt text](image-5.png)
![Alt text](image-6.png)
![Alt text](image-7.png)

## SERVER HTTP

## STACJA ROBOCZA
![Alt text](image.png)
![Alt text](image-1.png)

## PINGI 

## FINAL WP.PL