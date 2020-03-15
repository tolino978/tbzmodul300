﻿# Vagrant Web Server
Vagrant Web Server ist ein standart Ubuntu 16.04 LTS Server, welcher Apache installiert hat.
## Installation
Vagrant [herunterladen](https://www.vagrantup.com/) und installieren

Das GitHub Verzeichniss herunterladen oder klonen

Ein Terminal im oben erwähnten Verzeichniss öffnen

Folgenden Befehl ausführen:
```sh
vagrant up
```
Der Webserver ist unter http://localhost:8080 erreichbar
## Konfiguration
Standardmässig wird die Systemdokumentation als Webseite angezeigt. Wenn ein eigenes HTML File verwendet werden soll, kann einfach das index.html im Projektverzeichniss ersetzt werden.

Falls der Port 8080 auf dem Hostgerät bereits besetzt wird, wird automatisch ein anderer gewählt.

 
