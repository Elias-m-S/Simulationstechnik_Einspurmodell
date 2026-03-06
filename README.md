# Einspurmodell: Simulation, Analyse und Optimierung

Dieses Repository enthält den vollständigen Programmentwurf zur Analyse der Querdynamik eines Kraftfahrzeugs mittels des Einspurmodells. Das Projekt umfasst die Herleitung nichtlinearer Bewegungsgleichungen, den Vergleich mit linearisierten Zustandsraummodellen sowie eine automatisierte Parameteroptimierung.

## Projektstruktur

Das Projekt ist in fünf Kernaufgaben unterteilt:

* **Aufgabe 1 & 2:** Modellbildung und Simulation des nichtlinearen Einspurmodells in MATLAB.
* **Aufgabe 3:** Grafischer Vergleich zwischen linearem und nichtlinearem Modell in Simulink inklusive automatisierter Fehlerberechnung (Maximalabweichung).
* **Aufgabe 4:** Analyse des Frequenzgangs (Bode-Diagramm) für das Übertragungsverhalten vom Lenkwinkel zum Schwimmwinkel.
* **Aufgabe 5:** Optimierung der Fahrgeschwindigkeit $v$ zur Minimierung des stationären Schwimmwinkels mittels MATLAB-Simulink Co-Simulation.

## Dateiliste

| Datei | Beschreibung |
| :--- | :--- |
| `Programmentwurf_Simulationstechnik.mlx` | Haupt-Live-Script: Steuert alle Simulationen und die Optimierung. |
| `Simulink.slx` | Zentrales Simulink-Modell für den Vergleich und die Co-Simulation. |

## Installation & Ausführung

1. Klonen Sie das Repository oder laden Sie die Dateien herunter.
2. Stellen Sie sicher, dass MATLAB und Simulink installiert sind.
3. Öffnen Sie das Live Script `Programmentwurf_Simulationstechnik.mlx`.
4. Führen Sie die Sektionen nacheinander aus. Das Skript ruft die zugehörigen Simulink-Modelle automatisch im Hintergrund auf.
