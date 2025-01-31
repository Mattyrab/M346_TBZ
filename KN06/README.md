# KN06: Skalierung

## Installation App

#### Was ist ein Reverse Proxy?

Ein Reverse Proxy ist ein Server, der Anfragen aus dem Internet an die Webserver umleitet und verteilt.

### Swagger
![Swagger](<Screenshot 2025-01-30 203721.png>)

Resultate für Produkte mit GET Methode

![MongoDB Results](<Screenshot 2025-01-30 203744.png>)

### MongoDB
![MongoDB](<Screenshot 2025-01-30 234951.png>)

### Cloud-Init
#### Welche(r) Teil(e) macht/machen hier überhaupt keinen Sinn in einer produktiven Umgebung?

- Der DB Passwort ist nicht verschlüsselt und wird über eine unsichere Verbindung zur DB Server geschickt.
- Es sollte HTTPS anstatt HTTP verwendet, um empfindliche Daten zu schützen.
- Der Benützer auf der Web Server hat unbegrenzte Zugang zur der System, was eine Sicherheitsrisko ist.
- Root würde nicht deaktiviert, was auch ein Sicherheitsrisko ist.

## Vertikale Skalierung

#### Instanz Volume vergrössern
![Instance Volume Before](<Screenshot 2025-01-31 000643.png>)

Schritte:
- Instanz anhalten
- Navigieren Sie zu den Details der angehängten Volumen und klicken Sie auf die Modifizieren-Taste
- Ändern Sie die Größe des Volumens und speichern Sie die Änderung
- Warten bis der Änderung fertig ist und danach der Insantz wieder Starten.

![Instance Volume After](<Screenshot 2025-01-31 002249.png>)

#### Instanz Type ändern
![Instance Volume Before](<Screenshot 2025-01-31 123359.png>)

Schritte:
- Instanz anhalten
- Navigieren Sie zu den Instanz-Einstellungen durch der Aktion Taste und klicken Sie auf die "Instanztyp Ändern"
- Ändern Sie der Instanztyp und speichern Sie die Änderung
- Warten bis der Änderung fertig ist und danach der Insantz wieder Starten.

![Instance Volume After](<Screenshot 2025-01-31 124057.png>)


## Horizontale Skalierung

