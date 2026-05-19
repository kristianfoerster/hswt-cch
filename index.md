
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


