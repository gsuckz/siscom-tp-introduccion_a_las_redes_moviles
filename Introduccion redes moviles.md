# Introduccion Redes Moviles 

## Introducción
El presente informe para la materia Sistema de Comunicaciones tiene como objetivo principal  acercarnos a uno de los ejes temáticos que propone la cátedra como son  las redes móviles. 
Las redes móviles en la actualidad comprenden un vasto conjunto de sistemas, que en algunos casos quedaron en desuso/obsoletos. Por lo tanto, en este informe haremos un abordaje introductorio sobre el tema, centrándonos en un grupo específico de tecnologías.
 



## Metodología
La metodología de trabajo que se empleó consistió en la recopilación de información acerca de los temas propuestos para luego realizar una selección de la misma haciendo foco en la fiabilidad de las fuentes para finalmente poder asegurar el uso de información de calidad para la elaboración del informe  

## Movilidad y Redes Móviles
Aquí presentarán el concepto de movilidad y discutirán que hace que una red pueda denominarse red móvil. Indicarán las partes de una red móvil y las funciones de red necesarias para implementar la movilidad. Deben citar las fuentes bibliográficas empleadas.

En la actualidad, la movilidad es una de las piezas fundamentales para el estilo de vida moderno en el  mundo que vivimos. Durante todo el día, desde que despertamos  hasta incluso durante nuestro descanso poseemos cerca dispositivos electrónicos que forman parte de nuestras rutinas. 
Esto no fue siempre así, solo con retroceder un par de décadas podemos recordar que las comunicaciones en general tenían como  sustento principal las conexiones cableadas entre dispositivos, lo cual resultaba  en una movilidad limitada para el establecimiento de comunicación.


En este contexto , se puede introducir el concepto de movilidad como la capacidad que posee un dispositivo electrónico para mantener la conexión entre la red y él mismo mientras se encuentra desplazándose en el espacio.
Pero este espacio en donde puede desplazarse un dispositivo y establecer una conexión debe estar dentro del área de la cobertura de la red.
Al igual que las redes fijas cableadas, las redes móviles ofrecen transmisión de datos pero mediante conexiones inalámbricas. Dichas redes tienen una componente radio, pero también tienen una gran parte de infraestructura fija para poder ofrecer todo tipo de servicios. Cada vez que aparece una nueva generación, tiene una mayor capacidad de forma que puede satisfacer requisitos cada vez más complejos.

### Estructura de una red móvil

La conectividad de los teléfonos móviles se consigue gracias a los recursos de telecomunicaciones radio y su funcionamiento se basa en los procedimientos de las redes de telefonía fija.
Uno de los principios más fundamentales aplicados en los modernos sistemas de telecomunicaciones móviles se basa en la división del territorio en áreas parciales más pequeñas denominadas como celdas, que están siempre gestionadas por una estación base concreta
El tamaño de las celdas utilizadas en los diversos sistemas móviles depende principalmente del tipo y el propósito del sistema móvil y se pueden clasificar como sigue:
femtoceldas (pisos u oficinas): destinado a cubrir áreas que reciben un señal de baja calidad de otras celdas. En general el área de cobertura de las femtoceldas tiene un radio de varios metros.
picocelda (oficina y área residencial): El margen de cobertura de esta señal es de pocas decenas de metros.
microceldas (áreas urbanas con gran densidad de población): destinado principalmente a usuarios con movimiento lento ( peatones o  auto en tráfico urbano). La cobertura de una sola microcelda es de pocas centenas de metros.
macroceldas (áreas grandes y escasamente pobladas): principalmente orientadas a usuarios en movimiento con alta velocidad (autos en ruta ). El radio del área de cobertura máxima es de unos pocos kilómetros.
Celda satelital (área accesible por satélite de telecomunicaciones): permite la conexión en lugares inaccesibles para los tipos de células anteriores. El alcance de la señal depende de la posición relativa de los satélites y de los parámetros de transmisión y recepción de los dispositivos.

La forma de las celdas que se emplean en  redes móviles es hexagonal, y se debe básicamente a una mayor eficiencia en el cubrimiento de las áreas.
Si tomamos como ejemplo una forma circular para la celda, observaremos que es posible que una pequeña área quede sin cobertura ó que se produzca un solapamiento en las áreas de cobertura de cada una de las celdas. 

En general podemos decir que una red de comunicaciones móviles se compone por:
#### Estaciones móviles (MS - Mobile Station): 
    son los equipos que suministran el servicio de comunicación concreto a los usuarios en el lugar, instante y formato adecuados. Cada estación móvil ( teléfonos celulares) puede actuar en modo emisor, receptor o en ambos modos. Cuando una MS establece comunicación con una estación base (BTS), la señal transmitida por la MS y recibida por la BTS se llama enlace de subida (UL: UpLink).
    Los teléfonos celulares cuentan con transmisores de RF de baja potencia, normalmente de entre 0,6W a 3W.. La estación central típicamente también transmite a bajo potencia, esto para que las transmisiones de una celda no salgan de su alcance e interfieran con otra. Esto hace posible que una celda contigua pueda reutilizar las mismas frecuencias por célula para dar el servicio. La baja potencia de transmisión también permite el contar con dispositivos móviles ligeros y compactos.

#### Estación base (BTS - Base Telephone Station): 
    se encargan de mantener el enlace radioeléctrico entre la MS y la estación de control de servicio durante la comunicación. Cuando una BTS establece comunicación con una estación móvil (MS), la señal transmitida por la BTS y recibida por la MS se llama enlace de bajada (DL: DownLink).
    Cada conjunto de celdas tiene su estación base, que está ubicada en el territorio de una célula. La célula donde se encuentra la estación base más las 6 células a la vuelta de la misma conforman un “clúster de células”. Una estación base está conformada por una torre y un pequeño edificio donde se tiene el equipo de telecomunicaciones. Todas estas estaciones base son manejadas desde centrales telefónicas que controlan todas las estaciones y también las conectan con la red de telefonía fija. Estas estaciones centrales se llaman centros de conmutación de telefonía móvil ( MTSO  siglas en inglés). En zonas urbanas hay estaciones base separadas entre 1 y 3 km, y en áreas rurales pueden llegar a separarse más de 35km.
    Una ciudad puede llegar a tener cientos de torres emisoras, pero pese a esto los costos de estas infraestructuras son bajos debido a la gran cantidad de gente que usa los servicios celulares.

#### Estaciones de control ( BSC - Base Station Control): 
    realiza las funciones de gestión y mantenimiento del servicio de comunicación. Su función principal es interconectar a las estaciones base de la región.

#### Centros de conmutación (MSC - Mobile Service Switching Center):
     permiten la conexión entre las redes públicas y privadas con la red de comunicaciones móviles, así como la interconexión entre estaciones móviles de control localizadas en distintas áreas geográficas de la red móvil, terminando de conectar todos los elementos que conforman un sistema de comunicaciones de telefonía celular.


## Redes de Acceso
Aquí presentarán el concepto de Red de Acceso. Discutirán los distintos tipos de red de acceso, sus características, ventajas y desventajas. Deben citar las fuentes bibliográficas empleadas.
Las redes de acceso para redes móviles son los sistemas y tecnologías que permiten a los dispositivos móviles conectarse y acceder a los servicios de comunicación ofrecidos por los operadores de redes móviles. Estas redes son la infraestructura subyacente que posibilita la conectividad de dispositivos móviles, como teléfonos inteligentes, tabletas y dispositivos IoT (Internet de las cosas), a la red de comunicaciones.
Existen varias tecnologías de acceso utilizadas en redes móviles, cada una diseñada para proporcionar diferentes niveles de velocidad, cobertura y capacidad. Algunas de las tecnologías de acceso más comunes incluyen:
GSM (Sistema Global para Comunicaciones Móviles): Una de las primeras tecnologías de acceso utilizadas en redes móviles, que proporciona servicios de voz y datos a través de conexiones inalámbricas.

El lanzamiento del sistema GSM fue realizado en distintas fases, dado que las especificaciones no fueron finalizadas en el tiempo establecido. Cada fase fue introduciendo mejoras y nuevos servicios basándose en la anterior.

En GSM las aplicaciones básicas operan en la banda de 900 MHz. El incremento del tráfico de datos dio lugar al desarrollo de otras versiones con múltiples bandas de frecuencia. Así pues, hay tres estándares, que difieren principalmente en el rango de frecuencia utilizado y en el número de canales asignados: GSM 900 ( banda de frecuencias de 900 MHz, capacidad máxima de 2 × 124 canales, ancho de banda de 2 × 25 MHz), GSM 1800 (banda de frecuencia de 1800 MHz, capacidad máxima de 2 × 374 canales, ancho de banda de 2 × 75 MHz), GSM 1900 ( banda de frecuencias de 1900 MHz, capacidad máxima de 2 ×298 canales, ancho de banda de 2 × 75 MHz)














### UMTS (Sistema Universal de Telecomunicaciones Móviles): Una evolución de GSM que ofrece velocidades de datos más altas y una mayor capacidad de red.

	Las bandas de frecuencia de funcionamiento de sistema UMTS están dispuestas alrededor de 2 GHz, lo cual garantiza características razonables de transmisión, baja atenuación de señal y fácil penetración de la señal en edificios (indoor). Las bandas de frecuencia asignadas dependen de si UMTS opera usando duplexación por división de tiempo (Time Division Duplex, TDD) o en duplexación por división de frecuencia (Frequency Division Duplex, FDD).





### LTE (Evolution Long-Term Evolution): También conocido como 4G LTE, es una tecnología de acceso de banda ancha móvil que proporciona velocidades de datos significativamente más rápidas que las tecnologías anteriores.

    LTE se define en la Release 8 y 9 de 3GPP. A diferencia de UMTS, LTE utiliza acceso OFDMA y SC-FDMA (Single Carrier
    OFDMA) para los enlaces descendente y ascendente respectivamente en lugar de WCDMA, utilizada en UMTS. Por lo tanto, las características de transmisión son muy diferentes si las comparamos con UMTS. Sin embargo, LTE está
    considerado como parte de los sistemas 3G, ya que no cumple con los requisitos definidos por la ITU para las redes 4G. El primer estándar clasificado como 4G es LTE-A (Long Term Evolution - Advanced) estandarizado en junio de 2011de
    acuerdo con la Release 10 de3GPP. Es la evolución del anterior LTE definido en las Release 8 o 9 y basado en los mismos principios que ambas versiones de LTE, pero está alineado con el conjunto de requisitos definidos por la ITU y conocidos como IMT-Advanced. En comparación con LTE, LTE-A introduce agregación de portadora, coordinación de la interferencia entre celdas, o mejoras en la
    transmisión de múltiples antenas (MIMO).







### 5G (Quinta Generación de Tecnología Móvil): La última generación de tecnología móvil que promete velocidades ultra rápidas, menor latencia y una mayor capacidad de red para admitir una variedad de aplicaciones emergentes, como IoT, realidad virtual y aumentada, y comunicaciones críticas.

    La primera especificación a partir de diciembre del 2017 se limita a la operación NR no autónoma (non-standalone), que implica que los dispositivos NR se basan en LTE para el acceso inicial y la movilidad. Es decir, el dispositivo solo puede operar en la interfaz NR si a la vez está conectado en otra banda a LTE (principalmente para canales de control). La especificación 15 final también soporta el funcionamiento independiente, conocido como standalone. La diferencia entre el autónomo y no autónomo afecta principalmente a las capas superiores y la interfaz al núcleo de red; la tecnología radio es la misma

##### BIBLIOGRAFIA
1.  M. Sauter, "From GSM to LTE: An Introduction to Mobile Networks and Mobile
Broadband" Wiley, 2011.
Zdenek Becvar, Pavel Mach, Ivan Pravda, “Redes Móviles”
Antonio Satué Villar, “Comunicaciones sin hilo”,2019

## Evolución de las Redes de Acceso Radioeléctrico
La evolución de las redes de acceso radioeléctrico ha sido significativa en las últimas décadas, impulsada por avances tecnológicos, demanda creciente de servicios de comunicación y la necesidad de mayor velocidad y eficiencia en la transmisión de datos. Aquí está un desarrollo detallado de esta evolución:

#### Redes 1G (Primera Generación): 
Las redes de primera generación (1G) marcaron el comienzo de la telefonía móvil y la comunicación inalámbrica a gran escala. La primera implementación comercial significativa de estas redes comenzó en la década de 1980 y se basaba principalmente en tecnologías analógicas, como AMPS (Advanced Mobile Phone System) en América del Norte y NMT (Nordic Mobile Telephone) en Europa. Las redes 1G permitían la comunicación telefónica móvil a través de estaciones base que utilizaban modulación de amplitud y frecuencia para transmitir señales analógicas. Sin embargo, estas redes tenían limitaciones significativas en términos de capacidad, calidad de voz y seguridad de la comunicación.
 
#### Redes 2G (Segunda Generación): 
Las redes 2G, como GSM (Global System for Mobile Communications) y CDMA (Code Division Multiple Access), marcaron el inicio de la telefonía móvil digital. Estas redes permitían la transmisión de voz y mensajes de texto, pero con velocidades limitadas para la transmisión de datos, principalmente utilizadas para SMS.
 
#### Redes 3G (Tercera Generación): 
La introducción de las redes 3G representó un avance significativo al permitir la transmisión de datos a velocidades más altas, lo que habilitó servicios como la navegación web móvil, correos electrónicos y aplicaciones más básicas. Tecnologías como UMTS (Universal Mobile Telecommunications System) y CDMA2000 mejoraron la capacidad y la velocidad de las conexiones inalámbricas.
 
#### Redes 4G (Cuarta Generación): 
La llegada de las redes 4G, basadas en tecnologías como LTE (Long-Term Evolution) y WiMAX (Worldwide Interoperability for Microwave Access), revolucionó la comunicación móvil al ofrecer velocidades de datos mucho más rápidas. Esto permitió la transmisión de video de alta definición, aplicaciones en tiempo real y servicios de comunicación más avanzados.
 
#### Redes 5G (Quinta Generación): 
Actualmente, la evolución más reciente es la implementación de redes 5G, que representan un salto significativo en términos de capacidades y funcionalidades. Algunas de las características clave de 5G incluyen:

    - Mayor ancho de banda: Ofrece velocidades de descarga y carga mucho más rápidas, lo que permite la transmisión de contenido de alta calidad en tiempo real.
     Menor latencia: La latencia reducida facilita aplicaciones que requieren respuestas instantáneas, como juegos en línea, telemedicina y vehículos autónomos.
    - Mayor densidad de dispositivos conectados: 5G puede soportar una mayor cantidad de dispositivos conectados simultáneamente, lo que es crucial para el desarrollo de la IoT y la conectividad masiva de dispositivos.
    - Mayor eficiencia energética: Las redes 5G están diseñadas para ser más eficientes en el uso de energía, lo que es beneficioso tanto para los operadores como para los usuarios finales. 

En síntesis podemos decir que evolución de las redes de acceso radioeléctrico:
Se refiere a cómo han evolucionado las tecnologías de transmisión inalámbrica utilizadas para conectar dispositivos móviles a las redes de telecomunicaciones.
Comenzó con las redes de primera generación (1G), que eran principalmente analógicas y se centraban en servicios de voz.
Luego, las redes de segunda generación (2G) introdujeron tecnologías digitales y servicios de mensajes de texto (SMS).
Las redes de tercera generación (3G) permitieron velocidades de datos más altas y la introducción de servicios más avanzados, como la navegación web móvil.
Las redes de cuarta generación (4G) representaron un salto significativo en velocidad y capacidad de datos, habilitando servicios como streaming de video de alta calidad.
Actualmente, las redes 5G están en proceso de implementación masiva, ofreciendo velocidades ultra rápidas, baja latencia y soporte para una gran cantidad de dispositivos conectados.


## Evolución de las Redes Centrales o Core
La evolución de las redes centrales, también conocidas como Core Networks en inglés, ha sido fundamental para el desarrollo y la mejora de los servicios de comunicaciones móviles. Aquí está la evolución de las redes centrales en términos generales:
 
### Redes Centrales 1G (Primera Generación):
En la era del 1G, las redes centrales estaban principalmente diseñadas para soportar comunicaciones de voz analógicas. Estas redes utilizaban una arquitectura de conmutación de circuitos, donde se establecía un circuito físico dedicado para cada llamada.
El elemento central en las redes 1G era el Mobile Telephone Switching Office (MTSO), también conocido como Mobile Switching Center (MSC). El MTSO/MSC era responsable de gestionar las llamadas, la movilidad de los usuarios y la interconexión con otras redes telefónicas.
 
### Redes Centrales 2G y 3G:
Circuit Switched Core (CSC): En las redes 2G y 3G, el Core Network estaba diseñado principalmente para admitir comunicaciones de voz y mensajes de texto. Utilizaban un enfoque de conmutación de circuitos (Circuit Switched) para establecer conexiones dedicadas durante una llamada.
Mobile Switching Center (MSC): Era el elemento principal del Core Network en las redes 2G y 3G. El MSC gestionaba la movilidad de los usuarios, el enrutamiento de llamadas y la conexión con otras redes telefónicas públicas o privadas.
 
### Redes Centrales 4G:
IP Multimedia Core Network Subsystem (IMS): Con la llegada de las redes 4G, se introdujo el IMS, que marcó un cambio hacia servicios de comunicación basados en IP. Esto permitió la integración de servicios multimedia, como video llamadas, mensajería multimedia y servicios basados en la web.
Evolved Packet Core (EPC): El EPC se convirtió en el núcleo de las redes LTE (4G). Fue diseñado para admitir una mayor velocidad y capacidad de datos, utilizando tecnologías de conmutación de paquetes y protocolos IP para optimizar la transmisión de datos.
Funciones Virtuales (NFV) y Arquitectura de Redes Definidas por Software (SDN): En las redes 4G, también se comenzaron a implementar tecnologías como NFV y SDN para virtualizar y optimizar las funciones del Core Network, lo que permitió una mayor flexibilidad y eficiencia en la gestión de recursos.
 
### Redes Centrales 5G:
5G Core (5GC) o Next Generation Core Network (NGC): Con la llegada de las redes 5G, se ha desarrollado un nuevo Core Network diseñado específicamente para aprovechar al máximo las capacidades de 5G, como mayor ancho de banda, menor latencia y soporte para una gran cantidad de dispositivos conectados.
Network Slicing: Una característica clave en las redes 5G es la capacidad de crear "rebanadas de red" (network slices), que son segmentos virtuales de la red adaptados para diferentes tipos de servicios y aplicaciones, como IoT, servicios de misión crítica, realidad virtual, entre otros.
Edge Computing y MEC (Multi-Access Edge Computing): Las redes 5G también están integrando capacidades de computación en el borde de la red (edge computing) a través de MEC, lo que permite procesar datos y ejecutar aplicaciones más cerca de los usuarios y dispositivos, reduciendo la latencia y mejorando la experiencia de usuario.
En síntesis la evolución de las redes centrales o Core Networks:
Se refiere a cómo han evolucionado las arquitecturas y tecnologías en el corazón de las redes de telecomunicaciones, encargadas de gestionar el tráfico de datos, las conexiones de los usuarios y los servicios ofrecidos.
En las primeras generaciones (1G, 2G, 3G), las redes centrales estaban diseñadas principalmente para soportar comunicaciones de voz y mensajes de texto, utilizando conmutación de circuitos en redes más antiguas y luego migrando a conmutación de paquetes en redes más modernas.
Con la llegada de las redes 4G, las redes centrales evolucionaron hacia arquitecturas totalmente IP (Internet Protocol), como el Evolved Packet Core (EPC), que permitió velocidades de datos más altas, menor latencia y servicios multimedia avanzados.
Las redes centrales 5G (5GC o NGC) representan una arquitectura completamente nueva diseñada para aprovechar las capacidades únicas de 5G, como network slicing (rebanado de red), Edge Computing, mayor eficiencia energética y soporte para una amplia variedad de servicios y dispositivos.

[RedHat](https://www.redhat.com/es/topics/5g-networks/evolution-to-a-5g-core)


## Evolución de los Terminales de Usuario

### 1G (1970-1980). 

    El primer dispositivo móvil fue el celular  modelo Motorola DynaTAC 8000X, en la ciudad de New York, el cual se comercializó para los años 1984. Para la época de los 80 se considera al teléfono móvil de primera generación, lo cual representó un gran avance, por primera vez se pudo mantener una llamada de hasta 30 minutos, desde cualquier lugar y sin uso de cables. Estos teléfonos tenían pantallas pequeñas, teclados físicos y, en algunos casos, pantallas monocromáticas para mostrar información básica.
    
### 2G (1980-2000).

    En el año 1992 se presentó una tecnología digital que surge ante la necesidad de transmitir datos y voz desde cualquier móvil y que todavía se usa hoy en día y que se conoce como GSM.
    Nacen así los mensajes de texto o SMS usados todavía.
    Además tenía servicios de Roaming Internacional, llamada en espera, exclusión de llamada, identificación de número llamante y servicios de USSD.
 
### 3G (2003-2007)

    Esta generación daba servicio a alta velocidad, Internet Inalámbrico Fijo, telefonía Inalámbrica de voz, videollamada, videoconferencia, navegación web, correo, mapas de navegación, juego, música móvil, fotos digitales y películas, actualización de tráfico y clima además de otros. En esta generación se hicieron muy populares los móviles BLACKBERRY y más adelante el  primer smartphone que revolucionó la telefonía móvil: el Iphone.
    
### 4G (2007-2015)

    Se basa en la tecnología de telefonía IP que se alcanza por la convergencia entre las redes de cable y redes inalámbricas.
    Como tiene una capacidad para dar velocidades de acceso mayores le permite dar servicios de cualquier clase, en cualquier momento y en cualquier lugar con un mínimo coste.
    La 4G se caracteriza por un aumento muy significativo del tráfico de datos, que puede alcanzar los 150 Mb/s en determinadas condiciones aunque en la práctica, la mayoría de los clientes sólo llegarán a una velocidad máxima de 20 Mbps.
    Da acceso a los servicios de Internet móvil, telefonía IP, videoconferencia de televisión móvil de alta definición, televisión 3D, Digital Video Broadcasting (DVB), etc. Un ejemplo de móvil es el SAMSUNG Galaxy J1Ace.
    4G es la tecnología móvil que llevan casi todos los móviles actuales.
 
### 5G (2015-2020)

    Esta generación tiene una implantación en el mundo entero y usa la arquitectura inalámbrica abierta (OWA). Utiliza la tecnología de telefonía IP banda ancha. Sus servicios tienen dispositivos en cualquier lugar y en cualquier momento y la dirección de IP es asignada según la red y la posición geográfica y otras aplicaciones.
    Se prevé que para 2025 una de cada cinco conexiones móviles se realizara sobre redes 5G .

[Diferencias de redes móviles](https://www.mixideal.com/blog/tecnologia/redes-moviles-1g-2g-3g-4g-y-5g-cuales-son-sus-diferencias)

## Convergencia
    Aquí explorarán la evolución de los sistemas de comunicaciones a lo largo del tiempo. Presentarán el concepto de convergencia de servicios. Considerarán como ha cambiado la forma en que los usuarios acceden a contenidos y como se ha adaptado el modelo de negocios de los prestadores de servicios. Deben citar las fuentes bibliográficas empleadas.

## Internet de las Cosas
    Aquí presentarán el concepto de Internet de las Cosas, sus inicios y evolución a lo largo del tiempo. Presentarán los servicios de conectividad orientados a comunicaciones entre máquinas e internet de las cosas en las redes móviles modernas. Discutirán los modelos de negocios propuestos para la prestación de servicios de conectividad entre máquinas e Internet de las Cosas. Deben citar las fuentes bibliográficas empleadas.
    Conclusiones
    En este espacio deben reflexionar sobre lo aprendido durante la investigación. En especial en lo referente a la evolución, presente y futuro de las redes móviles, las telecomunicaciones y el acceso a la información y el conocimiento en nuestra sociedad.



