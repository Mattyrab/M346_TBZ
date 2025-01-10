# KN05: Netzwerk / Sicherheit

## Grundbegriffe und private IP wählen

### Public IP
Die öffentliche IP-Adresse bietet grundsätzlich eine weltweit erkennbare Adresse die es alle Geräten ermöglicht, Daten oder Pakete über eine Vielzahl von Netzen zu übertragen und zu empfangen. 

### Private IP
Private IP-Adressen sind die Adressen, die innerhalb des lokalen Netzes funktionieren. Diese Adressen sind im Internet nicht weiterleitbar. Die Adresse wird vom Netzwerk-Router an der Gerät vergeben.

### Static IP
Eine statische IP-Adresse ist eine IP-Adresse, die sich nie ändert und von Tools wie DHCP nicht beeinflusst wird. Ein Gerät mit statischer IP-Adressierung behält seine IP-Adresse bei, egal wie oft es neu gestartet wird oder wie lange es offline ist.

### VPC = Virutal Private Cloud
Ein VPC ist ein virtuelles Netzwerk, das logisch von allen anderen Public Cloud- Kunden isoliert ist und einen privaten, sicheren Bereich in der Public Cloud schafft.

### Subnetz
Ein Subnetz oder Subnetz ist ein Netz innerhalb eines Netzes. Subnetze machen Netzwerke effizienter. Durch Subnetze kann der Netzwerkverkehr eine kürzere Strecke zurücklegen, ohne überflüssige Router zu durchqueren, um sein Ziel zu erreichen.

### Private IPs für Instanzen

KN04-WEB Private IP: 172.31.32.20
KN04-DB Private IP: 172.31.32.30

## Objekte und Instanzen erstellen

Sicherheitsgruppen:
![Security Groups](<Screenshot 2024-12-20 133457.png>)

Inbound-Regeln für KN05-WEB
![Inboud Rules Web KN05](<Screenshot 2025-01-10 141234.png>)

Inbound-Regeln für KN05-DB
![Inboud Rules DB KN05](<Screenshot 2025-01-10 152457.png>)


Hier sieht man das nur der Web Instanz eine öffentliche IP hat, die auch statisch ist, und das beide Instanzen in der gleiche Subnetz sind.
![Instances](<Screenshot 2025-01-10 141049.png>)