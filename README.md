# REQ-OSINT y Ciberinvestigación
------------------------------------
### Distribución Kali Linux para ivestigación OSINT

### OSINT: El Arte de la Inteligencia Abierta con Herramientas Especializadas
En la inmensidad de datos digitales en el que nos encontramos inmersos, la información es la moneda de cambio más valiosa. En este contexto, el OSINT (Open Source Intelligence), o inteligencia de fuentes abiertas, emerge como una disciplina crucial en el ámbito de la seguridad, la investigación y la toma de decisiones estratégicas. 
#
En la actualidad, escasean los proyectos que integran las herramientas esenciales para el trabajo de un analista de inteligencia, especialmente aquellos desarrollados en castellano. Esto nos obliga a recurrir a distribuciones generalistas, o a instalar manualmente las herramientas en un sistema operativo limpio.

El objetivo principal de este Trabajo  es doble:

  •	Crear una distribución específica: Desarrollar una distribución que reúna y ponga a disposición de aquellos que lo necesiten las herramientas consideradas más necesarias para un analista de inteligencia, y mejorar la capacidad de realizar OSINT de manera efectiva con un impacto directo en la detección y mitigación de amenazas, estando estructurada por categorías claramente definidas para facilitar el acceso a los usuarios , permitiendo una navegación intuitiva y eficiente.

  •	Garantizar continuidad al proyecto: Establecer mecanismos que aseguren la sostenibilidad a largo plazo del proyecto, evitando que caiga en el olvido.

Es fundamental abordar la carencia de soluciones integrales en este ámbito, facilitando a los profesionales una plataforma adaptada a sus necesidades


![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/aaab72a1-b33f-45e5-9f1f-d1e2aec795dc)

## NAVEGADORES
---------
LA distribución  cuenta con 4 navegadores distintos que son: 
#### - Chromium
#### - Google Chrome
#### - Firefox
#### - Tor Browser
![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/f48939a1-04a1-45b0-a2c2-bc9e3c3520a0)

## HERRAMIENTAS
---------
La distribución cuenta con una gran cantida de herramientas, las cuales estan distribuidas por categorías y son accesibles a través del menu XFCE.

### Recopilación de información 
![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/1dadff66-ebf3-40b2-b1df-de5389013c5c)

- [**Maltego**]([url](https://www.maltego.com/categories/osint/)) : Utilizada para la recopilación y visualización de información sobre objetivos específicos en Internet. Utiliza técnicas de minería de datos para recopilar información de fuentes públicas, como redes sociales, bases de datos públicas y motores de búsqueda, y la presenta de manera gráfica para facilitar su análisis
- [**TheHarvester**]([url](https://github.com/laramies/theHarvester)) : Diseñada para la recopilación de información de fuentes públicas en línea. Permite a los investigadores recopilar direcciones de correo electrónico, nombres de dominio, subdominios, hosts virtuales y nombres de usuarios de diversas fuentes, como motores de búsqueda, redes sociales y servicios de correo electrónico
- [**Recon-ng**]([url](https://github.com/lanmaster53/recon-ng)) : Es una herramienta de código abierto de reconocimiento de información diseñada para recopilar datos de fuentes públicas y privadas en línea. Utiliza módulos de reconstrucción específicos para recopilar información sobre objetivos, como direcciones de correo electrónico, subdominios, nombres de host y perfiles de redes sociales. Recon-ng es altamente modular y puede ampliarse fácilmente con nuevos módulos desarrollados por la comunidad
- [**Sn1per**]([url](https://github.com/1N3/Sn1per)) : Herramienta de penetración de código abierto diseñada para facilitar pruebas de penetración y evaluaciones de seguridad de redes y sistemas. Desarrollada por 1N3@CrowdShield, Sn1per automatiza numerosas fases del proceso de pentesting, incluida la recopilación de información, el escaneo de vulnerabilidades, la explotación y la generación de informes. 
- [**Spiderfoot**]([url](https://github.com/smicallef/spiderfoot)) :Automatiza la recopilación de información sobre objetivos específicos en internet. Utiliza múltiples fuentes de datos públicas y privadas para extraer información relevante sobre dominios, direcciones IP, direcciones de correo electrónico y otros elementos de interés. SpiderFoot realiza un análisis exhaustivo de la superficie de ataque potencial de una organización o entidad, identificando posibles vulnerabilidades y amenazas

  #### Herramientas Web
  Habilitadas en su carpeta  dentro del navegador Chromium.
  ![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/af91a32c-5b21-4dcc-a9c5-bb8590661676)

- [**Shodan**]( https://www.shodan.io/)   
- [**OSINT.Industries**]( https://osint.industries/) 
- [**Sherlockeye**](https://sherlockeye.io/) 
- [**Censys**]( https://search.censys.io/ )
- [**Pipl**]( https://pipl.com/) 
    
### Análisis de Redes Sociales
  ![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/16da7ffa-9092-4d80-8842-389cffa8c351)

- [**Sherlock**]([url](https://github.com/sherlock-project/sherlock)) : Localiza perfiles de redes sociales asociados a un nombre de usuario en múltiples plataformas en línea. Desarrollada en Python, Sherlock automatiza la tarea de búsqueda de perfiles en redes sociales, permitiendo a los usuarios encontrar perfiles potenciales en sitios populares como Facebook, Instagram, Twitter, LinkedIn, Reddit, y muchos más
- [**OSINT Framework**]([url](https://osintframework.com/)) :  Plataforma que centraliza y organiza herramientas y recursos de fuentes abiertas en línea para facilitar la investigación y recopilación de información.
- [**User recon**]([url](https://github.com/vijaysahuofficial/UserReCon)) : Busca perfiles en redes sociales utilizando un nombre de usuario específico. Permite a los usuarios buscar perfiles en una amplia gama de plataformas de redes sociales y servicios en línea, incluyendo Facebook, Instagram, Twitter, LinkedIn
- [**Social Analizer**]([url](https://github.com/qeeqbox/social-analyzer)) :Analizar perfiles de redes sociales en busca de posibles riesgos de seguridad o privacidad. Esta herramienta está diseñada para ayudar a los usuarios a evaluar la exposición de su información personal en línea y a tomar medidas para proteger su privacidad y seguridad.

  #### Herramientas Web
  Habilitadas en su carpeta  dentro del navegador Chromium.
  ![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/3278e69c-83e3-425c-8fb9-889da142c9b0)

- [**NodeXL**]( https://nodexl.com/) 
- [**IntelTechniques**]( https://inteltechniques.com/)
- [**Usersearch**]( https://usersearch.org/ )
- [**Instant Username Search**]( https://instantusername.com/#/)
- [**Namechk**]( https://namechk.com/)

### Análisis de Metadatos y Archivos
![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/8848da7d-c534-4591-ab79-7b3cbbccd430)

- [**Exiftool**]([url](https://github.com/exiftool/exiftool)) : Herramienta de línea de comandos que se utiliza para leer, escribir y editar metadatos incrustados en archivos digitales, como imágenes, audio, video y documentos. Los metadatos son información adicional sobre el archivo que puede incluir detalles como la fecha y la hora de creación, la ubicación geográfica, la cámara utilizada para tomar una fotografía, la configuración de la cámara, la información del autor 
- [**Metagoofil**]([url](https://github.com/opsdisk/metagoofil)) : Extrae metadatos de archivos públicos almacenados en sistemas de archivos compartidos, como servidores FTP o servidores web. Esta herramienta utiliza técnicas de búsqueda en Internet para recopilar documentos de los servidores y extraer información importante de los metadatos incrustados en esos documentos.
- [**Binwalk**]([url](https://github.com/ReFirmLabs/binwalk)) : Herramienta es especialmente útil para investigadores de seguridad y profesionales de la informática forense que necesitan analizar archivos binarios para buscar vulnerabilidades, extraer datos incrustados o realizar ingeniería inversa en dispositivos integrados.
- [**Foremost**]([url](https://github.com/gerryamurphy/Foremost)) : Herramienta de recuperación de datos y análisis forense digital utilizada principalmente en sistemas operativos basados en Unix, como Linux. Su función principal es extraer archivos eliminados o perdidos de sistemas de archivos, particiones y dispositivos de almacenamiento. Foremost es muy útil en investigaciones forenses digitales para recuperar evidencia de archivos, como imágenes, documentos, archivos de audio y video, entre otros, incluso si han sido eliminados o están fragmentados en el disco.

#### Herramientas Web
  Habilitadas en su carpeta  dentro del navegador Chromium.
  ![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/9c56805f-e142-498f-9b77-151e755765a5)

- [**Forensically**]( https://29a.ch/photo-forensics/#forensic-magnifier) 
- [**TinEye**](https://tineye.com/ )
- [**Fotoforensics**](https://fotoforensics.com/ )
- [**Jimpl**](https://jimpl.com/ )
- [**Metadato**](https://www.metadato.org/ )
- [**Exifdata**]( https://exifdata.com/)
  
### Análisis de Vulnerabilidades y Exploits
![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/23d69071-5b46-46f9-bbeb-5fd405e91dd1)

- [**Nmap**]([url](https://github.com/nmap/nmap)) : "Network Mapper", es una herramienta de código abierto ampliamente utilizada para exploración de redes y auditoría de seguridad. Permite a los administradores de sistemas descubrir dispositivos en una red, mapear la topología de la red, y encontrar servicios y puertos abiertos en los sistemas. Nmap es conocido por su versatilidad y potencia, ofreciendo opciones avanzadas para escaneos de red, detección de sistemas operativos, detección de servicios y scripts personalizados para realizar análisis detallados
- [**Track-IP**]([url](https://github.com/htr-tech/track-ip)) : Rastrea la ubicación física de una dirección IP en Internet. A través del uso de bases de datos y algoritmos de geolocalización, esta herramienta puede proporcionar información sobre la ubicación aproximada de una dirección IP, incluyendo el país, región, ciudad e incluso la latitud y longitud.
- [**Owasp Zap**]([url](https://github.com/zaproxy/zaproxy)) : Herramienta de seguridad de aplicaciones web de código abierto que ayuda a identificar y corregir vulnerabilidades en aplicaciones web. Ofrece funciones como escaneo de vulnerabilidades, interceptación de proxy, spidering, creación de scripts y generación de informes de seguridad. 
- [**Wfuzz**]([url](https://github.com/xmendez/wfuzz)) : Utilizada para pruebas de seguridad y análisis de vulnerabilidades en aplicaciones web. Permite automatizar y realizar ataques de fuerza bruta, fuzzing y enumeración de directorios y archivos en una aplicación web. WFuzz es altamente configurable y flexible, lo que permite a los usuarios realizar una amplia gama de pruebas de seguridad, como la identificación de puntos débiles en la autenticación, la búsqueda de archivos y directorios ocultos.
- [**Skipfish**]([url](https://github.com/spinkham/skipfish)) : Herramienta de escaneo de seguridad de aplicaciones web de código abierto desarrollada por Google. Está diseñada para identificar vulnerabilidades en aplicaciones web mediante la realización de escaneos exhaustivos y automatizados. Skipfish realiza un análisis profundo de la estructura y el comportamiento de una aplicación web, buscando posibles puntos de entrada, vulnerabilidades de inyección, errores de configuración y otros problemas de seguridad comunes
- [**Wapiti**]([url](https://github.com/wapiti-scanner/wapiti)) : Realiza pruebas de seguridad en aplicaciones web. Está diseñada para identificar y explotar vulnerabilidades comunes de seguridad en aplicaciones web, como inyecciones SQL, cross-site scripting (XSS), cross-site request forgery (CSRF)
- [**Nikto**]([url](https://github.com/sullo/nikto)) : Escaneo de seguridad de código abierto altamente reconocida en la comunidad de ciberseguridad. Su propósito principal es realizar un análisis exhaustivo de servidores web en busca de posibles vulnerabilidades y configuraciones erróneas que podrían ser explotadas por atacantes. Desarrollado por Chris Sullo, Nikto se ha convertido en una herramienta esencial para profesionales de seguridad, auditores de sistemas y administradores de servidores.

#### Herramientas Web
  Habilitadas en su carpeta  dentro del navegador Chromium.
![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/9a4225b7-d2f5-499e-a2de-fea2a55980e8)

- [**Web-check**](https://web-check.xyz/)
  
 ### Monitoreo de Amenazas e Inteligencia
 ![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/00653f1f-0ad9-4406-a61a-32446e213654)

- [**Holehe**]([url](https://github.com/megadose/holehe)): Herramienta de análisis de seguridad diseñada para ayudar en la identificación de vulnerabilidades y amenazas en sistemas informáticos y redes. 
Se emplea para recopilar información sobre posibles amenazas en línea, como actividades maliciosas, ataques cibernéticos o comportamientos sospechosos en la red. 
- [**YARA**]([url](https://github.com/Yara-Rules/rules)): . Permite a los investigadores y analistas de seguridad crear reglas para identificar y clasificar archivos basados en patrones de texto, cadenas hexadecimales y estructuras específicas. Estas reglas pueden ser utilizadas para escanear grandes volúmenes de archivos en busca de indicadores de compromiso (IOCs), como firmas de malware, comportamientos maliciosos o características específicas de malware conocido
- [**Mr.Holmes**]([url](https://github.com/Lucksi/Mr.Holmes)): Ofrece capacidades de monitoreo y detección de amenazas en tiempo real, con un enfoque en la inteligencia de amenazas y la visualización de datos. Mr. Holmes se centra en identificar y responder a actividades maliciosas en redes empresariales, utilizando tecnologías modernas y algoritmos de detección de intrusiones para proteger contra una amplia variedad de amenazas cibernéticas
- [**Suricata**]([url](https://github.com/OISF/suricata)): Es un motor de detección de intrusiones (IDS) y prevención de intrusiones (IPS) de código abierto, diseñado para monitorear y proteger redes contra actividades maliciosas. Utiliza un enfoque basado en reglas para analizar el tráfico de red en tiempo real y detectar posibles amenazas como intrusiones, exploits, malware y ataques de denegación de servicio.
- [**Netdiscover**]([url](https://github.com/netdiscover-scanner/netdiscover)): Utilizada para escanear y descubrir dispositivos en una red local. Esta herramienta realiza un barrido de red pasivo, enviando y recibiendo paquetes ARP para identificar dispositivos que están conectados a la misma red.

  #### Herramientas Web
  Habilitadas en su carpeta  dentro del navegador Chromium.
![image](https://github.com/jrequena69/REQ-OSINT/assets/54437813/05dbb6a0-776c-4392-aa93-1dc1411c846f)

- [**OTX AlienVault**](https://otx.alienvault.com/)
- [**VirusTotal**](https://www.virustotal.com/)
- [**Recorded Future**](https://go.recordedfuture.com/get-started#demo-form/)

### Descarga distribución 
------------


### Video demostración .
------------

  
