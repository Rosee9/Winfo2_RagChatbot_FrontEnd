# RAG-Chatbot Frontend
**Autor u. Entwickler:** E. Ekinci

## Übersicht

Das RAG-Chatbot Frontend bietet eine benutzerfreundliche Oberfläche, die Benutzern ermöglicht, mit dem RAG-Chatbot-System zu interagieren. Dieses Frontend ist eng mit dem [RAG-Chatbot Backend](https://github.com/Rosee9/Winfo2_RagChatbot) verbunden und bietet Funktionen zur Anmeldung, Registrierung und Verwaltung von PDF-Dokumenten. Der Chatbot liefert dynamische Antworten entsprechend des beim Anmelden gewählten Abonnements.

## Aktueller Status

### Frontend Struktur

- **HTML und CSS:**
  - Jede HTML-Datei hat eine dazugehörige CSS-Datei, die das Layout und das Styling der Benutzeroberfläche definiert.
  - JavaScript-Code ist direkt in den HTML-Dateien integriert und ermöglicht die Kommunikation mit dem Backend.

- **Startpunkt:**
  - Die Interaktion mit dem System beginnt auf der Seite `SignIn1.html`, die sicherstellt, dass das Backend ordnungsgemäß arbeiten kann.

### Funktionalitäten

- **Benutzerverwaltung:**
  - Benutzer können sich registrieren, indem sie ein Abonnement wählen, das die Qualität der KI-Antworten beeinflusst.
  - Einmal registriert, können sich Benutzer über das Anmeldeformular einloggen.

- **Dokumentenmanagement:**
  - Über das Frontend können Benutzer PDFs hochladen und auch wieder löschen. Diese Aktionen synchronisieren sich direkt mit dem Backend.

- **Interaktion mit dem Backend:**
  - Das Frontend nutzt API-Endpunkte des [RAG-Chatbot Backend](https://github.com/Rosee9/Winfo2_RagChatbot) für alle serverseitigen Funktionen.
  - Die Kommunikation umfasst die Anmeldung, Registrierung sowie das Hochladen und Löschen von PDFs.

- **Erweiterte Funktionen:**
  - Nutzer des teuersten Abomodells erhalten Zugriff auf eine Statistikfunktion, die die Anzahl der gesendeten Nachrichten anzeigt.

## Voraussetzungen

- **Aktives Backend:** Das Spring Boot Backend muss aktiv sein, bevor mit dem Frontend interagiert wird. Hinweise dazu finden sich in der Backend-README-Datei.
- **Live Server Erweiterung:** Installiere die Erweiterung, um das Frontend auf dem empfohlenen Port 5500 zu starten.
  - Dies verhindert mögliche Kommunikationsprobleme zwischen Frontend und Backend.

## Setup-Anleitung

1. **Backend starten**
   - Stelle sicher, dass das [RAG-Chatbot Backend](https://github.com/Rosee9/Winfo2_RagChatbot) aktiv ist, bevor du das Frontend benutzt. Details zum Start sind in der Backend-README beschrieben.

2. **Frontend verwenden**
   - Öffne die `SignIn1.html` in einem Webbrowser, um mit dem System zu interagieren.
   - Starte das Frontend idealerweise auf Port 5500 mithilfe der Live Server Erweiterung.
   - Folge den Anweisungen auf dem Bildschirm zur Anmeldung oder Registrierung.

## Funktionen

- **Anmeldung und Registrierung:** 
  - Beginne den Prozess auf der `SignIn1.html`-Seite, um alle Funktionen des Systems zu nutzen.
  - Wähle ein Abonnement, das der gewünschten Antwortqualität entspricht.

- **PDF-Verwaltung:**
  - Hochladen von PDF-Dokumenten direkt über die Benutzeroberfläche.
  - Ermöglicht das Löschen von PDFs, die sowohl aus dem Frontend als auch aus dem Backend entfernt werden.

## Hinweise

- Für eine reibungslose Nutzung sollten das Frontend und das Backend konsistent miteinander kommunizieren. Beginne immer auf `SignIn1.html` und teste sorgfältig, um sicherzustellen, dass alle Funktionen korrekt synchronisiert sind.
- Starte das Frontend auf Port 5500, um optimale Funktionalität und Kompatibilität zu gewährleisten.

## Unterstützung

Bei Fragen oder Problemen bezüglich der Anwendung wende dich bitte direkt an den Entwickler.