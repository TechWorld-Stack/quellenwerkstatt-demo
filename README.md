# Quellenwerkstatt · DCR × HCI/CSCW

[![Demo](https://img.shields.io/badge/Live-Demo%20(Render)-blue)](https://quellenwerkstatt-demo.onrender.com)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0%20(Vanilla%20JS)-green)](#technische-architektur--datenschutz)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Interaktive Lehr- und Erhebungsplattform für ein experimentelles Paradigma zum universitären Peer-Review: Eine Person erstellt aus vier Quellen ein Entscheidungsmemo; eine zweite Person prüft und überarbeitet es im strukturierten Peer-Review.

> **Live-Instanz:** [quellenwerkstatt-demo.onrender.com](https://quellenwerkstatt-demo.onrender.com)  
> *(Statische Single-Page-Application ohne Backend, gehostet in Frankfurt a. M.)*

---

## Quickstart (Lokale Ausführung)

Das gesamte Tool besteht aus einer einzigen Datei ohne Build-Schritt oder Abhängigkeiten:

```bash
# Repository klonen
git clone [https://github.com/TechWorld-Stack/quellenwerkstatt-demo.git](https://github.com/TechWorld-Stack/quellenwerkstatt-demo.git)

# Datei direkt im Browser öffnen
cd quellenwerkstatt-demo
open index.html # unter macOS (unter Windows: start index.html / Linux: xdg-open index.html)
