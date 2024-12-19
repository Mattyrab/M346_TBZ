# KNO4: Cloud-init und AWS

## SSH-Key und Cloud-init

![Instance details](<Screenshot 2024-12-13 130444.png>)

Falsche Schlüssel verwendet.
![Login Fail](<Screenshot 2024-12-13 130712.png>)

Richtige Schlüssel verwendet (eigene gesetzt im user-data).
![Login Success](<Screenshot 2024-12-13 130629.png>)

(Der OS wurde nachher korrigiert auf Ubuntu 24.04 für alle Instanzen.)

## Template

[Cloud Init YAML](cloud-init.yaml)

## Installation automatisieren

[Cloud Init YAML for Web](cloud-init-web.yaml)<br>
![User Data Web Config](<Screenshot 2024-12-19 104525.png>)

[Cloud Init YAML for DB](cloud-init-db.yaml)
![User Data DB Config](<Screenshot 2024-12-19 103554.png>)

## Database

Eingeloggt im DB durch der Browser
![DB in Browser](<Screenshot 2024-12-19 105707.png>)
