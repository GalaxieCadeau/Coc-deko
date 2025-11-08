
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <title>Clash of Clans – Decorstions Übersicht</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="all Clash of Clans Decorations." />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: radial-gradient(circle at top, #18182b, #050509 55%);
      color: #f7f7ff;
      line-height: 1.6;
      -webkit-font-smoothing: antialiased;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .page {
      max-width: 1100px;
      margin: 0 auto;
      padding: 1.5rem;
    }

    header {
      background: rgba(5, 5, 20, 0.96);
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
      position: sticky;
      top: 0;
      z-index: 10;
      backdrop-filter: blur(14px);
    }

    .nav {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0.8rem 1.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 1rem;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 0.8rem;
    }

    .brand-icon {
      width: 38px;
      height: 38px;
      border-radius: 999px;
      background: radial-gradient(circle at 30% 20%, #ffe07a, #f5a623);
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 750;
      font-size: 1.1rem;
      color: #2b1800;
      box-shadow: 0 0 0 2px rgba(0, 0, 0, 0.3);
    }

    .brand-text {
      display: flex;
      flex-direction: column;
      gap: 0.1rem;
    }

    .brand-title {
      font-size: 1rem;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      font-weight: 700;
    }

    .brand-sub {
      font-size: 0.78rem;
      opacity: 0.7;
    }

    .nav-tag {
      font-size: 0.8rem;
      padding: 0.45rem 0.75rem;
      border-radius: 999px;
      border: 1px solid rgba(255, 255, 255, 0.16);
      background: radial-gradient(circle at top left, rgba(255, 255, 255, 0.12), rgba(255, 255, 255, 0.02));
      display: flex;
      align-items: center;
      gap: 0.45rem;
      white-space: nowrap;
    }

    .nav-tag span {
      font-size: 0.75rem;
      opacity: 0.75;
    }

    main {
      padding-top: 1.5rem;
      padding-bottom: 3rem;
    }

    .intro {
      margin-bottom: 1.8rem;
      display: grid;
      grid-template-columns: minmax(0, 2.3fr) minmax(0, 1.8fr);
      gap: 1.5rem;
    }

    .intro h1 {
      font-size: clamp(1.8rem, 3vw, 2.1rem);
      margin-bottom: 0.7rem;
    }

    .intro p {
      font-size: 0.93rem;
      opacity: 0.88;
    }

    .intro-card {
      border-radius: 18px;
      padding: 1rem 1.2rem;
      background: linear-gradient(145deg, rgba(23, 23, 45, 0.95), rgba(7, 7, 22, 0.98));
      border: 1px solid rgba(255, 255, 255, 0.09);
      box-shadow: 0 18px 40px rgba(0, 0, 0, 0.45);
      font-size: 0.86rem;
      position: relative;
      overflow: hidden;
    }

    .intro-card::before {
      content: "";
      position: absolute;
      inset: -60%;
      opacity: 0.06;
      background:
        radial-gradient(circle at 20% 0%, #ffcf71 0, transparent 55%),
        radial-gradient(circle at 80% 120%, #8b5cf6 0, transparent 55%);
      pointer-events: none;
    }

    .intro-card-title {
      font-size: 0.84rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      opacity: 0.82;
      margin-bottom: 0.4rem;
    }

    .pill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.35rem;
      margin-top: 0.7rem;
    }

    .pill {
      font-size: 0.75rem;
      padding: 0.25rem 0.6rem;
      border-radius: 999px;
      background: rgba(10, 10, 25, 0.9);
      border: 1px solid rgba(255, 255, 255, 0.12);
      opacity: 0.92;
    }

    .filter-bar {
      margin-bottom: 1.5rem;
      padding: 0.95rem 1.1rem;
      border-radius: 18px;
      background: rgba(9, 9, 25, 0.98);
      border: 1px solid rgba(255, 255, 255, 0.09);
      display: flex;
      flex-wrap: wrap;
      gap: 0.8rem;
      align-items: center;
    }

    .filter-label {
      font-size: 0.8rem;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: #fbbf24;
      margin-right: 0.3rem;
    }

    .filter-group {
      display: flex;
      flex-wrap: wrap;
      gap: 0.6rem;
      flex: 1 1 220px;
    }

    .field {
      position: relative;
      flex: 1 1 150px;
      min-width: 0;
    }

    .field label {
      font-size: 0.7rem;
      text-transform: uppercase;
      letter-spacing: 0.14em;
      opacity: 0.6;
      margin-bottom: 0.25rem;
      display: block;
    }

    .field input,
    .field select {
      width: 100%;
      border-radius: 999px;
      border: 1px solid rgba(148, 163, 184, 0.6);
      background: rgba(15, 23, 42, 0.95);
      padding: 0.4rem 0.9rem;
      color: #e5e7eb;
      font-size: 0.82rem;
      outline: none;
    }

    .field input:focus,
    .field select:focus {
      border-color: #fbbf24;
      box-shadow: 0 0 0 1px rgba(251, 191, 36, 0.35);
    }

    .grid-meta {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 0.6rem;
      margin-bottom: 0.7rem;
      font-size: 0.8rem;
      opacity: 0.8;
    }

    .grid-meta span strong {
      font-weight: 600;
    }

    .deko-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1rem;
    }

    .deko-card {
      border-radius: 18px;
      background: radial-gradient(circle at top left, rgba(31, 41, 55, 0.9), rgba(15, 23, 42, 0.92));
      border: 1px solid rgba(148, 163, 184, 0.35);
      padding: 0.85rem;
      display: flex;
      flex-direction: column;
      gap: 0.55rem;
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.4);
      position: relative;
      overflow: hidden;
    }

    .deko-card::before {
      content: "";
      position: absolute;
      inset: -40%;
      opacity: 0.08;
      background:
        radial-gradient(circle at 0 0, #f97316 0, transparent 55%),
        radial-gradient(circle at 100% 120%, #22d3ee 0, transparent 55%);
      pointer-events: none;
    }

    .deko-media {
      position: relative;
      border-radius: 14px;
      overflow: hidden;
      background: radial-gradient(circle at 30% 0%, #4b5563, #020617);
      min-height: 120px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .deko-media img {
      max-width: 100%;
      height: auto;
      display: block;
    }

    .deko-tag {
      position: absolute;
      left: 0.6rem;
      top: 0.55rem;
      border-radius: 999px;
      padding: 0.1rem 0.45rem;
      font-size: 0.7rem;
      text-transform: uppercase;
      letter-spacing: 0.11em;
      background: rgba(15, 23, 42, 0.85);
      border: 1px solid rgba(251, 191, 36, 0.75);
      color: #fde68a;
    }

    .deko-body {
      position: relative;
      z-index: 1;
    }

    .deko-title {
      font-weight: 650;
      font-size: 0.96rem;
      margin-bottom: 0.1rem;
    }

    .deko-meta-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.35rem;
      font-size: 0.75rem;
      opacity: 0.85;
      margin-bottom: 0.35rem;
    }

    .deko-meta-chip {
      padding: 0.14rem 0.5rem;
      border-radius: 999px;
      border: 1px solid rgba(148, 163, 184, 0.7);
      background: rgba(15, 23, 42, 0.9);
    }

    .rarity-common {
      border-color: #9ca3af;
      color: #e5e7eb;
    }

    .rarity-rare {
      border-color: #38bdf8;
      color: #bae6fd;
    }

    .rarity-epic {
      border-color: #a855f7;
      color: #e9d5ff;
    }

    .rarity-legendary {
      border-color: #fbbf24;
      color: #fef9c3;
    }

    .deko-desc {
      font-size: 0.8rem;
      opacity: 0.9;
    }

    footer {
      margin-top: 2.4rem;
      font-size: 0.74rem;
      opacity: 0.7;
      border-top: 1px solid rgba(148, 163, 184, 0.35);
      padding-top: 0.8rem;
    }

    footer a {
      text-decoration: underline;
      text-decoration-style: dotted;
    }

    @media (max-width: 768px) {
      .nav {
        flex-direction: column;
        align-items: flex-start;
      }

      .intro {
        grid-template-columns: minmax(0, 1fr);
      }

      .filter-bar {
        flex-direction: column;
        align-items: stretch;
      }

      .grid-meta {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="nav">
      <a class="brand" href="#top">
        <div class="brand-icon">D</div>
        <div class="brand-text">
          <div class="brand-title">CoC Dekos</div>
          <div class="brand-sub"> Deko-Archiv</div>
        </div>
      </a>
      <div class="nav-tag">
        
      </div>
    </div>
  </header>

  <main class="page" id="top">
    <section class="intro">
      <div>
        <h1>see all Clash of Clans Decorations</h1>
        <p>
          
          <strong></strong> <strong></strong> 
          
        </p>
      </div>
      <aside class="intro-card">
        <div class="intro-card-title">Hinweis</div>
        <p>
          
        </p>
        <div class="pill-row">
          <span class="pill"> </span>
          <span class="pill"></span>
          <span class="pill">Eigene </span>
        </div>
      </aside>
    </section>

    <section class="filter-bar">
      <div class="filter-label">Filter</div>
      <div class="filter-group">
        <div class="field">
          <label for="search">Suche</label>
          <input id="search" type="text" placeholder="Name, Event, Notiz …" />
        </div>
        <div class="field">
          <label for="year-filter">Jahr</label>
          <select id="year-filter">
            <option value="">Alle Jahre</option>
            <option>2014</option>
            <option>2015</option>
            <option>2016</option>
            <option>2017</option>
            <option>2018</option>
            <option>2019</option>
            <option>2020</option>
            <option>2021</option>
            <option>2022</option>
            <option>2023</option>
            <option>2024</option>
          </select>
        </div>
        <div class="field">
          <label for="rarity-filter">Seltenheit</label>
          <select id="rarity-filter">
            <option value="">Alle</option>
            <option value="common">Normal</option>
            <option value="rare">Selten</option>
            <option value="epic">Episch</option>
            <option value="legendary">Legendär</option>
          </select>
        </div>
      </div>
    </section>

    <div class="grid-meta">
      <span>Gefundene Dekos: <strong id="count">0</strong></span>
      <span>Tipp: Tippe auf eine Karte und notiere dir, ob du die Deko besitzt.</span>
    </div>

    <section class="deko-grid" id="deko-grid">
      <!-- BEISPIELE – Diese kannst du anpassen oder löschen -->

      <article class="deko-card"
        data-name="Weihnachtsgeschenk 2014"
        data-year="2014"
        data-rarity="rare">
        <div class="deko-media">
          <span class="deko-tag">Winter</span>
          <!-- HIER eigenes Bild eintragen: -->
          <img src="Screenshot_20251108_160035_Google.jpg" alt="Weihnachtsgeschenk 2014">
        </div>
        <div class="deko-body">
          <h2 class="deko-title">Weihnachtsgeschenk 2014</h2>
          <div class="deko-meta-row">
            <span class="deko-meta-chip">Jahr: 2014</span>
            <span class="deko-meta-chip">Event: Winter-Update</span>
            <span class="deko-meta-chip rarity-rare">Selten</span>
          </div>
          <p class="deko-desc">
            Wurde während des Winter-Events 2014 als Hindernis auf der Dorfkarte gespawnt.
          </p>
        </div>
      </article>

      <article class="deko-card"
        data-name="Halloween Grabstein"
        data-year="2016"
        data-rarity="epic">
        <div class="deko-media">
          <span class="deko-tag">Halloween</span>
          <img src="images/platzhalter-halloween.png" alt="Halloween Grabstein">
        </div>
        <div class="deko-body">
          <h2 class="deko-title">Halloween-Grabstein</h2>
          <div class="deko-meta-row">
            <span class="deko-meta-chip">Jahr: 2016</span>
            <span class="deko-meta-chip">Event: Halloween</span>
            <span class="deko-meta-chip rarity-epic">Episch</span>
          </div>
          <p class="deko-desc">
            Klassischer Grabstein, der nur während des Halloween-Events 2016 aufgetaucht ist.
          </p>
        </div>
      </article>

      <article class="deko-card"
        data-name="Asiatisches Neujahr Laterne"
        data-year="2020"
        data-rarity="legendary">
        <div class="deko-media">
          <span class="deko-tag">Spezial</span>
          <img src="https://raw.githubusercontent.com/GalaxieCadeau/Cocdeko/main/laterne.jpg" alt="Neujahr Laterne">
        </div>
        <div class="deko-body">
          <h2 class="deko-title">Neujahrs-Laterne</h2>
          <div class="deko-meta-row">
            <span class="deko-meta-chip">Jahr: 2020</span>
            <span class="deko-meta-chip">Event: Lunar New Year</span>
            <span class="deko-meta-chip rarity-legendary">Legendär</span>
          </div>
          <p class="deko-desc">
            Limitierte Deko zum asiatischen Neujahrs-Event – nur kurze Zeit im Shop erhältlich.
          </p>
        </div>
      </article>

      <article class="deko-card"
        data-name="Klassischer Weihnachtsbaum"
        data-year="2015"
        data-rarity="common">
        <div class="deko-media">
          <span class="deko-tag">Winter</span>
          <img src="images/platzhalter-baum.png" alt="Weihnachtsbaum 2015">
        </div>
        <div class="deko-body">
          <h2 class="deko-title">Klassischer Weihnachtsbaum 2015</h2>
          <div class="deko-meta-row">
            <span class="deko-meta-chip">Jahr: 2015</span>
            <span class="deko-meta-chip">Event: Winter-Update</span>
            <span class="deko-meta-chip rarity-common">Normal</span>
          </div>
          <p class="deko-desc">
            Standard-Weihnachtsbaum, der jedes Jahr etwas anders aussah. Dieses Design stammt aus 2015.
          </p>
        </div>
      </article>

      <!-- ENDE BEISPIELE -->
    </section>

    <footer>
      Fan-Projekt von dir. Clash of Clans und alle zugehörigen Inhalte sind Marken von Supercell.
      Dies ist keine offizielle Seite. Nutze bitte nur eigene Screenshots oder neutrale Grafiken.
    </footer>
  </main>

  <script>
    const searchInput = document.getElementById("search");
    const yearFilter = document.getElementById("year-filter");
    const rarityFilter = document.getElementById("rarity-filter");
    const cards = Array.from(document.querySelectorAll(".deko-card"));
    const countSpan = document.getElementById("count");

    function applyFilters() {
      const search = searchInput.value.toLowerCase().trim();
      const year = yearFilter.value;
      const rarity = rarityFilter.value;

      let visible = 0;

      cards.forEach(card => {
        const name = card.dataset.name.toLowerCase();
        const cardYear = card.dataset.year;
        const cardRarity = card.dataset.rarity;

        let ok = true;

        if (search && !name.includes(search)) ok = false;
        if (year && cardYear !== year) ok = false;
        if (rarity && cardRarity !== rarity) ok = false;

        card.style.display = ok ? "" : "none";
        if (ok) visible++;
      });

      countSpan.textContent = visible.toString();
    }

    searchInput.addEventListener("input", applyFilters);
    yearFilter.addEventListener("change", applyFilters);
    rarityFilter.addEventListener("change", applyFilters);

    applyFilters();
  </script>
</body>
</html>
