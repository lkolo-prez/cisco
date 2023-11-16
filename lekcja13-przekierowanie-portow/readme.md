# schemat
![Alt text](image-5.png)

# switch
![Alt text](image-6.png)
![Alt text](image-7.png)

## komendy do VLANów

```
configure terminal
vlan 10
name 10

vlan 20
name 20

interface FastEthernet0/1
switchport mode access
switchport access vlan 10 
interface FastEthernet0/2
switchport mode access
switchport access vlan 20 

interface GigabitEthernet0/1
switchport mode trunk
```

## pc 1
![Alt text](image.png)

## pc 2
![Alt text](image-1.png)

## pc 3
![Alt text](image-2.png)

## pc 4
![Alt text](image-3.png)


# pingi
## bez vlanów 
![Alt text](image-4.png)

## z vlanmia

