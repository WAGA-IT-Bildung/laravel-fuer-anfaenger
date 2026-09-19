# 🚀 WAGA IT – Laravel für Anfänger

<p align="center">
  <img src="https://laravel.com/img/logomark.min.svg" width="120" alt="Laravel Logo">
</p>

<p align="center">
  <strong>Von den ersten Laravel-Grundlagen bis zur vollständigen Webanwendung.</strong>
</p>

<p align="center">
  Schritt für Schritt • Praxisnah • Für Anfänger
</p>

---

## 🔴 Was ist Laravel?

**Laravel** ist ein modernes **PHP-Framework** zur Entwicklung von Webanwendungen.

PHP ist die Programmiersprache.

Laravel stellt darauf aufbauend eine fertige Struktur und viele Werkzeuge bereit, damit wir nicht bei jeder Webanwendung alles von Grund auf selbst programmieren müssen.

Ganz vereinfacht:

```text
PHP
│
└── Laravel
    │
    ├── Routing
    ├── Controller
    ├── Views
    ├── Datenbank
    ├── Models
    ├── Validierung
    ├── Sessions
    ├── Authentifizierung
    ├── APIs
    └── viele weitere Werkzeuge
```

Laravel ist also **keine eigene Programmiersprache**.

Wir programmieren weiterhin mit **PHP**, verwenden dabei aber die Struktur und die Funktionen des Laravel-Frameworks.

---

## 🌍 Wofür wird Laravel verwendet?

Laravel eignet sich für sehr unterschiedliche Webanwendungen.

Zum Beispiel:

- Unternehmenswebseiten
- Kundenportale
- Admin-Bereiche
- Lernplattformen
- Kursverwaltungen
- Teilnehmerverwaltungen
- Buchungssysteme
- Online-Shops
- Formulare
- Benutzer- und Login-Systeme
- REST-APIs
- Dashboards
- interne Verwaltungsprogramme
- Backend-Systeme für React, Vue oder mobile Apps

Laravel wird besonders interessant, sobald eine Webseite nicht mehr nur aus statischem HTML besteht, sondern **Logik, Daten und Datenbankzugriffe** benötigt.

---

## 🤔 Warum verwendet man ein Framework wie Laravel?

Natürlich könnte man eine Webanwendung auch nur mit PHP programmieren.

Dann müssten wir jedoch viele Dinge selbst entwickeln und organisieren.

Zum Beispiel:

```text
URL auswerten
       ↓
richtige PHP-Datei finden
       ↓
Datenbank verbinden
       ↓
SQL ausführen
       ↓
Eingaben prüfen
       ↓
Fehler behandeln
       ↓
HTML erzeugen
       ↓
Sicherheit beachten
```

Laravel gibt uns dafür bereits eine klare Struktur.

Das bedeutet nicht, dass Laravel die Programmierung für uns übernimmt.

Laravel hilft uns dabei, eine Anwendung **übersichtlich, wartbar und strukturiert** aufzubauen.

---

## 🧠 Was lernen wir mit Laravel?

Wir beginnen bewusst mit den Grundlagen.

Aus der Laravel-Standardinstallation entsteht Schritt für Schritt eine eigene kleine Webanwendung.

```text
Laravel installieren
        ↓
Projektstruktur verstehen
        ↓
Routes
        ↓
Blade Views
        ↓
Blade Layouts
        ↓
Controller
        ↓
Datenbank
        ↓
Migrationen
        ↓
Models
        ↓
Eloquent ORM
        ↓
Formulare
        ↓
Validierung
        ↓
CRUD
        ↓
vollständige Webanwendung
```

Das Ziel ist also nicht:

> „Ein paar Laravel-Befehle auswendig lernen.“

Sondern zu verstehen, **wie eine moderne PHP-Webanwendung aufgebaut ist und wie die einzelnen Bestandteile zusammenspielen**.

---

## 🏗️ Was bauen wir in diesem Kurs?

Unser Lernprojekt entwickelt sich Schritt für Schritt weiter.

Am Anfang lernen wir nur die Laravel-Struktur kennen.

Danach kommen eigene Seiten, Routen, Controller und später eine Datenbank hinzu.

Geplant sind unter anderem:

```text
✅ Laravel installieren
✅ Projekt starten
✅ Projektstruktur kennenlernen
✅ Routes verstehen
✅ Blade Views verwenden
🔜 Blade Layouts
🔜 Controller
🔜 Datenbank
🔜 Migrationen
🔜 Models
🔜 Eloquent
🔜 Formulare
🔜 Validierung
🔜 Datensätze anzeigen
🔜 Datensätze hinzufügen
🔜 Datensätze bearbeiten
🔜 Datensätze löschen
```

Später entsteht daraus eine kleine **WAGA IT Verwaltungsanwendung**.

---

## 🧩 Die wichtigsten Laravel-Bausteine

Laravel besteht aus mehreren Bereichen, die zusammenarbeiten.

```text
Browser
   ↓
Route
   ↓
Controller
   ↓
Model
   ↓
Datenbank
   ↓
Controller
   ↓
View
   ↓
Browser
```

### Route

Eine **Route** entscheidet, was bei einer bestimmten URL passiert.

Beispiel:

```text
http://127.0.0.1:8000/ueber-uns
```

Laravel schaut in unsere Routen und entscheidet, welche Aktion ausgeführt werden soll.

---

### Controller

Ein **Controller** enthält später einen großen Teil unserer Programmlogik.

Zum Beispiel:

```text
Teilnehmer laden
Teilnehmer speichern
Eingaben prüfen
Daten an eine View übergeben
```

---

### Model

Ein **Model** repräsentiert Daten unserer Anwendung.

Beispielsweise könnte ein Model später heißen:

```text
Teilnehmer
Kurs
Dozent
Anmeldung
```

Laravel verwendet dafür unter anderem **Eloquent ORM**.

---

### View

Eine **View** ist für die Darstellung zuständig.

Laravel verwendet dafür die Template-Engine **Blade**.

Blade-Dateien sehen zum Beispiel so aus:

```text
welcome.blade.php
ueber-uns.blade.php
```

und liegen normalerweise unter:

```text
resources/views/
```

---

## 🗺️ Wie läuft eine Anfrage durch Laravel?

Ein stark vereinfachtes Beispiel:

```text
1. Browser ruft /ueber-uns auf

             ↓

2. Laravel prüft routes/web.php

             ↓

3. passende Route wird gefunden

             ↓

4. Laravel lädt eine View

             ↓

5. Blade erzeugt HTML

             ↓

6. Browser zeigt die fertige Seite
```

Später kommt noch der Controller dazwischen:

```text
Browser
   ↓
Route
   ↓
Controller
   ↓
Model / Datenbank
   ↓
View
   ↓
Browser
```

---

## 🐘 PHP + Laravel

Laravel basiert auf **PHP**.

Das bedeutet:

```text
PHP = Programmiersprache

Laravel = Framework für PHP
```

Ein einfaches PHP-Projekt könnte aus vielen einzelnen PHP-Dateien bestehen.

Laravel gibt uns dagegen eine feste Projektstruktur:

```text
app/
config/
database/
public/
resources/
routes/
storage/
tests/
```

Dadurch finden Entwickler bestimmte Bestandteile einer Laravel-Anwendung schneller wieder.

---

## 📦 Was ist Composer?

Für Laravel verwenden wir **Composer**.

Composer ist der Paketmanager für PHP.

Wer bereits mit React gearbeitet hat, kann sich Composer ungefähr so merken:

| React / JavaScript | Laravel / PHP |
|---|---|
| npm | Composer |
| `package.json` | `composer.json` |
| `package-lock.json` | `composer.lock` |
| `node_modules/` | `vendor/` |

Composer lädt PHP-Pakete herunter und verwaltet deren Abhängigkeiten.

Laravel selbst wird ebenfalls über Composer installiert.

Zum Beispiel:

```powershell
composer create-project laravel/laravel laravel-fuer-anfaenger
```

---

## 🛠️ Was ist Artisan?

Laravel bringt ein eigenes Kommandozeilenwerkzeug mit:

```text
Artisan
```

Artisan wird über PHP gestartet:

```powershell
php artisan
```

Beispiele:

```powershell
php artisan serve
php artisan route:list
php artisan migrate
```

Später verwenden wir Artisan auch zum Erstellen von:

```text
Controllern
Models
Migrationen
Requests
Commands
```

---

## 🔴 Laravel + Blade

Laravel verwendet **Blade** als Template-Engine.

Blade erweitert normales HTML um Laravel-Funktionen.

Eine Blade-Datei erkennt man an:

```text
.blade.php
```

Beispiel:

```text
resources/views/welcome.blade.php
```

Später lernen wir unter anderem:

```blade
@extends(...)
@section(...)
@yield(...)
@if(...)
@foreach(...)
```

Damit können wir Seiten wiederverwenden und dynamische Inhalte erzeugen.

---

## ⚛️ Laravel und React – was ist der Unterschied?

Laravel und React erfüllen unterschiedliche Aufgaben.

| Laravel | React |
|---|---|
| PHP-Framework | JavaScript-Bibliothek |
| läuft hauptsächlich auf dem Server | läuft hauptsächlich im Browser |
| Backend und Webanwendungslogik | Benutzeroberfläche / Frontend |
| Datenbankzugriffe | interaktive Oberfläche |
| Routing auf dem Server | Komponenten im Frontend |
| APIs erstellen | APIs verwenden |

Vereinfacht:

```text
Laravel
= Backend / Server / Daten

React
= Frontend / Benutzeroberfläche
```

Beide können später sogar zusammenarbeiten:

```text
┌─────────────────────┐
│        React        │
│      Frontend       │
└──────────┬──────────┘
           │
           │ HTTP / REST API
           ▼
┌─────────────────────┐
│       Laravel       │
│       Backend       │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│        MySQL        │
│      Datenbank      │
└─────────────────────┘
```

So sehen wir später auch, wie sich unser React-Lernprojekt und Laravel ergänzen können.

---

## 🎯 Für wen ist diese Reihe gedacht?

Diese Reihe richtet sich ausdrücklich an **Einsteiger**.

Du musst Laravel vorher nicht kennen.

Hilfreich sind erste Grundlagen in:

- HTML
- CSS
- PHP

SQL-Kenntnisse werden später hilfreich, wenn wir mit Datenbanken arbeiten.

Alle wichtigen Laravel-Konzepte werden Schritt für Schritt aufgebaut.

---

## 💻 Entwicklungsumgebung

Für dieses Lernprojekt verwenden wir unter anderem:

- PHP
- Laravel
- Composer
- Git
- GitHub
- Visual Studio Code
- PowerShell
- SQLite

Später können zusätzlich hinzukommen:

- MySQL / MariaDB
- REST API
- React

---

## 🚀 Laravel installieren

### Voraussetzungen prüfen

PHP:

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

---

### Projekt erstellen

```powershell
composer create-project laravel/laravel laravel-fuer-anfaenger
```

Danach:

```powershell
cd laravel-fuer-anfaenger
```

---

## ▶️ Laravel starten

Laravel bringt einen lokalen Entwicklungsserver mit.

Start:

```powershell
php artisan serve
```

Danach ist die Anwendung normalerweise unter folgender Adresse erreichbar:

```text
http://127.0.0.1:8000
```

---

## 🖥️ Zwei Terminals verwenden

Für die Arbeit mit Laravel sind zwei Terminals praktisch.

### Terminal 1

Hier läuft der Laravel-Server:

```powershell
php artisan serve
```

Dieses Terminal bleibt geöffnet.

### Terminal 2

Hier führen wir weitere Befehle aus:

```powershell
php artisan route:list
git status
git add .
git commit
composer install
```

---

## 📁 Laravel-Projektstruktur

Eine neue Laravel-Anwendung sieht ungefähr so aus:

```text
laravel-fuer-anfaenger/
│
├── app/
├── bootstrap/
├── config/
├── database/
├── docs/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
├── vendor/
│
├── .env
├── .env.example
├── artisan
├── composer.json
├── composer.lock
├── package.json
└── README.md
```

Für den Anfang sind besonders wichtig:

```text
routes/
resources/views/
app/
database/
```

---

## 📂 Wichtige Ordner

### `routes/`

Hier befinden sich die Routen der Anwendung.

Für normale Webseiten ist besonders wichtig:

```text
routes/web.php
```

---

### `resources/views/`

Hier liegen unsere Blade-Views.

Zum Beispiel:

```text
resources/views/welcome.blade.php
```

---

### `app/`

Hier befindet sich später ein großer Teil unserer eigenen PHP-Logik.

Zum Beispiel:

```text
app/Http/Controllers/
app/Models/
```

---

### `database/`

Hier finden wir unter anderem:

```text
Migrations
Seeder
Factories
SQLite-Datenbank
```

---

### `vendor/`

Hier liegen die von Composer installierten PHP-Pakete.

Dieser Ordner ist ungefähr vergleichbar mit:

```text
node_modules/
```

bei React beziehungsweise JavaScript.

Den Inhalt von `vendor/` bearbeiten wir nicht von Hand.

---

## 📚 Kursübersicht

### ✅ Teil 1 – Einstieg, Installation und Projektstart

In Teil 1 lernen wir:

- Was ist Laravel?
- Was ist PHP?
- Was ist Composer?
- Voraussetzungen prüfen
- Laravel installieren
- Projekt in VS Code öffnen
- lokalen Server starten
- Laravel-Projektstruktur verstehen
- erste Artisan-Befehle

Dokumentation:

👉 [Teil 1 – Einstieg & Installation](docs/teil-01-einstieg-installation.md)

👉 [Teil 1 – Projektstruktur](docs/teil-01-projektstruktur.md)

👉 [Teil 1 – Wichtige Befehle](docs/teil-01-befehle.md)

Git-Stand:

```text
teil-01
```

---

### 🟠 Teil 2 – Routes und Views

In Teil 2 verlassen wir die Laravel-Standardseite und erstellen unsere ersten eigenen Seiten.

Wir lernen:

- `routes/web.php`
- `Route::get()`
- Startseite `/`
- Test-Route `/hallo`
- Blade-Views
- `welcome.blade.php`
- `ueber-uns.blade.php`
- mehrere Seiten miteinander verbinden

Dokumentation:

👉 [Teil 2 – Routes und Views](docs/teil-02-routes-views.md)

👉 [Teil 2 – Wichtige Befehle](docs/teil-02-befehle.md)

Aktuelle URLs:

```text
/
 /ueber-uns
 /hallo
```

---

### 🔜 Teil 3 – Blade Layouts

In Teil 3 räumen wir unseren bisherigen HTML-Code auf.

Geplant:

- gemeinsames Layout
- `layouts/app.blade.php`
- `@extends`
- `@section`
- `@yield`
- gemeinsame Navigation
- gemeinsamer Footer
- weniger doppelter HTML-Code

---

### 🔜 Teil 4 – Controller

Geplant:

```text
Route
   ↓
Controller
   ↓
View
```

Wir verschieben Programmlogik aus den Routen in eigene Controller.

---

### 🔜 Teil 5 – Datenbank und Migrationen

Geplant:

- Datenbankverbindung
- SQLite / MySQL
- Migrationen
- Tabellen erstellen
- Datenbankstruktur versionieren

---

### 🔜 Teil 6 – Models und Eloquent

Geplant:

- Models
- Eloquent ORM
- Datensätze lesen
- Beziehungen zwischen Tabellen

---

### 🔜 Teil 7 – CRUD

CRUD bedeutet:

```text
Create
Read
Update
Delete
```

Wir lernen also:

```text
Datensatz anlegen
Datensatz anzeigen
Datensatz bearbeiten
Datensatz löschen
```

---

### 🔜 Teil 8 – Formulare und Validierung

Geplant:

- Formulare
- POST-Requests
- CSRF-Schutz
- Validierung
- Fehlermeldungen
- alte Eingabewerte wieder anzeigen

---

## 🏷️ Git-Tags für die Lernstände

Die einzelnen Teile werden als eigene Git-Tags gespeichert.

Zum Beispiel:

```text
teil-01
teil-02
teil-03
```

Dadurch kann ein bestimmter Lernstand später exakt wieder aufgerufen werden.

Beispiel:

```powershell
git checkout teil-01
```

Zurück zum aktuellen Stand:

```powershell
git checkout main
```

---

## 🧪 Aktueller Stand des Projekts

Aktuell bearbeiten wir:

```text
Teil 2 – Routes und Views
```

Unsere Anwendung besitzt aktuell folgende Seiten beziehungsweise Routen:

| URL | Bedeutung |
|---|---|
| `/` | Startseite |
| `/ueber-uns` | Über dieses Lernprojekt |
| `/hallo` | einfache Laravel-Testausgabe |

---

## 🔄 Wie entwickelt sich unser Projekt?

```text
Teil 1
Laravel-Grundinstallation
        ↓
Teil 2
Routes + Views
        ↓
Teil 3
Blade Layouts
        ↓
Teil 4
Controller
        ↓
Teil 5
Datenbank
        ↓
Teil 6
Models + Eloquent
        ↓
Teil 7
CRUD
        ↓
Teil 8
Formulare + Validierung
        ↓
vollständige kleine Webanwendung
```

---

## 🏫 WAGA IT Bildung

Praxisorientierter IT-Unterricht Schritt für Schritt.

**GitHub Organisation:** WAGA-IT-Bildung  
**Owner:** WagasWorld

---

> **Immer schön WAGA bleiben.** 🚀
