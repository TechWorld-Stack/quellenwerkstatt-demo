
# Quellenwerkstatt · DCR × HCI/CSCW

[![Demo](https://img.shields.io/badge/Live-Demo%20(Render)-blue)](https://quellenwerkstatt-demo.onrender.com)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0%20(Vanilla%20JS)-green)](#technische-architektur--datenschutz)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Interaktive Lehr- und Erhebungsplattform für ein experimentelles Paradigma zum universitären Peer-Review: Eine Person erstellt aus vier Quellen ein Entscheidungsmemo; eine zweite Person prüft und überarbeitet es im strukturierten Peer-Review.

> **Live-Instanz:** [quellenwerkstatt-demo.onrender.com](https://quellenwerkstatt-demo.onrender.com)  
> *(Statische Single-Page-Application ohne Backend, gehostet in Frankfurt a. M.)

---

## Quickstart (Lokale Ausführung)

Das gesamte Tool besteht aus einer einzigen Datei ohne Build-Schritt oder externe Abhängigkeiten:

```bash
# Repository klonen
git clone https://github.com/TechWorld-Stack/quellenwerkstatt-demo.git

# Datei direkt im Browser öffnen
cd quellenwerkstatt-demo
open index.html # unter macOS (Windows: start index.html / Linux: xdg-open index.html)

```

---

## Wissenschaftliches Konzept: Ein Interface, zwei Bedingungen, eine Übergabe

Zwei Unterstützungsbedingungen unterscheiden sich ausschließlich in der Erstellung des Erstentwurfs. Die anschließende Übergabe und das Peer-Review sind in beiden Bedingungen identisch:

* **HCI-Perspektive:** Individuelle Fehlererkennung und quellenbezogene Begründungsqualität der erstellenden Person.


* **CSCW-Perspektive:** Informationstransparenz (*Workspace Awareness*), Fehlerfortpflanzung und nachgelagerter Verifikationsaufwand im gemeinsamen Endmemo.


### Die experimentellen Bedingungen

| Bedingung | Operative Umsetzung |
| --- | --- |
| **A · Substitute** | Vollständiger KI-Lösungsvorschlag; kann übernommen, editiert oder verworfen werden.

 |
| **B · Scaffold** | Eigene Erarbeitung über drei Leitfragen: vorläufige Hypothese, Evidenzabwägung, begründete Zwischenentscheidung. Kein Textentwurf.

 |

* **Kontrollierter Fehler:** Beide Bedingungen enthalten dieselbe Diskrepanz zur Budgetannahme (120 € Wochenbudget im Entwurf/Hinweis vs. 80 € tatsächliches Budget bei 120 € Kosten laut Quelle B). Der Fehler ist ausschließlich durch Primärquellenprüfung auflösbar.


* **Standardisierte Übergabe:** Beide Gruppen deklarieren pro Kernargument die genutzte Quelle, eine Prüfbegründung, die Herkunft (*Eigen, KI-Unterstützung, Gemischt, Unbekannt*) sowie den Prüfstatus (*Offen, Geprüft, Strittig*).



---

## Forschungsdesign & Hypothesen

### Primäre Endpunkte (Holm-Bonferroni-korrigiert)

* **HCI-H1:** In *Scaffold* identifiziert die erstellende Person den eingebetteten Fehler signifikant häufiger als in *Substitute*.


* **CSCW-H2:** In *Scaffold* gelangt der eingebettete Fehler nach dem Peer-Review seltener in die finale Entscheidungsempfehlung als in *Substitute*.



### Messgrößen

| Dimension | Erfassung & Auswertung |
| --- | --- |
| **Fehlererkennung** | Verblindete Kodierung von Erst-Memo und Endmemo anhand Antwortschlüssel

 |
| **Review-Beitrag** | Differenzierung: Fehler beibehalten, korrigiert oder neu eingeführt

 |
| **Workspace Awareness** | Erfassung des deklarierten vs. wahrgenommenen Prüfstands vor der Quellenprüfung

 |
| **Prozessmetriken** | Phasenzeiten (Erstellung vs. Review); optionale lokale Ereigniserfassung

 |
| **Subjektive Maße** | Skalen zu Arbeitsbelastung, Transparenz und interpersonalem Vertrauen (E1, P1, P2, E2)

 |

---

## Bezug zu DCR (Dominant ChatGPT Reliance)

Das Paradigma operationalisiert die Kernfragen des DCR-Frameworks: Wo entsteht der erste inhaltlich tragende Lösungsbeitrag (*Delegation Centrality*) und wie wirkt sich primärer KI-Zugriff auf eigenständige Prüfprozesse aus? Im Experiment wird die Assistenzarchitektur randomisiert, nicht das habituelle DCR-Merkmal der Person.

---

## Technische Architektur & Datenschutz

* **Zero-Backend:** Eine statische HTML/JS-Datei. Keine externen CDNs, keine Tracking-Skripte, keine Datenbankanbindung.


* **Datensparsamkeit:** Sämtliche Eingaben verbleiben rein flüchtig im Arbeitsspeicher des Browsers (kein LocalStorage).


* **Datenaustausch:** Übergaben und Reviews werden manuell via JSON-Download/Upload zwischen den Zweiergruppen übergeben.


* **Ereignis-Logging:** Die Erfassung von Interaktionszeiten ist standardmäßig deaktiviert und erfasst bei Aktivierung keine Textinhalte oder Tastenanschläge.



---

## Roadmap vor Produktiveinsatz

* [x] Funktionsfähiger Prototyp mit Moduswahl und JSON-Export


* [x] SoSci-Survey-Instrumente und XML-Export für universitäre Instanzen


* [ ] Modus-Sperre für getrennt verblindete Versuchsgruppen
* [ ] Pilotierung mit 12–16 Zweiergruppen zur Bestimmung der Basisraten


* [ ] Präregistrierung der binomialen GEE-Auswertungsmodelle



## Citation & Kontakt

Wenn Sie diesen Prototyp für Lehr- oder Forschungszwecke nutzen:

@misc{grahl2026quellenwerkstatt,
  author = {Grahl, Christian},
  title = {Quellenwerkstatt: Dyadisches Peer-Review-Paradigma für Mensch-KI-Interaktion und CSCW},
  year = {2026},
  publisher = {GitHub},
  howpublished = https://github.com/TechWorld-Stack/quellenwerkstatt-demo
}

**Kontakt:** Christian Grahl · Promotionsvorhaben *Dominant ChatGPT Reliance*

**Lizenz:** [MIT License](https://www.google.com/search?q=LICENSE)
