# Laravel für Anfänger

Ein Schritt-für-Schritt-Lernprojekt von **WAGA IT Bildung**.

Dieses Repository begleitet den Einstieg in Laravel von der Installation bis zu einer kleinen vollständigen Webanwendung.

Die Lernreihe ist bewusst in einzelne Teile gegliedert. Jeder Teil baut auf dem vorherigen auf und bekommt später einen eigenen nachvollziehbaren GitHub-Stand.

---

## Lernreihe

- **Teil 1 – Einstieg, Installation und Projektstart**
- Teil 2 – Routes und Views
- Teil 3 – Blade Layouts
- Teil 4 – Controller
- Teil 5 – Datenbank und Migrationen
- Teil 6 – Models und Eloquent
- Teil 7 – CRUD
- Teil 8 – Formulare und Validierung

---

## Aktueller Stand

Wir befinden uns aktuell bei:

**Teil 1 – Einstieg, Installation und Projektstart**

Die ausführliche Anleitung findest du hier:

- [Teil 1 – Einstieg und Installation](docs/teil-01-einstieg-installation.md)
- [Teil 1 – Projektstruktur](docs/teil-01-projektstruktur.md)
- [Teil 1 – Wichtige Befehle](docs/teil-01-befehle.md)

---

## Was ist Laravel?

Laravel ist ein modernes PHP-Framework zur Entwicklung von Webanwendungen.

Laravel unterstützt unter anderem:

- Routing
- Views und Templates
- Datenbankzugriffe
- Formulare
- Validierung
- Authentifizierung
- APIs
- Tests
- strukturierte Webanwendungen nach dem MVC-Prinzip

---

## Was ist Composer?

Composer ist der Paketmanager für PHP.

Ein einfacher Vergleich:

| React / JavaScript | Laravel / PHP |
|---|---|
| npm | Composer |
| package.json | composer.json |
| package-lock.json | composer.lock |
| node_modules | vendor |

Composer lädt Laravel und alle benötigten PHP-Pakete herunter.

---

## Voraussetzungen

Für dieses Lernprojekt werden verwendet:

- PHP
- Composer
- Git
- Laravel
- Visual Studio Code

Versionen prüfen:

```powershell
php -v
composer --version
git --version
```

---

## Projekt starten

Im Projektordner:

```powershell
php artisan serve
```

Danach im Browser öffnen:

```text
http://127.0.0.1:8000
```

---

## Wichtiger Hinweis für GitHub

Wer Laravel selbst mit Composer neu installiert, erhält die originale Laravel-Grundinstallation.

Wer dieses Repository klont, erhält dagegen den jeweils gespeicherten Stand unseres Lernprojekts.

Später werden die einzelnen Lernstände zusätzlich über Git-Branches oder Tags nachvollziehbar gemacht.

Beispiele:

```text
teil-01-einstieg
teil-02-routes-views
teil-03-blade-layouts
teil-04-controller
```

---

## Ziel des Projekts

Am Ende soll nachvollziehbar sein, wie die wichtigsten Laravel-Bausteine zusammenspielen:

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
View
```

---

**WAGA IT Bildung**  
Laravel für Anfänger
