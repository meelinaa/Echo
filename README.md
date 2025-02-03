# Echo - Fullstack Health Tracker 📊

<img src="/README-images/Banner.png" alt="Beschreibung" style="width: 100%; display: block;">

Echo ist eine interaktive Webanwendung, die Nutzern hilft, ihre mentale und körperliche Gesundheit zu dokumentieren und langfristig zu analysieren. Durch eine benutzerfreundliche Oberfläche können tägliche Gesundheitsdaten wie Stimmung, Schritte oder Schlaf erfasst und Trends leicht nachvollzogen werden.

## Features

- **Tägliche Datenerfassung:** Eingabe von Schlaf, Trinken, Schritte, Sport und Gedanken.
- **Benutzerkonto:** Verwaltung von persönlichen Daten wie Größe, Gewicht und Alter.
- **Reaktionsschnelles Frontend:** Entwickelt mit React, HTML und CSS für eine intuitive Benutzererfahrung.
- **Backend-Integration:** RESTful APIs für die Kommunikation zwischen Frontend und Backend.
- **Datenbank:** Speicherung und Verwaltung der Daten mit PostgreSQL, bereitgestellt via Docker.
- **Testing:** Unit-Tests sind implementiert, Integrationstests sind in Planung.
- **Erweiterbarkeit:** Die Architektur erlaubt einfache Integration zusätzlicher Features.
  
## Geplante Features
- **Mentale Gesundheitschecks:** Tests zur Selbsteinschätzung von Depression, Burnout und anderen psychischen Faktoren.
- **Datenanalyse:** Anzeige von Durchschnittswerten sowie Erkennung von Regelmäßigkeiten oder Abweichungen in den erfassten Daten.
- **Datenvisualisierung:** Interaktive Diagramme zur Darstellung von Trends und Durchschnittswerten.

## Projektstruktur

Da Frontend und Backend in separaten Repositories gepflegt werden, finden Sie die aktuellen Inhalte hier:
- [Frontend Repository](https://github.com/meelinaa/EchoFrontend)
- [Backend Repository](https://github.com/meelinaa/EchoBackend)

## Technologien

- ⚛️ **Frontend:** React (JavaScript ES6+, HTML, CSS)
- ☕ **Backend:** Java mit Spring Boot, Spring Data JPA, Lombok
- 🔗 **API:** RESTful Services
- 🗄️ **Datenbank:** PostgreSQL (via Docker)
- 🐳 **Containerisierung:** Docker
- ✅ **Testing:** JUnit und Mockito für das Backend, Jest für das Frontend

## Software-Entwicklung und Planung

Dieses Projekt wurde vollständig von Grund auf selbst geplant und entwickelt. Dazu gehören:

- **Planung und Architektur:** Erstellung der gesamten Software-Architektur, einschließlich der Backend- und Frontend-Struktur.
- **Coding-Praktiken:** Verwendung von Clean Code-Prinzipien und bewährten Design Patterns.
- **Iterative Entwicklung:** Features werden schrittweise hinzugefügt, basierend auf einem agilen Entwicklungsansatz.
- **Lernfokus:** Dieses Projekt vertieft meine Fähigkeiten in der Fullstack-Entwicklung, einschließlich API-Design, Datenbankintegration und Frontend-Design.

## Screenshots

1. **Hauptseite:** Übersicht der täglichen Einträge
<img src="/README-images/bento1.png" alt="Hauptseite" style="width: 100%; display: block;">

2. **Bento:** Bearbeitungsmodus für die jeweiligen Bento Cards
<img src="/README-images/bento2.png" alt="Hauptseite" style="width: 100%; display: block;">


## 🛠️ Setup & Installation
### Backend starten
1. **Projekt klonen**
   ```sh
   git clone https://github.com/meelinaa/EchoFullstack.git
   cd EchoFullstack 
   ```
2. **Docker-Container für PostgreSQL starten**
   ```sh
   docker-compose up -d
   docker run --name echo_postgres -e POSTGRES_USER=Echo -e POSTGRES_PASSWORD=passwordEcho -e POSTGRES_DB=databaseEcho -p 5433:5432 -d postgres
   ```
3. **Spring Boot Anwendung starten**
   ```sh
   mvn spring-boot:run
   ```

### Frontend starten (Geplant)
1. **In das Frontend-Verzeichnis wechseln**
   ```sh
   cd frontend
   ```
2. **Node-Module installieren**
   ```sh
   npm install
   ```
3. **React App starten**
   ```sh
   npm start
   ```
---

## 🌐 Lizenz & Kontakt
Dieses Projekt steht unter der [MIT-Lizenz](LICENSE). 

Kontakt: [E-Mail](mailto:melinakiefer@hotmail.de) | [GitHub](https://github.com/meelinaa)
