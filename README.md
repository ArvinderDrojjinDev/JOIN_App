# JOIN App

**Live-Demo:** https://arvinderdrojjindev.github.io/JOIN_App/

**JOIN App** ist eine Web-App für **Aufgaben- und Kontaktverwaltung** im Kanban-Stil (ähnlich Trello).  
Enthalten sind **Login/Sign-up**, ein **Summary-Dashboard**, ein **Board mit Drag & Drop**, **Task-Erstellung** (Priorität, Kategorie, Fälligkeitsdatum, Subtasks, Assignees) sowie ein **Kontaktbereich**.

---

## ✨ Features

- 🔐 **Login & Sign-up**
- 📊 **Summary Dashboard** (Überblick über Aufgaben und Status)
- 🗂️ **Kanban Board** (z. B. To Do / In Progress / Await Feedback / Done)
- 🖱️ **Drag & Drop** zum Verschieben von Aufgaben zwischen Spalten
- ✅ **Add Task** mit Kategorie, Priorität, Datum, Beschreibung
- 🧩 **Subtasks** inkl. Fortschritt
- 👥 **Assignees** (Aufgaben an Kontakte zuweisen)
- 📇 **Contacts** (Anlegen / Bearbeiten / Löschen)

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, Vanilla JavaScript
- **Datenhaltung:** Firebase Realtime Database (REST via `fetch`)

---

## 🚀 Lokales Setup

Dieses Projekt sollte über einen lokalen Server gestartet werden (nicht per `file://`).

### VS Code Live Server

1. Projekt in VS Code öffnen
2. Extension **Live Server** installieren
3. `index.html` öffnen → **Go Live**

### Python HTTP Server

```bash
python -m http.server 5500
```

Danach im Browser öffnen:

http://localhost:5500/

---

## 📁 Projektstruktur

- index.html – Einstieg / Login
- pages/ – Unterseiten (z. B. Board, Summary, Contacts, Add Task, Help)
- scripts/ – JavaScript-Logik (Board, Tasks, Contacts, Auth, UI/Overlays)
- styles/ / style.css – Styling
- assets/ – Bilder, Icons, Fonts

---

## 👤 Mein Beitrag

- LogIn/LogOut HTML&CSS
- Summary-Dashboard HTML, CSS & JS Logik 
- Privacy Policy & Legal Notice errichtet
- Board/Task Overlays eingerichtiet 

---

## 🗺️ Roadmap

- [ ] UI/UX Verbesserungen
- [ ] Besseres Error Handling
- [ ] Validierung ausbauen
- [ ] Mobile Optimierungen
