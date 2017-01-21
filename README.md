# Redes-Locales
La configuracion que tiene el archivo es la siguiente:
- Primera Red
 * Tiene un router con 2 ip una se dirije a los routers y la otra a los ordenadores/servidores
 * IP hacia los routers 10.0.0.1/8
 * IP hacia los ordenadores 192.168.0.166/29
 * Rip por las dos redes que van al router 192.168.0.0 y 10.0.0.0
 * Tiene un servidor Web en la ip 192.168.0.165/29 y conectado con un servidor DNS a la url www.albacete.es
 * Tiene tres subredes conectadas al switch
 * 1ª Subred 192.168.0.0/25 126 Host conectada a cuatro ordenadores
 * 2ª Subred 192.168.0.128/27 30 Host conectada a cuatro ordenadores
 * 3ª Subredes 192.168.0.160/29 6 Host conectada a cuatro ordenadores
 * Solo la tercera puede salir

- Segunda Red
 * Tiene un router con 3 ip una se dirije a los routers y la otra a los ordenadores/servidores
 * IP hacia los routers 10.0.0.2/8 y 11.0.0.1/8
 * IP hacia los ordenadores 192.168.1.254/29
 * Rip por las tres redes que van al router 192.168.1.0 , 10.0.0.0 y 11.0.0.0
 * Tiene un servidor Web en la ip 192.168.1.1/29 y conectado con un servidor DNS a la url www.wagner.de
 * Ese servidor actua como DNS reconociendo los dominios www.albacete.es, www.wagner.de, www.dilar.com
 * El servidor tambien actua como DHCP asignado ips desde la 192.168.1.10 hasta la 192.168.1.253
 * Switch Conectada a ocho ordenadores y un servidor

