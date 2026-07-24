<style>
@import url("https://fonts.googleapis.com/css2?family=Source+Sans+3:wght@400;500;600;700&family=Source+Serif+4:opsz,wght@8..60,500;8..60,600;8..60,700&display=swap");

:root{
  --teal:#0f766e;
  --teal-dark:#0b5f59;
  --ink:#1f2937;
  --muted:#6b7280;
  --light-muted:#9ca3af;
  --card-bg:#ffffff;
  --card-br:#e5e7eb;

  --font-sans:"Source Sans 3", -apple-system, BlinkMacSystemFont,
              "Segoe UI", sans-serif;

  --font-serif:"Source Serif 4", Georgia, "Times New Roman", serif;
}

/* General page typography */
.page__content{
  font-family:var(--font-sans);
  color:var(--ink);
  font-size:1.02rem;
  line-height:1.65;
}

/* Introductory text */
.page-intro{
  max-width:760px;
  margin:0 0 .7rem;
  color:var(--ink);
  font-size:1.08rem;
  line-height:1.65;
}

.page-intro:first-of-type{
  font-size:1.18rem;
  font-weight:500;
}

/* Section separators */
hr.section{
  border:0;
  border-top:1px solid var(--card-br);
  margin:2.6rem 0 2.15rem;
}

/* Section headings */
.section-title{
  margin:0 0 1.4rem;
  text-align:center;
  font-family:var(--font-serif);
  font-size:1.55rem;
  font-weight:600;
  line-height:1.25;
  letter-spacing:-.01em;
  color:var(--ink);
}

/* Optional grid/card components */
.grid{
  display:grid;
  gap:1.25rem;
  grid-template-columns:repeat(auto-fit, minmax(320px, 1fr));
}

.card{
  padding:1.25rem 1.4rem;
  background:var(--card-bg);
  border:1px solid var(--card-br);
  border-radius:14px;
}

/* Lists */
.list-tight{
  margin:0;
  padding-left:1.25rem;
}

.list-tight > li{
  margin:0;
  padding:0 0 1.5rem .2rem;
  line-height:1.55;
}

.list-tight > li:last-child{
  padding-bottom:0;
}

/*
Optional: subtle separators between entries.
Remove this block if you prefer a completely open layout.
*/
.list-tight > li:not(:last-child){
  margin-bottom:1.5rem;
  border-bottom:1px solid #f0f1f3;
}

/* Paper titles */
.paper-title{
  font-family:var(--font-serif);
  font-size:1.08rem;
  font-weight:600;
  font-style:normal;
  line-height:1.4;
  color:var(--ink);
}

/* Status labels */
.paper-status{
  margin-left:.2rem;
  color:var(--muted);
  font-family:var(--font-sans);
  font-size:.94rem;
  font-weight:400;
  font-style:italic;
}

/* Authors, journals, conference information */
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
  text-underline-offset:3px;
  text-decoration-color:rgba(15, 118, 110, .45);
  transition:
    color .15s ease,
    text-decoration-color .15s ease;
}

a.paper-link:hover{
  color:var(--teal-dark);
  text-decoration-color:var(--teal-dark);
}

/* Badges */
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

/* Presentation history */
sup.presented{
  display:block;
  margin-top:.45rem;
  color:var(--light-muted);
  font-family:var(--font-sans);
  font-size:.84rem;
  font-weight:400;
  line-height:1.5;
  vertical-align:baseline;
}

/* Improve mobile spacing */
@media (max-width:600px){
  .page__content{
    font-size:1rem;
  }

  .page-intro{
    font-size:1.03rem;
  }

  .section-title{
    font-size:1.4rem;
  }

  hr.section{
    margin:2.2rem 0 1.8rem;
  }

  .list-tight > li{
    padding-bottom:1.25rem;
  }

  .list-tight > li:not(:last-child){
    margin-bottom:1.25rem;
  }



<div class="page-intro">
  I am a Senior Economist at the Banca d'Italia.
</div>

<div class="page-intro">
  My research interests are International Finance, International Trade, and Networks.
</div>

<p class="page-intro">
  Here's my <a class="paper-link" href="https://giacomo-romanini.github.io/files/CV_Romanini.pdf" target="_blank" rel="noopener">Curriculum Vitae</a>
</p>


<hr class="section">

<div class="section">
  <div class="section-title">Publications</div>
  <ul class="list-tight">
        <li>
      <span class="paper-title">
        <a class="paper-link" href="https://onlinelibrary.wiley.com/doi/10.1111/twec.70131" target="_blank" rel="noopener">Fragmentation and the Future of GVCs</a>
      </span>
      <span class="paper-meta">(2026) <strong>The World Economy</strong></span><br>
      <span class="paper-meta">also chapter in the CEPR book </span>  
          &nbsp;
      <a class="paper-link" href="https://cepr.org/publications/books-and-reports/state-globalisation" target="_blank" rel="noopener">The State of Globalization (2025)</a><br>
      <span class="paper-meta">with Francesco Paolo Conteduca, Michele Mancini, Simona Giglioli, Alessandro Borin, Maria Grazia Attinasi, Lukas Boeckelmann, and Baptiste Meunier</span><br>
    </li>
    <li>
      <span class="paper-title">
        <a class="paper-link" href="https://www.sciencedirect.com/science/article/abs/pii/S002219962500011X" target="_blank" rel="noopener">Banking Complexity in the Global Economy</a>
      </span>
      <span class="paper-meta">(2025) <strong>Journal of International Economics</strong></span><br>
      <span class="paper-meta">also circulated as</span>
      &nbsp;
      <a class="paper-link" href="https://www.bancaditalia.it/pubblicazioni/temi-discussione/2025/2025-1485/index.html?com.dotmarketing.htmlpage.language=1" target="_blank" rel="noopener">The Network Gravity of Global Banking</a><br>
      <span class="paper-meta">with Raoul Minetti, Oren Ziv</span>
    </li>

    <li>
      <span class="paper-title">
        <a class="paper-link" href="https://www.sciencedirect.com/science/article/abs/pii/S0304393220300015" target="_blank" rel="noopener">Recessions and Recoveries: Multinational Banks in the Business Cycle</a>
      </span>
      <span class="paper-meta">(2021) <strong>Journal of Monetary Economics</strong></span><br>
      <span class="paper-meta">with Qingqing Cao, Raoul Minetti, Maria Pia Olivero</span>
    </li>
  </ul>
</div>


<hr class="section">

<div class="section">
  <div class="section-title">Working Papers</div>
  <ul class="list-tight">
    <li>
      <span class="paper-title">Global Financial Chains</span>
      <span class="paper-status">(new draft coming soon!)</span><br>
      <span class="paper-meta">with Raoul Minetti, Oren Ziv</span><br>
      <sup class="presented">Presented at 2024 Financial Intermediation Workshop Bank of Italy – EIEF; NBER SI 2024; Luiss Business School; 2024 ECB–FRB–FRBNY Global Research Forum on International Macroeconomics and Finance; EEA 2025 Congress; CEPR IMF 2025.</sup>
    </li>

    <li>
      <span class="paper-title">
        <a class="paper-link" href="https://fabrizioleone.github.io/files/CELPR.pdf" target="_blank" rel="noopener">The Impact of Trade Wars on Firms in Third Countries</a>
      </span>
      <span class="paper-status">(submitted)</span>
      <a class="paper-link" href="https://cepr.org/voxeu/columns/impact-trade-wars-firms-third-countries" target="_blank" rel="noopener">[VoxEU blog]</a><br>
      <span class="paper-meta">with Francesco Paolo Conteduca, Marco Errico, Fabrizio Leone, Ludovic Panon</span><br>
    </li>

    <li>
      <span class="paper-title">Beyond firm size: network position and shock transmission in firm-to-firm production networks across five economies</span>
      <span class="paper-status">(first draft coming soon!)</span><br>
      <span class="paper-meta">with G. Magerman, A. Palazzolo, E. Dhyne, A. Borsos, D. Kulikov, A. Linarello, A. Paulus, and M. Saldias</span><br>
    </li>

  </ul>
</div>


<hr class="section">

<div class="section">
  <div class="section-title">Work in Progress</div>
  <ul class="list-tight">
    <li>
      <span class="paper-title">Inside Out: The Allocative Impact of Firms’ Make-or-Buy Decisions on Aggregate Energy Intensity</span><br>
      <span class="paper-meta">with Carole Marullaz</span><br>
    </li>

    <li>
      <span class="paper-title">Geopolitical Tensions, Trade Exposure and Bank Lending</span><br>
      <span class="paper-meta">with Fabio Massimo Piersanti</span><br>
    </li>

    <li>
      <span class="paper-title">Does JIT production change the network structure of GVCs? Evidence from Italian firms</span><br>
      <span class="paper-meta">with Simona Giglioli</span><br>
    </li>
  </ul>
</div>


<hr class="section">

<div class="section">
  <div class="section-title">Discussions</div>
  <ul class="list-tight">
    <li>
      <span class="paper-title">Trade, Multinationals and Corporate Taxation</span>, by Dubus, Ferrari, Parenti
      <div class="paper-meta">2025 BdI, ECB, WB workshop on “Trade, value chains and financial linkages in the global economy”</div>
    </li>

    <li>
      <span class="paper-title">Beyond Bilateral Flows: Indirect Connections and Exchange Rates</span>, by Bahaj, Della Corte, Massacci, Seyde
      <div class="paper-meta">2025 BIS, BoE, ECB and IMF Spillover Conference</div>
    </li>

    <li>
      <span class="paper-title">Trade Intermediation and Resilience in Global Sourcing</span>, by Perelló
      <div class="paper-meta">2024 BdI, ECB, WB workshop on “Trade, value chains and financial linkages in the global economy”</div>
    </li>

    <li>
      <span class="paper-title">The Ripple Effect: Supply Chain Reconfigurations and Cross-border Credit Dynamics</span>, by Correa, Fabiani, Ossandon, Sarmiento
      <div class="paper-meta">2024 10th Annual Banking Research Network Workshop</div>
    </li>

    <li>
      <span class="paper-title">A Sufficient Statistics Approach for Endogenous Production Networks: Theory and Evidence from Ukraine’s War</span>, by Korovkin, Makarin, Miyauchi
      <div class="paper-meta">2023 BdI, ECB, WB workshop on “Trade, value chains and financial linkages in the global economy”</div>
    </li>
  </ul>
</div>


<hr class="section">

<div class="section">
  <div class="section-title">Policy Works</div>
  <ul class="list-tight">
    <li>
      <span class="paper-title">
        The effects of US tariffs on Italian firms: An ex-ante micro-level perspective
        <a class="paper-link" href="https://www.bancaditalia.it/pubblicazioni/qef/2025-0994/index.html?com.dotmarketing.htmlpage.language=1" target="_blank" rel="noopener">[paper]</a>
      </span><br>
      <span class="paper-meta">with Stefano Federico, Fadi Hassan</span><br>
    </li>
  </ul>
</div>

}
</style>
