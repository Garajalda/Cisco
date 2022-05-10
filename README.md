# Cisco
## Fundamentos de redes
### Componentes de red
1. Rol de host
2. Rol de host en redes p2p
3. Dispositivos de red intermedios (switches, puntos de acceso inalámbricos, routers, firewalls...)
4. AP inalámbricos
5. Categorías de APS
6. Los medios de red: Cableados e Inalámbricos
### Dispositivos de seguridad
1. Componentes de red enfocados a la seguridad: Servidores VPN, ASA, IDS/IPS, ESA/WSA, AAA
### Redes jerárquicas
1. Cisco Borderless Networks.
2. Modelos de diseño jerárquicos de redes de campus: Modelo tres capas y dos capas.
3. Funciones de cada capa: Capa de acceso, capa de distribución, capa de nucleo.
### Clasificación de las redes según el tamaño
1. Modelos de clasificación: Área geográfica, cantidad de usuarios, tipos de servicios, área de responsabilidad que cubre dicha red.
2. Internet y entidades.
3. LAN vs WAN
### La capa física
1. Conectividad física: NIC (cableadas o inalámbricas)
2. Funciones de la capa física: transportar bits...
3. Estándares de la capa física: Componentes físicos, codificación (Manchester, NRZ, 4B/5B), estándares (EIA/TIA, ISO, ITU, IEEE) y señalización (Represe.ntación de bits). 
4. Parámetros físicos: Latencia, Rendimiento, Capacidad de transferencia util.
### Medios de cobre
1. Mitigación de problemas en medios de cobre: Atenuación, EMI y RFI, Diafonía.
2. Clasificación de par trenzado: UTP, FTP, STP, SFTP.
3. Categoría de cableado EIA/TIA
4. Cableado coaxial
### Características de la fibra óptica
1. Tipos de fibra óptica: Monomodo, multimodo.
2. Dispersión de fibra óptica.
3. Usos de la fibra óptica.
4. Conectores de fibra óptica.
5. Cables de conexión: SM SC-SC, SM LC-LC, MM ST-SC
6. Comparación de fibra y cobre.
### Medios inalámbricos
1. Limitaciones de los medios inalámbricos: Área de cobertura, interferencia, seguridad, funcionamiento half-duplex.
2. Estándares de capa física de wlan.
### Direcciones IPV4
1. Parte de red y parte de host.
2. Longitud de prefijo, máscara de subred.
3. Direcciones de red y de broadcast.
### Tipos de direcciones IPV4 según destinatario
1. Unicast
2. Multicast
3. Broadcast
### Direccionamiento privado
1. Tipos de direcciones: Públicas y privadas (RFC 1918)
2. Direcciones privadas y NAT
3. Direcciones loopback.
4. Direcciones de enlace local (APIPA)
### Clases en direccionamiento IPV4
1. RFC 790
2. Entidades responsables del direccionamiento IPV4
### Segmentación de redes
1. Dominios de broadcast
2. Segmentación de los dominios de broadcast
### Planteamiento del problema de la división en subredes
### Ejercicios de división de subredes
### VLSM
### Agotamiento del direccionamiento IPV4
1. Situación del espacio de direccionamiento IPV4
2. Coexistencia de IPV4 e IPV6
3. Técnicas de migración: Dual stack, Tunneling, Translation.
### Estructura de una dirección IPV6
1. Formato de una dirección IPV6
2. Reglas en direcciones IPV6
3. Ambigüedad en el uso de ::
### Tipos de direcciones IPV6
1. Configuración estática de direcciones GUA y LLA
2. Configuración estática GUA en un router
3. Configuración estática LLA en un router
4. Configuración estática GUA en un host windows
### Configuración dinámica de direcciones GUA
1. Mensajes ICMPv6 RS y RA
2. Métodos para configurar dinámicamente una GUA: SLAAC, SLAAC con servidor DHCPv6 stateless, Stateful DHCPv6 (no SLAAC)
3. Generación de id de interfaz
4. Id de interfaz generado mediante EUI-64
5. Id de interfaz generado aleatoriamente (Windows)
### Configuración dinámica de direcciones LLA
1. Direcciones LLA dinámicas en windows
2. Direcciones LLA dinámicas en routers
### Multicast en IPv6
1. Prefijo de direcciones de multicast IPV6: FF00::/8, dirección de red multicast conocida y de nodo solicitado.
### Subredes en IPv6
### Funciones de la capa de transporte
### TCP
1. Características de TCP.
2. Cabecera de un segmento TCP.
3. Servicios y aplicaciones que usan TCP.
### UDP
1. Características de UDP.
2. Cabecera UDP.
3. Servicios y aplicaciones que usan UDP
### Números de puerto
1. Utilidad de los números de puerto.
2. Socket.
3. Rangos de números de puertos.
4. Ejemplos de números de puertos.
5. Verificación de sockets (NETSTAT).
### Sesiones TCP
1. Servicios y puertos.
2. Establecimiento de una conexión TCP
3. Finalización de una conexión TCP
4. Protocolo Three way handshake
### Comunicación UDP
1. Confiabilidad de UDP
2. Reensamblado de datos en UDP
### Tecnologías inalámbricas
1. Tipos de redes inalámbricas
2. Tecnologías wimax y bluetooth
3. Tecnologías de banda ancha celular y satelital
4. Tecnologías IEEE 802.11
5. Bandas de frecuencias en las que operan las normas de IEEE 802.11
### Componentes de una WLAN
1. WLC
2. Antenas
### Funcionamiento de una WLAN
1. Tipologías inalámbricas 802.11
2. Conjuntos de servicios
3. Trama 802.11
4. CSMA/CA
5. Asociación de un cliente a un AP
6. Modo de entrega activa y pasiva
### CAPWAP
1. Protocolo CAPWAP
2. Tuneles en capwap
3. Arquitectura split mac
4. Cifrado dtls
5. flexconnect
### Gestión de canales
1. Uso de los canales de modo eficiente
2. Selección de canales a 2,4 gHz
3. Selección de canales 5 gHz
### Seguridad en WLANS
1. Técnicas elementales de protección
2. Autenticación en IEEE 802.11
3. Profundización en la seguridad de las redes WLAN
### Computación en la nube
1. Aspectos fundamentales de la computación en la nube
2. Servicios en la nube
3. Tipos de nubes
4. Computación en la nube y centros de datos
### Virtualización
1. Computación en la nube y virtualización
2. Servidores dedicados
3. Virtualización de servidores
4. Capas de abstracción
5. Ventajas de la virtualización de servidores
### Hypervisores
1. Tipos de hypervisores: Bare-metal, Hypervisor alojado.
2. Administración de hypervisor de tipo 1
3. Ejemplos de hypervisor de tipo 2.
### Virtualización de los servicios de red
1. La complejidad de la virtualización de red.
2. Flujos de tráfico en una arquitectura virtualizada
3. Virtualización de funciones de red: (Subinterfaces, Interfaces virtuales, VLAN, VRFs)
### Direcciones MAC
1. Asignación de una dirección mac a un dispositivo
2. Procesamiento de tramas
3. Tipos de direcciones MAC (Unidifusión, Multidifusión, Difusión)
### Tabla MAC de un switch
1. Modo de funcionamiento de un switch
2. Aprendizaje y reenvio de un switch
### Conmutación en un switch
1. Métodos de conmutación
2. Gestión de memoria en los switches
3. Velocidad y duplex
4. Auto-mdix
## Prácticas de fundamentos de redes
### Práctica de la conectividad física en packet tracer. 
### Realización de redes IPv4 e IPv6 con PacketTracer y a papel
### Simular comunicaciones de capa de transporte Packet Tracer
## Acceso a la red
