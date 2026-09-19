# Teil 1 – Wichtige Befehle

Diese Übersicht enthält die wichtigsten Befehle aus Teil 1.

---

## PHP-Version prüfen

```powershell
php -v
```

---

## Composer-Version prüfen

```powershell
composer --version
```

---

## Git-Version prüfen

```powershell
git --version
```

---

## Neues Laravel-Projekt erstellen

```powershell
composer create-project laravel/laravel laravel-fuer-anfaenger
```

---

## In das Projekt wechseln

```powershell
cd laravel-fuer-anfaenger
```

---

## Projekt in Visual Studio Code öffnen

```powershell
code .
```

---

## Laravel-Server starten

```powershell
php artisan serve
```

Standardadresse:

```text
http://127.0.0.1:8000
```

---

## Laravel-Version anzeigen

```powershell
php artisan --version
```

---

## Alle Artisan-Befehle anzeigen

```powershell
php artisan list
```

---

## Routen anzeigen

Dieser Befehl wird ab Teil 2 besonders interessant:

```powershell
php artisan route:list
```

---

## Git-Status prüfen

```powershell
git status
```

---

## Composer-Abhängigkeiten installieren

Dieser Befehl wird wichtig, wenn ein bestehendes Laravel-Projekt von GitHub geklont wurde:

```powershell
composer install
```

---

## Merksatz

```text
PHP
→ Programmiersprache

Laravel
→ PHP-Framework

Composer
→ Paketmanager für PHP

Artisan
→ Laravel-Kommandozeilenwerkzeug

Git
→ Versionsverwaltung
```
