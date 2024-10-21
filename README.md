
# PI LAB

### Comandos básicos

**Assignar IP:** ifconfig interface <interface> <direccion Ip> netmask <netmask>

**Añadir red:** route add -net <red> netmask <netmask> gw <gw>

**Eliminar red:** route del -net <red> netmask <netmask> gw <gw>

**Ver tabla arp:** arp

**Asignar dirección hw a dirección IP:** arp -s <direccion IP> <direccion hw>

**Eliminar dirección IP:** arp -d <direccion IP>

**Enviar traza ICMP:** ping <direccion IP>

**Ver tracreroute:** tracreroute <option: (common -ni)> <direccion IP>

**Escuchar interface:** tcpdump <interface>

**- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -**

### Configurar router

**:** enable

**:** configure terminal

**:** interface <interface>
 
 **:** enable password cisco

 **:** line vty 0 4

 **:** password cisco

 **:** exit

 **:** ip addres @ip mask

 **:** no shutdown

 **:** show ip interface brief

 **:** enable

 **:** vlan vlan-id

 **:** name name
 
 **:** show vlan id 

 **:** switchport mode trunk

 **:** switchport acces vlan

 **:** show running-config <interface>

 **:** show mac-address-table

 **:** spanning-tree vlan <vlan-id>

 **:** spanning-tree <vlan vlan-id> cost cost
 
 **:** spanning-tree <vlan vlan-id> port-priority priority

 **:** name name
