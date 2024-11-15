# KN01:Virtualisierung
## Hypervisor
### Type 1
---
Ein Hypervisor des Typs 1 oder ein Bare-Metal-Hypervisor interagiert direkt mit der zugrunde liegenden Host-Hardware. Ein Bare-Metal-Hypervisor wird direkt auf der physischen Hardware des Host-Computer installiert, nicht über ein Betriebssystem. In einigen Fällen ist ein Hypervisor vom Typ 1 in die Firmware des Computers eingebettet.
<br><br>
Der Hypervisor vom Typ 1 verhandelt direkt mit der Host-Hardware, um den VMs dedizierte Ressourcen zuzuweisen. Er kann auch flexibel Ressourcen gemeinsam nutzen, je nach den verschiedenen VM-Anforderungen.
<br><br>
### Type 2
---
Ein Hypervisor vom Typ 2 oder ein gehosteter Hypervisor interagiert mit der zugrunde liegenden Hardware des Host-Computer über das Betriebssystem des Host-Rechners.Sie installieren ihn auf dem Rechner, wo er als Anwendung ausgeführt wird.
<br><br>
Der Typ-2-Hypervisor verhandelt mit dem Betriebssystem, um die zugrunde liegenden Systemressourcen zu erhalten. Das Host-Betriebssystem räumt jedoch seinen eigenen Funktionen und Anwendungen Vorrang vor den virtuellen Workloads ein.
<br><br>
### Tabelle Zusammenfassung
---
|               | Type 1 hypervisor | Type 2 hypervisor |
| ------------- | ------------- | ------------- | 
| Auch bekannt als | Bare Metal Hypervisor. | Gehostete Hypervisor. |
| Läuft auf | Zugrunde liegende physische <br> Hardware des Hostsystems. | Zugrunde liegendes <br> Betriebssystem (Host OS). |
| Am besten geeignet für | Große, ressourcenintensive Arbeitslasten <br> oder solche mit fester Laufzeit. | Desktop- und Entwicklungsumgebungen. |
| Kann sie über dedizierte <br> Ressourcen verhandeln? | Ja | Nein |
| Erforderliche Kenntnisse | Systemadministrator-Ebene. | Grundlegende Benutzerkenntnisse. |
| Beispiele | VMware ESXi, Microsoft Hyper-V, KVM | Oracle VM VirtualBox, VMware Workstation, <br> Microsoft Virtual PC |

## Virtualisierungssoftware

### Host System Information
- OS: Windows 11
- OS Version: 23H2
- RAM: 32GB
- SSD: 952GB, davon frei: 472GB
- CPU: AMD Ryzen 7 7840U w/ Radeon 780M Graphics
- CPU Core Anzahl: 8
- CPU Thread Anzahl: 16
<br><br>

CPU INFO
![CPU INFO](<Screenshot 2024-11-15 152507.png>)
<br><br>

RAM INFO
![RAM INFO](<Screenshot 2024-11-15 152728.png>)
<br><br>

### Virtual System Information
- Virtual Hypervisor: VMWare Workstation
- OS: Ubuntu
- OS Version 22.04.3
- RAM: 16GB
- SSD: 200GB, davon frei: 12.5GB
- CPU Core Anzahl: 4
<br><br>

Virtual OS INFO
![alt text](<Screenshot 2024-11-15 153003.png>)