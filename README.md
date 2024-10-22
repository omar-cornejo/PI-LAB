
# PI LAB

### Comandos básicos

**Asignar IP:** ifconfig interface "interface" "direccion IP" netmask "netmask"

**Añadir red:** route add -net "red" netmask "netmask" gw "gw"

**Eliminar red:** route del -net "red" netmask "netmask" gw "gw"

**Ver tabla arp:** arp

**Asignar dirección hw a dirección IP:** arp -s "direccion IP" "direccion hw"

**Eliminar dirección IP:** arp -d "direccion IP"

**Enviar traza ICMP:** ping "direccion IP"

**Ver tracreroute: tracreroute "option:** (common -ni)" "direccion IP"

**Escuchar interface:** tcpdump "interface"

**- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -**

### Configurar router

**Cambiar a modo privilegiado:** enable

**Cambiar a modo configuración:** configure terminal

**Seleccionar interfaz:** interface "interface"

**Establecer contraseña para modo privilegiado:** enable password "password"

**Establecer conexiones virtuales:** line vty "min" "max"

**Establecer contraseña Telnet/SSH:** password "password"

**Salir del modo actual:** exit

**Asignar la dirección IP y la máscara de subred:** ip address "dirección IP" "netmask"

**Habilitar la interfaz (si está deshabilitada):** no shutdown

**Resumen estado interfaces de red:** show ip interface brief

**Creación VLAN:** vlan "vlan-id"

**Asignar un nombre a la VLAN:** name "name"

**Mostrar información VLAN:** show vlan "vlan id"

**Configurar una interfaz en modo trunk:** switchport mode trunk

**Configurar una interfaz en modo acceso:** switchport access vlan "vlan-id"

**Mostrar configuración interfaz específica:** show running-config interface "interface-id"

**Mostrar la tabla de direcciones MAC:** show mac-address-table

**Activar STP en VLAN:** spanning-tree vlan "vlan-id"

**Configurar costo camino al (Root Bridge):** spanning-tree vlan "vlan-id" cost "cost"

**Establecer prioridad del puerto para VLAN específica:** spanning-tree vlan "vlan-id" port-priority "priority"

**Mostrar estado STP VLAN especificada:** show spanning-tree vlan "vlan-id"
