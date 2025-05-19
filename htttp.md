# HTTP-Kommunikation zwischen Client und Server


---

## 🔤 HTTP-Verben (Methoden)

| Methode | Beschreibung                            |
|---------|-----------------------------------------|
| `GET`   | Fordert Daten vom Server an             |
| `POST`  | Sendet Daten an den Server              |
| `PUT`   | Aktualisiert vorhandene Daten komplett  |
| `PATCH` | Aktualisiert Daten teilweise            |
| `DELETE`| Löscht Daten auf dem Server             |

---

## 📡 HTTP-Statuscodes

| Kategorie | Bedeutung                | Beispiele          |
|-----------|--------------------------|--------------------|
| `2xx`     | ✅ Erfolg                 | `200 OK`, `201 Created` |
| `3xx`     | 🔁 Umleitung              | `301 Moved Permanently`, `302 Found` |
| `4xx`     | ❌ Client-Fehler          | `400 Bad Request`, `404 Not Found` |
| `5xx`     | 💥 Server-Fehler          | `500 Internal Server Error`, `503 Service Unavailable` |

---

## 🌐 URL-Aufbau

**Beispiel-URL:**


| Teil         | Bedeutung                              |
|--------------|----------------------------------------|
| `https`      | Protokoll                              |
| `www.example.com` | Hostname (Domain)                 |
| `:8080`      | Port (optional, hier: 8080)            |
| `/eb/index.html` | Pfad zur Datei/Seite               |
| `?id=123&name=x` | Query-Parameter (Schlüssel=Wertepaar) |
| `#Fragment`  | Fragment (verlinkt z. B. zu einem Anker auf der Seite) |

---

✅ Diese Struktur hilft dir beim Verständnis, wie eine HTTP-Anfrage aufgebaut ist und was bei der Kommunikation zwischen Client und Server passiert.


:

# 📦 CSS Box Model

Das CSS Box Model beschreibt die Struktur jedes HTML-Elements im Layout. Es besteht aus vier Bereichen (von innen nach außen):

+-----------------------------+
| margin |
| +-----------------------+ |
| | border | |
| | +-----------------+ | |
| | | padding | | |
| | | +-----------+ | | |
| | | | content | | | |
| | | +-----------+ | | |
| | +-----------------+ | |
| +-----------------------+ |
+-----------------------------+


## 🔹 1. `content`
Der eigentliche Inhalt – z. B. Text, Bild usw.

## 🔹 2. `padding`
Innenabstand zwischen dem Inhalt und dem Rahmen (border).

```css
padding: 20px;           /* alle Seiten */
padding: 10px 15px;      /* oben/unten: 10px, rechts/links: 15px */

border: 2px solid black;

margin: 20px;            /* alle Seiten */
margin: 0 auto;          /* zentriert horizontal */

