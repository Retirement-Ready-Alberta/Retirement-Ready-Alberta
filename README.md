<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-4HJ5DQLFZH"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'G-4HJ5DQLFZH');
  </script>

  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Retirement Ready Alberta | Free Alberta Retirement Planning Tools</title>
  <meta name="description" content="Free Alberta-focused retirement calculators, CPP and OAS planning tools, retirement confidence score, checklist, and printable report." />
  
  <link rel="canonical" href="https://retire-alberta.ca/" />
  <meta property="og:title" content="Retirement Ready Alberta | Free Alberta Retirement Planning Tools" />
  <meta property="og:description" content="Free Alberta-focused retirement calculators, CPP and OAS planning tools, retirement confidence score, checklist, and printable report." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://retire-alberta.ca/" />
  <meta property="og:site_name" content="Retirement Ready Alberta" />
  <meta name="twitter:card" content="summary_large_image" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
<header class="site-header">
  <div class="wrap nav">
    <a class="brand" href="index.html" aria-label="Retirement Ready Alberta home">
      <span class="brand-icon">✓</span>
      <span><strong>Retirement Ready</strong><small>Alberta</small></span>
    </a>
    <button class="mobile-menu" onclick="toggleMenu()" aria-label="Open menu">☰</button>
    <nav id="mainNav">
      <a href="#tools">Tools</a>
      <a href="#calculator">Calculator</a>
      <a href="cpp-oas-guide.html">CPP & OAS</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </div>
</header>

<main>
  <section class="hero">
    <div class="wrap hero-grid">
      <div class="hero-copy">
        <p class="eyebrow">Built for Albertans planning retirement</p>
        <h1>Helping Albertans retire with confidence.</h1>
        <p class="lead">Estimate your retirement income, compare CPP timing, understand your pension, and create a personalized Retirement Readiness Report in minutes.</p>
        <div class="hero-actions">
          <a class="btn primary" href="#calculator">Start my free plan</a>
          <a class="btn ghost" href="#report">View report sample</a>
        </div>
        <div class="trust-row">
          <span>✓ No sign-up required</span>
          <span>✓ Educational tools</span>
          <span>✓ Alberta focused</span>
        </div>
      </div>
      <div class="hero-panel">
        <div class="score-preview">
          <span>Retirement Confidence Score™</span>
          <strong>87/100</strong>
          <div class="progress"><i style="width:87%"></i></div>
          <p>Clear numbers. Plain-language next steps.</p>
        </div>
        <div class="mini-stats">
          <div><small>Monthly Income</small><b>$5,840</b></div>
          <div><small>Income Gap</small><b>+$420</b></div>
          <div><small>Report</small><b>Ready</b></div>
        </div>
      </div>
    </div>
  </section>

  <section id="tools" class="wrap section">
    <div class="section-heading">
      <p class="eyebrow">Plan smarter</p>
      <h2>Free retirement tools in one place</h2>
    </div>
    <div class="feature-grid">
      <article class="feature-card"><span>📊</span><h3>Retirement Calculator</h3><p>Estimate savings, monthly income, and gaps before retirement.</p></article>
      <article class="feature-card"><span>💰</span><h3>CPP & OAS Planner</h3><p>Compare CPP at 60, 65, and 70 using your own estimate.</p></article>
      <article class="feature-card"><span>🏛</span><h3>Pension Centre</h3><p>Learn how defined benefit pensions can fit into your plan.</p></article>
      <article class="feature-card"><span>📄</span><h3>Printable Report</h3><p>Create a clean summary you can save as PDF or print.</p></article>
    </div>
  </section>

  <section class="wrap section confidence-section">
    <div class="confidence-copy">
      <p class="eyebrow">More than a calculator</p>
      <h2>Your Retirement Confidence Score™</h2>
      <p>Retirement planning is easier when the numbers turn into a simple score and action plan. Your score considers estimated income, savings, debt, CPP/OAS, pension income, and income gap.</p>
    </div>
    <div class="score-components">
      <div><span>Savings</span><div class="bar"><i style="width:78%"></i></div></div>
      <div><span>Income</span><div class="bar"><i style="width:88%"></i></div></div>
      <div><span>Debt</span><div class="bar"><i style="width:62%"></i></div></div>
      <div><span>CPP Strategy</span><div class="bar"><i style="width:84%"></i></div></div>
    </div>
  </section>

  <section id="calculator" class="wrap section calculator-shell">
    <div class="section-heading narrow">
      <p class="eyebrow">Start here</p>
      <h2>Retirement Readiness Calculator</h2>
      <p>Enter your information below. Use the help icons if you are unsure what a field means.</p>
    </div>

    <div class="app-grid">
      <section class="card form-card">
        <h3>Your numbers</h3>
        <div class="form-grid">
          <div class="form-group"><label>Current Age <button class="help-icon" onclick="showHelp('currentAge')">ⓘ</button></label><input type="text" inputmode="decimal" id="currentAge" value="55"></div>
          <div class="form-group"><label>Retirement Age <button class="help-icon" onclick="showHelp('retirementAge')">ⓘ</button></label><input type="text" inputmode="decimal" id="retirementAge" value="65"></div>
          <div class="form-group"><label>Current RRSP Savings <button class="help-icon" onclick="showHelp('rrsp')">ⓘ</button></label><input type="text" inputmode="decimal" id="rrsp" value="20000"></div>
          <div class="form-group"><label>Current TFSA Savings <button class="help-icon" onclick="showHelp('tfsa')">ⓘ</button></label><input type="text" inputmode="decimal" id="tfsa" value="1000"></div>
          <div class="form-group"><label>Monthly Contributions <button class="help-icon" onclick="showHelp('monthlyContribution')">ⓘ</button></label><input type="text" inputmode="decimal" id="monthlyContribution" value="250"></div>
          <div class="form-group"><label>Expected Annual Return % <button class="help-icon" onclick="showHelp('annualReturn')">ⓘ</button></label><input type="text" inputmode="decimal" id="annualReturn" value="5"></div>
          <div class="form-group"><label>CPP Estimate / Month at 65 <button class="help-icon" onclick="showHelp('cpp')">ⓘ</button></label><input type="text" inputmode="decimal" id="cpp" value="900"></div>
          <div class="form-group"><label>OAS Estimate / Month <button class="help-icon" onclick="showHelp('oas')">ⓘ</button></label><input type="text" inputmode="decimal" id="oas" value="725"></div>
          <div class="form-group"><label>Workplace Pension / Month <button class="help-icon" onclick="showHelp('pension')">ⓘ</button></label><input type="text" inputmode="decimal" id="pension" value="0"></div>
          <div class="form-group"><label>Mortgage or Debt <button class="help-icon" onclick="showHelp('debt')">ⓘ</button></label><input type="text" inputmode="decimal" id="debt" value="390000"></div>
          <div class="form-group full"><label>Desired Retirement Income / Month <button class="help-icon" onclick="showHelp('incomeNeed')">ⓘ</button></label><input type="text" inputmode="decimal" id="incomeNeed" value="5000"></div>
          <div class="form-group full couple-toggle">
            <label><input type="checkbox" id="includeSpouse" onchange="toggleSpouseFields()"> Plan as a couple / household</label>
            <p class="field-note">Add spouse or partner income, savings, CPP, OAS, and pension estimates for a combined household retirement assessment.</p>
          </div>
          <div id="spouseFields" class="couple-fields hidden form-group full">
            <h4>Spouse / Partner numbers</h4>
            <div class="form-grid">
              <div class="form-group"><label>Spouse Current Age</label><input type="text" inputmode="decimal" id="spouseCurrentAge" value="56"></div>
              <div class="form-group"><label>Spouse Retirement Age</label><input type="text" inputmode="decimal" id="spouseRetirementAge" value="65"></div>
              <div class="form-group"><label>Spouse RRSP Savings</label><input type="text" inputmode="decimal" id="spouseRrsp" value="12000"></div>
              <div class="form-group"><label>Spouse TFSA Savings</label><input type="text" inputmode="decimal" id="spouseTfsa" value="1000"></div>
              <div class="form-group"><label>Spouse CPP Estimate / Month at 65</label><input type="text" inputmode="decimal" id="spouseCpp" value="900"></div>
              <div class="form-group"><label>Spouse OAS Estimate / Month</label><input type="text" inputmode="decimal" id="spouseOas" value="725"></div>
              <div class="form-group full"><label>Spouse Workplace Pension / Month</label><input type="text" inputmode="decimal" id="spousePension" value="0"></div>
            </div>
          </div>
        </div>
        <button class="btn primary" onclick="calculateRetirement()">Calculate Retirement</button>
      </section>

      <aside class="card results-card">
        <h3>Your snapshot</h3>
        <div id="results" class="results hidden">
          <div class="snapshot-score"><span id="score"></span><small id="status"></small></div>
          <p><strong>Estimated Savings:</strong> <span id="futureSavings"></span></p>
          <p><strong>Monthly Income:</strong> <span id="monthlyIncome"></span></p>
          <p id="resultMessage"></p>
          <a href="#dashboard" class="btn secondary">View dashboard</a>
        </div>
        <div id="preResults" class="empty-state"><p>Complete the calculator to generate your score, dashboard, checklist, and report.</p></div>
      </aside>
    </div>
  </section>

  <section id="dashboard" class="wrap section card dashboard-card-main">
    <div class="report-header"><div><p class="eyebrow">Dashboard</p><h2>Retirement Dashboard</h2></div></div>
    <div id="emptyDashboard" class="empty-state"><p>Complete the calculator above to generate your dashboard.</p></div>
    <div id="dashboardContent" class="hidden">
      <div class="dashboard-grid">
        <div class="metric-card"><span>Score</span><strong id="dashScore"></strong><small id="dashStatus"></small></div>
        <div class="metric-card"><span>Savings at Retirement</span><strong id="dashSavings"></strong></div>
        <div class="metric-card"><span>Monthly Income</span><strong id="dashIncome"></strong></div>
        <div class="metric-card"><span>Income Gap</span><strong id="dashGap"></strong></div>
        <div class="metric-card spouse-only hidden"><span>Household Plan</span><strong id="dashHousehold">Couple</strong><small id="dashSpouseIncome"></small></div>
      </div>
      <div class="chart-grid">
        <div class="chart-card"><h3>Savings Growth</h3><canvas id="savingsChart" width="500" height="280"></canvas></div>
        <div class="chart-card"><h3>Monthly Income Breakdown</h3><canvas id="incomeChart" width="500" height="280"></canvas></div>
      </div>
      <div class="gap-meter"><h3>Income Gap Meter</h3><div class="meter-track"><div id="gapMeterFill" class="meter-fill"></div></div><p id="gapMeterText"></p></div>
    </div>
  </section>

  <section id="cpp-optimizer" class="wrap section card">
    <p class="eyebrow">CPP planning</p><h2>CPP Optimizer</h2>
    <p class="section-intro">Compare starting CPP at 60, 65, and 70 using your estimated CPP at age 65.</p>
    <div class="form-grid compact">
      <div class="form-group"><label>Estimated CPP at 65 / Month</label><input type="text" inputmode="decimal" id="cppAt65" value="900"></div>
      <div class="form-group"><label>Current Age</label><input type="text" inputmode="decimal" id="cppCurrentAge" value="55"></div>
    </div>
    <button class="btn primary" onclick="calculateCpp()">Compare CPP Timing</button>
    <div id="cppResults" class="hidden table-wrap"><table class="comparison-table"><thead><tr><th>Start Age</th><th>Estimated Monthly CPP</th><th>Simple Explanation</th></tr></thead><tbody><tr><td>60</td><td id="cpp60"></td><td>Lower monthly payment, but income starts earlier.</td></tr><tr><td>65</td><td id="cpp65"></td><td>Standard comparison age.</td></tr><tr><td>70</td><td id="cpp70"></td><td>Higher monthly payment, but income starts later.</td></tr></tbody></table><p class="educational-note">Delaying CPP can increase monthly income, but the best choice depends on health, cash flow, taxes, pensions, spouse income, and life expectancy.</p></div>
  </section>

  <section id="checklist" class="wrap section card">
    <p class="eyebrow">Next steps</p><h2>Personalized Retirement Checklist</h2>
    <div id="emptyChecklist" class="empty-state"><p>Complete the calculator to generate your checklist.</p></div>
    <div id="checklistContent" class="hidden"><h3 id="checklistTitle"></h3><ul id="checklistItems" class="checklist"></ul></div>
  </section>

  <section id="report" class="wrap section card report-card">
    <div class="report-header"><div><p class="eyebrow">Printable</p><h2>Retirement Readiness Report</h2><p>Your personalized beginner-friendly retirement summary.</p></div><button class="btn primary print-btn" onclick="window.print()">Print / Save as PDF</button></div>
    <div id="emptyReport" class="empty-state"><p>Complete the calculator above to generate your report.</p></div>
    <div id="reportContent" class="hidden">
      <div class="report-title"><h3>Retirement Ready Alberta Summary</h3><p id="reportDate"></p></div>
      <div class="report-grid"><div class="report-metric"><span>Readiness Score</span><strong id="reportScore"></strong></div><div class="report-metric"><span>Status</span><strong id="reportStatus"></strong></div><div class="report-metric"><span>Savings at Retirement</span><strong id="reportSavings"></strong></div><div class="report-metric"><span>Monthly Income Estimate</span><strong id="reportIncome"></strong></div></div>
      <div class="report-section"><h4>What This Means</h4><p id="reportMeaning"></p></div>
      <div class="report-section"><h4>Your Estimated Monthly Retirement Income</h4><ul><li>CPP estimate: <strong id="reportCpp"></strong></li><li>OAS estimate: <strong id="reportOas"></strong></li><li>Workplace pension estimate: <strong id="reportPension"></strong></li><li>Estimated monthly withdrawal from savings: <strong id="reportWithdrawal"></strong></li><li>Desired monthly income: <strong id="reportIncomeNeed"></strong></li></ul></div>
      <div id="spouseReportSection" class="report-section hidden"><h4>Couple / Household Summary</h4><ul><li>Combined CPP estimate: <strong id="reportCombinedCpp"></strong></li><li>Combined OAS estimate: <strong id="reportCombinedOas"></strong></li><li>Combined workplace pension estimate: <strong id="reportCombinedPension"></strong></li><li>Combined retirement savings estimate: <strong id="reportCombinedSavings"></strong></li></ul></div>
      <div class="report-section"><h4>Possible Risks</h4><ul id="riskList"></ul></div>
      <div class="report-section"><h4>Suggested Next Steps</h4><ul id="nextSteps"></ul></div>
      <div class="report-section educational-note"><h4>Beginner Note</h4><p>This report is an educational estimate only. It does not replace professional financial advice. Retirement planning should also consider taxes, inflation, health costs, pension survivor options, CPP timing, OAS clawback, estate planning, and debt.</p></div>
    </div>
  </section>

  <section class="wrap section knowledge-section">
    <div class="section-heading"><p class="eyebrow">Learn</p><h2>Alberta Retirement Centre</h2></div>
    <div class="learn-grid">
      <a href="cpp-oas-guide.html" class="learn-card"><h3>CPP & OAS</h3><p>Understand federal retirement benefits.</p></a>
      <a href="about.html" class="learn-card"><h3>Workplace Pensions</h3><p>Learn how pension income changes your plan.</p></a>
      <a href="disclaimer.html" class="learn-card"><h3>Retirement Risks</h3><p>Debt, taxes, inflation, and longevity.</p></a>
    </div>
  </section>
</main>

<div id="helpModal" class="modal"><div class="modal-content"><button class="close-btn" onclick="closeHelp()">×</button><h3 id="helpTitle"></h3><p id="helpText"></p><p id="helpTip" class="tip"></p></div></div>

<footer class="site-footer">
  <div class="wrap footer-grid">
    <div><strong>Retirement Ready Alberta</strong><p>Educational retirement planning tools for Albertans.</p></div>
    <div><a href="about.html">About</a><a href="contact.html">Contact</a><a href="privacy.html">Privacy</a><a href="disclaimer.html">Disclaimer</a></div>
  </div>
  <p class="wrap copyright">© 2026 Retirement Ready Alberta. Educational information only.</p>
</footer>

<script src="script.js"></script>
<script>
function toggleMenu(){document.getElementById('mainNav').classList.toggle('open');}
const originalCalculate = window.calculateRetirement;
window.calculateRetirement = function(){
  originalCalculate();
  const pre = document.getElementById('preResults');
  if(pre) pre.style.display = 'none';
}
</script>
</body>
</html>
Add Retirement Ready Alberta version 2.2
