# Physikalische Visualisierungen

Interaktive Lern-Webseiten zur Vorlesung *Grundlagen der Plasmaphysik* (JLU Gießen).
Jede App ist eine einzelne, eigenständige HTML-Datei ohne externe Abhängigkeiten und läuft direkt im Browser.

| Ordner | Inhalt |
|---|---|
| [`driftlabor/`](driftlabor/) | **Driftlabor** – Einzelteilchenbewegung und Driften (E×B, ∇B, Krümmung u. a.) |
| [`debye/`](debye/) | **Debye-Labor** – Abschirmung im Plasma: 1D-Zwei-Fluid-Simulation mit Debye-Hückel-Vergleich |
| [`plasmawave/`](plasmawave/) | **Plasmaspiegel** – EM-Welle trifft auf ein Plasma: 1D-FDTD-Simulation von Reflexion, Eindringen und Transmission (Cutoff bei der Plasmafrequenz) |
| [`plasmakarte/`](plasmakarte/) | **Plasma-Landkarte** – Dichte-Temperatur-Karte idealer, nicht-idealer und entarteter Plasmen mit Teilchenbild, Längenvergleich und Beispielen vom Sonnenwind bis zum Weißen Zwerg |
| [`kopplung/`](kopplung/) | **Kopplungslabor** – stark gekoppelte Plasmen: 2D-Molekulardynamik geladener Teilchen (Yukawa) vom Gas über die Flüssigkeit zum Coulomb-Kristall, mit Paarkorrelation g(r), Phasendiagramm und Umrechnung auf Staubplasma, Ionenfalle und Elektronen auf Helium |

Pro Ordner:

- `index.html` – die App (lokal im Browser öffnen)
- `*_ilias.zip` – Paket für ein ILIAS-HTML-Lernmodul (Startdatei: `index.html`)
- `*_kachel.png` – Kachelbild für ILIAS
