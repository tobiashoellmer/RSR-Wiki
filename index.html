<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Wiki: Methodik des (Rapid) Scoping Review</title>
<style>
  @font-face {
    font-family: 'Aptos';
    src: local('Aptos');
  }
  :root{
    --bg: #f5f6f8;
    --sidebar-bg: #1b2a41;
    --sidebar-bg-active: #28405f;
    --sidebar-text: #cfd9e8;
    --accent: #2f6fed;
    --accent-dark: #1d4fbf;
    --card-bg: #ffffff;
    --border: #e2e5eb;
    --text: #222633;
    --text-muted: #5c6270;
    --tag-bg: #eef2ff;
    --tag-text: #2f4bb0;
    --rapid-bg: #fff4e5;
    --rapid-border: #f0b155;
    --success: #1c8a5a;
    --warn: #b3400f;
  }
  *{box-sizing:border-box;}
  html,body{
    margin:0; padding:0;
    font-family: 'Aptos','Aptos Display','Calibri','Segoe UI',system-ui,-apple-system,sans-serif;
    background: var(--bg);
    color: var(--text);
    scroll-behavior:smooth;
  }
  a{color:var(--accent); text-decoration:none;}
  a:hover{text-decoration:underline;}

  /* Layout */
  .layout{
    display:grid;
    grid-template-columns: 300px 1fr;
    min-height:100vh;
  }
  /* Sidebar */
  .sidebar{
    background: var(--sidebar-bg);
    color: var(--sidebar-text);
    padding: 20px 16px 40px;
    position: sticky;
    top:0;
    height:100vh;
    overflow-y:auto;
  }
  .sidebar h1{
    font-size: 17px;
    color:#fff;
    margin: 4px 0 2px;
    line-height:1.3;
  }
  .sidebar .subtitle{
    font-size:12px;
    color:#93a3bd;
    margin-bottom:18px;
  }
  .search-box{
    position:relative;
    margin-bottom: 18px;
  }
  .search-box input{
    width:100%;
    padding:9px 34px 9px 12px;
    border-radius:8px;
    border:1px solid #3a4a63;
    background:#233650;
    color:#fff;
    font-size:13.5px;
    font-family:inherit;
    outline:none;
  }
  .search-box input::placeholder{color:#8ea0bd;}
  .search-box input:focus{border-color:var(--accent);}
  .search-box .icon{
    position:absolute; right:10px; top:50%; transform:translateY(-50%);
    color:#8ea0bd; font-size:14px; pointer-events:none;
  }
  .search-results{
    display:none;
    position:absolute;
    left:0; right:0; top:calc(100% + 6px);
    background:#fff;
    color:#222;
    border-radius:8px;
    box-shadow:0 10px 30px rgba(0,0,0,.35);
    max-height:420px;
    overflow-y:auto;
    z-index:60;
    border:1px solid #d8dce4;
  }
  .search-results.show{display:block;}
  .search-results .sr-count{
    padding:8px 12px; font-size:11.5px; color:#777; border-bottom:1px solid #eee; background:#fafafa;
  }
  .search-results .sr-item{
    display:block; width:100%; text-align:left; padding:9px 12px;
    border:0; border-bottom:1px solid #f0f0f0; background:#fff; cursor:pointer;
    font-family:inherit;
  }
  .search-results .sr-item:hover{background:#f2f6ff;}
  .search-results .sr-item .sr-section{
    font-size:10.5px; text-transform:uppercase; letter-spacing:.03em; color:var(--accent-dark); font-weight:600;
  }
  .search-results .sr-item .sr-snippet{
    font-size:12.5px; color:#333; margin-top:2px; line-height:1.4;
  }
  .search-results .sr-item mark{ background:#ffe792; padding:0 1px; }
  .search-results .sr-empty{ padding:14px 12px; font-size:12.5px; color:#888; }

  nav.toc{font-size:13.5px;}
  nav.toc details{ margin-bottom:2px; }
  nav.toc summary{
    cursor:pointer; list-style:none; padding:7px 8px; border-radius:6px;
    font-weight:600; color:#fff;
  }
  nav.toc summary::-webkit-details-marker{display:none;}
  nav.toc summary:hover{background: var(--sidebar-bg-active);}
  nav.toc summary:before{
    content:"▸"; display:inline-block; margin-right:6px; font-size:10px; transition:transform .15s;
  }
  nav.toc details[open] summary:before{ transform:rotate(90deg); }
  nav.toc ul{
    list-style:none; margin:2px 0 8px; padding-left:22px;
  }
  nav.toc ul li a{
    display:block; color: var(--sidebar-text); padding:5px 8px; border-radius:6px; font-size:13px;
  }
  nav.toc ul li a:hover, nav.toc ul li a.active{
    background: var(--sidebar-bg-active); color:#fff; text-decoration:none;
  }

  /* Main content */
  main{
    padding: 36px 48px 120px;
    max-width: 980px;
  }
  .page-header{
    margin-bottom: 30px;
    border-bottom: 1px solid var(--border);
    padding-bottom:20px;
  }
  .page-header h1{
    font-size: 30px;
    margin:0 0 8px;
    letter-spacing:-.01em;
  }
  .page-header p.lead{
    color: var(--text-muted);
    font-size:15.5px;
    line-height:1.6;
    max-width:760px;
  }
  .meta-row{
    display:flex; gap:10px; flex-wrap:wrap; margin-top:14px;
  }
  .meta-pill{
    background: var(--tag-bg); color:var(--tag-text);
    font-size:11.5px; font-weight:600; padding:4px 10px; border-radius:20px;
  }

  section.wiki-section{
    margin-bottom: 44px;
    scroll-margin-top: 24px;
  }
  section.wiki-section > h2{
    font-size:22px;
    margin: 0 0 6px;
    padding-bottom:8px;
    border-bottom: 2px solid var(--accent);
    display:inline-block;
  }
  section.wiki-section > .section-intro{
    color:var(--text-muted); font-size:14px; margin: 8px 0 18px; max-width:760px;
  }
  h3.sub-heading{
    font-size:17.5px; margin: 26px 0 10px;
    color:#132043;
  }
  h4.step-heading{
    font-size:15.5px; margin: 18px 0 8px; color:#132043;
  }

  .card{
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-left: 4px solid var(--accent);
    border-radius: 10px;
    padding: 16px 18px;
    margin-bottom: 14px;
    box-shadow: 0 1px 3px rgba(20,30,60,.04);
  }
  .card.rapid{
    border-left-color: #e08a1e;
    background: var(--rapid-bg);
  }
  .card h4{ margin:0 0 6px; font-size:14.5px; }

  p.searchable, li.searchable{
    line-height:1.65; font-size:14.5px; margin: 0 0 10px;
  }
  ul.clean, ol.clean{ margin:6px 0 14px 0; padding-left:22px; }
  ul.clean li, ol.clean li{ margin-bottom:7px; line-height:1.6; font-size:14.5px; }

  .flash{
    animation: flashbg 1.8s ease;
  }
  @keyframes flashbg{
    0%{ background: #fff4c2; }
    100%{ background: transparent; }
  }

  /* citation button + popover */
  .cite{
    display:inline-flex; align-items:center; justify-content:center;
    width:18px; height:18px; border-radius:50%;
    background: var(--tag-bg); color: var(--tag-text);
    font-size:10.5px; font-weight:700; border:1px solid #d6ddf5;
    cursor:pointer; vertical-align:middle; margin-left:4px;
    line-height:1;
    user-select:none;
  }
  .cite:hover{ background: var(--accent); color:#fff; border-color:var(--accent);}
  .cite.open{ background: var(--accent); color:#fff; }

  #popover{
    position:absolute; z-index:200; max-width:340px;
    background:#111827; color:#f3f4f6; border-radius:10px;
    padding:12px 14px; font-size:12.5px; line-height:1.55;
    box-shadow: 0 14px 40px rgba(0,0,0,.35);
    display:none;
  }
  #popover.show{display:block;}
  #popover .pop-title{
    font-size:10.5px; text-transform:uppercase; letter-spacing:.04em; color:#9db4ff; font-weight:700; margin-bottom:8px;
  }
  #popover .pop-src{ margin-bottom:10px; padding-bottom:10px; border-bottom:1px solid #2a3345; }
  #popover .pop-src:last-child{ border-bottom:0; margin-bottom:0; padding-bottom:0; }
  #popover .pop-cite{ font-weight:600; color:#fff; margin-bottom:3px;}
  #popover .pop-note{ color:#b8c1d9; font-style:italic; }
  #popover .pop-file{ color:#7fa8ff; font-size:11px; margin-top:3px; }
  #popover .pop-close{
    position:absolute; top:8px; right:10px; cursor:pointer; color:#8791a8; font-size:14px;
  }

  table.wiki-table{
    width:100%; border-collapse:collapse; margin: 10px 0 20px;
    font-size:13px; background:#fff;
  }
  table.wiki-table th, table.wiki-table td{
    border:1px solid var(--border); padding:8px 10px; text-align:left; vertical-align:top;
  }
  table.wiki-table th{ background:#eef1f7; font-weight:700; }
  table.wiki-table tr:nth-child(even) td{ background:#fafbfd; }

  .badge-step{
    display:inline-flex; align-items:center; justify-content:center;
    min-width:26px; height:26px; padding:0 6px;
    border-radius:8px; background: var(--accent); color:#fff; font-weight:700; font-size:13px;
    margin-right:8px;
  }
  .step-title-row{ display:flex; align-items:center; gap:4px; margin-top:24px;}

  blockquote.def{
    margin: 6px 0 16px; padding: 12px 16px;
    border-left: 4px solid #7c8db5;
    background:#f2f4f9; font-style:italic; font-size:14px; color:#333;
  }

  footer.wiki-footer{
    border-top:1px solid var(--border); margin-top:40px; padding-top:18px;
    font-size:12px; color:var(--text-muted);
  }

  .toolbar-note{
    font-size:12px; color:#93a3bd; margin-top:10px; line-height:1.5;
  }

  @media (max-width: 900px){
    .layout{ grid-template-columns: 1fr; }
    .sidebar{ position:relative; height:auto; }
    main{ padding: 24px; }
  }
</style>
</head>
<body>
<div class="layout">

  <!-- SIDEBAR -->
  <aside class="sidebar">
    <h1>Rapid Scoping Review</h1>
    <div class="subtitle">Methodik-Wiki · basierend auf 7 Fachquellen</div>

    <div class="search-box">
      <input type="text" id="searchInput" placeholder="Wiki durchsuchen … (z. B. „PCC“, „Data Charting“)" autocomplete="off">
      <span class="icon">⌕</span>
      <div class="search-results" id="searchResults"></div>
    </div>

    <nav class="toc" id="toc">
      <details open>
        <summary>1 · Überblick &amp; Definition</summary>
        <ul>
          <li><a href="#def-scoping">1.1 Was ist ein Scoping Review?</a></li>
          <li><a href="#def-abgrenzung">1.2 Abgrenzung zu anderen Reviewtypen</a></li>
          <li><a href="#def-rapid">1.3 Was macht einen Review „rapid“?</a></li>
          <li><a href="#def-warum-rapid">1.4 Warum „rapid“? Der Kontext</a></li>
        </ul>
      </details>
      <details>
        <summary>2 · Wann durchführen?</summary>
        <ul>
          <li><a href="#indikationen-munn">2.1 Sechs Indikationen (Munn et al.)</a></li>
          <li><a href="#indikationen-arksey">2.2 Vier Anwendungsbereiche</a></li>
          <li><a href="#entscheidung">2.3 Scoping vs. Systematic Review</a></li>
        </ul>
      </details>
      <details>
        <summary>3 · Rahmenwerke</summary>
        <ul>
          <li><a href="#rahmenwerke">3.1 Entwicklung der Frameworks</a></li>
        </ul>
      </details>
      <details>
        <summary>4 · Review-Team &amp; Protokoll</summary>
        <ul>
          <li><a href="#team">4.1 Das Review-Team</a></li>
          <li><a href="#protokoll">4.2 Protokoll &amp; Registrierung</a></li>
        </ul>
      </details>
      <details>
        <summary>5 · Der Ablauf (9 Schritte)</summary>
        <ul>
          <li><a href="#schritt1">Schritt 1 · Ziel &amp; Fragestellung</a></li>
          <li><a href="#schritt2">Schritt 2 · Einschlusskriterien</a></li>
          <li><a href="#schritt3">Schritt 3 · Vorgehen planen</a></li>
          <li><a href="#schritt4">Schritt 4 · Suche</a></li>
          <li><a href="#schritt5">Schritt 5 · Auswahl</a></li>
          <li><a href="#schritt6">Schritt 6 · Extraktion</a></li>
          <li><a href="#schritt7">Schritt 7 · Analyse</a></li>
          <li><a href="#schritt8">Schritt 8 · Darstellung</a></li>
          <li><a href="#schritt9">Schritt 9 · Synthese &amp; Fazit</a></li>
        </ul>
      </details>
      <details>
        <summary>6 · Rapid-Anpassungen</summary>
        <ul>
          <li><a href="#rapid-anpassungen">6.1 Wo lässt sich kürzen?</a></li>
        </ul>
      </details>
      <details>
        <summary>7 · Berichterstattung</summary>
        <ul>
          <li><a href="#prisma-scr">7.1 PRISMA-ScR-Checkliste</a></li>
          <li><a href="#aufbau-bericht">7.2 Aufbau des Abschlussberichts</a></li>
        </ul>
      </details>
      <details>
        <summary>8 · Herausforderungen</summary>
        <ul>
          <li><a href="#herausforderungen">8.1 Herausforderungen &amp; Lösungen</a></li>
          <li><a href="#staerken-schwaechen">8.2 Stärken &amp; Schwächen</a></li>
        </ul>
      </details>
      <details>
        <summary>9 · Glossar &amp; Quellen</summary>
        <ul>
          <li><a href="#glossar">9.1 Glossar</a></li>
          <li><a href="#quellen">9.2 Quellenverzeichnis</a></li>
        </ul>
      </details>
    </nav>
    <div class="toolbar-note">Jede Aussage ist über das kleine <strong>„Q“</strong>-Symbol mit ihrer Originalquelle verknüpft. Klicken zum Anzeigen.</div>
  </aside>

  <!-- MAIN -->
  <main id="main">

    <div class="page-header">
      <h1>Methodik des (Rapid) Scoping Review</h1>
      <p class="lead">Diese Wiki-Seite fasst die Methodik von Scoping Reviews zusammen und ordnet ein, wie sich daraus – im Sinne eines „Rapid Review“ – ein <strong>Rapid Scoping Review (RSR)</strong> ableitet. Alle Inhalte stammen ausschließlich aus den sieben hochgeladenen Fachquellen; jede Aussage ist per Klick auf das Quellen-Symbol nachprüfbar.</p>
      <div class="meta-row">
        <span class="meta-pill">7 Quellen</span>
        <span class="meta-pill">JBI- &amp; PRISMA-ScR-basiert</span>
        <span class="meta-pill">Erweiterbar</span>
      </div>
    </div>

    <!-- 1 ÜBERBLICK -->
    <section class="wiki-section" id="ueberblick">
      <h2>1 · Überblick &amp; Definition</h2>
      <p class="section-intro">Grundbegriffe, Abgrenzung und die Frage, was einen Review „rapid“ macht.</p>

      <h3 class="sub-heading" id="def-scoping">1.1 Was ist ein Scoping Review?</h3>
      <blockquote class="def searchable">
        „…exploratory projects that systematically map the literature available on a topic, identifying key concepts, theories, sources of evidence and gaps in the research.“ (Canadian Institutes of Health Research, zit. n. Peters et al.)
        <span class="cite" data-src="peters2020" data-note="Abschnitt „What are scoping reviews…“">Q</span>
      </blockquote>
      <p class="searchable">Scoping Reviews sind ein zunehmend genutzter Ansatz der Evidenzsynthese, um Literatur zu einem Thema, Feld, Konzept oder einer Fragestellung systematisch zu identifizieren und deren Umfang abzubilden – häufig unabhängig von der Quelle (Primärforschung, Reviews, nicht-empirische Evidenz) und über verschiedene Kontexte hinweg. <span class="cite" data-src="pollock2024" data-note="Abstract / Kapitel 1 „Background“">Q</span></p>
      <p class="searchable">Im Gegensatz zu klassischen systematischen Reviews, die sich mit präzisen, eng umrissenen Fragestellungen befassen (z. B. Wirksamkeit einer Intervention), dienen Scoping Reviews dazu, Schlüsselkonzepte eines Forschungsbereichs abzubilden, Arbeitsdefinitionen zu erstellen oder die inhaltlichen Grenzen eines Themas abzustecken. Ein Scoping Review liefert einen Überblick über die vorhandene Evidenz unabhängig von deren methodischer Qualität. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Warum ein Scoping Review?“, S. 2">Q</span></p>
      <p class="searchable">Auch in der deutschsprachigen Literatur werden Scoping Reviews beschrieben als Reviews, „die darauf abzielen, die Literatur zu einem bestimmten Thema oder Forschungsbereich zu erfassen und die Möglichkeit bieten, Schlüsselkonzepte, Forschungslücken sowie Arten und Quellen von Evidenzen zu identifizieren, um Praxis, Politik und Forschung zu informieren“. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.1 „Was sind Scoping Reviews?“, S. 242">Q</span></p>

      <h3 class="sub-heading" id="def-abgrenzung">1.2 Abgrenzung zu anderen Reviewtypen</h3>
      <p class="searchable">Systematic Reviews, Scoping Reviews, Mapping Reviews, Evidence &amp; Gap Maps (EGM) und Overviews sind eigenständige, sich ergänzende Evidenzsynthese-Formate. Die folgende Tabelle fasst die zentralen Unterscheidungsmerkmale zusammen: <span class="cite" data-src="pollock2024" data-note="Table 1 „Differences of evidence synthesis types“">Q</span></p>
      <table class="wiki-table searchable">
        <thead><tr><th></th><th>Systematic Review</th><th>Scoping Review</th><th>Mapping Review</th><th>Evidence &amp; Gap Map</th><th>Overview</th></tr></thead>
        <tbody>
          <tr><td><strong>Ziel</strong></td><td>Umfassende Synthese relevanter Studien mit strengen, transparenten Methoden</td><td>Sammlung, Beschreibung &amp; Katalogisierung verfügbarer Evidenz zu einer Frage</td><td>Sammlung, Beschreibung &amp; Katalog der verfügbaren Evidenz</td><td>Systematisches Produkt, das Evidenz visuell darstellt &amp; Lücken zeigt</td><td>Umfassende Synthese vorhandener systematischer Reviews</td></tr>
          <tr><td><strong>Protokoll erforderlich</strong></td><td>Ja</td><td>Ja</td><td>Empfohlen, nicht zwingend</td><td>Empfohlen</td><td>Ja</td></tr>
          <tr><td><strong>Fragestellung</strong></td><td>Eng, z. B. Wirksamkeit einer Intervention</td><td>Breit: Welche Charakteristika/Definitionen/Faktoren gibt es zu einem Konzept?</td><td>Breit: Was wissen wir über ein Thema?</td><td>Breit, nach PICOS strukturiert</td><td>Breit, über mehrere systematische Reviews hinweg</td></tr>
          <tr><td><strong>Critical Appraisal</strong></td><td>Ja</td><td>Optional, nicht verpflichtend</td><td>Optional</td><td>Optional</td><td>Ja</td></tr>
          <tr><td><strong>Analyse</strong></td><td>Deduktive Zusammenfassung (z. B. Meta-Analyse)</td><td>Induktiv (zu entwickeln) oder deduktiv, inkl. qualitativer Inhaltsanalyse</td><td>Deduktive Zusammenfassung mit vordefinierten Codes</td><td>Deduktiv, abhängig vom Framework</td><td>Deduktive Zusammenfassung</td></tr>
          <tr><td><strong>Certainty of Evidence</strong></td><td>Ja (bei Wirksamkeitsfragen)</td><td>Nein</td><td>Nein</td><td>Nein</td><td>Empfohlen</td></tr>
        </tbody>
      </table>
      <p class="searchable">Scoping-, Mapping-Reviews und Evidence &amp; Gap Maps unterscheiden sich u. a. in der Art der Fragestellung (induktiv vs. deduktiv), der Extraktionstiefe (Scoping Reviews extrahieren meist umfangreicher) und der Art der Ergebnisdarstellung. <span class="cite" data-src="pollock2024" data-note="Kapitel 6, Aufzählung der Unterschiede">Q</span></p>

      <h3 class="sub-heading" id="def-rapid">1.3 Was macht einen Review „rapid“?</h3>
      <div class="card rapid">
        <h4>Zentrale Definition</h4>
        <p class="searchable">„Rapid reviews … we define these review types as ‚systematic reviews with shortcuts‘.“ Die Autor:innen betonen, dass die Entscheidung für einen Rapid Review in erster Linie keine Frage der Zielsetzung ist, sondern der <strong>Durchführbarkeit</strong> angesichts begrenzter finanzieller/zeitlicher Ressourcen: Ein Rapid Review kann grundsätzlich für jede der Indikationen eines Scoping- oder Systematic Reviews durchgeführt werden, wobei einzelne Schritte des Standardprozesses verkürzt oder ganz ausgelassen werden. <span class="cite" data-src="munn2018" data-note="Discussion, Absatz zu „Rapid reviews“">Q</span></p>
      </div>
      <p class="searchable">Ein <strong>Rapid Scoping Review</strong> übernimmt somit die methodische Grundstruktur eines Scoping Reviews (Kapitel 5 dieser Seite), passt aber – wie in Kapitel 6 dargestellt – einzelne Prozessschritte an Zeit- und Ressourcenrestriktionen an. Keine der sieben Quellen verwendet den zusammengesetzten Begriff „Rapid Scoping Review“ wörtlich; die Ableitung erfolgt aus der Kombination der Scoping-Review-Methodik mit der Definition von „Rapid Review“ nach Munn et al.</p>

      <h3 class="sub-heading" id="def-warum-rapid">1.4 Warum „rapid“? Der Kontext</h3>
      <p class="searchable">Der Bedarf an schlankeren, schnelleren Syntheseverfahren wird durch das enorme Wachstum der Primär- und Sekundärliteratur begründet: Wurden 1979 rund 14 klinische Studien pro Tag veröffentlicht, sind es heute etwa <strong>75 Studien und 11 systematische Reviews pro Tag</strong> – mit weiter steigender Tendenz. <span class="cite" data-src="bastian2010" data-note="Summary Points / Abschnitt „Where Are We Now?“">Q</span></p>
      <p class="searchable">Selbst große, gut ressourcierte Organisationen wie die Cochrane Collaboration schaffen es nicht, auch nur die Hälfte ihrer Reviews aktuell zu halten. Die Autor:innen fordern daher „leanere“, effizientere Methoden, um mit der wachsenden Evidenzbasis Schritt zu halten, ohne die wissenschaftliche Vertretbarkeit zu gefährden. <span class="cite" data-src="bastian2010" data-note="Abschnitt „Where to Now?“">Q</span></p>
    </section>

    <!-- 2 WANN -->
    <section class="wiki-section" id="wann">
      <h2>2 · Wann einen Scoping Review durchführen?</h2>
      <p class="section-intro">Indikationen und Entscheidungshilfen zur Wahl des richtigen Reviewtyps.</p>

      <h3 class="sub-heading" id="indikationen-munn">2.1 Sechs Indikationen nach Munn et al. (2018)</h3>
      <ol class="clean searchable">
        <li>Um die <strong>Arten verfügbarer Evidenz</strong> in einem bestimmten Feld zu identifizieren. <span class="cite" data-src="munn2018" data-note="Abschnitt „Indications for scoping reviews“">Q</span></li>
        <li>Um <strong>Schlüsselkonzepte/Definitionen</strong> in der Literatur zu klären. <span class="cite" data-src="munn2018">Q</span></li>
        <li>Um zu untersuchen, <strong>wie Forschung</strong> zu einem Thema durchgeführt wird (Methodik-Fokus). <span class="cite" data-src="munn2018">Q</span></li>
        <li>Um <strong>Schlüsselcharakteristika oder Faktoren</strong> zu einem Konzept zu identifizieren. <span class="cite" data-src="munn2018">Q</span></li>
        <li>Als <strong>Vorstudie</strong> für einen systematischen Review. <span class="cite" data-src="munn2018">Q</span></li>
        <li>Um <strong>Wissenslücken</strong> zu identifizieren und zu analysieren. <span class="cite" data-src="munn2018">Q</span></li>
      </ol>
      <p class="searchable">Diese sechs Indikationen können sich überschneiden – ein Review kann gleichzeitig mehrere Zwecke verfolgen. <span class="cite" data-src="munn2018" data-note="Discussion">Q</span></p>

      <h3 class="sub-heading" id="indikationen-arksey">2.2 Vier Hauptanwendungsbereiche (Arksey &amp; O'Malley / Daudt et al.)</h3>
      <ul class="clean searchable">
        <li>Um Ausmaß und Bandbreite bestehender Forschungstätigkeit zu erheben. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Warum ein Scoping Review?“">Q</span> <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.3">Q</span></li>
        <li>Als Vorstudie, ob ein vollständiger systematischer Review bzw. eine Metaanalyse angebracht ist. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.3">Q</span></li>
        <li>Um Forschungsergebnisse zusammenzufassen und zu verbreiten. <span class="cite" data-src="ritschl2024">Q</span></li>
        <li>Um Wissenslücken in der bestehenden Literatur zu identifizieren. <span class="cite" data-src="ritschl2024">Q</span></li>
      </ul>
      <p class="searchable">Ein wesentlicher Unterschied zu systematischen Reviews: Scoping Reviews sind auch bezüglich der Art der einbezogenen Literatur flexibel und eignen sich auch für Themen, zu denen wenig oder keine „wissenschaftliche“ Literatur vorhanden ist – graue und nicht-wissenschaftliche Literatur können eingeschlossen werden. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.3, S. 242f.">Q</span></p>

      <h3 class="sub-heading" id="entscheidung">2.3 Scoping Review oder Systematic Review?</h3>
      <p class="searchable">Die wichtigste Leitfrage: Soll das Ergebnis eine klinisch bedeutsame, konkrete Frage beantworten bzw. Praxis unmittelbar informieren (→ Systematic Review), oder geht es um die Identifikation/Kartierung von Charakteristika, Konzepten und deren Diskussion (→ Scoping Review)? <span class="cite" data-src="munn2018" data-note="Abschnitt „Deciding between a systematic review and a scoping review approach“">Q</span></p>
      <table class="wiki-table searchable">
        <thead><tr><th>Merkmal</th><th>Traditioneller Literatur-Review</th><th>Scoping Review</th><th>Systematic Review</th></tr></thead>
        <tbody>
          <tr><td>A-priori-Protokoll</td><td>Nein</td><td>Ja (teilweise)</td><td>Ja</td></tr>
          <tr><td>PROSPERO-Registrierung</td><td>Nein</td><td>Nein (aktuell nicht möglich)</td><td>Ja</td></tr>
          <tr><td>Transparente, peer-reviewte Suchstrategie</td><td>Nein</td><td>Ja</td><td>Ja</td></tr>
          <tr><td>Standardisierte Datenextraktionsformulare</td><td>Nein</td><td>Ja</td><td>Ja</td></tr>
          <tr><td>Verpflichtendes Critical Appraisal</td><td>Nein</td><td>Nein</td><td>Ja</td></tr>
          <tr><td>Synthese zu „Summary Findings“</td><td>Nein</td><td>Nein</td><td>Ja</td></tr>
        </tbody>
      </table>
      <p class="searchable">Quelle der Tabelle: <span class="cite" data-src="munn2018" data-note="Table 1 „Defining characteristics…“">Q</span> Scoping Reviews können aktuell nicht bei PROSPERO registriert werden; Autor:innen sollten das Protokoll stattdessen z. B. über Open Science Framework, Figshare oder ResearchGate veröffentlichen. <span class="cite" data-src="peters2020" data-note="Abschnitt „Methodological updates“">Q</span></p>
    </section>

    <!-- 3 RAHMENWERKE -->
    <section class="wiki-section" id="rahmenwerke-sec">
      <h2>3 · Rahmenwerke im Überblick</h2>
      <p class="section-intro" id="rahmenwerke">Scoping-Review-Methodik hat sich seit 2005 in mehreren Schritten weiterentwickelt.</p>
      <p class="searchable">Arksey &amp; O'Malley legten 2005 den ersten methodischen Rahmen vor; Levac, Colquhoun &amp; O'Brien erweiterten diesen 2010; das Joanna Briggs Institute (JBI) baute darauf ein eigenes, seither mehrfach aktualisiertes Rahmenwerk (2015, 2017, 2020). <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Scoping Review-Framework“, Tabelle 1, S. 3">Q</span></p>
      <table class="wiki-table searchable">
        <thead><tr><th>#</th><th>Arksey &amp; O'Malley (2005)</th><th>Levac, Colquhoun &amp; O'Brien (2010) – Verbesserungen</th><th>Peters et al. / JBI – Verbesserungen</th></tr></thead>
        <tbody>
          <tr><td>1</td><td>Identifizierung der Forschungsfrage</td><td>Klärung &amp; Verknüpfung von Zweck und Forschungsfrage</td><td>Definition und Abgleich der Zielsetzung(en) und Fragestellung(en)</td></tr>
          <tr><td>2</td><td>Identifizierung relevanter Studien</td><td>Abwägung von Machbarkeit und Breite/Vollständigkeit</td><td>Entwicklung &amp; Anpassung der Einschlusskriterien mit Zielsetzung(en)</td></tr>
          <tr><td>3</td><td>Studienauswahl</td><td>Iterative Vorgehensweise im Team bei Auswahl &amp; Extraktion</td><td>Beschreibung der geplanten Vorgehensweise (Suche, Auswahl, Extraktion, Darstellung)</td></tr>
          <tr><td>4</td><td>Darstellung der Daten</td><td>Numerische Zusammenfassung + qualitative thematische Analyse</td><td>Suche nach Evidenz</td></tr>
          <tr><td>5</td><td>Zusammenstellung, Zusammenfassung, Berichterstattung</td><td>Auswirkungen der Ergebnisse auf Policy/Praxis/Forschung identifizieren</td><td>Auswahl der Evidenz</td></tr>
          <tr><td>6</td><td>Beratung (optional)</td><td>Beratung als notwendige Komponente einführen</td><td>Extrahieren der Evidenz</td></tr>
          <tr><td>7</td><td>–</td><td>–</td><td>Graphische Darstellung der Evidenz</td></tr>
          <tr><td>8</td><td>–</td><td>–</td><td>Zusammenfassung der Evidenz bzgl. Zielsetzung/Fragestellung</td></tr>
          <tr><td>9</td><td>–</td><td>–</td><td>(Fortlaufende) Beratung mit Informationswissenschaftler:innen/Bibliothekar:innen/Expert:innen</td></tr>
        </tbody>
      </table>
      <p class="searchable">Diese neun JBI-Schritte bilden – ergänzt um die aktuelle PRISMA-ScR-Berichtslogik – das Grundgerüst, das in Kapitel 5 dieser Seite im Detail dargestellt wird. <span class="cite" data-src="pollock2024" data-note="Kapitel 4 „What are the steps involved…“">Q</span></p>
    </section>

    <!-- 4 TEAM & PROTOKOLL -->
    <section class="wiki-section" id="team-protokoll">
      <h2>4 · Review-Team &amp; Protokoll</h2>

      <h3 class="sub-heading" id="team">4.1 Das Review-Team</h3>
      <p class="searchable">Ein Scoping Review kann nicht von einer einzelnen Person durchgeführt werden – er erfordert ein Team aus inhaltlichen, methodischen und informationswissenschaftlichen Expert:innen. <span class="cite" data-src="pollock2024" data-note="Kapitel 3 „Scoping review team“">Q</span></p>
      <p class="searchable">Ein zentrales Merkmal der JBI-Guidance im Vergleich zu anderen Ansätzen ist die Empfehlung, <strong>Knowledge User</strong> aktiv in Durchführung und Berichterstattung einzubeziehen – also Personen, die an der Forschung interessiert sind oder von ihr betroffen sein könnten: Wissenschaftler:innen, Patient:innen, Gesundheitsdienstleister:innen, Politikgestalter:innen, Fördermittelgeber:innen, Interessenvertretungen u. a. <span class="cite" data-src="pollock2024" data-note="Kapitel 3">Q</span></p>
      <p class="searchable">Für jeden Auswahlschritt (Titel-/Abstract-Screening ebenso wie Volltext-Screening) sowie die Datenextraktion werden mindestens zwei unabhängig arbeitende Reviewer:innen empfohlen; Diskrepanzen werden durch Konsens oder eine dritte Person gelöst. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Studienauswahl“, S. 5">Q</span> <span class="cite" data-src="peters2020" data-note="Abschnitt „Evidence screening and selection“">Q</span></p>

      <h3 class="sub-heading" id="protokoll">4.2 Protokoll &amp; Registrierung</h3>
      <p class="searchable">Wie bei allen gut durchgeführten systematischen Reviews muss vor der Durchführung eines Scoping Reviews zunächst ein <strong>Protokoll</strong> erstellt werden. Es legt Ziele, Methoden und Berichterstattung fest, macht den Prozess transparent und minimiert „Reporting-Bias“. Abweichungen des Abschlussberichts vom Protokoll sollten im Methodenteil klar benannt und begründet werden. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Scoping Review-Protokoll und Abschlussbericht“, S. 2">Q</span></p>
      <p class="searchable">Da eine Registrierung bei PROSPERO für Scoping Reviews derzeit nicht möglich ist, wird empfohlen, das Protokoll dennoch öffentlich zugänglich zu machen (z. B. über Open Science Framework, Figshare, ResearchGate oder Research Square) oder in einer Fachzeitschrift zu publizieren. <span class="cite" data-src="peters2020" data-note="Abschnitt „Methodological updates“">Q</span></p>
      <p class="searchable">Aufgrund der iterativen Natur eines Scoping Reviews können Änderungen gegenüber dem Protokoll im Verlauf der Erstellung notwendig werden – diese sollten transparent im Methodenteil des Abschlussberichts beschrieben und begründet werden. In „leeren Reviews“ (kein Studieneinschluss möglich) sollten nicht angewandte Methoden nicht im Detail beschrieben werden. <span class="cite" data-src="vonElm2019" data-note="S. 2">Q</span></p>
    </section>

    <!-- 5 ABLAUF -->
    <section class="wiki-section" id="ablauf">
      <h2>5 · Der Ablauf: Neun Schritte</h2>
      <p class="section-intro">Die neun Schritte nach JBI-Guidance (Peters et al. 2020 / Pollock et al. 2024), ergänzt um Detailangaben aus den übrigen Quellen. Die ersten drei Schritte erfolgen in der Protokollphase, die übrigen in der eigentlichen Reviewdurchführung. <span class="cite" data-src="pollock2024" data-note="Kapitel 4">Q</span></p>

      <div class="step-title-row" id="schritt1"><span class="badge-step">1</span><h3 class="sub-heading" style="margin:0;">Zielsetzung(en) und Fragestellung(en) definieren und abgleichen</h3></div>
      <p class="searchable">Die Fragestellung leitet die Suchstrategie und alle nachfolgenden Schritte; sie sollte breit gefächert sein, um einen weiten Bereich abzudecken. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.1">Q</span> Ein Scoping Review hat i. d. R. eine primäre Fragestellung, ergänzt um Unterfragen zu einzelnen Aspekten. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Fragestellung“, S. 4">Q</span></p>
      <p class="searchable">Empfohlen wird das Akronym <strong>PCC</strong> (Population, Concept, Context) zur Strukturierung von Titel und Fragestellung – es stellt sicher, dass Titel, Zielsetzung, Fragestellung und Einschlusskriterien konsistent sind. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Titel- und Autor*inneninformationen“, S. 3">Q</span> <span class="cite" data-src="peters2020" data-note="Abschnitt „Title and review questions“">Q</span></p>
      <p class="searchable">Bezieht sich die Fragestellung auf Interventionen, eignet sich alternativ das <strong>PICO</strong>-Schema (Population/Problem, Intervention, Comparison, Outcome). <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.1, S. 244">Q</span> Der Titel sollte zusätzlich die Formulierung „… ein Scoping Review“ enthalten, nicht als Frage formuliert sein und max. 12–14 Wörter umfassen. <span class="cite" data-src="vonElm2019" data-note="S. 3">Q</span></p>

      <div class="step-title-row" id="schritt2"><span class="badge-step">2</span><h3 class="sub-heading" style="margin:0;">Einschlusskriterien entwickeln und mit Zielsetzung abgleichen</h3></div>
      <p class="searchable">Die Einschlusskriterien legen fest, welche Informationsquellen für die Aufnahme in den Review herangezogen werden, und dienen sowohl Leser:innen als auch Reviewer:innen als Orientierung. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Einschlusskriterien“, S. 4">Q</span></p>
      <ul class="clean searchable">
        <li><strong>Population/Teilnehmer:innen:</strong> Alter, Geschlecht und weitere relevante Merkmale; nicht immer zwingend erforderlich. <span class="cite" data-src="peters2020" data-note="Abschnitt „Participants“">Q</span></li>
        <li><strong>Concept/Konzept:</strong> Das untersuchte Kernkonzept – kann Interventionen, Phänomene, Outcomes oder Definitionen umfassen. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Konzept“, S. 4">Q</span></li>
        <li><strong>Context/Kontext:</strong> Geografische Lage, kulturelle/geschlechtsspezifische Aspekte oder Setting (z. B. Akutversorgung, Primärversorgung, Gemeinde). <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Kontext“, S. 4">Q</span></li>
      </ul>
      <p class="searchable">Als Quellentypen kommt praktisch jede vorhandene Literatur infrage: Primärstudien, systematische Reviews, Leitlinien, Websites, Blogs – Reviewer:innen können den Studientyp bewusst offenlassen, um alle Literaturarten einzubeziehen, oder gezielt einschränken. <span class="cite" data-src="peters2020" data-note="Abschnitt „Types of evidence sources“">Q</span></p>

      <div class="step-title-row" id="schritt3"><span class="badge-step">3</span><h3 class="sub-heading" style="margin:0;">Vorgehen bei Suche, Auswahl, Extraktion, Analyse und Darstellung beschreiben</h3></div>
      <p class="searchable">Bereits im Protokoll wird festgelegt, wie Evidenz gesucht, ausgewählt, extrahiert, analysiert und dargestellt werden soll – inklusive eines Entwurfs der Extraktionstabelle („Chart“). <span class="cite" data-src="pollock2024" data-note="Kapitel 4, Punkt 3">Q</span> <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Datenextraktion“, S. 5">Q</span></p>

      <div class="step-title-row" id="schritt4"><span class="badge-step">4</span><h3 class="sub-heading" style="margin:0;">Suche nach Evidenz</h3></div>
      <p class="searchable">Die Suchstrategie sollte im Idealfall so umfassend wie möglich sein, um innerhalb des Zeit- und Ressourcenrahmens sowohl veröffentlichte als auch unveröffentlichte Primärstudien und Reviews (graue Literatur) zu identifizieren. Empfohlen wird eine <strong>dreistufige Suchstrategie</strong>: <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Suchstrategie“, S. 5">Q</span></p>
      <ol class="clean searchable">
        <li>Eingeschränkte Anfangssuche in mind. zwei relevanten Datenbanken, Analyse der Textwörter in Titel/Abstract sowie der Indexbegriffe. <span class="cite" data-src="vonElm2019">Q</span></li>
        <li>Vollständige Suche mit allen identifizierten Stichwörtern und Indexbegriffen in allen infrage kommenden Datenbanken. <span class="cite" data-src="vonElm2019">Q</span></li>
        <li>Durchsuchen der Referenzlisten gefundener Artikel nach zusätzlichen Studien (Snowballing). <span class="cite" data-src="vonElm2019">Q</span></li>
      </ol>
      <p class="searchable">Die Suche kann iterativ angelegt sein, da Review-Autor:innen im Verlauf zunehmend mit der Evidenzbasis vertraut werden und neue Suchbegriffe entdecken. Der Beitrag einer Bibliothekar:in oder Informationsspezialist:in ist bei Erstellung und Verfeinerung der Suche wertvoll. <span class="cite" data-src="vonElm2019" data-note="S. 5">Q</span> Die vollständige Suchstrategie für mindestens eine Datenbank muss dokumentiert werden – dies ist zentral für die wissenschaftliche Aussagekraft des Reviews. <span class="cite" data-src="vonElm2019" data-note="S. 5–6">Q</span></p>
      <p class="searchable">Ein explorativer erster Suchdurchlauf hilft, Keywords und MeSH-Begriffe zu identifizieren; Fachexpert:innen können hierbei nach Schlüsselpublikationen und Suchbegriffen befragt werden. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.2, S. 244">Q</span> Sprachliche Einschränkungen sollten möglichst vermieden werden, sofern keine begründete Notwendigkeit (Machbarkeit/Ressourcen) besteht. <span class="cite" data-src="peters2020" data-note="Abschnitt „Search strategy“">Q</span></p>

      <div class="step-title-row" id="schritt5"><span class="badge-step">5</span><h3 class="sub-heading" style="margin:0;">Auswahl der Evidenz (Screening)</h3></div>
      <p class="searchable">Die Studienauswahl erfolgt anhand der im Protokoll festgelegten Einschlusskriterien, zunächst basierend auf Titel/Abstract, danach im Volltext; sie wird von mindestens zwei Reviewer:innen unabhängig durchgeführt, Diskrepanzen werden durch Konsens oder eine dritte Person gelöst. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Studienauswahl“, S. 5">Q</span> <span class="cite" data-src="peters2020" data-note="Abschnitt „Evidence screening and selection“">Q</span></p>
      <p class="searchable">Der praktische Selektionsprozess lässt sich in vier Teilschritte gliedern: <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.3, S. 244–245">Q</span></p>
      <ol class="clean searchable">
        <li>Entfernen von Duplikaten (idealerweise mit Literaturverwaltungssoftware).</li>
        <li>Selektion anhand der Titel gegen die Einschluss-/Ausschlusskriterien.</li>
        <li>Selektion anhand der Abstracts für alle nicht eindeutig ausgeschlossenen Titel.</li>
        <li>Selektion anhand der Volltexte für alle verbleibenden Artikel.</li>
      </ol>
      <p class="searchable">Details zu ausgeschlossenen Quellen der Volltextprüfung müssen mit Ausschlussgründen dokumentiert werden; der Auswahlprozess wird sowohl narrativ als auch als <strong>Flussdiagramm</strong> (angepasst nach PRISMA) dargestellt. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Ergebnisse“, S. 5–6, Abbildung 1">Q</span> <span class="cite" data-src="peters2020" data-note="Abschnitt „Evidence screening and selection“">Q</span></p>
      <p class="searchable">Ein Critical Appraisal / Risk-of-Bias-Assessment der eingeschlossenen Quellen ist bei Scoping Reviews grundsätzlich <strong>nicht vorgesehen</strong>, da das Ziel die Abbildung der verfügbaren Evidenz ist – es sei denn, das spezifische Reviewziel erfordert es ausdrücklich. <span class="cite" data-src="peters2020" data-note="Abschnitt „Evidence screening and selection“">Q</span> Ob eine Qualitätsbewertung dennoch sinnvoll ist, hängt vom Fokus ab: Bei Interventions-/Wirksamkeitsfragen ist sie hilfreicher als bei Terminologie- oder Wissenslücken-Fragen. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.3, S. 245–246">Q</span></p>

      <div class="step-title-row" id="schritt6"><span class="badge-step">6</span><h3 class="sub-heading" style="margin:0;">Extraktion der Evidenz (Data Charting)</h3></div>
      <p class="searchable">Die Datenextraktion wird bei Scoping Reviews häufig als <strong>„Data Charting“</strong> bezeichnet. Ein Extraktionsformular bzw. eine Tabelle sollte bereits in der Protokollphase entworfen und getestet werden, um Autor:in, bibliografische Referenz und relevante Ergebnisse strukturiert zu erfassen; sie kann im Verlauf iterativ verfeinert werden. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Datenextraktion“, S. 5">Q</span> <span class="cite" data-src="peters2020" data-note="Abschnitt „Data extraction“">Q</span></p>
      <p class="searchable">Es werden zwei Hauptkategorien von Daten unterschieden: (1) allgemeine Informationen wie Forschungsmethode, Publikationsjahr, Ort der Studie, und (2) spezifische, forschungsfragenbezogene Informationen. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.4, S. 245">Q</span></p>
      <p class="searchable">Es wird empfohlen, dass mindestens zwei Reviewer:innen das Formular an zwei bis drei Studien pilotieren, bevor die eigentliche Extraktion beginnt, um Vollständigkeit sicherzustellen; die Extraktion sollte von mindestens zwei Personen unabhängig oder in Duplikat erfolgen. <span class="cite" data-src="vonElm2019" data-note="S. 5">Q</span> <span class="cite" data-src="peters2020" data-note="Abschnitt „Data extraction“">Q</span></p>

      <div class="step-title-row" id="schritt7"><span class="badge-step">7</span><h3 class="sub-heading" style="margin:0;">Analyse der Ergebnisse</h3></div>
      <p class="searchable">Die Analyse sollte bereits im Protokoll festgelegt werden. In den meisten Fällen ist keine Synthese von Ergebnissen/Outcomes einzelner Quellen beabsichtigt – üblich ist eine einfache deskriptive Analyse (z. B. Häufigkeiten von Konzepten, Populationen oder Studienorten). Eine Meta-Analyse ist für Scoping Reviews nicht vorgesehen; auch eine thematische oder meta-aggregative Synthese qualitativer Daten liegt außerhalb des typischen Rahmens. <span class="cite" data-src="peters2020" data-note="Abschnitt „Data analysis“">Q</span></p>
      <p class="searchable">Eine deskriptive qualitative Codierung zu Kategorien kann sinnvoll sein, insbesondere wenn Konzepte oder Definitionen geklärt werden sollen. Entscheidend ist Transparenz: Autor:innen müssen ihre Vorgehensweise nachvollziehbar begründen. <span class="cite" data-src="peters2020" data-note="Abschnitt „Data analysis“">Q</span></p>

      <div class="step-title-row" id="schritt8"><span class="badge-step">8</span><h3 class="sub-heading" style="margin:0;">Darstellung der Ergebnisse</h3></div>
      <p class="searchable">Die Ergebnisse eines Scoping Reviews werden häufig als „Karte“ (Map) präsentiert: Daten aus den eingeschlossenen Quellen werden grafisch oder tabellarisch dargestellt, ergänzt durch eine narrative Zusammenfassung. Die PCC-Elemente helfen, die passende Darstellungsform zu finden. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Ergebnisse“, S. 6">Q</span></p>
      <p class="searchable">Mögliche Darstellungsformen: Tabellen und andere visuelle Zusammenfassungen (Wortwolken, Balkendiagramme), begleitet von einer narrativen Zusammenfassung. <span class="cite" data-src="pollock2024" data-note="Table 1, Zeile „Presentation of results“">Q</span> In der deutschsprachigen Literatur werden ergänzend Sankey-Diagramme (für komplexe Beziehungen zwischen Merkmalen) und „Worldmaps“ (geografische Herkunft der Studien) genannt. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.5, S. 246">Q</span></p>
      <p class="searchable">Der Ergebnisteil sollte zunächst zeigen, wie viele Studien identifiziert und ausgewählt wurden (narrativ + Flussdiagramm), gefolgt von Details zu Studienmerkmalen, sortiert z. B. nach Erscheinungsjahr, Herkunftsland, Interventionsbereich oder Studienmethodik. <span class="cite" data-src="vonElm2019" data-note="S. 5–6">Q</span></p>

      <div class="step-title-row" id="schritt9"><span class="badge-step">9</span><h3 class="sub-heading" style="margin:0;">Zusammenfassung, Schlussfolgerungen &amp; Implikationen</h3></div>
      <p class="searchable">Abschließend werden die Ergebnisse im Verhältnis zu Zweck und Fragestellung(en) des Reviews zusammengefasst, Schlussfolgerungen gezogen und Implikationen der Befunde benannt (in aktualisierter JBI-Terminologie: „implications of the findings“ statt „implications for practice“). <span class="cite" data-src="pollock2024" data-note="Kapitel 4, Punkt 9">Q</span> <span class="cite" data-src="peters2020" data-note="Abschnitt „Major areas of update“">Q</span></p>
      <p class="searchable">Da im Scoping Review keine Bewertung der Evidenzqualität erfolgt, können Praxisempfehlungen nicht abschließend gradiert werden; ein eigener Abschnitt „Empfehlungen für die Praxis“ entfällt gegebenenfalls ganz. Empfehlungen für zukünftige Forschung sollten hingegen klar und spezifisch auf Basis identifizierter Wissenslücken formuliert werden. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Schlussfolgerungen und Empfehlungen“, S. 7">Q</span></p>
      <p class="searchable">Optional (Schritt 9 im engeren Sinn) kann eine fortlaufende Beratung mit Informationswissenschaftler:innen, Bibliothekar:innen und/oder weiteren Fachexpert:innen sowie eine Konsultation von Stakeholdern erfolgen, um zusätzliche Perspektiven auf die Daten einzubeziehen. <span class="cite" data-src="vonElm2019" data-note="Tabelle 1, S. 3">Q</span> <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.6">Q</span></p>
    </section>

    <!-- 6 RAPID -->
    <section class="wiki-section" id="rapid-anpassungen">
      <h2>6 · Rapid-Anpassungen: Wo lässt sich beschleunigen?</h2>
      <p class="section-intro">Dieser Abschnitt überträgt die generische Rapid-Review-Definition von Munn et al. (2018) auf die neun Scoping-Review-Schritte aus Kapitel 5. Er ist als <em>Ableitung</em> gekennzeichnet, da keine der Quellen einen eigenen „Rapid Scoping Review“-Prozess beschreibt.</p>
      <div class="card rapid">
        <h4>Grundprinzip</h4>
        <p class="searchable">Ein Rapid Review „verkürzt oder überspringt einzelne Schritte des Standardprozesses eines systematischen oder Scoping Reviews“ vollständig, während die grundsätzliche Zielsetzung (z. B. eine der sechs Indikationen aus Kapitel 2.1) unverändert bleibt. Die Wahl für „rapid“ wird primär durch Zeit- und Ressourcenrestriktionen begründet, nicht durch die inhaltliche Fragestellung selbst. <span class="cite" data-src="munn2018" data-note="Discussion, letzter Absatz vor „Conclusion“">Q</span></p>
      </div>
      <p class="searchable">Mögliche Ansatzpunkte für Kürzungen, abgeleitet aus den in Kapitel 5 beschriebenen Standardschritten:</p>
      <ul class="clean searchable">
        <li><strong>Suchstrategie (Schritt 4):</strong> Beschränkung auf weniger Datenbanken oder Verzicht auf den dritten Suchschritt (Referenzlisten-Screening), sofern dies im Protokoll transparent begründet und dokumentiert wird – jede Einschränkung der Suchbreite muss laut Anleitung „eingehend erläutert und begründet“ werden. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Suchstrategie“, S. 5">Q</span></li>
        <li><strong>Screening (Schritt 5):</strong> Wo im Standardprozess zwei unabhängige Reviewer:innen für Titel-/Abstract- und Volltext-Screening vorgesehen sind, kann dieser Schritt in ressourcenbeschränkten Projekten – wie beim generellen Rapid-Review-Prinzip des „Überspringens“ von Schritten – reduziert werden; dies widerspricht jedoch dem in den Quellen empfohlenen Zwei-Reviewer-Prinzip und sollte als Limitation ausgewiesen werden. <span class="cite" data-src="peters2020" data-note="Abschnitt „Evidence screening and selection“">Q</span> <span class="cite" data-src="munn2018" data-note="Discussion">Q</span></li>
        <li><strong>Critical Appraisal:</strong> Da eine Qualitätsbewertung im Scoping Review ohnehin optional/nicht vorgesehen ist, entfällt hier im Vergleich zum systematischen Review bereits standardmäßig ein zeitintensiver Schritt. <span class="cite" data-src="peters2020" data-note="Abschnitt „Evidence screening and selection“">Q</span></li>
        <li><strong>Datenanalyse (Schritt 7):</strong> Die ohnehin empfohlene einfache deskriptive Analyse (Häufigkeiten, keine Meta-Analyse) ist bereits „schlank“ und muss für ein Rapid-Format i. d. R. nicht weiter reduziert werden. <span class="cite" data-src="peters2020" data-note="Abschnitt „Data analysis“">Q</span></li>
      </ul>
      <p class="searchable">Unabhängig vom Tempo gilt: Auch ein beschleunigter Review muss weiterhin „rigoros und transparent“ bleiben – alle vorgenommenen Kürzungen sind im Methodenteil offenzulegen und im Diskussions-/Limitationsabschnitt zu reflektieren. <span class="cite" data-src="munn2018" data-note="Conclusion">Q</span> <span class="cite" data-src="pollock2024" data-note="Kapitel 7 „What are some challenges…“">Q</span></p>
    </section>

    <!-- 7 BERICHTERSTATTUNG -->
    <section class="wiki-section" id="berichterstattung">
      <h2>7 · Berichterstattung</h2>

      <h3 class="sub-heading" id="prisma-scr">7.1 PRISMA-ScR-Checkliste</h3>
      <p class="searchable">Zur Verbesserung der Berichtstransparenz sollten Scoping Reviews der <strong>PRISMA-ScR</strong> (PRISMA Extension for Scoping Reviews) folgen – einer 20-Punkte-Checkliste (plus 2 optionale Punkte), entwickelt von einem 24-köpfigen Expert:innengremium nach EQUATOR-Standards. <span class="cite" data-src="tricco2018" data-note="Abstract">Q</span> <span class="cite" data-src="pollock2024" data-note="Kapitel 5 „Reporting scoping reviews“">Q</span></p>
      <table class="wiki-table searchable">
        <thead><tr><th>#</th><th>Abschnitt</th><th>Checklisten-Punkt (gekürzt)</th></tr></thead>
        <tbody>
          <tr><td>1</td><td>Titel</td><td>Bericht als Scoping Review kenntlich machen.</td></tr>
          <tr><td>2</td><td>Abstract</td><td>Strukturierte Zusammenfassung (Hintergrund, Ziele, Einschlusskriterien, Quellen, Charting-Methoden, Ergebnisse, Schlussfolgerungen).</td></tr>
          <tr><td>3</td><td>Einleitung – Rationale</td><td>Begründung des Reviews im Kontext des bereits Bekannten; warum ein Scoping-Review-Ansatz passt.</td></tr>
          <tr><td>4</td><td>Einleitung – Ziele</td><td>Explizite Aussage zu Fragen/Zielen mit Bezug zu Schlüsselelementen (z. B. PCC).</td></tr>
          <tr><td>5</td><td>Protokoll &amp; Registrierung</td><td>Existenz/Zugänglichkeit eines Protokolls, Registrierungsnummer falls vorhanden.</td></tr>
          <tr><td>6</td><td>Eligibility-Kriterien</td><td>Charakteristika der Quellen als Einschlusskriterien (Jahre, Sprache, Publikationsstatus) inkl. Begründung.</td></tr>
          <tr><td>7</td><td>Informationsquellen</td><td>Alle Suchquellen inkl. Abdeckungszeitraum, Datum der letzten Suche.</td></tr>
          <tr><td>8</td><td>Suche</td><td>Vollständige elektronische Suchstrategie für mind. eine Datenbank.</td></tr>
          <tr><td>9</td><td>Auswahl der Evidenzquellen</td><td>Prozess von Screening &amp; Eligibility-Prüfung.</td></tr>
          <tr><td>10</td><td>Data-Charting-Prozess</td><td>Methode der Datenerfassung (Formulare, Pilotierung, Duplikat-Extraktion).</td></tr>
          <tr><td>11</td><td>Datenelemente</td><td>Liste/Definition aller erhobenen Variablen, Annahmen, Vereinfachungen.</td></tr>
          <tr><td>12*</td><td>Critical Appraisal einzelner Quellen</td><td>Optional – falls durchgeführt: Rationale, Methode, Verwendung.</td></tr>
          <tr><td>13</td><td>Summary Measures</td><td>Nicht anwendbar für Scoping Reviews.</td></tr>
          <tr><td>14</td><td>Synthese der Ergebnisse</td><td>Methode der Handhabung/Zusammenfassung der gechartetenen Daten.</td></tr>
          <tr><td>15 / 16</td><td>Risk of Bias / weitere Analysen</td><td>Nicht anwendbar für Scoping Reviews.</td></tr>
          <tr><td>17</td><td>Ergebnisse – Auswahl der Quellen</td><td>Anzahl gescreenter/eingeschlossener Quellen, idealerweise als Flussdiagramm.</td></tr>
          <tr><td>18</td><td>Charakteristika der Quellen</td><td>Für jede Quelle die gecharteten Charakteristika inkl. Zitation.</td></tr>
          <tr><td>19*</td><td>Critical Appraisal (Ergebnisse)</td><td>Optional – falls durchgeführt: Daten dazu präsentieren.</td></tr>
          <tr><td>20</td><td>Ergebnisse einzelner Quellen</td><td>Relevante gecharteten Daten je Quelle, bezogen auf Fragestellung/Ziele.</td></tr>
          <tr><td>21</td><td>Synthese der Ergebnisse</td><td>Zusammenfassung/Darstellung der Charting-Ergebnisse.</td></tr>
          <tr><td>22 / 23</td><td>Risk of Bias / weitere Analysen</td><td>Nicht anwendbar für Scoping Reviews.</td></tr>
          <tr><td>24</td><td>Diskussion – Zusammenfassung der Evidenz</td><td>Hauptergebnisse, Bezug zu Fragestellung/Zielen, Relevanz für Zielgruppen.</td></tr>
          <tr><td>25</td><td>Limitationen</td><td>Grenzen des Scoping-Review-Prozesses diskutieren.</td></tr>
          <tr><td>26</td><td>Schlussfolgerungen</td><td>Allgemeine Interpretation, Implikationen, nächste Schritte.</td></tr>
          <tr><td>27</td><td>Finanzierung</td><td>Finanzierungsquellen der eingeschlossenen Quellen und des Reviews; Rolle der Geldgeber.</td></tr>
        </tbody>
      </table>
      <p class="searchable">* Punkte 12 und 19 (Critical Appraisal) sind optionale Zusatzitems. <span class="cite" data-src="tricco2018" data-note="Table, Fußnote">Q</span> Diese Checkliste entstand in einem dreirundigen, modifizierten Delphi-Verfahren mit einem internationalen 24–31-köpfigen Expert:innenpanel (Konsensschwelle 85 %). <span class="cite" data-src="tricco2018" data-note="Abschnitt „Results“">Q</span></p>

      <h3 class="sub-heading" id="aufbau-bericht">7.2 Aufbau des Abschlussberichts</h3>
      <p class="searchable">Die deutschsprachige JBI-Anleitung beschreibt den vollständigen Aufbau von Protokoll und Abschlussbericht: Titel- und Autor:inneninformationen, Zusammenfassung/Abstrakt (max. 500 Wörter, gegliedert in Zielsetzung, Einführung, Einschlusskriterien, Methoden, Ergebnisse, Schlussfolgerungen), Fragestellung, Einleitung (ca. 1.000 Wörter), Methoden (Einschlusskriterien, Suchstrategie, Studienauswahl, Datenextraktion), Ergebnisse, Diskussion, Schlussfolgerungen &amp; Empfehlungen sowie weitere Informationen (Interessenkonflikte, Finanzierung, Danksagungen). <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Wesentliche Elemente eines Scoping Reviews“, S. 3–7">Q</span></p>
      <p class="searchable">Die Abschnitte von „Titel“ bis „Methoden“ gelten gleichermaßen für Protokoll und Abschlussbericht; die Abschnitte „Ergebnisse“ bis „Weitere Informationen“ betreffen ausschließlich den Abschlussbericht. <span class="cite" data-src="vonElm2019" data-note="S. 3">Q</span></p>
    </section>

    <!-- 8 HERAUSFORDERUNGEN -->
    <section class="wiki-section" id="herausforderungen-sec">
      <h2>8 · Herausforderungen, Stärken &amp; Schwächen</h2>

      <h3 class="sub-heading" id="herausforderungen">8.1 Herausforderungen &amp; Lösungsansätze</h3>
      <table class="wiki-table searchable">
        <thead><tr><th>Herausforderung</th><th>Möglicher Lösungsansatz</th></tr></thead>
        <tbody>
          <tr><td>Wenig Personen mit Scoping-Review-Methodenkompetenz</td><td>JBI Scoping Review Network bietet Ressourcen &amp; Schulungen.</td></tr>
          <tr><td>Unklarheit, wann ein Scoping Review angemessen ist</td><td>„Right Review“-Tool führt durch Fragen zur passenden Reviewform.</td></tr>
          <tr><td>Wahl eines Scoping Reviews, obwohl ein anderer Synthese-Typ passender wäre</td><td>Entscheidungshilfen des JBI-Netzwerks nutzen.</td></tr>
          <tr><td>Unklarheit, welche Daten extrahiert und wie sie analysiert werden sollen</td><td>Aktuelle JBI-Guidance zu Extraktion/Analyse; Webinare mit Beispielen.</td></tr>
          <tr><td>Darstellung der Ergebnisse</td><td>Siehe Kapitel 5, Schritt 8 (Tabellen, visuelle Zusammenfassungen).</td></tr>
          <tr><td>Teils geringe methodische Qualität von Scoping Reviews</td><td>A-priori-Protokoll veröffentlichen, JBI-Guidance befolgen, nach PRISMA-ScR berichten; Team mit Themenexpert:in, Bibliothekar:in, Methodolog:in besetzen.</td></tr>
          <tr><td>Schlussfolgerungen werden überinterpretiert (z. B. als Praxisempfehlung)</td><td>Klar beschreiben, wie Ergebnisse Wissen erweitern; Knowledge User frühzeitig einbinden; Stärken/Schwächen-Abschnitt ergänzen.</td></tr>
          <tr><td>Fehleinschätzungen von Umfang/Funktion durch Editor:innen, Gutachter:innen, Autor:innen</td><td>Schulung für Editor:innen und Forschungsgemeinschaft.</td></tr>
        </tbody>
      </table>
      <p class="searchable">Quelle der Tabelle: <span class="cite" data-src="pollock2024" data-note="Table 2 „Challenges and solutions in scoping reviews“">Q</span> Eine zusätzliche Herausforderung ist der Umgang mit sehr großen Evidenzmengen (viele eingeschlossene Quellen, hohes Datenvolumen, komplexe Analysen); empfohlen wird u. a. eine frühzeitige Klärung von Teamzusammensetzung, Fokussierung der Frage-/Suchstrategie und Analyseplanung. <span class="cite" data-src="pollock2024" data-note="Kapitel 7, Absatz zu großen Reviews">Q</span></p>

      <h3 class="sub-heading" id="staerken-schwaechen">8.2 Stärken &amp; Schwächen</h3>
      <div class="card">
        <h4>Stärken</h4>
        <ul class="clean searchable">
          <li>Guter Überblick über ein sehr heterogenes Literatur-/Quellenkörper. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.6">Q</span></li>
          <li>Forschungsthemen können umfassend dargestellt und mögliche Wissenslücken aufgedeckt werden. <span class="cite" data-src="ritschl2024">Q</span></li>
        </ul>
      </div>
      <div class="card rapid">
        <h4>Schwächen</h4>
        <ul class="clean searchable">
          <li>Nicht geeignet, um die Effektivität von Interventionen abschließend zu beurteilen. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.6">Q</span></li>
          <li>Die Aussagekraft ist immer nur so gut wie die zugrunde liegenden Daten/Studien – bei unzureichender Suchstrategie liefert selbst ein methodisch sauberer Scoping Review kein vollständiges Bild der Evidenzlage. <span class="cite" data-src="ritschl2024">Q</span></li>
          <li>Wie jeder Review ist er von der Verfügbarkeit relevanter Informationen abhängig; relevante Quellen können übersehen werden. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Diskussion“, S. 6–7">Q</span></li>
        </ul>
      </div>
    </section>

    <!-- 9 GLOSSAR -->
    <section class="wiki-section" id="glossar-quellen">
      <h2>9 · Glossar &amp; Quellenverzeichnis</h2>

      <h3 class="sub-heading" id="glossar">9.1 Glossar</h3>
      <ul class="clean searchable">
        <li><strong>PCC:</strong> Population, Concept, Context – Mnemonic zur Strukturierung von Titel, Fragestellung und Einschlusskriterien eines Scoping Reviews. <span class="cite" data-src="vonElm2019">Q</span> <span class="cite" data-src="peters2020">Q</span></li>
        <li><strong>PICO:</strong> Population/Problem, Intervention, Comparison, Outcome – alternative Strukturierungshilfe, v. a. bei interventionsbezogenen Fragestellungen. <span class="cite" data-src="ritschl2024" data-note="Kap. 8.3.4.1">Q</span></li>
        <li><strong>Data Charting:</strong> Begriff für die Datenextraktion in Scoping Reviews (synonym zu „Datenextraktion“). <span class="cite" data-src="peters2020" data-note="Abschnitt „Data extraction“">Q</span></li>
        <li><strong>Graue Literatur:</strong> Unveröffentlichte oder außerhalb klassischer Verlage publizierte Quellen (z. B. Berichte, Dissertationen, Websites), die in Scoping Reviews regelhaft einbezogen werden können. <span class="cite" data-src="vonElm2019" data-note="Abschnitt „Suchstrategie“">Q</span> <span class="cite" data-src="ritschl2024">Q</span></li>
        <li><strong>PRISMA-ScR:</strong> PRISMA-Erweiterung für Scoping Reviews – 20-Punkte-Berichtsleitlinie (+2 optionale Punkte). <span class="cite" data-src="tricco2018">Q</span></li>
        <li><strong>Evidence &amp; Gap Map (EGM):</strong> Systematisches Evidenzsyntheseprodukt mit visueller, interaktiver Darstellung von Evidenz und Forschungslücken, meist nach PICOS strukturiert. <span class="cite" data-src="pollock2024" data-note="Table 1">Q</span></li>
        <li><strong>Rapid Review:</strong> „Systematic reviews with shortcuts“ – Reviews, die einzelne methodische Schritte aufgrund von Zeit-/Ressourcenrestriktionen verkürzen oder auslassen, unabhängig von der ursprünglichen Reviewform (systematisch oder Scoping). <span class="cite" data-src="munn2018">Q</span></li>
        <li><strong>Knowledge User:</strong> An Forschung interessierte oder von ihr betroffene Personen (Kliniker:innen, Patient:innen, Politikgestalter:innen etc.), die laut JBI-Guidance aktiv in Scoping Reviews eingebunden werden sollten. <span class="cite" data-src="pollock2024" data-note="Kapitel 3">Q</span></li>
      </ul>

      <h3 class="sub-heading" id="quellen">9.2 Quellenverzeichnis</h3>
      <ol class="clean searchable" id="referenceList">
        <li id="ref-vonElm2019">von Elm E, Schreiber G, Haupt CC. Methodische Anleitung für Scoping Reviews (JBI-Methodologie). <em>Z. Evid. Fortbild. Qual. Gesundh.wesen (ZEFQ)</em>. 2019;143:1–7. <span class="pop-file-inline">(Datei: Anleitung Scoping Review.pdf)</span></li>
        <li id="ref-bastian2010">Bastian H, Glasziou P, Chalmers I. Seventy-Five Trials and Eleven Systematic Reviews a Day: How Will We Ever Keep Up? <em>PLoS Medicine</em>. 2010;7(9):e1000326. <span class="pop-file-inline">(Datei: Bastian Scoping Review.pdf)</span></li>
        <li id="ref-peters2020">Peters MDJ, Marnie C, Tricco AC, Pollock D, Munn Z, Alexander L, McInerney P, Godfrey CM, Khalil H. Updated methodological guidance for the conduct of scoping reviews. <em>JBI Evidence Synthesis</em>. 2020;18(10):2119–2126. <span class="pop-file-inline">(Datei: Methode scoping review.pdf)</span></li>
        <li id="ref-pollock2024">Pollock D, Evans C, Jia RM, Alexander L, Pieper D, Brandão de Moraes E, Peters MDJ, Tricco AC, Khalil H, Godfrey CM, Saran A, Campbell F, Munn Z. „How-to“: scoping review? <em>Journal of Clinical Epidemiology</em>. 2024;176:111572. <span class="pop-file-inline">(Datei: POLLOCK 2024 How to (VOR).pdf)</span></li>
        <li id="ref-tricco2018">Tricco AC, Lillie E, Zarin W, et al. PRISMA Extension for Scoping Reviews (PRISMA-ScR): Checklist and Explanation. <em>Annals of Internal Medicine</em>. 2018;169(7):467–473. <span class="pop-file-inline">(Datei: PRISMAScRAIME201810020-M180850published.pdf)</span></li>
        <li id="ref-ritschl2024">Sperl L, Stamm T, Putz P, Sturma A, Ritschl V. Kapitel 8.3 „Scoping Reviews“. In: Ritschl V et al. (Hrsg.), Lehrbuch qualitative/wissenschaftliche Gesundheitsforschung, Kap. 8 „Übersicht über bestehende Literatur: (Literatur)Reviews“, S. 236–248. <span class="pop-file-inline">(Datei: Qualitative Forschung.pdf)</span></li>
        <li id="ref-munn2018">Munn Z, Peters MDJ, Stern C, Tufanaru C, McArthur A, Aromataris E. Systematic review or scoping review? Guidance for authors when choosing between a systematic or scoping review approach. <em>BMC Medical Research Methodology</em>. 2018;18:143. <span class="pop-file-inline">(Datei: Systematic or scoping review.pdf)</span></li>
      </ol>
    </section>

    <footer class="wiki-footer">
      Diese Seite wurde auf Basis von sieben hochgeladenen PDF-Quellen erstellt und ist bewusst erweiterbar angelegt: Weitere Quellen und Abschnitte können jederzeit ergänzt werden, ohne die bestehende Struktur (Definition → Indikationen → Rahmenwerke → 9-Schritte-Ablauf → Rapid-Anpassungen → Berichterstattung → Herausforderungen → Glossar) zu verändern.
    </footer>

  </main>
</div>

<div id="popover">
  <span class="pop-close" id="popClose">✕</span>
  <div class="pop-title">Quelle(n)</div>
  <div id="popBody"></div>
</div>

<script>
// ---------- SOURCE DATABASE ----------
const SOURCES = {
  vonElm2019: {
    short: "von Elm, Schreiber &amp; Haupt (2019)",
    full: "Methodische Anleitung für Scoping Reviews (JBI-Methodologie). Z. Evid. Fortbild. Qual. Gesundh.wesen (ZEFQ) 143:1–7.",
    file: "Anleitung Scoping Review.pdf"
  },
  bastian2010: {
    short: "Bastian, Glasziou &amp; Chalmers (2010)",
    full: "Seventy-Five Trials and Eleven Systematic Reviews a Day: How Will We Ever Keep Up? PLoS Medicine 7(9):e1000326.",
    file: "Bastian Scoping Review.pdf"
  },
  peters2020: {
    short: "Peters et al. (2020)",
    full: "Updated methodological guidance for the conduct of scoping reviews. JBI Evidence Synthesis 18(10):2119–2126.",
    file: "Methode scoping review.pdf"
  },
  pollock2024: {
    short: "Pollock et al. (2024)",
    full: "„How-to“: scoping review? Journal of Clinical Epidemiology 176:111572.",
    file: "POLLOCK 2024 How to (VOR).pdf"
  },
  tricco2018: {
    short: "Tricco et al. (2018)",
    full: "PRISMA Extension for Scoping Reviews (PRISMA-ScR): Checklist and Explanation. Annals of Internal Medicine 169(7):467–473.",
    file: "PRISMAScRAIME201810020-M180850published.pdf"
  },
  ritschl2024: {
    short: "Sperl, Stamm, Putz, Sturma &amp; Ritschl",
    full: "Kapitel 8.3 „Scoping Reviews“, in: Kapitel 8 „Übersicht über bestehende Literatur: (Literatur)Reviews“, S. 236–248.",
    file: "Qualitative Forschung.pdf"
  },
  munn2018: {
    short: "Munn et al. (2018)",
    full: "Systematic review or scoping review? Guidance for authors when choosing between a systematic or scoping review approach. BMC Medical Research Methodology 18:143.",
    file: "Systematic or scoping review.pdf"
  }
};

// ---------- CITATION POPOVER ----------
const popover = document.getElementById('popover');
const popBody = document.getElementById('popBody');
let currentCiteBtn = null;

function closePopover(){
  popover.classList.remove('show');
  if(currentCiteBtn) currentCiteBtn.classList.remove('open');
  currentCiteBtn = null;
}

document.addEventListener('click', function(e){
  const btn = e.target.closest('.cite');
  if(btn){
    e.stopPropagation();
    if(currentCiteBtn === btn){ closePopover(); return; }
    if(currentCiteBtn) currentCiteBtn.classList.remove('open');
    currentCiteBtn = btn;
    btn.classList.add('open');

    const ids = btn.getAttribute('data-src').split(',').map(s => s.trim());
    const note = btn.getAttribute('data-note') || '';
    popBody.innerHTML = ids.map(id => {
      const s = SOURCES[id];
      if(!s) return '';
      return '<div class="pop-src">'
        + '<div class="pop-cite">' + s.short + '</div>'
        + '<div style="color:#d7ddee;">' + s.full + '</div>'
        + (note ? '<div class="pop-note">' + note + '</div>' : '')
        + '<div class="pop-file">📄 ' + s.file + '</div>'
        + '</div>';
    }).join('');

    const rect = btn.getBoundingClientRect();
    popover.classList.add('show');
    const popRect = popover.getBoundingClientRect();
    let left = rect.left + window.scrollX;
    let top = rect.bottom + window.scrollY + 8;
    if(left + popRect.width > window.scrollX + window.innerWidth - 16){
      left = window.scrollX + window.innerWidth - popRect.width - 16;
    }
    popover.style.left = left + 'px';
    popover.style.top = top + 'px';
    return;
  }
  if(!e.target.closest('#popover')){
    closePopover();
  }
});
document.getElementById('popClose').addEventListener('click', closePopover);
document.addEventListener('keydown', function(e){ if(e.key === 'Escape') closePopover(); });

// ---------- ACTIVE TOC HIGHLIGHT ----------
const tocLinks = Array.from(document.querySelectorAll('nav.toc a'));
function setActiveLink(){
  let currentId = null;
  document.querySelectorAll('main [id]').forEach(el => {
    const top = el.getBoundingClientRect().top;
    if(top - 100 <= 0) currentId = el.id;
  });
  tocLinks.forEach(a => a.classList.toggle('active', a.getAttribute('href') === '#' + currentId));
}
window.addEventListener('scroll', setActiveLink);
setActiveLink();

// open parent <details> when navigating via TOC link
tocLinks.forEach(a => {
  a.addEventListener('click', () => {
    const details = a.closest('details');
    if(details) details.open = true;
  });
});

// ---------- SEARCH ----------
const searchInput = document.getElementById('searchInput');
const searchResults = document.getElementById('searchResults');
const searchableEls = Array.from(document.querySelectorAll('main .searchable'));

function nearestSectionTitle(el){
  let node = el;
  while(node){
    const sec = node.closest ? node.closest('section.wiki-section') : null;
    if(sec){
      const h2 = sec.querySelector('h2');
      // try to find a closer h3/h4 above el within the section
      let heading = h2 ? h2.textContent : '';
      let sib = el;
      let bestSub = null;
      while(sib && sib !== sec){
        sib = sib.previousElementSibling || sib.parentElement;
        if(sib && sib.matches && (sib.matches('h3.sub-heading') || sib.matches('h4.step-heading') || sib.matches('.step-title-row'))){
          bestSub = sib.textContent.trim();
          break;
        }
        if(sib === sec) break;
      }
      return bestSub ? (heading + ' › ' + bestSub) : heading;
    }
    node = node.parentElement;
  }
  return 'Seite';
}

function escapeHtml(str){
  return str.replace(/[&<>]/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;'}[c]));
}

function runSearch(query){
  const q = query.trim().toLowerCase();
  if(q.length < 2){
    searchResults.classList.remove('show');
    searchResults.innerHTML = '';
    return;
  }
  const matches = [];
  searchableEls.forEach(el => {
    const text = el.innerText || el.textContent || '';
    const idx = text.toLowerCase().indexOf(q);
    if(idx !== -1){
      const start = Math.max(0, idx - 40);
      const end = Math.min(text.length, idx + q.length + 60);
      let snippet = (start > 0 ? '…' : '') + text.slice(start, end) + (end < text.length ? '…' : '');
      snippet = escapeHtml(snippet);
      const re = new RegExp('(' + q.replace(/[.*+?^${}()|[\]\\]/g,'\\$&') + ')', 'ig');
      snippet = snippet.replace(re, '<mark>$1</mark>');
      matches.push({ el, section: nearestSectionTitle(el), snippet });
    }
  });

  if(matches.length === 0){
    searchResults.innerHTML = '<div class="sr-empty">Keine Treffer für „' + escapeHtml(query) + '“.</div>';
    searchResults.classList.add('show');
    return;
  }

  const shown = matches.slice(0, 30);
  searchResults.innerHTML =
    '<div class="sr-count">' + matches.length + ' Treffer</div>' +
    shown.map((m, i) =>
      '<button class="sr-item" data-idx="' + i + '">' +
        '<div class="sr-section">' + escapeHtml(m.section) + '</div>' +
        '<div class="sr-snippet">' + m.snippet + '</div>' +
      '</button>'
    ).join('');
  searchResults.classList.add('show');

  searchResults.querySelectorAll('.sr-item').forEach((btn, i) => {
    btn.addEventListener('click', () => {
      const target = shown[i].el;
      target.scrollIntoView({behavior:'smooth', block:'center'});
      target.classList.remove('flash');
      void target.offsetWidth;
      target.classList.add('flash');
      searchResults.classList.remove('show');
    });
  });
}

let searchDebounce;
searchInput.addEventListener('input', (e) => {
  clearTimeout(searchDebounce);
  const val = e.target.value;
  searchDebounce = setTimeout(() => runSearch(val), 120);
});
searchInput.addEventListener('focus', () => { if(searchInput.value.trim().length >= 2) searchResults.classList.add('show'); });
document.addEventListener('click', (e) => {
  if(!e.target.closest('.search-box')) searchResults.classList.remove('show');
});
document.addEventListener('keydown', (e) => {
  if(e.key === 'Escape'){ searchResults.classList.remove('show'); }
});
</script>
</body>
</html>
