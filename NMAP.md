# Segurtasuna

Gure ip lortzeko ifconfig komandoa erabili (inet ip da gurea, 172.17.0.1)
  
ping egela.ehu.eus --> para sacar la IP de egela (158.227.0.93)

nmap --open 158.227.0.93 --> para mirar los puertos abiertos en egela estan abiertos

nmap -sV 158.227.0.93 --> lo mismo pero con la version

traceroute 158.227.0.93 --> aktiboak dauden makinak nipe makinatik egelara

nmap --open 10.40.70.4 --> sareak duen portu aktiboak

nmap -sV 10.40.70.4 -->berdin pero con la version

sudo nmap -O 10.40.70.4  -→ sistema eragilea

sudo nmap -O 35.210.82.142 --> google cloudeko sistema eragilea

sudo nmap  -O scanme.nmap.org 

Portuak ikusterakoan STATE open jartzen badu firewall-ik ez dagoela esan nahi du.
STATE filtered jartzen badu, ordea, firewall dagoela esan nahi du.
