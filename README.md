# 🚀 N/G - Ultimate Workspace

Willkommen bei **N/G**, deinem minimalistischen, datenschutzfokussierten und hochgradig anpassbaren Kanban-Workspace. 

Dieses Tool ist dein digitaler Anker für Produktivität. Da **N/G** zu 100 % in deinem Browser läuft, verlassen deine Daten niemals dein Gerät. Sie gehören dir – und nur dir.

---

## 🌐 Direkt loslegen
Du musst nichts installieren. N/G ist eine Web-App, die direkt in deinem Browser läuft:
👉 **[Hier geht's zum Workspace: N/G](https://zweiwelteninmir.github.io/N-G/)**

---

## 📖 Inhaltsverzeichnis
1. [Über das Projekt](#-über-das-projekt)
2. [Die "Zero-Server" Philosophie](#-die-zero-server-philosophie)
3. [Kern-Features](#-kern-features)
4. [Wichtige Hinweise zur Datenspeicherung](#-wichtige-hinweise-zur-datenspeicherung)
5. [Bedienungsanleitung](#-bedienungsanleitung)
6. [Sicherheit & Datenschutz](#-sicherheit--datenschutz)
7. [Fehlerbehebung](#-fehlerbehebung)

---

## 🎯 Über das Projekt
N/G ist ein Single-File-Workspace. Alles, was du siehst, läuft clientseitig. Es gibt keine Datenbank im Hintergrund, keine Benutzerkonten und kein Tracking. Es ist das perfekte Werkzeug für alle, die eine schnelle, private Umgebung für Aufgaben und Gedanken suchen.

---

## 🛡 Die "Zero-Server" Philosophie
Bei N/G gibt es keine "Cloud" in meinem Besitz. 
* **Deine Daten = Deine Daten.** * Wenn du die Seite aufrufst, wird der Code geladen, aber deine persönlichen Boards werden **lokal auf deinem Computer** verarbeitet. 
* Selbst wenn die GitHub-Seite nicht verfügbar wäre, könntest du die Datei einfach lokal speichern und sie würde offline genauso funktionieren.

---

## ✨ Kern-Features
* **Kanban-Board:** Drei intuitive Spalten (Zu tun, In Arbeit, Erledigt).
* **Workspace-Management:** Erstelle getrennte Bereiche (z. B. "Schule", "Projekt X", "Privat").
* **Custom Tags:** Definiere eigene Kategorien mit Wunschfarben.
* **Globales Archiv:** Behalte den Überblick, ohne dein Board zu überladen.
* **Offline-fähig:** Einmal geladen, funktioniert es (dank der Browser-Architektur) auch ohne Internetverbindung.

---

## 💾 Wichtige Hinweise zur Datenspeicherung

### 1. Die Browser-Speicherung (LocalStorage)
N/G nutzt den `localStorage` deines Browsers. Das ist ein Speicherbereich, der fest mit deinem Browser und deinem Gerät verknüpft ist.
* **Vorteil:** Deine Daten sind sofort da, wenn du die Seite öffnest.
* **Wichtig:** Wenn du den Browser-Cache leerst oder die Website-Daten in den Browsereinstellungen löschst, sind deine Aufgaben weg, **falls du vorher kein Backup gemacht hast!**

### 2. Das Backup-System
Da der `localStorage` bei einem Browser-Reset gelöscht werden kann, bietet N/G eine Backup-Funktion an:
* **Export:** Sichere deine Daten regelmäßig als verschlüsselte `.txt`-Datei auf deiner Festplatte.
* **Import:** Spiele diese Datei bei Bedarf einfach wieder ein.
* **Tipp:** Betrachte das Backup-System als deine "Versicherung". Mache dir daraus eine Gewohnheit!

---

## 🔐 Sicherheit & Datenschutz
* **Verschlüsselung:** Dein Backup wird via AES-GCM (256-Bit) verschlüsselt. Dein Passwort wird niemals übertragen – es existiert nur in deinem Kopf und deinem Browser-RAM.
* **Kein Tracking:** Es gibt kein Google Analytics, kein Tracking und keine externe Datenbank. Deine IP-Adresse und deine Aufgaben bleiben bei dir.

---

## 🚀 Installation & Lokaler Betrieb
Du möchtest N/G lieber komplett lokal laufen lassen?
1. Lade dir die `index.html` aus dem Repository herunter.
2. Doppelklicke sie, um sie im Browser zu öffnen.
3. Fertig! Du benötigst keine Internetverbindung mehr.

---

## ❓ Fehlerbehebung

### "Cannot read properties of undefined"
Dieser Fehler erscheint, wenn die Krypto-Funktion in einem nicht-sicheren Kontext blockiert wird.
* **Lösung:** Nutze einfach den offiziellen Link via **HTTPS** (GitHub Pages) oder starte die Seite über einen lokalen Server (localhost).

### Browser-Cache-Hinweis
Wenn du den Browser wechselst (z.B. von Chrome zu Firefox), sind deine Daten nicht automatisch "mitgewandert". Nutze hierfür das **Backup-System**, um deine Daten zwischen verschiedenen Browsern oder Geräten zu übertragen.

---

*Entwickelt für maximale Privatsphäre. N/G – Deine Daten, dein Workspace.*
