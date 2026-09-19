# Teil 1 – Laravel-Projektstruktur

Laravel legt beim Erstellen eines neuen Projekts viele Dateien und Ordner automatisch an.

Am Anfang wirkt das sehr umfangreich. Für den Einstieg müssen wir aber nur einige Bereiche wirklich kennen.

---

## Übersicht

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
│
├── .env
├── artisan
├── composer.json
└── composer.lock
```

---

## `app/`

Hier liegt später ein großer Teil unserer eigenen PHP-Anwendungslogik.

Beispiele:

- Controller
- Models
- weitere PHP-Klassen

Später wird unter anderem wichtig:

```text
app/
└── Http/
    └── Controllers/
```

---

## `bootstrap/`

Dieser Ordner gehört zum Startvorgang von Laravel.

Für Anfänger gilt:

> Normalerweise ändern wir hier zunächst nichts.

---

## `config/`

Hier befinden sich Konfigurationsdateien von Laravel.

Beispiele:

- Anwendung
- Datenbank
- Mail
- Cache
- Sessions

Viele Werte werden über die `.env`-Datei gesteuert.

---

## `database/`

Dieser Ordner wird später sehr wichtig.

Hier befinden sich unter anderem:

- Migrationen
- Seeder
- Factories
- bei SQLite auch die lokale Datenbankdatei

Beispiel:

```text
database/
├── factories/
├── migrations/
├── seeders/
└── database.sqlite
```

---

## `public/`

Das ist der öffentlich erreichbare Webordner.

Hier liegt unter anderem:

```text
public/index.php
```

Diese Datei ist der Einstiegspunkt der Webanwendung.

---

## `resources/`

Hier liegen Ressourcen unserer Anwendung.

Besonders wichtig:

```text
resources/
└── views/
```

Dort werden unsere Blade-Templates gespeichert.

Beispiel:

```text
resources/views/welcome.blade.php
```

---

## `routes/`

Hier befinden sich die Routen unserer Anwendung.

Für Web-Seiten ist besonders wichtig:

```text
routes/web.php
```

Damit beschäftigen wir uns ausführlich in Teil 2.

---

## `storage/`

Laravel verwendet diesen Ordner unter anderem für:

- Logs
- Cache
- temporäre Dateien
- generierte Dateien

Für die Fehlersuche wird später oft wichtig:

```text
storage/logs/
```

---

## `tests/`

Hier können automatisierte Tests gespeichert werden.

Für den Einstieg ist dieser Bereich noch nicht zentral.

---

## `vendor/`

Dieser Ordner enthält die PHP-Pakete, die Composer installiert hat.

Das ist vergleichbar mit:

```text
node_modules/
```

bei einem JavaScript- oder React-Projekt.

Wichtig:

> Den Inhalt von `vendor/` bearbeiten wir nicht von Hand.

---

## `.env`

Die `.env`-Datei enthält lokale Einstellungen der Anwendung.

Beispiele:

- Name der Anwendung
- Umgebung
- Datenbank
- Mail
- geheime Schlüssel

Die Datei kann sensible Informationen enthalten und gehört normalerweise nicht in ein öffentliches GitHub-Repository.

---

## `artisan`

`artisan` ist das Kommandozeilenwerkzeug von Laravel.

Beispiel:

```powershell
php artisan serve
```

Später verwenden wir Artisan beispielsweise auch für:

```powershell
php artisan route:list
php artisan make:controller
php artisan make:model
php artisan migrate
```

---

## `composer.json`

Diese Datei beschreibt die PHP-Abhängigkeiten des Projekts.

Composer liest diese Datei.

---

## `composer.lock`

Diese Datei speichert die genauen Versionen der installierten PHP-Pakete.

Dadurch können andere Entwickler möglichst genau dieselben Paketversionen installieren.

---

## Die wichtigsten Ordner für den Anfang

Für die ersten Laravel-Teile konzentrieren wir uns hauptsächlich auf:

```text
routes/
resources/views/
app/Http/Controllers/
database/
```

Alles andere lernen wir Stück für Stück kennen.
