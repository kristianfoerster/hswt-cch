
<p>
  <strong>Filtern nach:</strong>
  <button onclick="filterThemen('all')">Alle</button>
  <button onclick="filterThemen('bachelor')">Bachelor</button>
  <button onclick="filterThemen('master')">Master</button>
</p>

<script>
  function filterThemen(art) {
    const themen = document.querySelectorAll('.thema');
    themen.forEach(el => {
      if (art === 'all' || el.classList.contains(art)) {
        el.parentElement.style.display = 'block';
      } else {
        el.parentElement.style.display = 'none';
      }
    });
  }
</script>

---
layout: default
title: Themenangebote
---

## Verfügbare Abschlussarbeiten 📚

> Bearbeite einfach diese Datei auf GitHub, um neue Themen hinzuzufügen oder alte zu entfernen.

### 🏙️🌱 Hydrologische Modellierung von Gründachaufbauten mit verschiedenen Dimensionen mit einem physikalisch-basierten hydrologischen Modell
{: .thema .bachelor }
*Bereich*: Hydrologische Modellierung, Datenanalyse, Visualisierung
*Voraussetzung*: Belegung Hydrological Modeling
*Betreuenede*: Kristian Förster
*Start*: flexibel

---

### 🏙️🌱 Hydrological modeling of green roof structures with different dimensions using a physically-based hydrological model
{: .topic .master }
*Scope*: Hydrological modeling, data analysis, visualization
*Prerequisite*: Assignment Hydrological Modeling
*Supervisor*: Kristian Förster
*Start*: flexible


---

### 🏙️ Calibration of CRNS sensors for soil moisture simulations
{: .topic .master }
*Short description*: Field work to collect comparative data, data analysis
*Supervisors*: Kristian Förster
*Start*: WiSe 2025/26


---

<!-- Weitere Themen einfach im gleichen Format anhängen -->
