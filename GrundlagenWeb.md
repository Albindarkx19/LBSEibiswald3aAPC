#  Webentwicklung & Sicherheit  
**Autor:** Albin  
<br>
**LBS Eibiswald | 3aAPC**

---

##  1. Installation der Entwicklungsumgebung

Für die Entwicklung von PHP-basierten Webanwendungen wird eine lokale Serverumgebung benötigt.  
Diese besteht typischerweise aus drei Hauptkomponenten:

| Komponente | Beschreibung | Beispiel |
|-------------|---------------|-----------|
| **Webserver** | Liefert Webseiten an den Browser aus. | Apache, Nginx |
| **PHP** | Programmiersprache zur serverseitigen Verarbeitung. | PHP 8.x |
| **Datenbank** | Speichert Benutzerdaten, Logins, Produkte usw. | MySQL, MariaDB |

---

###  Mögliche Installationsarten

####  Variante 1: XAMPP (empfohlen)
Ein Komplettpaket mit **Apache**, **PHP** und **MySQL**.  
Ideal für Einsteiger, da alles vorkonfiguriert ist.

**Installation:**
1. Lade [XAMPP](https://www.apachefriends.org/de/index.html) herunter.  
2. Installiere und starte den **Apache**- und **MySQL**-Dienst.  
3. Lege dein Projekt unter  
   `C:\xampp\htdocs\HelloWorld\index.php`  
   ab.  
4. Rufe im Browser auf:  
    `http://localhost/HelloWorld`

**Vorteile:**
- Sehr einfach zu installieren  
- Keine manuelle Konfiguration nötig  
- Mit phpMyAdmin zur Datenbankverwaltung  

---

####  Variante 2: PHP Built-in Server
Nur PHP erforderlich – kein komplettes Paket.  
Diese Variante ist besonders nützlich für kleine Projekte oder Tests.

**Schritte:**
1. Stelle sicher, dass PHP installiert ist (`php -v` im Terminal).  
2. Öffne dein Projektverzeichnis im Terminal.  
3. Starte den Server:

   ```bash
   php -S localhost:8000
