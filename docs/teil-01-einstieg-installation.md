# Teil 1 – Einstieg, Installation und Projektstart

## 1. Ziel dieses Teils

In Teil 1 richten wir die Entwicklungsumgebung ein und erstellen ein neues Laravel-Projekt.

Nach diesem Teil solltest du wissen:

- was PHP ist
- was Laravel ist
- was Composer macht
- wie ein neues Laravel-Projekt erstellt wird
- wie der lokale Laravel-Server gestartet wird
- welche wichtigen Ordner Laravel automatisch anlegt

---

## 2. Was ist PHP?

PHP ist eine Programmiersprache, die sehr häufig für Webanwendungen verwendet wird.

PHP läuft auf dem Server.

Ein stark vereinfachtes Beispiel:

```text
Browser
   ↓
Webserver
   ↓
PHP
   ↓
HTML-Antwort
   ↓
Browser
```

Laravel basiert auf PHP.

---

## 3. Was ist Laravel?

Laravel ist ein Framework für PHP.

Ein Framework stellt bereits viele Werkzeuge und eine feste Projektstruktur bereit.

Ohne Framework müsste man viele Dinge selbst programmieren.

Laravel bringt beispielsweise Werkzeuge für folgende Bereiche mit:

- Routing
- Controller
- Views
- Datenbanken
- Models
- Validierung
- Sessions
- Authentifizierung
- Tests
- Kommandozeilenwerkzeuge

---

## 4. Was ist Composer?

Composer ist der Paketmanager für PHP.

Composer lädt PHP-Pakete herunter und verwaltet deren Abhängigkeiten.

Vergleich mit React:

| React / JavaScript | Laravel / PHP |
|---|---|
| npm | Composer |
| package.json | composer.json |
| node_modules | vendor |

Composer wird unter anderem benutzt, um Laravel herunterzuladen.

---

## 5. Voraussetzungen prüfen

Öffne PowerShell oder das Terminal in Visual Studio Code.

Prüfe zuerst PHP:

```powershell
php -v
```

Composer:

```powershell
composer --version
```

Git:

```powershell
git --version
```

Wenn alle drei Befehle funktionieren, kann das Projekt angelegt werden.

---

## 6. Projektordner

Für dieses Lernprojekt verwenden wir einen gemeinsamen Ordner für GitHub-Projekte.

Beispiel:

```text
1.0-Github-Projekte/
│
├── einfuehrung-react/
└── laravel-fuer-anfaenger/
```

Das Laravel-Projekt liegt also nicht im React-Projekt, sondern daneben.

---

## 7. Neues Laravel-Projekt erstellen

Wechsle zuerst in den Ordner, in dem das neue Projekt angelegt werden soll.

Danach:

```powershell
composer create-project laravel/laravel laravel-fuer-anfaenger
```

Composer erledigt dabei mehrere Dinge:

1. Laravel wird heruntergeladen.
2. Die PHP-Abhängigkeiten werden installiert.
3. Der Ordner `vendor` wird erzeugt.
4. Die `.env`-Datei wird vorbereitet.
5. Ein Application Key wird erzeugt.
6. Die Standard-Datenbank wird vorbereitet.
7. Die ersten Migrationen werden ausgeführt.

---

## 8. In den Projektordner wechseln

Nach der Installation:

```powershell
cd laravel-fuer-anfaenger
```

Das Terminal sollte jetzt im Laravel-Projekt stehen.

---

## 9. Projekt in Visual Studio Code öffnen

```powershell
code .
```

Der Punkt bedeutet:

> Öffne den aktuellen Ordner in Visual Studio Code.

---

## 10. Laravel-Server starten

Im Projektordner:

```powershell
php artisan serve
```

Laravel startet normalerweise unter:

```text
http://127.0.0.1:8000
```

Diese Adresse im Browser öffnen.

Wenn die Laravel-Startseite erscheint, funktioniert die Installation.

---

## 11. Zwei Terminals verwenden

Für die Arbeit mit Laravel sind zwei Terminals praktisch.

### Terminal 1

Hier läuft dauerhaft der Laravel-Server:

```powershell
php artisan serve
```

Dieses Terminal lässt man normalerweise offen.

### Terminal 2

Hier werden weitere Befehle ausgeführt, zum Beispiel:

```powershell
git status
php artisan route:list
php artisan migrate
composer install
```

Für normale Änderungen an Blade-, Route- oder Controller-Dateien muss der Laravel-Server nicht jedes Mal neu gestartet werden.

---

## 12. Was wurde automatisch erzeugt?

Laravel erstellt bereits eine vollständige Grundstruktur.

Unter anderem:

```text
laravel-fuer-anfaenger/
│
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
├── vendor/
├── .env
├── artisan
├── composer.json
└── composer.lock
```

Diese Struktur schauen wir uns in der Datei `teil-01-projektstruktur.md` genauer an.

---

## 13. Ergebnis von Teil 1

Am Ende von Teil 1 haben wir:

- PHP geprüft
- Composer geprüft
- Git geprüft
- Laravel installiert
- das Projekt in Visual Studio Code geöffnet
- den lokalen Laravel-Server gestartet
- die Laravel-Startseite im Browser aufgerufen

Damit ist die technische Grundlage für die nächsten Teile geschaffen.

---

## Nächster Teil

In **Teil 2** beschäftigen wir uns mit:

- `routes/web.php`
- der ersten eigenen Route
- einer einfachen Textausgabe
- Blade-Views
- einer zweiten eigenen Seite
