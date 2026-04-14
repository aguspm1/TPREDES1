# TP1 de redes

## Integrantes:

- [Agustina Machaca](https://github.com/aguspm1)
- [Brian Pitz](https://github.com/ElYabran)
- [Milagros Llanos](https://github.com/moonstone3798)

## Preguntas:

### 1-¿Qué es una VLAN?

Una VLAN o Virtual LAN es una red lógica dentro de un switch que agrupa dispositivos sin importar su ubicación física, permitiendo organizar el tráfico como si estuvieran en redes distintas, mejorando así la seguridad y el rendimiento.

2-¿Qué es una VPN?
Una VPN es una tecnología que nos permite crear redes lógicas independientes dentro de la misma red física. Sirve para dividir una red en subredes y usarlas de forma diferente. Presenta como ventajas una mayor seguridad, segmentación, flexibilidad y optimización de la red
![VPN](https://cdn.hswstatic.com/gif/VPN.jpg)

3- ¿Qué es una SAN?
Enlazan unidades de almacenamiento de información y datos. son rápidas y están instaladas paralelamente con las redes Local

4-Diferencias entre Hub, Repetidor, Router y SWITCH. Explicar las diferencias.

Hub: replica todas las tramas por todos los puertos (dominio de colisión único).

Repetidor: regenera la señal eléctrica para extender distancia, no toma decisiones.

Switch: filtra y reenvía tramas según dirección MAC, crea dominios de colisión por puerto.

Router: conecta redes distintas, reenvía paquetes según dirección IP, aísla dominios de broadcast.

5- ¿Qué es un protocolo de comunicaciones?
Un protocolo es un conjunto de reglas, restriciones, procedimientos y formatos que definen el intercambio de paquetes para comunicar 2 o más nodos. Ambos nodos deben utilizar el mismo protocolo para que se puedan comunicar.

6- Explique TCP/IP y NetBios, resuma sus diferencias. (Acá sí explicar cada uno y sus diferencias)

TCP/IP: Es el conjunto de protocolos estándar de Internet. Se encarga del direccionamiento (IP) y de garantizar que los datos lleguen de forma confiable y ordenada (TCP). Es enrutable, lo que permite la comunicación entre redes distintas a nivel global.
NetBIOS: Es una interfaz o API antigua que permite a las aplicaciones en computadoras separadas comunicarse dentro de una red local (LAN). Se utilizaba principalmente para identificar equipos por nombres (ej: "PC-VENTAS"). No es enrutable por sí solo.
Diferencias: TCP/IP es escalable para redes globales y utiliza direcciones IP, mientras que NetBIOS está diseñado para redes pequeñas y utiliza nombres de hasta 15 caracteres.

7- ¿Cómo está formado un paquete de datos TCP/IP?¿Qué es un "flag" en un paquete TCP/IP?

Un paquete TCP/IP se forma con cabecera IP (origen/destino, TTL, etc.) más la cabecera TCP (puertos, número de secuencia, flags, ventana) y los datos. Un flag en TCP es un bit de control (ej. SYN, ACK, FIN, RST) que indica estado de la conexión, como inicio, confirmación o fin.

8- Defina la red según su geografía. Explicar distintas variantes
Una red puede categorizarse según su alcance a nivel geografico. Hay redes que conectan y permiten el transpaso de información entre nodos de distintos países, y redes de alcances más pequeños.
Ejemplos de categroizar la red por su alcance, pueden ser:
LAN (local area network): son redes chicas, hogareñas o de oficina, que son poco costosas y alta velocidad.
MAN (metropolitan area network): son redes medianas (varias LANS conectadas),que son mayormente administradas por el gobierno y provedores ISP. Son el nexo de interconexión entre las LAN y las WAN.
WAN (wide area network): son redes grandes que interconectan países o regiones.
WLAN (Wireless local area network): como una LAN pero inalámbrica.
CAN (campus area network): como una MAN pero de una región más chica.
PAN (personal area network): conectan y permiten la transferencia de datos entre los dispositivos de un mismo usuario.
SAN (storage area network): enlazan unidades de almacenamiento de información y datos. Son rápidas y están instaladas paralelamente con las redes locales

![redes según su geografía](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhcs0T1Px0YEGdjIKJk3YS89gf53DbkYIjqMv3c6kcHPoOutUg8SKy86Va8jb-XeMohMP6OSsT1lwGNS8DlHThbto_PWe3HyDi-x3VScuwdwxbNz6yXvHz3oopExfLUQZFggGag6qVfBxC4/s320/redmeh.png)

9- Defina una red según su topología. Explicar distintas variantes.
La topología de red es la disposición geométrica de los puntos de conexión (nodos) y los enlaces de datos en una red. Según el gráfico, las variantes son:
Bus: Todos los nodos están conectados a un medio de transmisión común (un solo cable). Es sencilla de instalar pero, si el cable central falla, toda la red queda inoperativa.
Estrella: Todos los nodos se conectan a un dispositivo central (hub o switch). Es la más común, ya que si un nodo falla, el resto de la red sigue funcionando.
Mixta: Es una combinación de dos o más topologías diferentes (por ejemplo, partes en estrella y partes en bus) para adaptarse a las necesidades de la infraestructura.
Anillo: Cada nodo se conecta exactamente con otros dos, formando una ruta continua única para las señales a través de cada nodo.
Doble Anillo: Similar a la de anillo, pero con un segundo anillo redundante que conecta los mismos dispositivos. Esto permite que la red siga funcionando si uno de los anillos falla.
Árbol: Tiene un nodo raíz del cual se desprenden otros nodos de forma jerárquica. Se asemeja a una serie de redes en estrella conectadas entre sí.
Malla: Los nodos están conectados entre sí de manera que existan varios caminos para los datos. No todos los nodos están conectados con todos, pero hay suficiente redundancia.
Totalmente Conexa: Es un caso especial de malla donde cada nodo tiene una conexión directa con todos los demás nodos de la red. Ofrece la máxima redundancia y velocidad, pero es la más costosa de cablear.

10- Explicar el servicio de DHCP.

El servicio DHCP (Dynamic Host Configuration Protocol) es el encargado de asignar automáticamente las direcciones IP, máscara, gateway y DNS a los dispositivos en una red, mediante un proceso DORA (Discover, Offer, Request, Ack), evitando configuraciones manuales.

11- Explicar el servicio de DNS.

DNS (sistema de nombres de dominios), es un sistema que traduce nombres de dominio en direcciones IP númericas (que sonas que usan los dispositivos para comunicarse entre sí en internet). Facilita la navegación y el acceso a servicios en línea sin tener que recordar los IP de los mismos. Además permite distribuir el tráfico entre varios servidores para mejorar el rendimiento de la página
![DNS](https://kinsta.com/es/wp-content/uploads/sites/8/2018/05/qu%C3%A9-es-dns.png)

12- Explicar las tecnologías Wireless, y sus estándares.

13- ¿Qué es proxy?

El proxy es el intermediario entre un cliente e internet que recibe peticiones, las reenvía y devuelve respuestas. Se usa para filtrado, caché, anonimato o control de acceso.

14- Explicar el protocolo Spanning tree
El protocolo spanning tree es un protocolo de capa 2 diseñado para evitar bucles lógicos en redes Ethernet con enlaces redundantes.Si un enlace falla STP habilita automáticamente una ruta bloqueada.
![Spanning tree](https://i.ytimg.com/vi/WjzyH2vLdsc/maxresdefault.jpg)

15- Explicar el protocolo de comunicaciones OSPF.

16- Explicar el protocolo ARP.

ARP (Address Resolution Protocol) resuelve direcciones IP a direcciones MAC en una red local. Cuando un dispositivo necesita una IP, este la pregunta por broadcast y el dueño responde con su MAC.

17- ¿Qué es un Firewall?
Un firewall es una herramienta de seguridad que actua como una barrera entre una red interna y una red externa. Controla y filtra el tráfico de red para prevenir accesos no autorizador y proteger la red interna de amenazas y ataques
![Firewall](https://exa.net.uk/wp-content/uploads/2021/06/What-is-a-firewall.png)

18- ¿Qué es una DMZ?
Una DMZ (Zona Desmilitarizada) es un segmento de red aislado que actúa como intermediario entre la red interna (segura) y la red externa (pública/Internet). Su proposito es alojar servidores que deben ser accesibles desde el exterior (Web, Mail, FTP) sin exponer directamente la red privada.Implementa una capa de protección adicional; si un atacante compromete un servidor en la DMZ, el firewall interno actúa como una segunda barrera para evitar que acceda a los recursos críticos de la organización.

19- ¿Qué es un gateway?

Un gateway es un nodo que actúa como puerta de enlace entre dos redes diferentes (ej. LAN a WAN o redes con distintos protocolos), permitiendo la comunicación. En las redes domésticas suele ser el router.

20- Según Microsoft, ¿qué significa NBL?
Según Microsoft NBL hace referencia a Net Buffer List (lista de búferes de red) en el contexto de controladores de red de Windows. Es una estructura de datos (compatible con hasta 32 equipos por clústerS) usada por el controlador NDIS para gestionar paquetes de red. Balancea cargas TCP/IP permitiendo agregar o quitar dinámicamente hosts para manejar los aumentos de tráfico.

21- Tipos de enlace: MPLS, LAN to LAN, microonda, VSAT.
a. Explique cada uno de estos tipos de enlace.
b. Agregue dos tipos de enlaces, no mencionados anteriormente.
c. Ranking de enlaces según lo pedido (de uno a seis, siendo uno el mejor): Por económico, performance, mayor capacidad, mayor o mejor configuración de restricciones, soporte a mayor distancia, menor esfuerzo de configuración.
d. Elija un tipo de enlace para los siguientes escenarios:
1 d. Conectividad de varios de call centers con un data center central.
2 d. Conectar los datos de los pozos petroleros durante 15 minutos por día.
3 d. Comunicar dos edificios enfrentados en la misma calle

22- Describir la tecnología LTE.

LTE (Long Term Evolution) es un estándar de comunicación móvil 4G de alta velocidad, basado en comunicación de paquetes todo IP, con bajas latencias y velocidades teóricas que pueden llegar hasta los 300 Mbps de descarga.

23- Explique la solución de Microsoft Teams. Si quieren describir otra solución de
otra empresa es también válido.

24- ¿Qué significa aplicar calidad en un enlace MPLS?
Aplicar calidad en MPLS se refiere a la implementación de QoS (Quality of Service) para gestionar y priorizar el tráfico de datos. En lugar de tratar todos los paquetes por igual, se utilizan etiquetas para clasificar el tráfico según su importancia o sensibilidad esto permite garantizar ancho de banda y reducir la latencia en servicios críticos en tiempo real , dándoles prioridad de paso sobre tráfico menos sensible .

25- ¿Qué diferencias puede encontrar entre una conexión Coaxial, UTP o Fibra?

Coaxial: núcleo de cobre con blindaje, hasta ~10 Mbps a 500m, sensible a interferencias.
UTP: pares trenzados sin blindaje, hasta 10 Gbps (Cat6a) a 100m, económico, susceptible a EMI.
Fibra: vidrio/plástico, transmisión por luz, >100 Gbps y km, inmune a EMI, más cara.

26- Según Cisco, ¿qué significa CCENT, CCNA y CCNP? Descripción breve del Track
Routing & Switching y de algún otro a elección (ej. Wireless, Security, Cloud, etc).
Según Cisco, las certificaciones representan distintos niveles de maestría en redes.
CCENT: era el nivel básico inicial que certificaba conocimientos fundamentales para puestos de soporte técnico y administración de redes básicas. Actualmente quedo unificada en el nuevo CCNA
CCNA: cetrificación de nivel asociado que cubre los fundamentos de redes
CCNP: certificaión de nivel profesional que requiere 3-5 años de experiencia. Valida la capacidad de implementar, configurar y solucionar problemas de redes corporativas complejas cableadas e inalámbricas.

27- Explique el modelo OSI.
El modelo OSI (del inglés Open Systems Interconnection o interconexión de sistemas abiertos) es un marco de trabajo conceptual que define cómo se comunican los sistemas de redes y cómo se envían datos de un remitente a un destinatario. El modelo se usa para describir los componentes de la comunicación de datos, para poder establecer reglas y estándares acerca de las aplicaciones y la infraestructura de red. El modelo OSI contiene siete capas que se apilan (conceptualmente) de abajo a arriba. Las capas OSI son:
física, enlace de datos, red, transporte, sesión, presentación y aplicación.
Física: Transmisión de bits por el medio físico (cables, señales).
Enlace: Direccionamiento físico (MAC) y detección de errores.
Red: Direccionamiento lógico (IP) y determinación de rutas (Routers).
Transporte: Transferencia de datos de extremo a extremo (TCP/UDP).
Sesión: Control de los diálogos y conexiones entre aplicaciones.
Presentación: Traducción, cifrado y compresión de datos.
Aplicación: Interfaz que utilizan los programas (HTTP, FTP, etc.).

28- Explicar el estándar IEEE 802.3 regula la red. Cómo se implementa, ventajas y desventajas.

IEEE 802.3 define Ethernet (redes LAN cableadas). Se implementa con CSMA/CD (hoy full-dúplex) en UTP, fibra o coaxial. Ventajas: simple, económico, escalable. Desventajas: distancia limitada por tramo (100m en UTP), colisiones en half-dúplex obsoleto.

29- Explicar el estándar IEEE 802.4 regula la red.
El estándar IEEE 802.4 (token bus), regula una red local LAN que utiliza una topología física de bus pero con una lógica de paso de tokens para controlar el acceso al medio. Solo la estación que posee tokens puede transmitir datos

30- ¿Qué protocolos se usan para enviar y recibir correo?

Los protocolos que se usan son: POP recibe correo, SMTP envía correo.

31- ¿Qué protocolo puede usarse para leer correo recibido?

POP3 (Post Office Protocol v3) descarga correos del servidor al cliente eliminándolos del servidor, o IMAP (Internet Message Access Protocol) mantiene los correos en el servidor, permitiendo sincronización entre múltiples dispositivos.

32- Diferencias entre IPV4 e IPV6
IPV4: consta de 32 bits. cada grupo de bits, expresa entre 0-255 valores. Y se separan por puntos
IPV6: consta de 182 bits. Cada grupo de bits se expresa en hexadecimal.

33- Brian:

Tengo algo de experiencia en redes, básica dentro de todo pero es algo. Entro en el panel de configuración del router de mi casa, la red de mi departamento y de la casa de mis padres la configure yo, y en esta ultima también con repetidores de señal. Con amigos mas de una vez hemos creado redes LAN. Y por último el año pasado en un curso sobre ciber seguridad vi, estudié y trabajé con los protocoles de red.
