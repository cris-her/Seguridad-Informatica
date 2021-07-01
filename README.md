# Seguridad-Informatica

* Terminal y línea de comandos
* Básico de seguridad informática para empresas
* Preparación para la certificación en la norma ISO 27001
* DLP: Prevención de pérdida de datos
* Redes informáticas de internet
* Administración de servidores linux
* Introducción a la seguridad informática
* Fundamentos de pentesting
* Pentesting a redes
* Informática forense
* Hacking ético
* Análisis de malware
* Análisis de malware para dispositivos móviles
* Avanzado de redes de internet
* Autenticación con OAuth

Resize the standard Ubuntu Desktop inside of Virtualbox: sudo apt-get install virtualbox-guest-dkms virtualbox-guest-utils virtualbox-guest-x11

Código del curso de seguridad 
*Busquedas*
 -site: Para busquedas en dominio particular
 -intitle: Palabras en especifico en el titulo
 -inurl: Que traiga ese fragmento en la url 
 -cache: 
 -filetype: 
 https://www.exploit-db.com
 
 *Pentesting*
  theharvster: para obyener correos electronicos con ciertos dominios 
 -d: El dominio a buscar o la compañia
 -b: fuente de datos
 -s: Comienza en el numero de resultado
 -v: verifica el nombre del host via dns resolucion and busqueda por virtual host 
 -f: guarda los resultados dentro de un HTML y XML 
 -n: Realiza una consulta inversa de DNS en todos los rangos descubiertos 
 -c: realiza una fuerza bruta de DNS por el nombre del dominio 
 -t: Realiza un TLD a una DNS a un descubrimiento de expansion 
 -e: usa este DNS server
 -l: limita el numero de resultados
 -h: usa la base de datos SHODAN a una consulta hosts descubiertos
 min 14:49
 
 
 Netcraft: Nos permite saber qué servicios o que
aplicaciones está corriendo un sitio web en específico.


 whois: información de registro de DNS dentro de una base de datos de dominios en particular
 
  
 host: busqueda de IP
 -dnsenum: para enlistar todos los dominios
 --server: para especificar el servidor
 -dnsmap: Combinaciones posibles en nombres de dominio
     -w archivo de lista de palabras
     -r archivo de resultados regulares
     -c archivo de resultados csv
     -d retrasa milisegundos
     -i ips para ignorar
     min 20:23
 
  
-nslookup para busquedas rapidas 

- dig estructura de una nuswuqeda en los servicios de DNS, Query, Answer, Authority, Additional  
     +noall
     +answer
     +authority
     -t para que tipos de registro quiero obtener

# fierce


- man httrack
-les index 

- man fping 
29:18 

-cat hosts

-nmap  -Pn -p-  -p58175 -p22 -sT -sn -iL -sU -p14-50  -sX -p1-50 -sN 
--script banner -script vuln  

-cat nmap

Nessus: tenable.com

-UDP

 # apt install openvas   # openvas-setup #openvasmd -create-user 
 servidor local 127.0.0.1
 
 metasploit 
 msfconsole
  -search ms08-067
  -use exploit
  - show payloads
  -set payload windows
  - set RHOST 
  -exploit
  -hashdump
 - search netapi
 -set payload windows windows/meterpreter/bind_tcp
 
 
 Armitage
 
 creacion de diccionarios
 -man crunch 
 -crunch 1 4 | less
  

medusa
less password.lst
cp password.lest~/medusa
cp unix_users~/medusa
-h
-U
  
-hashes 

ophcrack


iwconfig
 -airmon -ng stop
 -airmon -ng start wlan0 2
 
aireplay
-ng --test wlan0mon

harvesting ip addres 
ping
setoolkit
2
3
1


 nikto 
  -h
  
  
WebScarab


golismero
scan webscantest.com -e  nikito -espider   -nd (no database)

192.168.20.23/    DVWA



---------------------------

Hacking etico 

-ifconfig


Para obtener informacion del servidor: ../../../../etc/
Inyeccion Para obtener la informacion de usuarios y contraseña ' or 1=1 --
Cross Site reflejado <script> alert(1)</script>
 
osint Framework 

nikto -h
nikto -h -o html
siperfoot:
pip 
./sf.py
apt


nmap escaneo de red


arpsfpoff -i enp0s3 -t -r 
