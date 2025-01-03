# 🕵️‍♂️ Shodan: Comandos Principales

**⚙️ Comandos relevantes para Shodan**

A continuación se presentan algunos de los filtros más relevantes para el uso de Shodan:

* **⏳ after:** Mostrar solo resultados después de la fecha dada (dd/mm/yyyy) string
* **🔢 asn:** Número de sistema autónomo string
* **🗓️ before:** Mostrar solo resultados antes de la fecha dada (dd/mm/yyyy) string
* **📂 category:** Categorías disponibles: ics, malwarestring
* **🏙️ city:** Nombre de la ciudad string
* **🌍 country:** Código de país de 2 letras string
* **🌐 geo:** Acepta entre 2 y 4 parámetros. 
    * Si son 2 parámetros: latitud, longitud. 
    * Si son 3 parámetros: latitud, longitud, rango. 
    * Si son 4 parámetros: latitud superior izquierda, longitud superior izquierda, latitud inferior derecha, longitud inferior derecha.
* **🔍 hash:** Hash del atributo de datos integer
* **✔️ has_ipv6:** Verdadero/Falso booleano
* **🖼️ has_screenshot:** Verdadero/Falso booleano
* **🖥️ server:** Dispositivos o servidores que contienen una bandera específica de cabecera de servidor string
* **🌐 hostname:** Nombre completo del host para el dispositivo string
* **🔌 ip:** Alias para el filtro de red string
* **📡 isp:** ISP que gestiona el bloque de red string
* **📡 net:** Rango de red en notación CIDR (por ejemplo, 199.4.1.0/24) string
* **🏢 org:** Organización asignada al bloque de red string
* **🖥️ os:** Sistema operativo string
* **🔢 port:** Número de puerto para el servicio integer
* **📪 postal:** Código postal (solo EE. UU.) string
* **🛠️ product:** Nombre del software/producto que proporciona el banner string
* **🌍 region:** Nombre de la región/estado string
* **🗺️ state:** Alias para región string
* **🆚 version:** Versión del producto string
* **🔒 vuln:** ID de CVE para una vulnerabilidad string
