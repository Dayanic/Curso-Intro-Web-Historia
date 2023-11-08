# Historia de la computación
Se podría decir que el abaco fue nuestra primera computadora, ya que se requería realizar calculos y para esto se generó. Luego como se requerían calculos más complejos se crearon nuevos elementos hasta llegar a los computadores humanos que realizaban ciertos cálculos complejos. De hecho se generó un libro con calculos previos para ayudar.

# ¿Quiénes eran las computadoras?
Antes se utilizaban tarjetas perforadas, y se le pasaban a una máquina para que realizará los calculos requeridos. Luego de esto nace el **Machine Code** que corresponde al manejo con cero y unos.

# Inputs y Outputs
* Imput: Es la entrega o entrada de información. Ejemplo un teclado.
* Proceso: Procesamiento de datos entregados por el Impput.
* Output: Es la salida de información. Por ejemplo un monitor.

# Binario
El lenguaje que usamos los seres humanos para comunicarnos entre nosotros no es el mismo lenguaje que usan las máquinas. Nosotros nos comunicamos por medio de sonidos que son interpretados en caracteres alfanuméricos. Las máquinas entienden un **código binario** que se basa en señales de corrientes eléctricas de diferentes capacidades.
## **¿Qué es el código binario?**
El código binario es una **representación de datos o información** que usa únicamente dos símbolos, el cero `”0”` y el uno `”1”`. Estos símbolos se conocen como bits (dígito binario). Un bit es la unidad básica de información en el código binario.

La combinación de **bits** permite representar información más compleja. Por ejemplo, ocho bits agrupados se denominan **byte**, y un byte puede representar **256 (2^8)** valores diferentes.

En código binario, los números se representan utilizando una serie de bits. Cada bit en una posición determinada tiene un valor asociado, y la combinación de todos los bits representa un número en el sistema binario. Además, el código binario se utiliza para representar caracteres, instrucciones de máquina, datos de archivo y cualquier otra información que pueda expresarse en términos de encendido (1) y apagado (0).

![](https://static.platzi.com/media/user_upload/binary_system-8acf99ec-1b88-46ca-b7b3-557f7b77b10c.jpg)

# Bits y Bytes
Las computadoras no entienden directamente el código binario, nosotros debemos decirle a la computadora que hacer por medio de un **proceso computacional**. Es como si le dijéramos a un cuchillo que corte una papa, no lo va a hacer hasta que nosotros tomémonos el cuchillo y cortemos la papa. Al final del día, las máquinas so herramientas que necesitan esos inputs para poder darnos resultados.

## **Bits**
Un bit es la **unidad básica** de información en el sistema binario y representa un dígito que puede ser `1` o `0`. Visualmente, puedes imaginar un bit como un interruptor que puede estar **encendido** (1) o **apagado** (0).

## **Byte**
Un byte es una **agrupación de ocho bits** consecutivos. Es la unidad de **almacenamiento fundamental** en la mayoría de los sistemas informáticos. Un byte es como ocho interruptores consecutivos, cada uno representa un bit.

Un byte puede representar diferentes valores, incluyendo caracteres, números y datos. Por ejemplo, en el estándar ASCII, cada byte representa un carácter.

![](https://www.dataunitconverter.com/blog/images/bit-nibble-byte-0.png)

# ASCII
**¿Cómo se representan diferentes caracteres en la computadora?**
Los caracteres se representan utilizando diferentes sistemas de codificación de caracteres. Uno de ellos es el sistema [**ASCII (American Standard Code for Information Interchange)**](https://www.ascii-code.com/) que es uno de los sistemas de codificación más antiguos y ampliamente utilizados.

Cada carácter en el conjunto ASCII se representa mediante un único **byte (8 bits)**. El conjunto ASCII original incluye **128 caracteres**, que incluyen letras mayúsculas y minúsculas, dígitos, signos de puntuación y caracteres especiales.

![](https://linuxhint.com/wp-content/uploads/2022/02/word-image-533.png)

# UNICODE
[Unicode es un sistema de codificación](https://home.unicode.org/) de caracteres más moderno que tiene como objetivo representar todos los caracteres utilizados en todos los sistemas de escritura del mundo. Unicode utiliza **más de un byte** para representar caracteres y ofrece diferentes formas de codificación, como **UTF-8, UTF-16 y UTF-32**.

**UTF-8** es el esquema de codificación más comúnmente utilizado en la web y en sistemas informáticos modernos. Utiliza de **1 a 4 bytes** para representar caracteres, según su valor.

**UTF-16** utiliza principalmente **2 bytes**, pero también puede usar **4 bytes** para caracteres más raros o menos comunes.

**UTF-32** utiliza **4 bytes**, lo que simplifica que todos los caracteres se representan con la misma cantidad de bytes.

**Este sistema es el que nos permite utilizar emojis 😋 que son una combinación de varios caracteres.** 💚

# RGB
**¿Cómo funcionan los colores?**
Su funcionamiento se basa en la interacción con los objetos y la percepción visual. Los colores son el resultado de cómo los objetos interactúan con la luz y cómo nuestros ojos y cerebro interpretan esa interacción.

**Sistema aditivo (RGB)**
Este sistema se usa en pantallas de dispositivos electrónicos, como televisores y monitores. En este sistema se crean colores combinando los colores primarios rojo (Red), verde (Green) y azul (Blue). Esos colores se conocen como colores RGB. Cuando se combinan diferentes intensidades, los colores se mezclan para formar diferentes tonos.

En un monitor, los colores están representados por píxeles. Cada píxel se compone de pequeños puntos de luz llamados sub píxeles, que emiten luz roja (Red), verde (Green) y azul (Blue) en diferentes intensidades.

Algunos ejemplos de cómo se crean diferentes colores con este sistema son:
* Si todos los sub píxeles están apagados, el píxel aparece **negro**.
* Si todos los sub píxeles están encendidos en su máxima intensidad, el píxel aparece **blanco**.
* Si solo el sub píxel rojo está encendido, el píxel aparece **rojo**.
* Si solo el sub píxel verde está encendido, el píxel aparece **verde**.
* Si solo el sub píxel azul está encendido, el píxel aparece **azul**.

Para representar colores más complejos, se utilizan **combinaciones de valores RGB** en una escala de **0** a **255 (256 valores)** para cada sub píxel. Esto significa que este sistema se basa en el sistema binario de **1 byte** para cada sub píxel (3 bytes para 1 píxel).

Por ejemplo, si queremos representar el nuevo color de **Platzi**, debemos combinar los valores `R = 10`, `G = 233` y `B = 138`.

En el sistema binario, estos números serían `R = 00001010`, `G = 11101001` y `B = 10001010`.

# ¿De donde viene el internet?
nternet es una **red global de computadoras interconectadas**. Su historia se remonta a la década de 1960, cuando el Departamento de **Defensa de Estados Unidos** desarrolló una red experimental llamada **ARPANET** ***(Advanced Rechearch Project Agency Network)***.

ARPANET fue diseñada como una **red descentralizada** para asegurar la comunicación entre instituciones y centros de investigación. Su objetivo principal era **garantizar que la información pudiera ser transferida** incluso en caso de un ataque nuclear, ya que ARPANET no tenía un punto central de control que pudiera ser destruido.

En los años 70 y 80, ARPANET se expandió para incluir a otras universidades e instituciones de investigación. ARPANET se transformó en lo que conocemos como Internet. Se estableció una estructura de dominios y se crearon los primeros servidores web.

En los años 90, se produjo un hito importante con la invención de la **World Wide Web** por **Tim Berners-Lee** que introdujo un sistema de **enlaces de hipertexto** que facilitaba la navegación y el acceso a la información en Internet.

**¿Cómo llega internet a nuestras casas?**
El internet llega a nuestras casas a través de los **ISP (Internet Service Provider)** como Claro, Movistar, etc. Estas compañías utilizan una variedad de tecnologías para brindar el servicio como cable coaxial y fibra óptica.

Los ISP construyen y mantienen una infraestructura de red para proporcionar acceso a internet. Esto incluye cables, torres de comunicación y demás equipos necesarios para transmitir datos. Luego, los ISP se conectan a una red de nivel superior, que es una red global que interconecta ISP por medio de cables submarinos intercontinentales que permiten la comunicación a nivel mundial.

# Internet internacional
En la década de 1970, ARPANET se expandió para incluir a otras universidades e instituciones de investigación. Se desarrollaron protocolos de comunicación estándar, como el **TCP/IP (Transmission Control Protocol/Internet Protocol)**, que permitieron la interconexión de redes y el intercambio de información de manera eficiente.

# Protocolos
**¿Qué es un protocolo de comunicación?**
Es un conjunto de **reglas y estándares** que definen cómo deben intercambiarse los datos y cómo debe llevarse a cabo la comunicación entre los sistemas de red. Estas reglas establecen el formato de los datos, los procedimientos de inicio y finalización de la comunicación, y las acciones que deben tomar los dispositivos involucrados.

**¿Por qué nace la necesidad de un protocolo?**
Nacen con el propósito de permitir la interoperabilidad y el intercambio de información entre diferentes dispositivos y sistemas en una red. Antes de su existencia, cada dispositivo o sistema tenía su propio formato de datos y sus propias reglas de comunicación, lo que dificultaba la interoperabilidad.

A lo largo del tiempo se han desarrollado muchos protocolos de comunicación para diferentes necesidades. Uno de estos es el **TCP/IP (Transmission Control Protocol/Internet Protocol)**, que permite la interconexión de redes y el intercambio de información.

# Paso a paso de cómo funciona los protocolos
**Modelo TCP/IP**
El modelo **TCP/IP (Protocolo de Control de Transmisión / Protocolo de Internet)** es la combinación y trabajo conjunto de dos protocolos:

* **TCP**: Define cómo una aplicación puede establecer un canal de comunicación a través de la red.
* **IP**: Es responsable del direccionamiento y enrutamiento del paquete para su entrega exitosa al destino.

Este modelo consta originalmente de **cuatro capas** (application, transport, internet y link), pero en la actualidad se dividió la capa “link” en dos: **Data link** y **Physical**. También se cambia el nombre de la capa “Internet” a “Network”.

![](https://network-byte.com/wp-content/uploads/2020/04/tcp-ip-protocol-min-1536x708.jpg)

**Application Layer**
Esta capa se encarga de las **aplicaciones y servicios** específicos que utilizan la red. Incluye **protocolos y servicios** como el HTTP y HTTPS para la web, SMTP para el correo electrónico, FTP para la transferencia de archivos, DNS para la resolución de nombres, entre otros.

**Transport Layer**
Esta capa es responsable de la **entrega confiable** de los datos de extremo a extremo. Utiliza principalmente dos protocolos: TCP y UDP.

* **TCP (Transmission Control Protocol)**: Proporciona una **comunicación confiable y orientada** a la conexión. Se encarga de la **segmentación** y **reensamblaje** de los datos en segmentos, establecimiento y cierre de conexiones, control de flujo y control de congestión. Garantiza que los datos lleguen sin errores y en el orden correcto, pero puede tener una mayor latencia debido a la verificación y la entrega confiable.
* **UDP (User Datagram Protocol)**: Proporciona una **comunicación no confiable y sin conexión**. Se utiliza cuando la entrega rápida es más importante que la confiabilidad. Los datos se envían en **datagramas** sin establecer una conexión previa ni verificar la entrega.

**Network Layer**
Esta capa se encarga de la **transmisión de los paquetes** de datos a través de la red. Utiliza **direcciones IP** para identificar los dispositivos y los paquetes se enrutan a través de la red utilizando protocolos de enrutamiento, como el **ICMP** y **RIP**. Además, esta capa proporciona la **fragmentación** y **reensamblaje** de los paquetes para su transporte eficiente.

**Data Link Layer**
Esta capa se ocupa de la **transmisión física** de los datos a través de un medio de red específico, como Ethernet o wifi. Esta capa **encapsula los datos** en tramas o paquetes y se encarga de la detección y corrección de errores en la transmisión. También gestiona el acceso al medio y las **direcciones físicas (MAC)** de los dispositivos en la red.

**Physical Layer**
La capa física define el **cableado y la energía** (por ejemplo, señales eléctricas) que fluyen por los cables. **Convierte** datos binarios en señales y transmite a través de los medios locales. Existen algunas reglas y convenciones cuando se envían datos por cable; sin embargo, esas reglas existen en la capa de enlace de datos del modelo TCP/IP.

![](https://network-byte.com/wp-content/uploads/2020/04/typcal_sin_TP_IP_nw-min-1536x938.jpg)

# ISP
**¿Qué es un ISP?**
Un **ISP (Internet Service Provider)**, es una compañía que suministra **acceso a internet y otros servicios** a individuos y organizaciones. Esta compañía implementa y mantiene la infraestructura necesaria para suministrar esos servicios.

El papel principal de un ISP es **proporcionar conectividad a Internet** a través de diferentes tecnologías y medios de transmisión, como líneas telefónicas, cable coaxial, fibra óptica, conexiones inalámbricas o satelitales. Estos servicios de conexión a Internet pueden ser ofrecidos tanto a nivel **residencial** como **empresarial**.

Además de ofrecer conectividad, también pueden proporcionar servicios como direcciones IP, correo electrónico, alojamiento web, servicios de seguridad, telefonía digital, televisión por cable, streaming de contenido, entre otros.

**¿Cómo funcionan los ISP?**
Los ISP están conectados a una o más **líneas de internet de alta velocidad**. Los ISP más grandes tienen sus propias líneas arrendadas de alta velocidad, por lo que dependen menos de los servicios de telecomunicaciones y pueden brindar un mejor servicio a sus clientes.

**Los ISP se agrupan en tres niveles:**
* **Tier 1 ISP**: Tienen un alcance global y poseen suficientes líneas de red física para transportar la mayor parte del tráfico por su cuenta. Los ISP de nivel 1 no dependen de otros ISP para alcanzar cualquier destino en Internet.

* **Tier 2 ISP**: Son proveedores que se conectan con ISP de nivel 1 y otros ISP de nivel 2 para acceder a Internet. Aunque no tienen la misma infraestructura y alcance global que los ISP de nivel 1, los ISP de nivel 2 suelen ofrecer conectividad a regiones geográficas específicas y tienen acuerdos de interconexión con otros ISP para expandir su cobertura.

* **Tier 3 ISP**: Son proveedores de servicios regionales o locales que se conectan con ISP de nivel 2 o nivel 1 para acceder a Internet. Estos ISP tienen un alcance más limitado y suelen operar en una región geográfica específica. Proporcionan servicios de acceso a Internet a usuarios y empresas en esa región y pueden tener acuerdos de interconexión con otros ISP para ampliar su cobertura.

# DNS
El **DNS (Domain Name System)** es un sistema que se utiliza para **traducir los nombres de dominio** legibles por nosotros, en **direcciones IP** que las computadoras entienden. El DNS permite asociar un nombre de dominio, como “platzi .com”, con la dirección IP correspondiente, como “104.17.175.85”.

El DNS nace para **facilitar la navegación** en internet. En lugar de tener que recordar un número complicado como la IP, podemos usar nombres de dominio más fáciles de recordar. El DNS se diseñó para resolver el problema de escalabilidad y la facilidad de uso al proporcionar una forma organizada y jerárquica de asignar nombres a direcciones IP.

**¿Cómo funciona el DNS?**
Se basa en una estructura jerárquica y distribuida que consta de diferentes tipos de servicios. Su comportamiento es el siguiente:
* **Consulta DNS**: Cuando el usuario ingresa un nombre de dominio en el navegador, como *“platzi .com”*, el sistema operativo envía una consulta DNS a un servidor DNS.

* **Resolución en caché local**: El servidor DNS local (como el suministrado por el ISP) verifica si tiene la respuesta en su caché. Si ha resuelto previamente ese DNS, puede devolver la dirección IP almacenada sin tener que hacer más consultas.

* **Consulta a servidores DNS root**: Si el servidor DNS local no tiene la respuesta en su caché, envía una consulta a los servidores DNS de nivel superior o servidores de raíz para obtener información sobre el dominio solicitado. Estos servidores no tienen información detallada sobre los DNS, pero pueden dirigir la consulta al servidor responsable del dominio de nivel superior (como .com o .org).

* **Respuesta del servidor DNS root**: El servidor DNS autoritativo responde al servidor local con la IP correspondiente al nombre de dominio solicitado.

* **Respuesta al usuario**: El servidor local recibe la respuesta almacenada en su caché para futuras consultas. Luego, envía la IP al dispositivo del usuario para establecer una conexión con el servidor web correspondiente.

![](https://cf-assets.www.cloudflare.com/slt3lc6tev37/1NzaAqpEFGjqTZPAS02oNv/bf7b3f305d9c35bde5c5b93a519ba6d5/what_is_a_dns_server_dns_lookup.png)

# El primer desarrollador Web
Este título se le atribuye a **Tim Berners-Lee** quien es un científico de la computación británico, quién es ampliamente reconocido como el **inventor de la World Wide Web (WWW)** y el creador del **primer sitio web**.

En 1989, Tim Berners-Lee trabajaba en el **CERN (Organización Europea para la Investigación Nuclear)** dónde desarrollo un sistema para compartir información y documentos científicos utilizando hipertexto. Este sistema se convirtió en la base del World Wide Web.

En 1990, Berners-Lee implementó el primer sitio web llamado *“info. cern. ch”*, que se convirtió en el **primer sitio web accesible públicamente**. Este sitio consistía en páginas estáticas que proporcionaban información sobre el proyecto WWW.

Este sitio fue creado con **HTML (HyperText Markup Language)** para la estructura del contenido y **HTTP (Hypertext Transfer Protocol)** para la transferencia de datos entre el servidor web y los clientes. No existían elementos visuales complejos o diseño gráfico, ya que su enfoque principal estaba en la estructura y accesibilidad de la información.

# Web Browser
Los navegadores web desempeñan un papel fundamental en la **navegación y el acceso a Internet**. Han experimentado un desarrollo significativo a lo largo de los años, impulsando la evolución de la web y mejorando la experiencia de los usuarios.

**NCSA Mosaic (1993)**: Desarrollado por el **National Center for Supercomputing Applications (NCSA)**, es considerado uno de los **primeros navegadores web** ampliamente utilizados. Introdujo características como la **visualización de imágenes** y la capacidad de mostrar **texto y gráficos** en la misma página.

**Netscape Navigator (1994)**: Desarrollado por **Netscape Communications Corporation**, fue uno de los navegadores más populares en los primeros días de la web. Introdujo características como las **pestañas** de navegación, el **soporte** para lenguajes de programación como **JavaScript** y la posibilidad de reproducir contenido multimedia.

**Internet Explorer (1995)**: Lanzado por **Microsoft** como parte del sistema operativo **Windows**, se convirtió en uno de los navegadores más utilizados debido a su **integración** con Windows y su amplia distribución. Durante años, fue el navegador dominante en el mercado.

**Safari (2003)**: Desarrollado por **Apple**, se introdujo como el navegador predeterminado en los dispositivos **macOS** e **iOS**. Se destacó por su **rendimiento** y su enfoque en la **integración** con otros productos de Apple.

**Mozilla Firefox (2004)**: Creado por la **Fundación Mozilla**, se destacó por su enfoque en la **seguridad**, la **personalización** y el **cumplimiento de los estándares web**. Ganó popularidad por su **velocidad y capacidad de extensión**, y se convirtió en una alternativa a Internet Explorer.

**Google Chrome (2008)**: Desarrollado por **Google**, se lanzó con un enfoque en la **velocidad**, la **simplicidad** y la **estabilidad**. Rápidamente, ganó popularidad y se convirtió en uno de los navegadores **más utilizados** debido a su rendimiento y la integración con los servicios de Google.

# W3C
El **W3C (World Wide Web Consortium)** es un consorcio internacional que se dedica a **establecer estándares abiertos** para la web y promover su desarrollo y evolución. Fue fundado en 1994 por **Tim Berners-Lee**, el inventor del **World Wide Web**, y tiene como objetivo principal garantizar la **interoperabilidad** y el **crecimiento continuo** de la web.

El W3C trabaja en colaboración con organizaciones, empresas y la comunidad web en general para **desarrollar** y **mantener** estándares técnicos que aseguren la **calidad, accesibilidad y usabilidad** de la web. Estos estándares cubren una amplia gama de áreas, incluyendo lenguajes de marcado **(HTML, XML)**, hojas de estilo **(CSS)**, accesibilidad, semántica web, seguridad, multimedia y muchos otros aspectos relacionados con la web.

**Algunos de los estándares más conocidos desarrollados por el W3C incluyen**:
* **HTML (HyperText Markup Language_)**: Es el lenguaje de marcado utilizado para estructurar el contenido de las páginas web.
* **CSS (Cascading Style Sheets)**: Es el lenguaje utilizado para describir la presentación y el estilo visual de las páginas web.
* **XML (eXtensible Markup Language)**: Es un lenguaje de marcado utilizado para estructurar datos de manera legible tanto para humanos como para máquinas.
* **DOM (Document Object Model)**: Es una interfaz de programación que permite el acceso y la manipulación de los elementos de una página web.
* **SVG (Scalable Vector Graphics)**: Es un formato de imágenes vectoriales que permite representar gráficos escalables y animaciones en la web.

El W3C también se dedica a la **educación y promoción** de las mejores prácticas web, así como a la creación de herramientas y recursos para ayudar a los desarrolladores a cumplir con los estándares y hacer que sus sitios web sean más accesibles y eficientes.

# Evolución del protocolo HTTP
**HTTP (HyperText Transfer Protocol)** es el protocolo que se usa para la **transferencia de datos entre el servidor web y los clientes**. Ha evolucionado, desde un protocolo para el intercambio de archivos en un laboratorio, al actual laberinto de Internet, sirviendo ahora para el intercambio de imágenes, videos en HD y en 3D.

**Evolución de HTTP**
* **HTTP/0.9 - El protocolo de una sola línea**: Lanzado en 1991, consistía en una **petición de una sola línea** por medio del único método posible `GET`, seguido por la dirección del recurso a pedir. Esta versión no usaba cabeceras HTTP, por eso solo se podían transmitir archivos **HTML**. Tampoco había información de error, en caso de un problema, el archivo HTML era devuelto con una descripción del error dentro de él para su análisis manual.

* **HTTP/1.0 - Desarrollando expansibilidad**: Lanzado en 1996, en esta versión se **añade la versión HTTP/1.0** a la línea de la petición `GET`. También se envía un código de estado al comienzo de la respuesta. Se presenta el concepto de **cabeceras HTTP** para petición y respuesta permitiendo la transmisión de metadatos. Con el uso de cabeceras HTTP, se pudieron transmitir otros documentos como imágenes.

* **HTTP/1.1 - El protocolo estándar**: Lanzado en 1997, agregando mejoras en la **gestión de la conexión y el caché**, así como soporte para peticiones **pipelining y host virtuales**. Este protocolo fue evolucionando en dos versiones lanzadas en 1999 y 2014 (previsión de HTTP/2).

* **HTTP/2 - Un protocolo para un mayor rendimiento**: Estandarizado de manera oficial en 2015, este protocolo **binario** no se puede leer directamente, ni crear manualmente. Gracias a este cambio es posible utilizar técnicas de optimización. Es un **protocolo multiplexado** con peticiones paralelas sobre la misma conexión, no está sujeto a un orden de los mensajes. **Comprime las cabeceras**, ya que son similares en un grupo de peticiones.

**Métodos de HTTP**
HTTP define un conjunto de **métodos de petición** para indicar la acción que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs.

* `GET`: Este método solicita una representación de un recurso específico. Las peticiones que usan este método solo deben recuperar datos.
* `HEAD`: Este método pide una respuesta idéntica a la de una petición `GET`, pero sin el cuerpo de la respuesta.
* `POST`: Este método se utiliza para enviar una entidad o recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.
* `PUT`: Este método reemplaza todas las respuestas actuales del recurso de destino con la carga útil de la petición.
* `DELETE`: Este método borra un recurso en específico.
* `CONNECT`: Este método establece un túnel hacia el servidor identificado por el recurso.
* `OPTIONS`: Este método se utiliza para describir las opciones de comunicación para el recurso de destino.
* `TRACE`: Este método realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino.
* `PATCH`: Este método se usa para aplicar modificaciones parciales a un recurso.

# HTTPS
**HTTPS (HTTP Secure)** es una versión **encriptada** del protocolo HTTP. Normalmente, utiliza **SSL o TLS** para cifrar toda la comunicación entre un cliente y un servidor. Esta conexión segura permite a los clientes **intercambiar datos confidenciales** de forma segura con un servidor, por ejemplo, para actividades bancarias o compras en línea.

Actualmente, los navegadores nos informan si la página a la que estamos intentando acceder es segura por medio de un mensaje de alerta si no lo es y un candado si es segura.

![](https://www.cloudflare.com/img/learning/security/glossary/what-is-ssl/http-vs-https.svg)

# Estandarés Web: navegadores
**[La guerra de los navegadores](https://www.mozilla.org/es-ES/firefox/browsers/browser-history/)**
En 1995, **Netscape Navigator** era la única forma de conectarse. **Microsoft** obtuvo la licencia del antiguo código de **Mosaic** y construyo **Internet Explorer**. Esto empezó una guerra por el dominio del acceso a internet, donde cada empresa creo nuevas versiones de sus programas.

Netscape creó y lanzó **JavaScript**, que dio a las páginas web potentes posibilidades. Microsoft contraatacó con **Cascading Style Sheets (CSS)**, qué se convirtió en el estándar para el diseño de páginas web.

En 1997, Microsoft lanzo **Internet Explorer 4.0**. El equipo construyo una “e” gigante y la puso en el césped de la sede de Netscape. El equipo de Netscape la derribo y puso encima su mascota, el dinosaurio [Mozilla](https://medium.com/@ddprrt/tales-from-the-browser-wars-mozilla-stomps-internet-explorer-799035887cb1).

Microsoft empezó a distribuir Internet Explorer con su sistema operativo **Windows**. En 4 años, obtuvo el **75% del mercado** y en 1999 tenía el **99%**. Netscape decidió abrir su código fuente y creó la organización sin ánimo de lucro **Mozilla**, que luego creó y lanzo **Firefox en 2002**. Para 2010, **Mozilla Firefox, Google Chrome, Safari** y otros navegadores habían reducido la participación de mercado de Internet Explorer al 50%.

En la actualidad, la gran mayoría de usuarios solo usan estos navegadores en **dispositivos móviles** debido al fácil acceso. A su vez, los navegadores cuentan con un motor que gestiona toda la interacción entre la web y el usuario. La gran mayoría utiliza el motor de Google Chrome llamado **Chronium**.

# Estandarés Web: HTML, CSS y Javascript
[Los estándares de la web](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards) son las tecnologías que utilizamos para crear **sitios web**. Estos estándares existen como extensos documentos técnicos llamados *especificaciones*, que detallan exactamente como debería funcionar la tecnología. Estos documentos están pensados para que los utilicen los **ingenieros de software** para implementar esas tecnologías.

***HTML (HyperTex Markup Language)***, es el lenguaje de marcado que consta de diferentes elementos en los que puedes ajustar (marcar) el contenido para darle significado (semántica) y estructura.

Si adoptamos una analogía de la construcción de casas, HTML sería como los **cimientos y las paredes** de la casa, que le dan estructura y la mantienen unida.

***CSS (Cascading Style Sheets)*** es un lenguaje basado en reglas que se utilizan para aplicar estilos a tu HTML, como establecer colores del texto y del fondo, agregar bordes, animar cosas o diseñar una página de cierta manera.

En la analogía de la casa, CSS es como la **pintura, el papel tapiz, las alfombras y los cuadros** que usarías para hacer que la casa se vea bien.

**JavaScript** es el lenguaje de programación que usamos para agregar interactividad a los sitios web, desde el cambio de estilo dinámico, hasta la obtención de actualizaciones desde el servidor, pasando por gráficos complejos en 3D.

En la analogía de la casa, JavaScript es como **la cocina, el televisor, el microondas o la secadora de pelo**. Son las cosas que le dan una **funcionalidad** útil a tu casa.

# Web Assembly
[Web Assembly](https://developer.mozilla.org/es/docs/WebAssembly) es un nuevo **tipo de código** que puede ser ejecutado en **navegadores modernos**. Es un lenguaje de **bajo nivel**, similar al lenguaje ensamblador, con un formato binario compacto que se ejecuta con rendimiento **casi nativo** y provee un **objetivo de compilación** para lenguajes como **C/C++ y Rust** que les permite correr en la web. También está diseñado para **correr a la par de JavaScript**, permitiendo que trabajen juntos.

# La Web moderna: ¿dónde estamos ahora?
En la actualidad, la web ha experimentado una evolución significativa y se ha convertido en una parte integral de nuestras vidas. Algunos aspectos clave que reflejan el estado actual de la web son:

* **Web interactiva y rica en contenido**: Los avances en tecnologías web, como **HTML5, CSS3y JavaScript**, han permitido crear sitios web **dinámicos, interactivos y visualmente atractivos**.

* **Dispositivos móviles y web responsive**: El auge de los dispositivos móviles ha llevado a una web adaptada a **diferentes tamaños de pantalla** y capacidades de interacción. Los sitios web responsivos se han vuelto indispensables para garantizar una experiencia óptima en **dispositivos móviles**, tabletas y otros dispositivos con pantallas de diferentes tamaños.

* **Contenido multimedia y streaming**: La web actual ofrece una amplia gama de **contenido multimedia**, como videos en línea, música en streaming y juegos en línea. Plataformas de streaming como YouTube, Netflix y Spotify se han vuelto populares y han transformado la forma en que **consumimos y compartimos** contenido en la web.

* **Redes sociales y colaboración**: Las redes sociales han tenido un impacto significativo en la web. Plataformas como Facebook, Twitter, Instagram y LinkedIn han facilitado **la conexión, la comunicación y la colaboración** entre las personas. Las **interacciones sociales y el intercambio de contenido** se han convertido en elementos clave de la experiencia web.

* **Inteligencia artificial y asistentes virtuales**: La inteligencia artificial (IA) y los asistentes virtuales, como Siri, Google Assistant, Alexa, ChatGPT, entre otros, están cambiando la forma en que interactuamos con la web. La IA se utiliza para **personalizar la experiencia del usuario, ofrecer recomendaciones, realizar búsquedas inteligentes** y brindar respuestas instantáneas a través de chatbots y asistentes virtuales.

**Privacidad y seguridad**: La privacidad y la seguridad en la web se han convertido en temas de gran importancia. Las regulaciones de protección de datos, como el **Reglamento General de Protección de Datos (GDPR)** en la Unión Europea, han llevado a una mayor conciencia sobre la privacidad en línea. Además, se han desarrollado técnicas y estándares de seguridad para proteger la información y mitigar los riesgos de **ciberseguridad**.

* **Web semántica y datos enlazados**: La web semántica busca proporcionar significado y contexto a los datos en línea. Los conceptos como los **datos enlazados (Linked Data)** y los estándares de vocabulario, como **RDF (Resource Description Framework)**, permiten la interconexión y el intercambio de datos estructurados en la web, lo que facilita la **integración y el descubrimiento** de información.

# La web moderna: internet of things, machine learning e inteligencia artificial
**Internet de las cosas (IoT)**: El Internet de las cosas se refiere a la **interconexión de dispositivos físicos** que van más allá de las computadoras y los teléfonos inteligentes, y que están equipados con **sensores y capacidad de comunicación**. Estos dispositivos pueden recopilar datos, intercambiar información y tomar decisiones automatizadas. La web moderna permite que estos dispositivos se conecten y comuniquen entre sí a través de la infraestructura de Internet, lo que crea nuevas oportunidades en áreas como el **hogar inteligente, la salud, la industria y la logística**.

**Aprendizaje automático (Machine Learning)**: El aprendizaje automático es una rama de la inteligencia artificial que se centra en **desarrollar algoritmos y modelos** que permiten a las máquinas **aprender y mejorar automáticamente** a partir de datos sin ser programadas explícitamente. En la web moderna, el aprendizaje automático se utiliza en diversas aplicaciones, como la **personalización de contenidos, la detección de fraudes, el reconocimiento de voz y rostro, la traducción automática y la recomendación de productos**.

**Inteligencia Artificial (IA)**: La inteligencia artificial se refiere a la capacidad de las máquinas para **simular el comportamiento humano y realizar tareas** que requieren inteligencia humana, como el razonamiento, la comprensión del lenguaje natural, la toma de decisiones y el reconocimiento de patrones. En la web moderna, la IA se utiliza para mejorar la experiencia del usuario, ofrecer asistentes virtuales, realizar análisis de datos avanzados, automatizar procesos y optimizar la eficiencia en diversas áreas.

**Despliegue de 5G**: Se refiere a la **quinta generación de redes móviles** que abre nuevas posibilidades en términos de conectividad masiva, velocidad, ancho de banda y capacidad de respuesta a una latencia ultrabaja y aplicaciones de realidad virtual (RV) y aumentada (RA).

# ¿Cómo funciona el navegador?
La función más importante del navegador web es **aceptar una URL a través de la barra de direcciones**, buscar recursos y mostrarlos en pantalla.

![](https://cdn-images-1.medium.com/v2/resize:fit:1024/1*grQU_pdyKp_Dm2hj5jhcXg.png)

# DOM
Es una **interfaz de programación** que comprende páginas web (nodos) que son etiquetas HTML como `<html>`, `<meta>`, `<title>`, `<body>` y `<footer>`, semánticas y no semánticas y otros objetos de nodos. El DOM, que es un **estándar W3**, representa las páginas web como una estructura de nodos en forma de árbol, conocida como documentos.

## **Estructura DOM o DOM Tree**
El DOM existe en una **estructura jerárquica similar a un árbol**, donde cada elemento web que compone el documento se puede considerar como un nodo, es decir, las etiquetas del elemento, el atributo asignado al elemento, el comentario, el contenido del texto y el documento también es un nodo.

![](https://www.lambdatest.com/blog/wp-content/uploads/2023/01/image18-27.png)

# CSSOM
El **CSSOM (CSS Object Model)** es una **API (Application Programming Interface)** que permite acceder y manipular dinámicamente los estilos y reglas CSS de una página web mediante código JavaScript. Proporciona una interfaz programática para interactuar con las propiedades y valores CSS de los elementos HTML de manera más dinámica y controlada.

## **[Estructura del CSSOM](https://www.lambdatest.com/blog/css-object-model/)**
La creación del CSSOM se genera como el DOM, pero con algunas diferencias. Este modelo recorre todo el DOM en búsqueda de reglas de CSS como clases, identificadores y estilos. A partir de esto, empieza a generar su estructura.

![](https://www.lambdatest.com/blog/wp-content/uploads/2023/03/image26-17.png)

# Render Tree
Una vez que tengamos todo el CSSOM y DOM ya cargados, se genera el **Render Tree** con los únicos nodos visibles relacionados. Es una unión de los dos pasos anteriores que relaciona la estructura de HTML con los estilos de CSS.

![](https://www.lambdatest.com/blog/wp-content/uploads/2023/03/image26-17.png)

# Layout
Es el proceso que determina la **posición y el tamaño** de cada elemento en una página web. Este le permite al navegador dibujar los elementos en pantalla de forma correcta.

El layout utiliza la información del Rendering Tree para determinar el diseño siguiendo estos pasos:

* El navegador asigna tamaño a cada elemento en el Rendering Tree.
* El navegador determina la posición de los elementos con relación a sus elementos padre y hermanos.
* Se aplican reglas de posicionamiento y escalado para determinar la posición final en pantalla.

Este proceso puede causar un gran impacto en el rendimiento de una página, especialmente en dispositivos móviles.

# Paint
Es el proceso en el que el navegador **dibuja los elementos** de la página en pantalla. Aquí, el navegador dibuja cada elemento en una capa de pintura independiente, luego se combinan para crear una sola imagen final que se muestra en pantalla.

# JS Engine
Este subsistema analiza el código en JavaScript y lo traduce a lenguaje máquina. Estos motores de JS pueden ser intérpretes estándar, o compiladores JIT (Just inTime). Uno de los motores más populares es el motor Google V8 que está escrito en C++.

**Este motor incluye dos componentes**:
* Memory heap que es dónde se almacenan variables, funciones y otros elementos de JS.
* Call Stack que es una cola de marcos de pila o pasos secuenciales ejecutados por el navegador.

**Algunos subprocesos de este motor son**:
* Obtener, compilar y ejecutar código
* Un hilo de creación de perfiles para analizar funciones y su consumo de tiempo.
* Optimización del proceso de ejecución.
* Recolectores de basura.

![](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*HORXUXQGF32LxnaL.png)
