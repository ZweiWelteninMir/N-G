# 🚀 N/G - Ultimate Workspace

Willkommen bei **N/G**, deinem minimalistischen, datenschutzfokussierten und hochgradig anpassbaren Kanban-Workspace. 

Dieses Tool wurde mit dem Ziel entwickelt, maximale Produktivität bei minimaler Ablenkung zu bieten. Alle Daten bleiben dort, wo sie hingehören: **Auf deinem Gerät.**

---

## 📖 Inhaltsverzeichnis
1. [Über das Projekt](#-über-das-projekt)
2. [Kern-Features](#-kern-features)
3. [Technische Architektur](#-technische-architektur)
4. [Installation & Start](#-installation--start)
5. [Bedienungsanleitung](#-bedienungsanleitung)
6. [Sicherheit & Datenschutz](#-sicherheit--datenschutz)
7. [Fehlerbehebung & FAQ](#-fehlerbehebung--faq)
8. [Roadmap](#-roadmap)

---

## 🎯 Über das Projekt
N/G ist ein Single-File-Workspace. Das bedeutet: Alles, was du brauchst, ist in einer einzigen `index.html` enthalten. Kein Setup, keine Datenbank, keine Server-Kosten. Perfekt für schnelle Notizen, Schulprojekte oder das private Task-Management.

---

## ✨ Kern-Features
* **Kanban-Board:** Drei intuitive Spalten (Zu tun, In Arbeit, Erledigt) für den perfekten Überblick.
* **Workspace-Management:** Erstelle beliebig viele getrennte Arbeitsbereiche.
* **Custom Tags:** Definiere eigene Kategorien mit individuellen Farben.
* **Globales Archiv:** Behalte erledigte Aufgaben, ohne dein Board zuzumüllen.
* **Zero-Server Backup:** Exportiere deinen gesamten Workspace als verschlüsselte Datei.

---

## 🛠 Technische Architektur
N/G basiert auf modernen Web-Technologien:
* **Frontend:** HTML5, CSS3 (Flexbox/Grid), Vanilla JavaScript (keine Abhängigkeiten!).
* **Speicherung:** Lokaler `localStorage` des Browsers.
* **Kryptografie:** Web Crypto API (AES-GCM 256-Bit) für sichere Backups (sofern HTTPS/localhost genutzt wird).
* **Design:** Modernes Dark-Mode-UI mit Fokus auf Ästhetik und UX.

---

## 🚀 Installation & Start

### Lokale Entwicklung
1. Klone das Repository oder lade die `index.html` herunter.
2. Öffne den Ordner in deinem Terminal.
3. Starte einen einfachen lokalen Server (z.B. mit `python -m http.server` oder der VS Code "Live Server" Extension).
4. Öffne `http://localhost:8000` in deinem Browser.

### Deployment (GitHub Pages)
1. Pushe die `index.html` in ein öffentliches Repository.
2. Aktiviere "GitHub Pages" in den Repository-Einstellungen.
3. Dein Workspace ist nun weltweit (und via HTTPS verschlüsselt) verfügbar.

---

## 💡 Bedienungsanleitung

### Workspaces wechseln
Klicke in der Seitenleiste auf den Namen deines Workspaces. Mit dem `+` Button erstellst du neue Kategorien.

### Aufgaben hinzufügen
Gib deinen Text in das Eingabefeld ein, wähle einen Tag und drücke Enter oder "Hinzufügen".

### Tags anpassen
Im Bereich unter dem Eingabefeld kannst du neue Tags vergeben. Wähle eine Farbe, gib einen Namen ein und klicke auf "Erstellen".

### Backup-Strategie
Sichere deine Daten regelmäßig:
1. Klicke auf "Backup erstellen".
2. Wähle ein starkes Passwort.
3. Speichere die `.txt` Datei an einem sicheren Ort.
4. Zum Wiederherstellen einfach "Backup einspielen" klicken.

---

## 🔐 Sicherheit & Datenschutz
**Deine Daten verlassen zu keinem Zeitpunkt deinen Browser.**
* **Lokale Speicherung:** Die Daten liegen im `localStorage` deines Browsers.
* **Verschlüsselung:** Das Backup-System nutzt die Web Crypto API. Deine Daten werden clientseitig verschlüsselt, bevor sie deinen Computer als Datei verlassen.
* **Hinweis:** In Umgebungen ohne HTTPS (HTTP) wird die Verschlüsselung aus Sicherheitsgründen vom Browser blockiert. Nutze für den vollen Schutz immer HTTPS oder `localhost`.

---

## ❓ Fehlerbehebung & FAQ

### "Fehler: Cannot read properties of undefined"
Dieser Fehler tritt auf, wenn der Browser die Web Crypto API blockiert (meist bei HTTP). 
* **Lösung:** Nutze `localhost` oder eine HTTPS-Verbindung.

### Meine Daten sind weg!
Prüfe, ob du versehentlich den Browser-Cache geleert hast. Wenn du ein Backup erstellt hast, kannst du es jederzeit über den Button "Backup einspielen" wiederherstellen.

---

## 🗺 Roadmap
- [ ] Drag-and-Drop Unterstützung für Karten.
- [ ] PWA-Support (App auf dem Desktop installieren).
- [ ] Import von anderen Formaten (JSON/CSV).
- [ ] Tastatur-Shortcuts für Power-User.

---

*Erstellt mit ❤️ für maximale Produktivität.*
