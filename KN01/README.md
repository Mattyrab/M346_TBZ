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
