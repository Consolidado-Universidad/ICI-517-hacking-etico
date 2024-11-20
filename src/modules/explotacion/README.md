Tener instalado kali
Exploit-DB

app version exploit db

https://www.exploit-db.com

Para saber la version de la app, utilizamos nmap

Esto nos dirá la versión de la app en el puerto 80
nmap -sV -p 80 <dirección_ip>

ejecutar exploit 

python exploit.py -H <dirección_ip> -p 80 -f <fichero>


nmap -p 21 –script=vuln IP_objetivo