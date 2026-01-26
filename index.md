
<p>
  <strong>Filtern nach:</strong>
  <button onclick="filterThemen('all')">All</button>
  <button onclick="filterThemen('bachelor')">Bachelor</button>
  <button onclick="filterThemen('master')">Master</button>
</p>

<script>
  function filterThemen(art) {
    const themen = document.querySelectorAll('.thema');
    themen.forEach(el => {
      if (art === 'all' || el.classList.contains(art)) {
        el.style.display = 'block';
      } else {
        el.style.display = 'none';
      }
    });
  }
</script>


# Verfügbare Abschlussarbeiten / Thesis topics 📚

<div class="thema bachelor" markdown="1">
### ❄️🏔️🌲 Vergleich von Beobachtungen der Schneedecke für Wald- und Wiesenstandorte
* Typ: Bachelorarbeit
* Bereich: Datenanalyse, Visualisierung
* Voraussetzung: Interesse an Datenauswertung
* Betreuenede: Kristian Förster
* Start: flexibel
* Kurzbeschreibung: Schneeprozesse in Wäldern unterscheiden maßgeblich von umliegenden Freiflächen. Auf Bäumen abgelagerter Schnee schmilzt durch die hohe aerodynamische Kopplung und durch die "dunklen" Bäume relativ schnell, wohingegen der Schnee auf dem Waldboden durch den Kronenraum der Bäume von kurzwelliger Strahlung und von Wind abgeschirmt wird. Diese Unterschiede zeigen sich in unterschiedlichen Schmelzraten. Im Rahmen dieser Arbeit können diese Prozesse anhand eines Datensatzes von Schneehöhen in Wäldern und Freilandflächen ausgewertet werden. Damit kann ein verbessertes Verständnis über den Wasserhaushalt im Winterhalbjahr erlangt werden.

</div>

<div class="thema bachelor" markdown="1">
### ☔️ Regenwasserernte am Hochschulgebäude H7
* Typ: Bachelorarbeit
* Bereich: Datenanalyse, Berechnungen
* Voraussetzung: Interesse an Datenauswertung und Berechnungen
* Betreuenede: Kristian Förster
* Start: flexibel
* Regenwasser am Gebäude H7 soll durch Regenwasserernten in Zisternen gesammelt werden. Die Bachelorarbeit soll die Zisternengröße ermitteln und die Versorgungssicherheit für Bewässerungszwecke anlysieren.

</div>

<div class="thema bachelor" markdown="1">
### 🌐 Datensätze zur hydrologischen Konnektivität der Landschaft
* Typ: Bachelorarbeit
* Bereich: Recherche, Datenanalyse
* Voraussetzung: Interesse an Hydrologie, internationale Literatur, Datenanalyse
* Betreuende: Kristian Förster
* Start: flexibel
* Die hydrologische Konnektivität beschreibt, wie Wasser, Sedimente oder Stoffe in der Landschaft miteinander verbunden sind. Ziel der Bachelorarbeit ist die Recherche relevanter internationaler Studien, eine erste Sichtung frei verfügbarer Datensätze zur hydrologischen Konnektivität sowie ein vergleichender Überblick über deren Inhalte, Auflösung und Einsatzmöglichkeiten. Auf dieser Basis sollen erste qualitative Aussagen und Einordnungsmöglichkeiten abgeleitet werden, insbesondere auch im Hinblick auf natur-basierte Lösungen.

</div>

<div class="thema bachelor" markdown="1">

### 🌍📡 Kalibrierung und Validierung von Bodenfeuchtesensoren auf Basis der Cosmic-Ray Neutron Sensing (CRNS)-Technologie
* Typ: Bachelorarbeit
* Bereich: Bodenfeuchte-Monitoring, Datenanalyse
* Voraussetzungen: Interesse an Messmethoden und Datenanalyse; Grundkenntnisse in Statistik und idealerweise Python; selbstständige Arbeitsweise
* Aufgaben: Literaturrecherche, Kalibrierung und Validierung der CRNS-Daten
* Optional (bei Interesse und Zeit): Entwicklung einer Kalibrierfunktion mit Python/R
* Betreuung: Kristian Förster
* Start: voraussichtlich ab sofort
* Kurzbeschreibung: Rund um jeden Sensor werden Bodenproben in mehreren Entfernungszonen entnommen, gravimetrisch analysiert und mit den Sensorwerten sowie Umweltparametern (Luftdruck, Luftfeuchte, kosmische Strahlung) abgeglichen. Ziel ist die Entwicklung standortspezifischer Kalibrierfunktionen zur Bestimmung des Bodenfeuchtegehalts.

</div>

<div class="thema bachelor" markdown="1">

### Entwicklung eines zielgruppenorientierten Maßnahmenkonzeptes zum Umgang mit Starkregen in der Region Rupertiwinkel
* Typ: Bachelorarbeit
* Bereich: Feldarbeit, Datenanalyse
* Voraussetzungen: Interesse an Mitarbeit im Verband der ILE Zukunftsregion Rupertiwinkel (Standort Kirchanschöring), Datenauswertung, selbstständige Arbeitsweise
* Aufgaben: Literaturrecherche, Auswertung Starkregenkarten der ILE Zukunftsregion Rupertiwinkel, Entwicklung eines zielgruppenorientierten Maßnahmenkonzeptes
* Betreuung: Kristian Förster, extern
* Start: frühestmöglich Herbst 2025; spätestmöglich Frühling 2026
* Kurzbeschreibung: Die ILE Zukunftsregion Rupertiwinkel erarbeitet derzeit ein Anpassungskonzept für Starkregen und Sturzfluten mit einem multifunktionalen, resilienten Ansatz. Im Zuge dieses Projektes, das bis März 2027 läuft, werden insgesamt 12 besonders betroffene Gebiete der ILE Gemeinden betrachtet und ein detailliertes Maßnahmenkonzept für diese Gebiete sowie für die gesamte Region durch ein Fachexpertengremium erarbeitet. Im Rahmen der Masterarbeit sollen für eine der bereits definierten Zielgruppen (Bürger:innen, Gewerbetreibende, Kommunen oder Landwirte) Verhaltens- und Handlungsempfehlungen erarbeitet werden, damit die Risiken von Starkregen zukünftig abgemildert werden.

</div>


<div class="thema master" markdown="1">

### 🌊🌱Hyper-resolution flood modeling in meso-scale catchments and implementation of nature-based solution
* Type: Master thesis
* Short description: hydrological modeling, data analysis
* Supervisor: Kristian Förster
* Start: flexible
* Short description: Utilizing hydrological models is a proven method to quantify the effect of Nature-based Solutions (NbS) on the water balance. Yet, "hyper-resolution" (i.e., with a spatial resolution well below 100 meters) models are being applied to small areas only. In this study, a physically-based hydrological model, which is capable to be adopted to massive grids with >10<sup>6</sup> grid cells, is tested. This work sheds light on the question whether this kind of models could be used for catchments with several 100 of sqaure kilometers.

</div>
