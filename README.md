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
| [`raumfahrt/startlabor/`](raumfahrt/startlabor/) | **Startlabor 3D** – von Newtons Kanonenkugel zum Raketenstart auf einer 3D-Erde: Startort und Startrichtung bestimmen die Bahnneigung, Gewinn durch die Erdrotation, Inertial- und mitrotierendes System, Bodenspur; zweistufige Rakete mit Gravity Turn, Δv-Bilanz (Raketengleichung, Schwerkraft- und Luftwiderstandsverluste) und Staudruck. Enthält three.js (MIT) und ein Erdbild der NASA |
| [`raumfahrt/kepler/`](raumfahrt/kepler/) | **Keplerlabor** – das Kepler-Problem: Bahnen aus Startort und -geschwindigkeit, Kegelschnitte, effektives Potential, Flächensatz, drittes Keplergesetz, Vis-viva-Gleichung, Kreisbahn- und Fluchtgeschwindigkeit, Beispiele von der ISS bis zum Hohmann-Transfer zum Mars |
| [`raumfahrt/zweikoerper/`](raumfahrt/zweikoerper/) | **Zweikörperlabor** – Schwerpunkt- und Relativbewegung zweier Massen, reduzierte Masse, Labor- und Schwerpunktsystem, Baryzentrum und Radialgeschwindigkeit, Beispiele von Erde–Mond bis zum Doppelstern |
| [`raumfahrt/gitterlabor/`](raumfahrt/gitterlabor/) | **Gitterlabor** – Schub im Gitterionentriebwerk (RIT-2X): Ionen zwischen Schirm- und Beschleunigungsgitter als Plattenkondensator, Potential, Feld, Ladungsdichte, Geschwindigkeit und Stromdichte im Spalt; homogene Raumladung, selbstkonsistente Lösung und Child-Langmuir-Grenze; elektrostatischer Druck auf die Gitter, T = ½ε₀(E₀² − E_d²) gegen ṁ·v_ex, Treibstoffe Xe, Kr, Ar; dazu ein 2D-Beamlet (ein Gitterloch, selbstkonsistent mit Boltzmann-Elektronen): Plasmameniskus, Ionenbahnen, Divergenz und Perveanzkurve, Auftreffen auf das Beschleunigungsgitter, Sattelpunkt gegen Elektronenrückströmung, Neutralisator |
| [`raumfahrt/diodenlabor/`](raumfahrt/diodenlabor/) | **Diodenlabor** – Raumladung in der Vakuumdiode (Child-Langmuir): Glühkathode nach Richardson-Dushman (Wolfram, LaB₆), Potential, Feld und Elektronendichte im Spalt, selbstkonsistent mit thermischen Startgeschwindigkeiten nach Langmuir (1923); virtuelle Kathode mit Potentialminimum und umkehrenden Elektronen, Vergleich mit Vakuum und kaltem U^(4/3)-Profil; Kennlinie I(U) mit Steigung 3/2 und Sättigung, I(T) wie in Langmuirs Messung, Perveanz, Elektronen gegen Xenonionen |
| [`raumfahrt/rueckstoss/`](raumfahrt/rueckstoss/) | **Rückstoßlabor** – ein Maschinengewehr als Triebwerk: Plattform auf Luftlager mit Zielscheibe (Rückstoß hin und zurück, Schwerpunkt in Ruhe, Geschwindigkeitspulse und mittlere Geschwindigkeit) gegen Raumsonde im All (Masse verlässt das System); Geschwindigkeitszuwachs Schuss für Schuss, Einzelschüsse gegen c·ln(M₀/M), Riemann-Summe gegen Integral, Einfluss der Feuerrate, Treibstoffbedarf in Abhängigkeit von der Ausstoßgeschwindigkeit |

## Aufbau

Pro Ordner:

- `index.html` – die App (lokal im Browser öffnen)
- `*_ilias.zip` – Paket für ein ILIAS-HTML-Lernmodul (Startdatei: `index.html`)
- `*_kachel.png` – Kachelbild für ILIAS
