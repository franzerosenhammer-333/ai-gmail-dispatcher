# AI-Powered Gmail Dispatcher & Sentiment Analyzer

Ein automatisierter No-Code/KI-Workflow, gebaut mit **Make.com** und **OpenAI API**, der eingehende E-Mails in Echtzeit analysiert, kategorisiert und strukturierte Antwortentwürfe generiert.

---

## 📌 Übersicht & Funktionalität

Dieser Workflow überwacht ein Gmail-Postfach auf neue eingehende Nachrichten und verarbeitet sie automatisch durch ein Large Language Model (LLM):

1. **Trigger:** Erfassung neuer Nachrichten im Gmail-Eingang.
2. **KI-Analyse (Prompt Engineering):**
   * **Sentiment-Analyse:** Erkennung der Stimmung (*Positiv / Neutral / Negativ*).
   * **Kategorisierung:** Zuordnung (*Support, Anfrage, Spam, Wichtig*).
   * **Priorisierung:** Dringlichkeitsskala von 1 bis 5.
   * **Zusammenfassung:** Kernaussage in max. 2 Sätzen.
   * **Antwort-Generierung:** Automatischer Entwurf einer passenden, professionellen Antwort.
3. **Output:** Ausgabe als strukturierte Daten zur weiteren Verarbeitung.

---

## 🛠️ Verwendete Technologien

* **Make.com** (Workflow-Automatisierung & Logik)
* **OpenAI API / LLM Prompting** (Text-Analyse & KI-Verarbeitung)
* **Gmail API Integration** (Trigger & Nachrichten-Handling)

---

## 🖼️ Workflow-Architektur

![Make.com Workflow](./Screenshot%202026-10-12%20092204.png)
