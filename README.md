# Echo - Fullstack Health Tracker

<img src="/README-images/banner.png" alt="Beschreibung" style="width: 100%; display: block;">

## ✨ Projektübersicht  
Echo ist ein **ganzheitlicher Fullstack Health-Tracker**, der Nutzern hilft, ihre **mentale** und **körperliche Gesundheit** täglich festzuhalten, nachzuverfolgen und besser zu verstehen. Dabei geht es nicht nur darum, einzelne Datenpunkte zu speichern, sondern durch einfache Übersichten und Analysen Muster und Entwicklungen im eigenen Wohlbefinden zu erkennen.

Das Ziel ist eine **Single-Page-Webanwendung**, die **tägliche Einträge** speichert und langfristig **Analysen und Auswertungen** der Daten ermöglicht. 

## 🕸️ Projektstruktur

Da Frontend und Backend in separaten Repositories gepflegt werden, finden Sie die aktuellen Inhalte hier:
- [Frontend Repository](https://github.com/meelinaa/EchoFrontend)  
- [Backend Repository](https://github.com/meelinaa/EchoBackend)

## 💪 Features & Funktionalität
Echo erlaubt es Nutzern, verschiedene Gesundheitsdaten täglich zu erfassen:

- **Allgemeine Daten**: Größe, Gewicht, Alter, BMI
- **Mentale Daten**: Stimmung, Gedanken, Träume
- **Körperliche Daten**: Getrunkene Flüssigkeitsmenge, Schritte, Schlafdauer, Sportaktivitäten

Die Daten werden täglich abgefragt und mit **PUT- & GET-Requests** gespeichert bzw. abgerufen. 
Zukünftige Erweiterungen umfassen:
- **Statistiken & Analysen**: Durchschnittswerte für verschiedene Kategorien
- **Visualisierung von Daten**: Diagramme zur Darstellung von Trends
- **Mentale Gesundheitschecks**: Tests zur Selbsteinschätzung von Depression, Burnout, ADHS und anderen psychischen Faktoren

## 👩‍💻 Geplantes Frontend
Das Frontend wird mit **React** als **Single-Page-Webanwendung (SPA)** entwickelt und enthält folgende Seiten:

### 🌍 Hauptseite
- Erfassung der **täglichen Einträge** (Schlaf, Trinken, Schritte, Sport, Gedanken)

### 👤 Benutzerseite
- Verwaltung der **Allgemeinen Daten** (Gewicht, Größe, Alter, etc.)
- Anpassung individueller Einstellungen

### 🌟 Analysen & Verlauf
- Historische **Datenvisualisierung** 
- **Durchschnittswerte & Prognosen**
- Interaktive Diagramme & Tabellen zur Darstellung der Datenentwicklung

🖌️ **Styling:** 
- Design soll **minimalistisch, modern und ästhetisch** sein 
- **CSS** für Styling
- Responsive Design **(Mobile-Ansicht optional geplant)** 

## 🔬 Technologie-Stack (Fullstack)
### **Backend** 
- **Java 21** & **Spring Boot** (REST API)  
- **Spring Data JPA** (ORM)  
- **PostgreSQL** (Docker-Container)  
- **JUnit & Mockito**  
- **Lombok** zur Code-Optimierung  

### **Frontend** (Geplant)  
- **React** (SPA)  
- **CSS** für Styling  
- **Jest** für Unit-Tests  
- **Fetch** für API-Requests  

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

## 📝 Was konnte ich aus diesem Projekt lernen?
- **Tiefes Verständnis für Backend-Architektur & REST APIs**
- **Testing auf hohem Niveau**
- **Einsatz von Docker & PostgreSQL für Datenbankmanagement**
- **Strukturierte Planung eines Fullstack-Projekts**
- **Vorbereitung auf moderne Frontend-Entwicklung mit React**

## ✨ Weitere Schritte
- **Frontend-Entwicklung starten** (React, CSS, Jest)
- **Statistiken & Datenanalysen entwickeln**

---

## 🌐 Lizenz & Kontakt
Dieses Projekt steht unter der [MIT-Lizenz](LICENSE). 

Kontakt: [E-Mail](mailto:melinakiefer@hotmail.de) | [GitHub](https://github.com/meelinaa)
