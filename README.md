# JOB-Board
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Crystal Cole | HR Job Board</title>
  <style>
    :root {
      --navy: #1a2a4a;
      --teal: #2a7f7f;
      --gold: #c8a84b;
      --light: #f5f7fa;
      --card: #ffffff;
      --border: #e2e8f0;
      --text: #2d3748;
      --muted: #718096;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Segoe UI', sans-serif; background: var(--light); color: var(--text); }

    header {
      background: linear-gradient(135deg, var(--navy) 0%, #2d4a7a 100%);
      color: white;
      padding: 40px 24px 32px;
      text-align: center;
    }
    header h1 { font-size: 2rem; letter-spacing: 2px; margin-bottom: 6px; }
    header p { color: #a8c0e8; font-size: 0.95rem; margin-bottom: 4px; }
    .header-badges {
      display: flex; flex-wrap: wrap; justify-content: center; gap: 8px; margin-top: 14px;
    }
    .badge {
      background: rgba(255,255,255,0.15); border-radius: 20px;
      padding: 4px 14px; font-size: 0.78rem; color: #e0ecff;
    }
    .stats-bar {
      background: var(--teal); color: white;
      display: flex; justify-content: center; gap: 40px;
      padding: 14px 24px; flex-wrap: wrap;
    }
    .stat { text-align: center; }
    .stat strong { display: block; font-size: 1.4rem; }
    .stat span { font-size: 0.78rem; opacity: 0.85; }

    main { max-width: 1100px; margin: 0 auto; padding: 32px 16px; }

    .section-title {
      font-size: 1.1rem; font-weight: 700; color: var(--navy);
      border-left: 4px solid var(--gold); padding-left: 12px;
      margin: 32px 0 16px;
    }

    .grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(320px, 1fr)); gap: 16px; }

    .card {
      background: var(--card); border: 1px solid var(--border);
      border-radius: 10px; padding: 18px 20px;
      transition: box-shadow 0.2s, transform 0.2s;
      position: relative;
    }
    .card:hover { box-shadow: 0 6px 24px rgba(26,42,74,0.13); transform: translateY(-2px); }

    .card-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 8px; }
    .card-title { font-size: 0.97rem; font-weight: 700; color: var(--navy); flex: 1; }
    .salary-tag {
      background: #e6f4ea; color: #2d6a4f;
      font-size: 0.72rem; font-weight: 700;
      border-radius: 12px; padding: 3px 10px; white-space: nowrap; margin-left: 8px;
    }
    .card-site { font-size: 0.76rem; color: var(--muted); margin-bottom: 4px; }
    .card-desc { font-size: 0.83rem; color: #4a5568; margin-bottom: 14px; line-height: 1.5; }
    .tags { display: flex; flex-wrap: wrap; gap: 5px; margin-bottom: 14px; }
    .tag {
      background: #eef2ff; color: #4338ca;
      font-size: 0.7rem; border-radius: 10px; padding: 2px 9px;
    }
    .apply-btn {
      display: inline-block; background: var(--navy); color: white;
      text-decoration: none; padding: 8px 20px; border-radius: 6px;
      font-size: 0.82rem; font-weight: 600; transition: background 0.2s;
    }
    .apply-btn:hover { background: var(--teal); }
    .apply-btn.linkedin { background: #0077b5; }
    .apply-btn.linkedin:hover { background: #005e93; }
    .apply-btn.indeed { background: #2164f3; }
    .apply-btn.indeed:hover { background: #1a52cc; }
    .apply-btn.glassdoor { background: #0caa41; }
    .apply-btn.glassdoor:hover { background: #0a8f36; }
    .apply-btn.zip { background: #f2733e; }
    .apply-btn.zip:hover { background: #d95e28; }
    .apply-btn.usajobs { background: #c0392b; }
    .apply-btn.usajobs:hover { background: #a93226; }
    .apply-btn.handshake { background: #e8321c; }
    .apply-btn.simply { background: #6b46c1; }

    .tip-box {
      background: #fffbeb; border: 1px solid var(--gold);
      border-radius: 10px; padding: 20px 24px; margin: 32px 0 8px;
    }
    .tip-box h3 { color: var(--navy); font-size: 1rem; margin-bottom: 12px; }
    .tip-box ol { padding-left: 18px; font-size: 0.87rem; color: var(--text); line-height: 2; }

    footer {
      text-align: center; padding: 28px; color: var(--muted); font-size: 0.8rem;
      border-top: 1px solid var(--border); margin-top: 40px;
    }

    @media (max-width: 600px) {
      header h1 { font-size: 1.4rem; }
      .stats-bar { gap: 20px; }
    }
  </style>
</head>
<body>

<header>
  <h1>CRYSTAL COLE</h1>
  <p>HR Manager | Employee Relations | Talent Strategy | Workforce Development</p>
  <p>📞 901-828-2633 &nbsp;|&nbsp; ✉️ crystalaidan@yahoo.com &nbsp;|&nbsp;
    <a href="https://linkedin.com/in/crystal-cole-mba-ab026271" style="color:#a8c0e8">LinkedIn Profile</a>
  </p>
  <div class="header-badges">
    <span class="badge">10+ Years HR Experience</span>
    <span class="badge">St. Jude Children's Research Hospital</span>
    <span class="badge">FedEx</span>
    <span class="badge">City of Memphis</span>
    <span class="badge">MBA · MHRM (2026)</span>
  </div>
</header>

<div class="stats-bar">
  <div class="stat"><strong>30+</strong><span>Curated Jobs</span></div>
  <div class="stat"><strong>$70K+</strong><span>Salary Target</span></div>
  <div class="stat"><strong>6</strong><span>Job Platforms</span></div>
  <div class="stat"><strong>Healthcare · Logistics · Public Sector</strong><span>Industry Focus</span></div>
</div>

<main>

  <!-- ──────────────────────────────────────── -->
  <div class="section-title">🏥 Healthcare HR — High Match</div>
  <div class="grid">

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Manager – Healthcare</div>
        <span class="salary-tag">$75K–$105K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">HR Manager roles at hospitals & health systems. Matches St. Jude background in employee relations, investigations, and leadership development.</div>
      <div class="tags"><span class="tag">Employee Relations</span><span class="tag">Healthcare</span><span class="tag">HRIS</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=HR+Manager+Healthcare&f_SB2=4&f_E=4%2C5" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Senior HR Business Partner – Health System</div>
        <span class="salary-tag">$80K–$110K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Strategic HR partner roles supporting clinical and non-clinical divisions. Perfect alignment with advisory experience at St. Jude.</div>
      <div class="tags"><span class="tag">HRBP</span><span class="tag">Workforce Planning</span><span class="tag">DEI</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=Senior+HR+Business+Partner+Health+System&l=&sc=0kf%3Aattr%28DSQF7%29%3B&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Employee Relations Manager – Hospital</div>
        <span class="salary-tag">$75K–$95K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Lead ER investigations and compliance in a hospital setting. Direct match for complex investigation experience at St. Jude.</div>
      <div class="tags"><span class="tag">Investigations</span><span class="tag">Compliance</span><span class="tag">Conflict Resolution</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=Employee+Relations+Manager+Hospital&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Director – Non-Profit / Research Org</div>
        <span class="salary-tag">$90K–$130K</span>
      </div>
      <div class="card-site">Glassdoor</div>
      <div class="card-desc">Director-level HR roles at research hospitals and non-profits. Crystal's St. Jude experience is a direct credential here.</div>
      <div class="tags"><span class="tag">Director</span><span class="tag">Non-Profit</span><span class="tag">Strategy</span></div>
      <a class="apply-btn glassdoor" href="https://www.glassdoor.com/Job/jobs.htm?suggestCount=0&suggestChosen=false&clickSource=searchBtn&typedKeyword=HR+Director+Healthcare&sc.keyword=HR+Director+Healthcare&locT=N&locId=1&jobType=&salary=70000" target="_blank">Search on Glassdoor →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Talent Acquisition Manager – Healthcare</div>
        <span class="salary-tag">$72K–$95K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Lead full-cycle recruitment for clinical/admin roles. Aligns with 30% time-to-fill reduction accomplishment at Parker Chelsea.</div>
      <div class="tags"><span class="tag">Recruiting</span><span class="tag">Full-Cycle</span><span class="tag">Onboarding</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=Talent+Acquisition+Manager+Healthcare&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Workforce Development Manager – Health</div>
        <span class="salary-tag">$70K–$90K</span>
      </div>
      <div class="card-site">ZipRecruiter</div>
      <div class="card-desc">Lead L&D and workforce programs at health organizations. Matches co-leading leadership dev program impacting 200+ employees.</div>
      <div class="tags"><span class="tag">L&D</span><span class="tag">Training</span><span class="tag">Leadership Dev</span></div>
      <a class="apply-btn zip" href="https://www.ziprecruiter.com/jobs-search?search=Workforce+Development+Manager+Healthcare&salary_min=70000" target="_blank">Search on ZipRecruiter →</a>
    </div>

  </div>

  <!-- ──────────────────────────────────────── -->
  <div class="section-title">🏛️ Government & Public Sector HR</div>
  <div class="grid">

    <div class="card">
      <div class="card-top">
        <div class="card-title">Human Resources Manager – Federal Gov</div>
        <span class="salary-tag">$78K–$120K</span>
      </div>
      <div class="card-site">USAJobs.gov</div>
      <div class="card-desc">Federal HR Manager positions (GS-12/13). City of Memphis government background is a major differentiator for federal roles.</div>
      <div class="tags"><span class="tag">Federal</span><span class="tag">GS-12/13</span><span class="tag">Public Sector</span></div>
      <a class="apply-btn usajobs" href="https://www.usajobs.gov/Search/Results?k=human+resources+manager&p=1&salary=70000" target="_blank">Search on USAJobs →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Specialist – Employee Relations (Federal)</div>
        <span class="salary-tag">$70K–$95K</span>
      </div>
      <div class="card-site">USAJobs.gov</div>
      <div class="card-desc">Employee relations specialist roles at federal agencies. Directly matches investigation and compliance expertise.</div>
      <div class="tags"><span class="tag">Federal ER</span><span class="tag">Compliance</span><span class="tag">GS-11/12</span></div>
      <a class="apply-btn usajobs" href="https://www.usajobs.gov/Search/Results?k=employee+relations+specialist&p=1&salary=70000" target="_blank">Search on USAJobs →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Manager – City/County Government</div>
        <span class="salary-tag">$70K–$95K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Municipal HR management roles. City of Memphis background gives a direct competitive edge for local government positions.</div>
      <div class="tags"><span class="tag">Municipal</span><span class="tag">Public Safety HR</span><span class="tag">Payroll Audit</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=HR+Manager+City+Government&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Director – State Agency</div>
        <span class="salary-tag">$85K–$115K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Director-level HR at state government agencies. Workforce analytics and policy administration experience is highly valued.</div>
      <div class="tags"><span class="tag">State Gov</span><span class="tag">Director</span><span class="tag">Policy</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=HR+Director+State+Government&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">People Operations Manager – Public Sector</div>
        <span class="salary-tag">$72K–$95K</span>
      </div>
      <div class="card-site">ZipRecruiter</div>
      <div class="card-desc">People Ops roles at public institutions and universities. Strong alignment with DEI, engagement, and workforce strategy expertise.</div>
      <div class="tags"><span class="tag">DEI</span><span class="tag">Engagement</span><span class="tag">Operations</span></div>
      <a class="apply-btn zip" href="https://www.ziprecruiter.com/jobs-search?search=People+Operations+Manager+Public+Sector&salary_min=70000" target="_blank">Search on ZipRecruiter →</a>
    </div>

  </div>

  <!-- ──────────────────────────────────────── -->
  <div class="section-title">📦 Logistics, Supply Chain & Corporate HR</div>
  <div class="grid">

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Manager – Logistics / Distribution</div>
        <span class="salary-tag">$75K–$100K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">HR management at logistics and distribution companies. FedEx background directly validates large-scale operations HR experience.</div>
      <div class="tags"><span class="tag">Logistics</span><span class="tag">Operations HR</span><span class="tag">FedEx-type</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=HR+Manager+Logistics+Distribution&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Senior HR Generalist – Manufacturing</div>
        <span class="salary-tag">$72K–$90K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Senior generalist supporting manufacturing plants. HRIS, payroll compliance, and workforce analytics are key requirements.</div>
      <div class="tags"><span class="tag">Manufacturing</span><span class="tag">HRIS</span><span class="tag">Generalist</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=Senior+HR+Generalist+Manufacturing&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Business Partner – Supply Chain</div>
        <span class="salary-tag">$80K–$105K</span>
      </div>
      <div class="card-site">Glassdoor</div>
      <div class="card-desc">HRBP embedded in supply chain orgs. Matches multi-business-unit HR support delivered at FedEx.</div>
      <div class="tags"><span class="tag">HRBP</span><span class="tag">Supply Chain</span><span class="tag">Workforce Planning</span></div>
      <a class="apply-btn glassdoor" href="https://www.glassdoor.com/Job/jobs.htm?suggestChosen=false&clickSource=searchBtn&sc.keyword=HR+Business+Partner+Supply+Chain&salary=70000" target="_blank">Search on Glassdoor →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Employee Relations Specialist – Corporate</div>
        <span class="salary-tag">$70K–$88K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Corporate ER specialist handling investigations and compliance. A strong fit given 25% improvement in ER case resolution.</div>
      <div class="tags"><span class="tag">Corporate ER</span><span class="tag">Investigations</span><span class="tag">Compliance</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=Employee+Relations+Specialist+Corporate&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Operations Manager – Fortune 500</div>
        <span class="salary-tag">$85K–$115K</span>
      </div>
      <div class="card-site">ZipRecruiter</div>
      <div class="card-desc">Oversee HR ops at large corporate orgs. Multi-site HRIS implementation, payroll, and compliance experience is a direct match.</div>
      <div class="tags"><span class="tag">HR Ops</span><span class="tag">HRIS</span><span class="tag">Kronos/Payroll</span></div>
      <a class="apply-btn zip" href="https://www.ziprecruiter.com/jobs-search?search=HR+Operations+Manager&salary_min=70000" target="_blank">Search on ZipRecruiter →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Talent Management Specialist – Corporate</div>
        <span class="salary-tag">$72K–$92K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Drive performance management, succession planning, and talent strategy. Aligns with leadership development work impacting 200+ employees.</div>
      <div class="tags"><span class="tag">Talent Management</span><span class="tag">Performance Mgmt</span><span class="tag">Succession</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=Talent+Management+Specialist&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

  </div>

  <!-- ──────────────────────────────────────── -->
  <div class="section-title">🎓 Education, University & Nonprofit HR</div>
  <div class="grid">

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Manager – University / Higher Ed</div>
        <span class="salary-tag">$72K–$95K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">HR management at colleges and universities. DEI expertise, L&D facilitation, and workforce analytics are highly sought here.</div>
      <div class="tags"><span class="tag">Higher Ed</span><span class="tag">DEI</span><span class="tag">L&D</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=HR+Manager+University&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Director – Nonprofit Organization</div>
        <span class="salary-tag">$75K–$100K</span>
      </div>
      <div class="card-site">Idealist.org</div>
      <div class="card-desc">Lead all HR functions at mission-driven nonprofits. Deep match with St. Jude nonprofit experience and DEI leadership.</div>
      <div class="tags"><span class="tag">Nonprofit</span><span class="tag">Director</span><span class="tag">Mission-Driven</span></div>
      <a class="apply-btn" style="background:#c0392b" href="https://www.idealist.org/en/jobs?q=HR+Director&type=JOB&salary_floor=70000" target="_blank">Search on Idealist →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">People & Culture Manager – Nonprofit</div>
        <span class="salary-tag">$70K–$90K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Culture, engagement and HR operations at nonprofits. Engagement initiatives contributing to 15% retention improvement is a perfect talking point.</div>
      <div class="tags"><span class="tag">Culture</span><span class="tag">Engagement</span><span class="tag">Retention</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=People+Culture+Manager+Nonprofit&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Training & Organizational Development Manager</div>
        <span class="salary-tag">$72K–$95K</span>
      </div>
      <div class="card-site">Glassdoor</div>
      <div class="card-desc">Lead OD and L&D strategy. Crystal's leadership development program design experience at St. Jude is a direct qualification.</div>
      <div class="tags"><span class="tag">OD</span><span class="tag">Training</span><span class="tag">Leadership Dev</span></div>
      <a class="apply-btn glassdoor" href="https://www.glassdoor.com/Job/jobs.htm?sc.keyword=Training+Organizational+Development+Manager&salary=70000" target="_blank">Search on Glassdoor →</a>
    </div>

  </div>

  <!-- ──────────────────────────────────────── -->
  <div class="section-title">🌟 DEI, Engagement & People Strategy</div>
  <div class="grid">

    <div class="card">
      <div class="card-top">
        <div class="card-title">DEI Program Manager</div>
        <span class="salary-tag">$75K–$105K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Lead diversity, equity & inclusion initiatives. Aligns with DEI training facilitation that reinforced organizational values at St. Jude.</div>
      <div class="tags"><span class="tag">DEI</span><span class="tag">Program Mgmt</span><span class="tag">Culture</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=DEI+Program+Manager&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Employee Engagement Manager</div>
        <span class="salary-tag">$72K–$95K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Own engagement strategy, surveys, recognition programs and retention initiatives. The 15% retention improvement stat is a key selling point.</div>
      <div class="tags"><span class="tag">Engagement</span><span class="tag">Recognition</span><span class="tag">Retention</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=Employee+Engagement+Manager&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Analytics Manager / Workforce Analyst</div>
        <span class="salary-tag">$78K–$108K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Data-driven HR roles using dashboards and workforce analytics. Matches regular use of HR analytics and workforce dashboards to guide decisions.</div>
      <div class="tags"><span class="tag">Analytics</span><span class="tag">Dashboards</span><span class="tag">Data-Driven</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=HR+Analytics+Manager&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HRIS Manager / HR Systems Manager</div>
        <span class="salary-tag">$80K–$110K</span>
      </div>
      <div class="card-site">ZipRecruiter</div>
      <div class="card-desc">Manage HR technology platforms. HRIS transition from Stromberg to Kronos is a strong credential for this role type.</div>
      <div class="tags"><span class="tag">HRIS</span><span class="tag">Kronos</span><span class="tag">Systems</span></div>
      <a class="apply-btn zip" href="https://www.ziprecruiter.com/jobs-search?search=HRIS+Manager&salary_min=70000" target="_blank">Search on ZipRecruiter →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">Change Management Specialist – HR</div>
        <span class="salary-tag">$75K–$100K</span>
      </div>
      <div class="card-site">Glassdoor</div>
      <div class="card-desc">Support organizational change initiatives using structured HR frameworks. Matches change management expertise across healthcare and logistics.</div>
      <div class="tags"><span class="tag">Change Mgmt</span><span class="tag">OD</span><span class="tag">Strategy</span></div>
      <a class="apply-btn glassdoor" href="https://www.glassdoor.com/Job/jobs.htm?sc.keyword=Change+Management+Specialist+HR&salary=70000" target="_blank">Search on Glassdoor →</a>
    </div>

  </div>

  <!-- ──────────────────────────────────────── -->
  <div class="section-title">🏢 Recruiter, Talent & HR Generalist Roles</div>
  <div class="grid">

    <div class="card">
      <div class="card-top">
        <div class="card-title">Talent Acquisition Lead / Senior Recruiter</div>
        <span class="salary-tag">$70K–$95K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Lead full-cycle recruiting. The 30% time-to-fill reduction at Parker Chelsea is a compelling accomplishment for these roles.</div>
      <div class="tags"><span class="tag">Full-Cycle</span><span class="tag">Recruiting</span><span class="tag">ATS</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=Senior+Recruiter+Talent+Acquisition+Lead&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Generalist III / Senior Generalist</div>
        <span class="salary-tag">$70K–$90K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Senior generalist covering all HR functions. Strong for orgs that want one experienced person to own employee relations, compliance, and talent.</div>
      <div class="tags"><span class="tag">Generalist</span><span class="tag">All HR</span><span class="tag">Compliance</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=Senior+HR+Generalist&salstart=70000" target="_blank">Search on Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Manager – Remote / Hybrid</div>
        <span class="salary-tag">$75K–$100K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Remote and hybrid HR Manager openings nationwide. Opens up opportunities well beyond Memphis metro.</div>
      <div class="tags"><span class="tag">Remote</span><span class="tag">Hybrid</span><span class="tag">Flexible</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=HR+Manager&f_WT=2%2C3&f_SB2=4" target="_blank">Search Remote on LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Manager – Memphis Metro Area</div>
        <span class="salary-tag">$70K–$95K</span>
      </div>
      <div class="card-site">Indeed</div>
      <div class="card-desc">Local HR Manager openings in the Memphis, TN area. Local network and market knowledge give Crystal a distinct advantage.</div>
      <div class="tags"><span class="tag">Memphis</span><span class="tag">Local</span><span class="tag">On-Site</span></div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=HR+Manager&l=Memphis%2C+TN&salstart=70000" target="_blank">Search Memphis Jobs →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">HR Compliance Manager</div>
        <span class="salary-tag">$75K–$100K</span>
      </div>
      <div class="card-site">ZipRecruiter</div>
      <div class="card-desc">Ensure HR regulatory and legal compliance across the organization. Matches compliance experience at FedEx and City of Memphis.</div>
      <div class="tags"><span class="tag">Compliance</span><span class="tag">Policy</span><span class="tag">Risk</span></div>
      <a class="apply-btn zip" href="https://www.ziprecruiter.com/jobs-search?search=HR+Compliance+Manager&salary_min=70000" target="_blank">Search on ZipRecruiter →</a>
    </div>

    <div class="card">
      <div class="card-top">
        <div class="card-title">People Operations Director – Startup/Tech</div>
        <span class="salary-tag">$90K–$130K</span>
      </div>
      <div class="card-site">LinkedIn Jobs</div>
      <div class="card-desc">Build and lead HR from the ground up at growth-stage companies. MBA + MHRM credentials and breadth of experience are a strong pitch.</div>
      <div class="tags"><span class="tag">Startup</span><span class="tag">Director</span><span class="tag">MBA</span></div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=People+Operations+Director&f_SB2=4" target="_blank">Search on LinkedIn →</a>
    </div>

  </div>

  <!-- ──────────────────────────────────────── -->
  <div class="section-title">🔍 Broad Search Links — All Platforms</div>
  <div class="grid">

    <div class="card">
      <div class="card-top"><div class="card-title">LinkedIn — All HR $70K+ Jobs</div><span class="salary-tag">$70K+</span></div>
      <div class="card-desc">Full LinkedIn job feed filtered to HR roles at $70K+ salary range with experience level filters applied.</div>
      <a class="apply-btn linkedin" href="https://www.linkedin.com/jobs/search/?keywords=Human+Resources+Manager&f_SB2=4&f_E=4%2C5" target="_blank">Open LinkedIn →</a>
    </div>

    <div class="card">
      <div class="card-top"><div class="card-title">Indeed — HR Manager $70K+</div><span class="salary-tag">$70K+</span></div>
      <div class="card-desc">Indeed's full HR Manager job board filtered by salary. Update location as needed for remote vs. local.</div>
      <a class="apply-btn indeed" href="https://www.indeed.com/jobs?q=HR+Manager&salstart=70000" target="_blank">Open Indeed →</a>
    </div>

    <div class="card">
      <div class="card-top"><div class="card-title">Glassdoor — HR Director/Manager</div><span class="salary-tag">$70K+</span></div>
      <div class="card-desc">Glassdoor HR management roles with company reviews and salary data to help evaluate offers.</div>
      <a class="apply-btn glassdoor" href="https://www.glassdoor.com/Job/jobs.htm?sc.keyword=HR+Manager&salary=70000" target="_blank">Open Glassdoor →</a>
    </div>

    <div class="card">
      <div class="card-top"><div class="card-title">ZipRecruiter — HR Roles $70K+</div><span class="salary-tag">$70K+</span></div>
      <div class="card-desc">ZipRecruiter aggregates jobs from many boards. Good for catching postings not on LinkedIn or Indeed.</div>
      <a class="apply-btn zip" href="https://www.ziprecruiter.com/jobs-search?search=Human+Resources+Manager&salary_min=70000" target="_blank">Open ZipRecruiter →</a>
    </div>

    <div class="card">
      <div class="card-top"><div class="card-title">USAJobs — Federal HR Positions</div><span class="salary-tag">$70K+</span></div>
      <div class="card-desc">All open federal HR positions. City of Memphis public sector background strengthens federal applications significantly.</div>
      <a class="apply-btn usajobs" href="https://www.usajobs.gov/Search/Results?k=human+resources&p=1" target="_blank">Open USAJobs →</a>
    </div>

    <div class="card">
      <div class="card-top"><div class="card-title">Simply Hired — HR Manager</div><span class="salary-tag">$70K+</span></div>
      <div class="card-desc">Simply Hired surfaces additional postings including small and mid-size employers. Good for unique finds.</div>
      <a class="apply-btn simply" href="https://www.simplyhired.com/search?q=HR+Manager&l=&fdb=70000" target="_blank">Open Simply Hired →</a>
    </div>

  </div>

  <!-- ──────────────────────────────────────── -->
  <div class="tip-box">
    <h3>📋 How to Host This Page on GitHub (Free)</h3>
    <ol>
      <li>Go to <strong>github.com</strong> and sign in (or create a free account)</li>
      <li>Click <strong>+ → New repository</strong> — name it <code>crystal-cole-jobs</code> (or anything you like)</li>
      <li>Check <strong>"Add a README file"</strong>, then click <strong>Create repository</strong></li>
      <li>Click <strong>Add file → Upload files</strong> and upload this <code>index.html</code> file</li>
      <li>Go to <strong>Settings → Pages → Source</strong> — set branch to <code>main</code> and click Save</li>
      <li>Your live link will be: <code>https://YOUR-USERNAME.github.io/crystal-cole-jobs/</code></li>
      <li>Share that link on your resume, LinkedIn, or in job applications!</li>
    </ol>
  </div>

</main>

<footer>
  Built for Crystal Cole · HR Manager | MBA · 10+ Years Experience<br>
  crystalaidan@yahoo.com · 901-828-2633 ·
  <a href="https://linkedin.com/in/crystal-cole-mba-ab026271" style="color:var(--teal)">LinkedIn Profile</a>
</footer>

</body>
</html>
