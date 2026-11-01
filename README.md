# Quellenwerkstatt · DCR × HCI/CSCW

Lokale Lehr- und Vortragsdemo für ein geplantes Experiment zum universitären Peer-Review. Eine Person erstellt aus vier kurzen Quellen ein Entscheidungsmemo, eine zweite Person prüft und überarbeitet es.

> **Status:** Die Anwendung ist eine funktionsfähige Demo mit erfundenen Lehrmaterialien. Sie ist kein validiertes Forschungsinstrument und enthält keine empirischen Ergebnisse. Es werden keine KI-Dienste aufgerufen; alle Unterstützungstexte sind fest vorgegeben.

## Idee: ein Interface, zwei Bedingungen, eine Übergabe

Zwei Unterstützungsbedingungen unterscheiden sich nur in der Erstellung der ersten Lösung. Die anschließende Übergabe ist in beiden Bedingungen identisch. Zwei Perspektiven gehören zu demselben Experiment (keine unabhängigen Replikationen):

- **HCI:** individuelle Fehlererkennung und Quellenbegründung.
- **CSCW:** welche Aussagen, Fehler und offenen Prüfaufgaben die zweite Person erreichen und wie sie im gemeinsamen Ergebnis behandelt werden.

## Lernaufgabe

„Soll ein universitärer Lernraum während einer zweiwöchigen Prüfungsphase werktags bis 22 Uhr geöffnet werden?“

Vier fiktive Quellen (A Nachfrage, B Kosten und Budget, C beobachtete Nutzung, D Rahmen des Piloten) bilden die Grundlage. Ergebnis ist ein kurzes Memo mit Empfehlung und zwei zentralen Aussagen, jeweils mit Quelle, Herkunft und Prüfstatus. Anschließend folgt ein Peer-Review mit gemeinsamem Endmemo. Die Aufgabe prüft quellengebundene Argumentation, keine Fachkenntnisse über reale Hochschulverwaltung. Es gibt keine automatische Benotung und keine Kompetenzdiagnose.

## Die beiden Bedingungen

| Bedingung | Inhalt |
|---|---|
| **A · Substitute** | Vollständiger fester Lösungsvorschlag, der übernommen, bearbeitet oder verworfen werden kann. |
| **B · Scaffold** | Eigene Bearbeitung in drei freiwilligen Schritten: vorläufige Hypothese, Evidenz und Einwand, begründete Zwischenentscheidung. Keine fertige Gesamtlösung. |

Quellen, Zeitbudget, Memo-Feld und Übergabeformular sind in beiden Bedingungen gleich.

**Kontrollierter Fehler:** Beide Varianten enthalten dieselbe falsche Budgetannahme (120 Euro verfügbares Wochenbudget). Quelle B nennt tatsächlich 80 Euro Budget bei 120 Euro Kosten pro Woche. Der Fehler ist im Quellenmaterial auflösbar. Die Bedingungen bilden ein **Bedingungspaket**; Unterschiede lassen sich nicht allein einem einzelnen Merkmal wie Friktion oder Textlänge zuschreiben. Auffälligkeit und Schwierigkeit des Fehlers sind vor einer Studie zu pilotieren.

## Übergabe

Beide Bedingungen übergeben:

1. Memo und zwei zentrale Aussagen,
2. zugeordnete Quelle und kurze Prüfbegründung,
3. Herkunft als Selbstauskunft (eigen, bereitgestellte Unterstützung, gemischt, unbekannt),
4. Prüfstatus (offen, nach eigener Angabe geprüft, strittig).

Private Scaffold-Notizen, Bedingung und Ereignisse bleiben zurück. „Geprüft“ ist eine Angabe der ersten Person; das System bestätigt keine sachliche Richtigkeit. Da die Übergabe konstant ist, kann der Vergleich nicht zeigen, dass Herkunftsmarkierungen oder das Formular gegenüber einem normalen Editor helfen.

## Studienprogramm

| Schritt | Inhalt |
|---|---|
| **1 · Machbarkeitspilot** | Ein-Aufgaben-Demo mit etwa 12–16 Zweiergruppen (organisatorischer Vorschlag, keine Power-Berechnung). Zufällige Zuteilung A/B je Gruppe, Rollen fest. Ablauf: 3 Min. Einführung, 12 Min. Erstellung, 8 Min. Review, 5 Min. Nachbefragung und Aufklärung. Die Übergabe ist der einzige Kommunikationskanal. Geprüft werden Verständlichkeit, Erkennbarkeit des Fehlers, Dauer und fehlende Eingaben. |
| **2 · Kontrollierter Hauptvergleich** | Mehrere vergleichbare Aufgaben (z. B. vier, davon zwei mit Fehlerfall), ausbalancierte Reihenfolge, Modus je Gruppe konstant, Stichprobenplanung und Präregistrierung. |
| **3 · Eigenleistung (optional)** | Neue ungestützte Aufgabe mit Baseline und verzögerter Nachmessung für „Retained Human Performance“. |

### Primäre Hypothesen

- **HCI-H1:** In Scaffold identifiziert die erstellende Person den eingebetteten Fehler häufiger korrekt als in Substitute.
- **CSCW-H2:** In Scaffold gelangt der eingebettete Fehler seltener in die finale gemeinsame Empfehlung als in Substitute.

Beide Tests bilden eine vorab definierte Holm-Familie. Berichtet werden Richtung und Effektgröße mit Unsicherheitsintervallen. Nicht signifikante Ergebnisse belegen keine Gleichwertigkeit.

### Messgrößen

| Messgröße | Erfassung |
|---|---|
| Individuelle Fehlererkennung | Verblindete Kodierung von Erst-Memo und Prüfbegründung anhand Antwortschlüssel |
| Fehler im gemeinsamen Endmemo | Verblindete Kodierung der finalen Empfehlung |
| Verifikationsqualität | Vorab definierte Rubrik (Quellenpassage, Schlussfolgerung, Umgang mit Widerspruch) |
| Review-Beitrag | Fehler bestehen geblieben, behoben oder neu eingeführt (Erst-Memo vs. Endmemo) |
| Awareness | Zweite Person benennt Prüfstatus und verbliebene Unsicherheit |
| Entscheidungsqualität | Verblindete Rubrikbewertung vor und nach Review |
| Zeit | Getrennte Dauer von Erstellung und Review |
| Wahrgenommene Kontrolle, Belastung | Kurze, vorab festgelegte Selbstberichte |

Quellenklicks gelten nicht als Verständnis. Binäre Endpunkte werden bei mehreren Aufgaben z. B. mit einem logistischen Modell mit Gruppeneffekt und Aufgabenadjustierung ausgewertet. Auswertung nach Zuteilung; Ausfälle werden dokumentiert, nicht als korrekt gewertet.

## Bezug zu DCR

DCR motiviert die Frage, wo substanzielle Lösungsarbeit entsteht. Im Experiment wird die Unterstützung randomisiert, nicht das DCR-Merkmal einer Person. Es wird kein DCR_EQ berechnet, und Ereignisse oder Herkunftsangaben sind keine diagnostischen DCR-Werte. Trust, Verifikation und Leistung bleiben getrennte Größen.

## Datensparsamkeit und Datenschutz

- Eine HTML-Datei mit eingebettetem JavaScript; kein Konto, keine Datenbank, kein Server, keine Netzwerkanfragen (per Content-Security-Policy gesperrt).
- Daten liegen nur im Arbeitsspeicher des Tabs. Beim Neuladen gehen nicht exportierte Eingaben verloren.
- Übergaben und Reviews werden manuell als JSON-Datei ausgetauscht. Sie enthalten bewusst freigegebene Freitexte und sind nicht automatisch anonym oder manipulationssicher.
- Die Ereigniserfassung ist freiwillig und standardmäßig aus. Sie erfasst nur relative Zeitpunkte und Ereignistypen, keine Tastaturmitschnitte oder Freitexte. Ein nachträglicher Beginn ist gekennzeichnet; fehlende Ereignisse bedeuten nicht Nichtnutzung.
- Eine echte Studie benötigt Einwilligung, lokale ethische Prüfung, freiwillige Teilnahme ohne Benotungsnachteile, eine Alternative, ein Aufbewahrungs- und Löschkonzept sowie Aufklärung über die kontrollierten Fehler.

## Grenzen der Demo

Die Demo legt ihre Struktur offen (freie Moduswahl, Beispielübergabe, Auflösung) und ist nicht unverändert als verblindetes Studieninstrument geeignet.

- **Vor dem Pilot ergänzen:** Teilnehmendenansicht ohne Moduswahl und Auflösung, verdeckte Zuteilung, Instruktion und Einwilligung, getestete Kodierregeln, Nachbefragung, standardisierte Übergabe.
- **Vor der Hauptstudie ergänzen:** zusätzliche Aufgaben und korrekte Vergleichsfälle, Stichprobenplanung, Präregistrierung, Ratertraining, Datenmanagement, Ausfallregeln.
- **Bewusst nicht enthalten:** Live-Generierung, LMS-Anbindung, Echtzeit-Mehrbenutzereditor, adaptive Risikoklassifikation, automatisches Herkunftsraten, DCR-Dashboard.

## Dateien und Hosting

| Datei | Zweck |
|---|---|
| `index.html` | Gesamte Anwendung (HTML, CSS, JavaScript) |
| `.github/workflows/pages.yml` | Workflow für die Veröffentlichung über GitHub Pages |

Die Seite ist statisch und benötigt weder Build- noch Start-Befehl. Auf einem Static-Site-Host genügen das Repository-Root als Publish-Verzeichnis und keine Umgebungsvariablen. Lokal lässt sich `index.html` direkt im Browser öffnen.

## Einordnung

Die Demo repliziert keine früheren Befunde und bestätigt keine Wirksamkeit. Alle Zahlen im Quellenpaket sind fiktiv.
