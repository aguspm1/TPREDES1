3- ¿Qué es una SAN?
Enlazan unidades de almacenamiento de información y datos. son rápidas y están instaladas paralelamente con las redes Local

6- Explique TCP/IP y NetBios, resuma sus diferencias. (Acá sí explicar cada uno y sus diferencias)

TCP/IP: Es el conjunto de protocolos estándar de Internet. Se encarga del direccionamiento (IP) y de garantizar que los datos lleguen de forma confiable y ordenada (TCP). Es enrutable, lo que permite la comunicación entre redes distintas a nivel global.
NetBIOS: Es una interfaz o API antigua que permite a las aplicaciones en computadoras separadas comunicarse dentro de una red local (LAN). Se utilizaba principalmente para identificar equipos por nombres (ej: "PC-VENTAS"). No es enrutable por sí solo.
Diferencias: TCP/IP es escalable para redes globales y utiliza direcciones IP, mientras que NetBIOS está diseñado para redes pequeñas y utiliza nombres de hasta 15 caracteres.


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


12- Explicar las tecnologías Wireless, y sus estándares. 

15- Explicar el protocolo de comunicaciones OSPF. 

18- ¿Qué es una DMZ? 
Una DMZ (Zona Desmilitarizada) es un segmento de red aislado que actúa como intermediario entre la red interna (segura) y la red externa (pública/Internet). Su proposito es alojar servidores que deben ser accesibles desde el exterior (Web, Mail, FTP) sin exponer directamente la red privada.Implementa una capa de protección adicional; si un atacante compromete un servidor en la DMZ, el firewall interno actúa como una segunda barrera para evitar que acceda a los recursos críticos de la organización.


21- Tipos de enlace: MPLS, LAN to LAN, microonda, VSAT.
a. Explique cada uno de estos tipos de enlace. 
b. Agregue dos tipos de enlaces, no mencionados anteriormente. 
c. Ranking de enlaces según lo pedido (de uno a seis, siendo uno el mejor): Por económico, performance, mayor capacidad, mayor o mejor configuración de restricciones, soporte a mayor distancia, menor esfuerzo de configuración. 
d. Elija un tipo de enlace para los siguientes escenarios: 
1 d. Conectividad de varios de call centers con un data center central. 
2 d. Conectar los datos de los pozos petroleros durante 15 minutos por día. 
3 d. Comunicar dos edificios enfrentados en la misma calle
 
24- ¿Qué significa aplicar calidad en un enlace MPLS? 
Aplicar calidad en MPLS se refiere a la implementación de QoS (Quality of Service) para gestionar y priorizar el tráfico de datos. En lugar de tratar todos los paquetes por igual, se utilizan etiquetas para clasificar el tráfico según su importancia o sensibilidad esto permite garantizar ancho de banda y reducir la latencia en servicios críticos en tiempo real , dándoles prioridad de paso sobre tráfico menos sensible .



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



30- ¿Qué protocolos se usan para enviar y recibir correo? 

Los protocolos que se usan son: POP recibe correo, SMTP envía correo.
