---
layout: archive
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
@import url("https://fonts.googleapis.com/css2?family=Source+Sans+3:wght@400;500;600;700&family=Source+Serif+4:opsz,wght@8..60,500;8..60,600;8..60,700&display=swap");

:root{
  --teal:#0f766e;
  --teal-dark:#0b5f59;
  --ink:#1f2937;
  --muted:#6b7280;
  --light-muted:#8b95a5;
  --border:#e5e7eb;
  --soft-border:#f0f1f3;
  --card-bg:#ffffff;

  --font-sans:"Source Sans 3", -apple-system, BlinkMacSystemFont,
              "Segoe UI", Arial, sans-serif;

  --font-serif:"Source Serif 4", Georgia, "Times New Roman", serif;
}

/* Main page typography */
.page__content{
  color:var(--ink);
  font-family:var(--font-sans);
  font-size:1.02rem;
  line-height:1.65;
}

/* Introductory text */
.page-intro{
  max-width:780px;
  margin:0 0 .75rem;
  color:var(--ink);
  font-size:1.08rem;
  line-height:1.65;
}

.page-intro:first-of-type{
  font-size:1.18rem;
  font-weight:500;
}

.page-intro:last-of-type{
  margin-top:1rem;
  margin-bottom:0;
}

/* Section layout */
.content-section{
  margin:0;
}

hr.section{
  margin:2.7rem 0 2.2rem;
  border:0;
  border-top:1px solid var(--border);
}

.section-title{
  margin:0 0 1.5rem;
  color:var(--ink);
  font-family:var(--font-serif);
  font-size:1.55rem;
  font-weight:600;
  line-height:1.25;
  letter-spacing:-.015em;
  text-align:center;
}

/* Lists */
.list-papers{
  margin:0;
  padding-left:1.3rem;
}

.list-papers > li{
  margin:0;
  padding:0 0 1.55rem .25rem;
  line-height:1.55;
}

.list-papers > li:not(:last-child){
  margin-bottom:1.55rem;
  border-bottom:1px solid var(--soft-border);
}

.list-papers > li:last-child{
  padding-bottom:0;
}

/* Paper titles */
.paper-title{
  color:var(--ink);
  font-family:var(--font-serif);
  font-size:1.08rem;
  font-style:normal;
  font-weight:600;
  line-height:1.4;
}

/* Paper status */
.paper-status{
  margin-left:.25rem;
  color:var(--muted);
  font-family:var(--font-sans);
  font-size:.94rem;
  font-style:italic;
  font-weight:400;
}

/* Authors, journals, conferences and other metadata */
.paper-meta{
  color:var(--muted);
  font-family:var(--font-sans);
  font-size:.96rem;
  line-height:1.55;
}

.paper-meta strong{
  color:#4b5563;
  font-weight:600;
}

/* Links */
a.paper-link{
  color:var(--teal);
  text-decoration-line:underline;
  text-decoration-thickness:1px;
  text-decoration-color:rgba(15,118,110,.45);
  text-underline-offset:3px;
  transition:
    color .15s ease,
    text-decoration-color .15s ease;
}

a.paper-link:hover{
  color:var(--teal-dark);
  text-decoration-color:var(--teal-dark);
}

/* Presentation history */
.presented{
  display:block;
  margin-top:.5rem;
  color:var(--light-muted);
  font-family:var(--font-sans);
  font-size:.84rem;
  font-weight:400;
  line-height:1.5;
}

/* Optional badge style */
small.badge{
  display:inline-block;
  padding:.15rem .55rem;
  border:1px solid #a5f3fc;
  border-radius:999px;
  background:#ecfeff;
  color:#0e7490;
  font-family:var(--font-sans);
  font-size:.76rem;
  font-weight:600;
}

/* Optional grid and cards */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(320px, 1fr));
  gap:1.25rem;
}

.card{
  padding:1.25rem 1.4rem;
  border:1px solid var(--border);
  border-radius:14px;
  background:var(--card-bg);
}

/* Mobile */
@media (max-width:600px){
  .page__content{
    font-size:1rem;
  }

  .page-intro{
    font-size:1.03rem;
  }

  .page-intro:first-of-type{
    font-size:1.1rem;
  }

  hr.section{
    margin:2.2rem 0 1.8rem;
  }

  .section-title{
    margin-bottom:1.25rem;
    font-size:1.4rem;
  }

  .list-papers{
    padding-left:1.1rem;
  }

  .list-papers > li{
    padding-bottom:1.25rem;
  }

  .list-papers > li:not(:last-child){
    margin-bottom:1.25rem;
  }

  .paper-title{
    font-size:1.04rem;
  }
}
</style>

<div class="page-intro">
  I am a Senior Economist at the Banca d'Italia.
</div>

<div class="page-intro">
  My research interests are in International Finance, International Trade, and Networks.
</div>

<p class="page-intro">
  Here's my
  <a
    class="paper-link"
    href="https://giacomo-romanini.github.io/files/CV_Romanini.pdf"
    target="_blank"
    rel="noopener"
  >Curriculum Vitae</a>.
</p>

<hr class="section">

<section class="content-section">
  <h2 class="section-title">Publications</h2>

  <ul class="list-papers">
    <li>
      <span class="paper-title">
        <a
          class="paper-link"
          href="https://onlinelibrary.wiley.com/doi/10.1111/twec.70131"
          target="_blank"
          rel="noopener"
        >Fragmentation and the Future of GVCs</a>
      </span>

      <span class="paper-meta">
        (2026) <strong>The World Economy</strong>
      </span>

      <br>

      <span class="paper-meta">
        Also published as a chapter in the CEPR book
      </span>

      <a
        class="paper-link"
        href="https://cepr.org/publications/books-and-reports/state-globalisation"
        target="_blank"
        rel="noopener"
      >The State of Globalisation</a>

      <span class="paper-meta">(2025).</span>

      <br>

      <span class="paper-meta">
        with Francesco Paolo Conteduca, Michele Mancini, Simona Giglioli,
        Alessandro Borin, Maria Grazia Attinasi, Lukas Boeckelmann, and
        Baptiste Meunier
      </span>
    </li>

    <li>
      <span class="paper-title">
        <a
          class="paper-link"
          href="https://www.sciencedirect.com/science/article/abs/pii/S002219962500011X"
          target="_blank"
          rel="noopener"
        >Banking Complexity in the Global Economy</a>
      </span>

      <span class="paper-meta">
        (2025) <strong>Journal of International Economics</strong>
      </span>

      <br>

      <span class="paper-meta">
        Also circulated as
      </span>

      <a
        class="paper-link"
        href="https://www.bancaditalia.it/pubblicazioni/temi-discussione/2025/2025-1485/index.html?com.dotmarketing.htmlpage.language=1"
        target="_blank"
        rel="noopener"
      >The Network Gravity of Global Banking</a>.

      <br>

      <span class="paper-meta">
        with Raoul Minetti and Oren Ziv
      </span>
    </li>

    <li>
      <span class="paper-title">
        <a
          class="paper-link"
          href="https://www.sciencedirect.com/science/article/abs/pii/S0304393220300015"
          target="_blank"
          rel="noopener"
        >Recessions and Recoveries: Multinational Banks in the Business Cycle</a>
      </span>

      <span class="paper-meta">
        (2021) <strong>Journal of Monetary Economics</strong>
      </span>

      <br>

      <span class="paper-meta">
        with Qingqing Cao, Raoul Minetti, and Maria Pia Olivero
      </span>
    </li>
  </ul>
</section>

<hr class="section">

<section class="content-section">
  <h2 class="section-title">Working Papers</h2>

  <ul class="list-papers">
    <li>
      <span class="paper-title">Global Financial Chains</span>
      <span class="paper-status">(new draft coming soon)</span>

      <br>

      <span class="paper-meta">
        with Raoul Minetti and Oren Ziv
      </span>

      <span class="presented">
        Presented at the 2024 Bank of Italy–EIEF Financial Intermediation
        Workshop; NBER Summer Institute 2024; Luiss Business School; the 2024
        ECB–Federal Reserve Board–Federal Reserve Bank of New York Global
        Research Forum on International Macroeconomics and Finance; the EEA
        2025 Congress; and CEPR–IMF 2025.
      </span>
    </li>

    <li>
      <span class="paper-title">
        <a
          class="paper-link"
          href="https://fabrizioleone.github.io/files/CELPR.pdf"
          target="_blank"
          rel="noopener"
        >The Impact of Trade Wars on Firms in Third Countries</a>
      </span>

      <span class="paper-status">(submitted)</span>

      <a
        class="paper-link"
        href="https://cepr.org/voxeu/columns/impact-trade-wars-firms-third-countries"
        target="_blank"
        rel="noopener"
      >[VoxEU]</a>

      <br>

      <span class="paper-meta">
        with Francesco Paolo Conteduca, Marco Errico, Fabrizio Leone,
        Ludovic Panon
      </span>
    </li>

    <li>
      <span class="paper-title">
        Beyond Firm Size: Network Position and Shock Transmission in
        Firm-to-Firm Production Networks across Five Economies
      </span>

      <span class="paper-status">(first draft coming soon)</span>

      <br>

      <span class="paper-meta">
        with G. Magerman, A. Palazzolo, E. Dhyne, A. Borsos, D. Kulikov,
        A. Linarello, A. Paulus, and M. Saldias
      </span>
    </li>
  </ul>
</section>

<hr class="section">

<section class="content-section">
  <h2 class="section-title">Work in Progress</h2>

  <ul class="list-papers">
    <li>
      <span class="paper-title">
        Inside Out: The Allocative Impact of Firms’ Make-or-Buy Decisions
        on Aggregate Energy Intensity
      </span>

      <br>

      <span class="paper-meta">
        with Carole Marullaz
      </span>
    </li>

    <li>
      <span class="paper-title">
        Geopolitical Tensions, Trade Exposure and Bank Lending
      </span>

      <br>

      <span class="paper-meta">
        with Fabio Massimo Piersanti
      </span>
    </li>

    <li>
      <span class="paper-title">
        Does JIT Production Change the Network Structure of GVCs?
        Evidence from Italian Firms
      </span>

      <br>

      <span class="paper-meta">
        with Simona Giglioli
      </span>
    </li>
  </ul>
</section>

<hr class="section">

<section class="content-section">
  <h2 class="section-title">Discussions</h2>

  <ul class="list-papers">
    <li>
      <span class="paper-title">
        Trade, Multinationals and Corporate Taxation
      </span>

      <span class="paper-meta">
        by Dubus, Ferrari, and Parenti.
      </span>

      <div class="paper-meta">
        2025 Bank of Italy, ECB, and World Bank workshop on “Trade, Value
        Chains and Financial Linkages in the Global Economy.”
      </div>
    </li>

    <li>
      <span class="paper-title">
        Beyond Bilateral Flows: Indirect Connections and Exchange Rates
      </span>

      <span class="paper-meta">
        by Bahaj, Della Corte, Massacci, and Seyde.
      </span>

      <div class="paper-meta">
        2025 BIS, Bank of England, ECB, and IMF Spillover Conference.
      </div>
    </li>

    <li>
      <span class="paper-title">
        Trade Intermediation and Resilience in Global Sourcing
      </span>

      <span class="paper-meta">
        by Perelló.
      </span>

      <div class="paper-meta">
        2024 Bank of Italy, ECB, and World Bank workshop on “Trade, Value
        Chains and Financial Linkages in the Global Economy.”
      </div>
    </li>

    <li>
      <span class="paper-title">
        The Ripple Effect: Supply Chain Reconfigurations and Cross-Border
        Credit Dynamics
      </span>

      <span class="paper-meta">
        by Correa, Fabiani, Ossandon, and Sarmiento.
      </span>

      <div class="paper-meta">
        2024 10th Annual Banking Research Network Workshop.
      </div>
    </li>

    <li>
      <span class="paper-title">
        A Sufficient Statistics Approach for Endogenous Production Networks:
        Theory and Evidence from Ukraine’s War
      </span>

      <span class="paper-meta">
        by Korovkin, Makarin, and Miyauchi.
      </span>

      <div class="paper-meta">
        2023 Bank of Italy, ECB, and World Bank workshop on “Trade, Value
        Chains and Financial Linkages in the Global Economy.”
      </div>
    </li>
  </ul>
</section>

<hr class="section">

<section class="content-section">
  <h2 class="section-title">Policy Work</h2>

  <ul class="list-papers">
    <li>
      <span class="paper-title">
        The Effects of US Tariffs on Italian Firms: An Ex-Ante Micro-Level
        Perspective (2025)
      </span>

      <a
        class="paper-link"
        href="https://www.bancaditalia.it/pubblicazioni/qef/2025-0994/index.html?com.dotmarketing.htmlpage.language=1"
        target="_blank"
        rel="noopener"
      >[paper]</a>

      <br>

      <span class="paper-meta">
        with Stefano Federico and Fadi Hassan.
      </span>
    </li>
  </ul>
</section>
