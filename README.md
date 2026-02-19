AI Voice Agent und Make Scenario für Demo GmbH

Dieses Repository enthält die Konfigurationen und Prompts für einen AI Voice Agent (ElevenLabs) zur telefonischen Unterstützung einer Hausverwaltung (Demo GmbH) sowie das zugehörige Make Scenario zur Datenverarbeitung.

Inhalte

Die Konfigurations- und Prompt-Dateien sind im Repo enthalten. Dazu gehören unter anderem der System-Prompt, Prompts für technische Anliegen, allgemeine Fragen, Abrechnungsfragen und Notfälle, die Kategorisierungs-Logik, die Wissensdatenbank und ein Beispiel für die erste Nachricht.

Es gibt außerdem mehrere Bilder, die Workflows und Datenstrukturen visualisieren, wie den Anruf-Workflow oder die Daten­erfassung nach dem Anruf.

Die Datei „AI Voice Agent Rezeptionist Scenario.blueprint.json“ ist der Blueprint-Export deines Make-Scenarios.

Verwendung

Um das Make Scenario wieder zu nutzen, importiere die JSON-Datei in Make. Öffne Make, wähle Scenario importieren und lade die Blueprint-Datei hoch. Module und Verknüpfungen können danach neu verbunden werden.

Für den ElevenLabs Agent öffne den Agent Builder in ElevenLabs. Kopiere die Inhalte der Prompt-Dateien in die jeweiligen Bereiche des Agenten (System Prompt, Tools, Wissen, Routing). Passe dort die nötigen API-Keys lokal an, diese gehören nicht ins Repository.

Wichtige Hinweise

API-Keys und Secrets gehören nicht ins Repository. Stattdessen sollten diese in einer .env Datei oder über GitHub Secrets gespeichert werden.

Umgebungsvariablen wie Webhooks und Links zu der Googlesheet müssen angepasst werden

Ziel

Dieses Repository bietet eine geteilte Basis für einen telefonischen AI-Agenten für Support, automatisierte Abläufe via Make und eine nachvollziehbare Dokumentation der Prompts und Workflow-Strukturen.
