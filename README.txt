---

# AI OUTBOUND LEAD AGENT – n8n WORKFLOW

Dieser n8n Workflow automatisiert den kompletten Prozess für
B2B Lead-Recherche und personalisierte Cold-Outreach-Kampagnen.

Der Fokus liegt auf:

* klarer Zielgruppendefinition
* automatisierter Lead-Recherche
* strukturierter Datenspeicherung
* KI-gestützter Personalisierung
* direkter Übergabe an Instantly

---

## FUNKTIONEN

1. FORMULAR & WEBHOOK

* Formular zur Eingabe von:

  * Kampagnenname
  * Branche
  * Stadt
* Übergabe der Daten per Webhook an n8n

2. GUARDRAILS & VALIDIERUNG

* Blockiert:

  * illegale / unethische Inhalte
  * Unsinn oder Prompt Injection
  * unrealistische oder generische Zielgruppen
* Lässt nur sinnvolle B2B-Nischen zu

3. LEAD-RECHERCHE (GOOGLE)

* Google-Suche über Serper API
* Automatische Filterung von:

  * Branchenverzeichnissen
  * Social Media
  * Bewertungsportalen

4. DATENEXTRAKTION

* Crawlt Ziel-Websites inkl.:

  * /impressum
  * /kontakt
* Extrahiert:

  * Firmenname
  * Ansprechpartner / Geschäftsführer
  * E-Mail-Adresse
  * Telefonnummer
  * Adresse
  * Website

5. DATENAUFBEREITUNG

* Normalisierung von Telefonnummern
* Strukturierte Weitergabe der Daten

6. GOOGLE SHEETS

* Speicherung aller Leads in einer Tabelle
* Saubere Spaltenstruktur für Weiterverarbeitung

7. KI-GESTÜTZTE COLD-E-MAILS

* Personalisierte E-Mail-Texte pro Lead
* Berücksichtigt:

  * Branche
  * Stadt
  * Firma
  * Ansprechpartner
* Kurz, natürlich, kein Massenmail-Stil

8. INSTANTLY INTEGRATION

* Automatische Kampagnenerstellung
* Leads werden direkt zur Kampagne hinzugefügt
* Übergabe von Custom Fields (Telefon, URL, Adresse, Text)

---

## VORAUSSETZUNGEN

Benötigte Services:

* n8n (Self-hosted oder Cloud)
* OpenAI API
* Serper API (Google Search)
* Google Sheets
* Instantly Account

Benötigte n8n Nodes:

* Webhook
* HTTP Request
* IF
* Code
* Google Sheets
* LangChain Nodes
* Instantly Node

---

## SICHERHEIT & DATENSCHUTZ

Dieser Workflow ist sicher für das Hochladen auf GitHub:

* Keine API Keys enthalten
* Keine OAuth Tokens enthalten
* Keine Credentials verknüpft
* Keine echten Webhook-Secrets
* Keine echten Lead-Daten (Pin Data entfernt)

Beim Import fragt n8n automatisch nach eigenen Credentials.

---

## INSTALLATION

1. n8n öffnen
2. "Import Workflow" auswählen
3. JSON-Datei importieren
4. Eigene Credentials setzen:

   * OpenAI
   * Serper
   * Google Sheets
   * Instantly
5. Webhooks aktivieren
6. Workflow aktivieren

---

## OPTIONALE ANPASSUNGEN

* Guardrail-Prompts anpassen
* Weitere Datenfelder extrahieren
* Andere Länder oder Sprachen ergänzen
* CRM statt Google Sheets anbinden
* Mehrstufige E-Mail-Sequenzen bauen

---

## USE CASES

* Leadgenerierung für Agenturen
* SaaS Outbound
* Lokale Dienstleister
* Vertriebsteams
* Automatisierte Akquise-Systeme

---

## RECHTLICHER HINWEIS

Dieser Workflow ist eine technische Vorlage.

Du bist selbst verantwortlich für:

* DSGVO-Konformität
* Cold-E-Mail-Gesetze
* Opt-Out-Mechanismen
* Einhaltung lokaler Vorschriften

---

## LIZENZ

Frei nutzbar für private und kommerzielle Zwecke.
Weitergabe oder Verkauf nur mit entsprechender Kennzeichnung.

---

Wenn du willst, kann ich dir als Nächstes auch:

* eine extrem kurze README (für Marketplace)
* eine Version für Kunden
* oder eine technische Architektur-Erklärung

machen.
