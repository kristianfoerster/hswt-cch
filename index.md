
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
* Kurzbeschreibung: Schneeprozesse in Wäldern unterscheiden sich maßgeblich von umliegenden Freiflächen. Auf Bäumen abgelagerter Schnee schmilzt durch die hohe aerodynamische Kopplung und durch die "dunklen" Bäume relativ schnell, wohingegen der Schnee auf dem Waldboden durch den Kronenraum der Bäume von kurzwelliger Strahlung und von Wind abgeschirmt wird. Diese Unterschiede zeigen sich in unterschiedlichen Schmelzraten. Im Rahmen dieser Arbeit können diese Prozesse anhand eines Datensatzes von Schneehöhen in Wäldern und Freilandflächen ausgewertet werden. Damit kann ein verbessertes Verständnis über den Wasserhaushalt im Winterhalbjahr erlangt werden.

</div>

<div class="thema bachelor" markdown="1">
### ☢️💧 Einfluss der Variabilität des Landschaftswasserhaushalts auf Radonkonzentrationen
* Typ: Bachelorarbeit
* Bereich: Eigene Messungen, Datenanalyse, Visualisierung
* Voraussetzung: Interesse an Datenauswertung
* Betreuenede: Kristian Förster
* Start: flexibel
* Kurzbeschreibung: Radon (Rn-222) ist ein radioaktives Gas, das durch den Zerfall von Radium im Uran-238-Zerfallsprozess entsteht. Es kann leicht in Wasser gelöst und in die Atmosphäre (und Gebäude) freigesetzt werden. Schwankungen des Grundwasserspiegels beeinflussen die Radonkonzentration in Innenräumen erheblich. Ein steigender Grundwasserspiegel sättigt die Bodenporen und verringert die Durchlässigkeit für Bodenluft, wodurch die Radonmigration in Gebäude reduziert wird. Sinkende Grundwasserspiegel hingegen führen zu einer höheren Bodenluftdurchlässigkeit und erleichtern den Radontransport ins Gebäudeinnere. Die Stärke und Richtung dieser Effekte hängen jedoch stark von den lokalen geologischen Gegebenheiten, der Bodenbeschaffenheit und der Bauweise der Gebäude ab. In dieser Arbeit sollen durch eigene Messungen und Beobachtungen von Grundwasser und Bodenfeuchte erste Zusammenhänge ermittelt werden.

</div>

<div class="thema bachelor" markdown="1">

### 🌍📡 Kalibrierung und Validierung von Bodenfeuchtesensoren auf Basis der Cosmic-Ray Neutron Sensing (CRNS)-Technologie
* Typ: Bachelorarbeit
* Bereich: Bodenfeuchte-Monitoring, Feldarbeit, Datenanalyse
* Voraussetzungen: Interesse an Feldarbeit, Messmethoden und Datenanalyse; Grundkenntnisse in Statistik und idealerweise Python; selbstständige Arbeitsweise
* Aufgaben: Literaturrecherche, Durchführung gravimetrischer Bodenproben im Gelände, Kalibrierung und Validierung der CRNS-Daten
* Optional (bei Interesse und Zeit): Entwicklung einer Kalibrierfunktion mit Python
* Betreuung: Kristian Förster
* Start: voraussichtlich ab August/September 2025
* Kurzbeschreibung: Die Arbeit kombiniert Feld- und Laborarbeit mit datenbasierter Modellierung. Rund um jeden Sensor werden Bodenproben in mehreren Entfernungszonen entnommen, gravimetrisch analysiert und mit den Sensorwerten sowie Umweltparametern (Luftdruck, Luftfeuchte, kosmische Strahlung) abgeglichen. Ziel ist die Entwicklung standortspezifischer Kalibrierfunktionen zur Bestimmung des Bodenfeuchtegehalts.

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

<div class="thema master" markdown="1">

### Development of a nature-based solution concept to mitigate the effects of heavy rainfall
* Type: Master thesis
* Area: Field work, data analysis
* Requirements: Interest in working with the ILE Zukunftsregion Rupertiwinkel association (based in Kirchanschöring), data analysis, ability to work independently
* Tasks: Literature research, analysis of heavy rainfall maps from the ILE Zukunftsregion Rupertiwinkel, field work on site, development of a solution concept
* Supervision: Kristian Förster and external
* Start: earliest possible date: autumn 2025; latest possible date: spring 2026
* Brief description: The ILE Zukunftsregion Rupertiwinkel is currently developing an adaptation concept for heavy rainfall and flash floods with a multifunctional, resilient approach. Part of this project, which will run until March 2027, is the examination of a total of 12 particularly affected areas of the ILE municipalities and the development of a detailed action plan for these areas as well as for the entire region by a panel of experts. Taking into account the available data, the goal of the master's thesis is the development of a solution strategy that is as nature-based and sustainable for one of these selected areas.
</div>

<div class="thema master" markdown="1">

### 🌍📡 Site-Dependent Variability in the Calibration of Cosmic-Ray Neutron Sensing (CRNS) Sensors
* Type: Master thesis
* Area: Field work, Data analysis, Environmental Monitoring
* Requirements: Basic knowledge of statistics and ideally Python, independent working style
* Tasks: Field sampling at multiple sites, Gravimetric soil moisture analysis, Sensor calibration and data evaluation, Comparison of calibration curves, Analysis of soil moisture time series and hydrological interpretation, Assessment of uncertainty due to site conditions and environmental corrections
* Supervision: Kristian Förster and team
* Start: As soon as possible (field work starting mid-October 2025)
* Brief description: How do calibration relationships of CRNS sensors vary across different site conditions, and what are the implications for soil moisture estimation? This thesis explores the transferability of CRNS calibrations and evaluates the accuracy of CRNS-derived soil moisture time series under variable environmental conditions.
* 
</div>