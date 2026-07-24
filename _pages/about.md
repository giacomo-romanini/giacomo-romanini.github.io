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
}
</style>
