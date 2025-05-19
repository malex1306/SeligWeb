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



