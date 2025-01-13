# Hacking Ético 🔐 
Notas sobre **Hacking Ético** y Ciberseguridad

## Descripción
Este documento ofrece recursos clave sobre herramientas como Shodan, Censys y Google Dorks para identificar vulnerabilidades en sistemas conectados a Internet, y cómo los expertos en ciberseguridad protegen estos sistemas.

## Enlaces útiles 🌐

- **Curso de Hacking Ético** 🎓: [Curso Completo de Hacking Ético y Ciberseguridad](https://www.udemy.com/course/curso-completo-de-hacking-etico-y-ciberseguridad)  
  _Un curso completo que te enseña desde lo básico hasta técnicas avanzadas de hacking ético y ciberseguridad._
  _Se usa VMWare para crear maquinas virtuales.

- **Exploit DB - Google Dorks - Combinaciones Probadas** 💻: [Google Dorks - Lista Completa](https://www.exploit-db.com/google-hacking-database)  
  _Una colección de combinaciones de búsqueda avanzadas que pueden usarse para encontrar vulnerabilidades de seguridad a través de Google._

- **Shodan - Buscador como Google para Dispositivos IoT (Internet de las Cosas)** 🌐: [Shodan](https://www.shodan.io/)  
  _Shodan es un motor de búsqueda especializado en encontrar dispositivos conectados a Internet, desde cámaras de seguridad, hasta servidores, exponiendo posibles vulnerabilidades._

- **Censys - Plataforma para Buscar Dispositivos y Servicios en Internet** 🔍: [Censys](https://censys.io/)  
  _Censys es una herramienta que permite explorar y analizar dispositivos y servicios conectados a Internet, ayudando a identificar vulnerabilidades y configuraciones inseguras._

- **Awesome Shodan Queries** 🔍: [Awesome Shodan Queries en GitHub](https://github.com/jakejarvis/awesome-shodan-queries)  
  _Una lista curada de consultas útiles para realizar búsquedas avanzadas en Shodan y encontrar dispositivos vulnerables._

- **Whois - Información sobre Dominios** 🌍: [Who.is](https://who.is/)  
  _Who.is es una herramienta que permite realizar consultas WHOIS, proporcionando información sobre dominios, como propietario, registros y más._  
   Ejemplo con la herramienta en la terminal:
  ```bash
    whois microsoft.com
  ```

- **Archive.org - Wayback Machine** 🕒: [Archive.org](https://archive.org/)  
  _Archive.org es una plataforma que ofrece una "Wayback Machine", permitiendo ver versiones archivadas de páginas web a lo largo del tiempo._

- **theHarvester - Herramienta de Reconocimiento** 🕵️‍♂️: [theHarvester](https://github.com/laramies/theHarvester)  
  _theHarvester es una herramienta utilizada para la recopilación de información (reconocimiento) sobre objetivos en pruebas de penetración y hacking ético, proporcionando acceso a diversas fuentes de información._  
  Ejemplo:
  ```bash
   theHarvester --domain microsoft.com --source all --limit 100
  ```

- **Maltego - Herramienta de Análisis y Visualización de Relaciones** 🕵️‍♂️: [Maltego](https://www.paterva.com/web7/)  
  _Maltego es una herramienta que permite descubrir relaciones entre personas, grupos, sitios web, dominios y otros elementos en la red. Usa por detras todas varias fuentes como whois, Shodan, etc. y mustra un grafico con 
todas las relaciones ._

- **VirusTotal - Análisis de Archivos y URLs** 🔍: [VirusTotal](https://www.virustotal.com/)  
  _VirusTotal es una herramienta que permite analizar archivos y URLs en busca de malware._  

- **Have I Been Pwned - Verificación de Brechas de Seguridad** 🔓: [Have I Been Pwned](https://haveibeenpwned.com/)  
  _Have I Been Pwned es una herramienta para verificar si una dirección de correo electrónico o cuenta ha sido comprometida en alguna brecha de seguridad a lo largo del tiempo._  

- **Recon-ng - Marco de Reconocimiento de OSINT** 🕵️‍♂️: [Recon-ng](https://github.com/lanmaster53/recon-ng)  
  _Recon-ng es una herramienta similar a Maltego pero para la terminal._  
  Ejemplo:
  ```bash
   recon-cli
   use recon/domains-hosts/hostnames
   set SOURCE microsoft.com
   run
  ```
 
- **OSINT.rocks - Herramientas de OSINT** 🔍: [OSINT.rocks](https://osint.rocks/)  
  _OSINT.rocks es un sitio que reúne herramientas y recursos útiles para la inteligencia de fuentes abiertas (OSINT), facilitando la recolección de información sobre objetivos en ciberseguridad y hacking ético._

- **CentralOps - Herramienta de Información de DNS y WHOIS** 🌐: [CentralOps](https://centralops.net/)  
  _CentralOps es una herramienta en línea que ofrece información sobre DNS, direcciones IP y registros WHOIS, permitiendo realizar consultas detalladas sobre dominios y servidores._

- **DNS Dumpster - Herramienta de Información de DNS** 🌐: [DNS Dumpster](https://dnsdumpster.com/)  
  _DNS Dumpster es una herramienta en línea que permite realizar búsquedas de información DNS sobre un dominio, proporcionando detalles sobre registros de DNS, direcciones IP, servidores asociados y más._


- **Qué es un Sniffer:**
  
  Un sniffer es una herramienta o programa que se utiliza para interceptar y analizar el tráfico de una red de computadoras. Su función principal es capturar y examinar los paquetes de datos que circulan por una red, lo que permite a los usuarios o administradores de red monitorizar las comunicaciones.

  Dependiendo del contexto, un sniffer puede tener distintos usos:
  
  - **Administradores de redes**: Los sniffers son empleados legítimamente para diagnosticar problemas de red, optimizar el rendimiento y asegurar que no haya comunicaciones no autorizadas.
  
  - **Ataques maliciosos**: Los sniffers también pueden ser utilizados por ciberdelincuentes para capturar información sensible, como contraseñas o datos bancarios, si se encuentran en una red insegura.

  - **Wireshark** 🌐: [Wireshark](https://www.wireshark.org/)  
    _Wireshark es uno de los sniffers más populares y ampliamente utilizados. Es una herramienta de análisis de red de código abierto que permite capturar y explorar los paquetes de datos que viajan por la red en tiempo real. Su interfaz gráfica facilita el análisis detallado de tráfico de red._ [captura](https://www.wireshark.org/docs/wsug_html_chunked/images/ws-main.png)
  
  - **TCPdump** 🌐: [TCPdump](https://www.tcpdump.org/)  
    _TCPdump es una herramienta de línea de comandos muy poderosa para capturar y analizar el tráfico de red. A menudo se usa en entornos de servidores debido a su eficiencia y flexibilidad en el análisis de paquetes de datos._
