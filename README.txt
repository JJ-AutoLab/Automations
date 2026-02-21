---

# Lead Qualification Automation (n8n)

Dieser Repository enthält einen **n8n Workflow zur automatisierten Lead-Qualifizierung** mit Conversational AI.

Der Workflow kombiniert:

* Chatbasierte Lead-Erfassung
* Knowledge-Base-gestützte Antworten
* Automatisches Lead Scoring
* Speicherung strukturierter Lead-Daten
* Vorbereitung für den Vertrieb

Der Fokus liegt auf **Business-Qualifizierung**, nicht auf direktem Verkauf.

---

## 🔍 Was der Workflow macht

* Nimmt Chat-Nachrichten über Webhook entgegen
* Beantwortet Fachfragen über eine Knowledge Base
* Führt natürliche Qualifizierungs-Gespräche
* Bewertet Leads automatisch (Cold / Warm / Hot)
* Speichert alle Informationen in Google Sheets
* Nutzt Vektorsuche (Supabase) für Kontext & Wissen

---

## 🧠 Kernkomponenten

* **AI Agent** (Conversational Lead Qualification)
* **Knowledge Base** (Vector Store)
* **Webhook / Chat Interface**
* **Lead Scoring Logic**
* **Google Sheets Integration**
* **Supabase Vector Store**
* **OpenAI / Mistral Embeddings**

---

## 📁 Repository Inhalt

* `Leads Qualifikation Automation.json` – n8n Workflow Export
* `README` – Projektbeschreibung

---

## ⚙️ Voraussetzungen

* n8n (Self-hosted oder Cloud)
* OpenAI oder Mistral API
* Supabase Projekt (Vector Store)
* Google Sheets (für Lead-Speicherung)

---

## 🔐 Sicherheit & Datenschutz

Dieser Workflow ist **bereinigt für öffentliche Repositories**:

* Keine API Keys enthalten
* Keine Tokens oder Secrets enthalten
* Keine echten Webhook-URLs
* Keine echten Lead-Daten
* Credentials müssen nach Import neu gesetzt werden

Beim Import fragt n8n automatisch nach eigenen Credentials.

---

## 🚀 Installation

1. n8n öffnen
2. Workflow importieren (`.json`)
3. Eigene Credentials hinterlegen
4. Webhooks aktivieren
5. Workflow starten

---

## ⚠️ Hinweise

* Dieser Workflow ist eine **technische Vorlage**
* Verantwortung für DSGVO, Datenspeicherung und rechtliche Vorgaben liegt beim Nutzer
* Keine Garantie für Lead-Qualität oder Conversion

---

## 📜 Lizenz

Frei nutzbar für private und kommerzielle Zwecke.
Weitergabe oder Anpassung erlaubt.

---

Wenn du willst, kann ich dir:

* eine **extrem kurze README (5–6 Zeilen)**
* eine **Version für Kunden**
* oder eine **README mit Architektur-Grafik**

machen.
