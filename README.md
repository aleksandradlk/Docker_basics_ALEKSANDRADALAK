# Docker_basics_ALEKSANDRADALAK

# Docker Basics: Docker Setup und Anwendungen

Serveranwendungen:

## Pi-hole
**Pi-hole** Ein Werbeblocker auf DNS-Ebene. Es filtert Werbung und Tracking-Domains und blockiert unerwünschte Inhalte in deinem Netzwerk. Man kann den DNS-Verkehr im Dashboard überwachen und Blocklisten anpassen.

**Webinterface**: `http://localhost/admin`  
**Passwort**: `cjW9VNPe`

## Portainer
**Portainer** Eine Webanwendung zur Verwaltung von Docker-Containern. Sie bietet eine benutzerfreundliche Oberfläche, um Container zu starten, zu stoppen und zu überwachen.

**Webinterface**: `http://localhost:9000`

## Watchtower
**Watchtower** Sorgt dafür, dass deine Docker-Container immer aktuell sind. Es prüft regelmäßig, ob es neue Versionen der verwendeten Images gibt, und aktualisiert die Container automatisch.

**Webinterface**: Kein Webinterface, läuft im Hintergrund.

## Nginx
**Nginx** Ein leistungsstarker Webserver, der auch als Reverse Proxy und Load Balancer dient. In diesem Fall läuft er als einfacher Webserver für HTTP-Anfragen.

**Webinterface**: Je nach Konfiguration, z.B. `http://localhost:8080`
