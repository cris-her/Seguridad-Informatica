# Seguridad-Informatica
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
  
