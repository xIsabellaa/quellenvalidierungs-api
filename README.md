# Quellenvalidierungs-API

---

## Beschreibung
Diese API überprüft eine Liste von URLs und liefert Validierungsinformationen wie den HTTP-Status, die Vertrauenswürdigkeit der Domain und eine Beschreibung der Ergebnisse.

---

## Funktionen
- Überprüft die Erreichbarkeit von URLs (HTTP-Statuscode).
- Bewertet die Vertrauenswürdigkeit der Domain basierend auf einer Liste bekannter und seriöser Domains.
- Liefert eine übersichtliche JSON-Ausgabe der Ergebnisse.

---

## Anforderungen
- Python 3.8 oder höher
- Flask
- Requests

---

## Installation
1. Klonen Sie das Repository:
    ```
    git clone https://github.com/IHR-USERNAME/quellenvalidierungs-api.git
    ```
2. Navigieren Sie in das Projektverzeichnis:
    ```
    cd quellenvalidierungs-api
    ```
3. Installieren Sie die erforderlichen Pakete:
    ```
    pip install -r requirements.txt
    ```

---

## Nutzung
1. Starten Sie den Server:
    ```
    python app.py
    ```
2. Greifen Sie auf die API zu:
- Endpoint: `http://localhost:5000/validate`
- Methode: `POST`
- Payload:
    ```
    {
      "urls": ["https://example.com", "https://another-example.com"]
    }
    ```

---

## Deployment auf Render
1. Erstellen Sie ein neues Web Service auf Render.
2. Verlinken Sie dieses Repository.
3. Geben Sie `app.py` als Startskript an.

---

## Lizenz
Dieses Projekt ist unter der MIT-Lizenz lizenziert. Weitere Informationen finden Sie in der Datei LICENSE.

---
