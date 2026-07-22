
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
### 🌐 Datensätze zur hydrologischen Konnektivität der Landschaft
* Typ: Bachelorarbeit
* Bereich: Recherche, Datenanalyse
* Voraussetzung: Interesse an Hydrologie, internationale Literatur, Datenanalyse
* Betreuende: Kristian Förster
* Start: flexibel
* Die hydrologische Konnektivität beschreibt, wie Wasser, Sedimente oder Stoffe in der Landschaft miteinander verbunden sind. Ziel der Bachelorarbeit ist die Recherche relevanter internationaler Studien, eine erste Sichtung frei verfügbarer Datensätze zur hydrologischen Konnektivität sowie ein vergleichender Überblick über deren Inhalte, Auflösung und Einsatzmöglichkeiten. Auf dieser Basis sollen erste qualitative Aussagen und Einordnungsmöglichkeiten abgeleitet werden, insbesondere auch im Hinblick auf natur-basierte Lösungen.

</div>

<div class="thema bachelor" markdown="1">
### ☔️ Auswertung von Beregnungsexperimenten von Dachbegrünungsaufbauten
* Typ: Bachelorarbeit
* Bereich: Recherche, Datenanalyse
* Betreuende: Kristian Förster
* Start: flexibel
* Für verschiedene Dachaufbauten (Länge, vertikaler-Aufbau, PV-Panele) werden Bergnungsexperimente systematisch ausgewertet und Zusammenhänge zwischen Charakteristika und Wasserabgaben herausgearbeitet.
</div>



<div class="thema master" markdown="1">
### 💧🌵 From floods to droughts - modelling water retention of nature-based solutions
* Type: Master thesis
* Methods: Literature review, data analysis, modelling
* Requirements: Interesst in hydrology and modelling
* Supervisor: Kristian Förster
* Start: flexible
* Most water retention studies for nature-based solutions at the hillslope scale focus on the temporal scale of pluvial flooding only. The role of infiltration and evapotranspiration in subsequent dry spells is neglected or represented in simple parameterizations in many modelling studies. This thesis sheds light on water retention processes after flooding.

</div>

<div class="thema master" markdown="1">
### 📊 Nature-base solutions vs. technical flood protection
* Type: Master thesis
* Methods: modelling
* Requirements: Interesst in hydrology and modelling
* Supervisor: Kristian Förster
* Start: flexible
* This thesis aims to compare the efficiency of decentralized, small-scale measure to retein water against clasdsical technical solutions (dams) for a meso-scale catchment in Germany (~ 20 km^2). This involves measures like small ponds, keyline design etc. 

</div>
