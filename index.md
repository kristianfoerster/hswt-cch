
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
* Voraussetzung: Interesse an Datenauswetung
* Betreuenede: Kristian Förster
* Start: flexibel

</div>


<!---
<div class="thema bachelor" markdown="1">

### 🏙️🌱 Hydrologische Modellierung von Gründachaufbauten mit verschiedenen Dimensionen mit einem physikalisch-basierten hydrologischen Modell
* Bereich: Hydrologische Modellierung, Datenanalyse, Visualisierung
* Voraussetzung: Belegung Hydrological Modeling
* Betreuenede: Kristian Förster
* Start: flexibel

</div>


<div class="thema master" markdown="1">
  
### 🏙️🌱 Hydrological modeling of green roof structures with different dimensions using a physically-based hydrological model
* Scope: Hydrological modeling, data analysis, visualization, [using this dataset](https://zenodo.org/records/15129787)
* Prerequisite: Assignment Hydrological Modeling
* Supervisor: Kristian Förster
* Start: flexible

</div>
-->

<div class="thema master" markdown="1">

### 🌱🌾 Calibration of Cosmic Ray Neutron Sensors for soil moisture observations
* Type: Master thesis
* Short description: Field work to collect comparative data, data analysis
* Supervisor: Kristian Förster
* Start: WiSe 2025/26

</div>


<!-- Weitere Themen einfach im gleichen Format anhängen -->
