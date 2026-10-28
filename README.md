# Physikalische Visualisierungen

Interaktive Lern-Webseiten für Lehrveranstaltungen an der JLU Gießen.
Jede App ist eine einzelne, eigenständige HTML-Datei ohne externe Abhängigkeiten und läuft direkt im Browser.

## Grundlagen der Plasmaphysik

| Ordner | Inhalt |
|---|---|
| [`driftlabor/`](driftlabor/) | **Driftlabor** – Einzelteilchenbewegung und Driften (E×B, ∇B, Krümmung u. a.) |
| [`debye/`](debye/) | **Debye-Labor** – Abschirmung im Plasma: 1D-Zwei-Fluid-Simulation mit Debye-Hückel-Vergleich |
| [`plasmawave/`](plasmawave/) | **Plasmaspiegel** – EM-Welle trifft auf ein Plasma: 1D-FDTD-Simulation von Reflexion, Eindringen und Transmission (Cutoff bei der Plasmafrequenz) |
| [`plasmakarte/`](plasmakarte/) | **Plasma-Landkarte** – Dichte-Temperatur-Karte idealer, nicht-idealer und entarteter Plasmen mit Teilchenbild, Längenvergleich und Beispielen vom Sonnenwind bis zum Weißen Zwerg |
| [`kopplung/`](kopplung/) | **Kopplungslabor** – stark gekoppelte Plasmen: 2D-Molekulardynamik geladener Teilchen (Yukawa) vom Gas über die Flüssigkeit zum Coulomb-Kristall, mit Paarkorrelation g(r), Phasendiagramm und Umrechnung auf Staubplasma, Ionenfalle und Elektronen auf Helium |
| [`entartung/`](entartung/) | **Entartungslabor** – das Elektronengas vom klassischen bis zum entarteten Grenzfall: Fermi-Kugel im Impulsraum, Fermi-Dirac gegen Maxwell-Boltzmann, Entartungsdruck, Debye- und Thomas-Fermi-Abschirmung, Masse-Radius-Beziehung weißer Zwerge mit Chandrasekhar-Grenze |
| [`ionisation/`](ionisation/) | **Ionisationslabor** – wann ein Gas zum Plasma wird: Saha-Gleichung für H, He, Na und Ar, Dichte-Temperatur-Karte des Ionisationsgrads, Kontinuumsabsenkung und Druckionisation, optional entartete Elektronen, Teilchenbild und Energieniveaus |

## Tutorium Raumfahrt

| Ordner | Inhalt |
|---|---|
| [`raumfahrt/potential/`](raumfahrt/potential/) | **Potentiallabor** – konservative Kräfte und Potentialfelder: Äquipotentiallinien und Feldvektoren mehrerer Massen, Arbeit entlang zweier Wege und auf geschlossenen Umläufen, Vergleich mit Wirbelfeld und Reibung, Probekörper mit Energiebilanz, mgh-Näherung gegen −GMm/r |
| [`raumfahrt/kanonenball/`](raumfahrt/kanonenball/) | **Newtons Kanonenball** – vom Wurf zur Umlaufbahn: Newtons Gedankenexperiment mit Bahnschar vom Berg, Wurfparabel auf flacher Erde gegen 1/r²-Gravitation, Fallstrecke gegen Erdkrümmung, Kreisbahn- und Fluchtgeschwindigkeit, optional Luftwiderstand |
| [`raumfahrt/kepler/`](raumfahrt/kepler/) | **Keplerlabor** – das Kepler-Problem: Bahnen aus Startort und -geschwindigkeit, Kegelschnitte, effektives Potential, Flächensatz, drittes Keplergesetz, Vis-viva-Gleichung, Kreisbahn- und Fluchtgeschwindigkeit, Beispiele von der ISS bis zum Hohmann-Transfer zum Mars |
| [`raumfahrt/zweikoerper/`](raumfahrt/zweikoerper/) | **Zweikörperlabor** – Schwerpunkt- und Relativbewegung zweier Massen, reduzierte Masse, Labor- und Schwerpunktsystem, Baryzentrum und Radialgeschwindigkeit, Beispiele von Erde–Mond bis zum Doppelstern |

## Aufbau

Pro Ordner:

- `index.html` – die App (lokal im Browser öffnen)
- `*_ilias.zip` – Paket für ein ILIAS-HTML-Lernmodul (Startdatei: `index.html`)
- `*_kachel.png` – Kachelbild für ILIAS
