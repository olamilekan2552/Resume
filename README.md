<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olalekan Oluwabunmi Olaleye | Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #1a2a6c;
            --secondary: #2980b9;
            --accent: #f1c40f;
            --text: #2c3e50;
            --bg: #f4f7f6;
            --white: #ffffff;
        }

        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background: var(--bg);
            color: var(--text);
            line-height: 1.6;
        }

        nav {
            background: var(--primary);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        nav a {
            color: white;
            margin: 0 12px;
            text-decoration: none;
            font-weight: 500;
            font-size: 0.9rem;
            transition: color .3s;
        }

        nav a:hover { color: var(--accent); }

        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
            letter-spacing: -1px;
        }

        header p {
            font-size: 1.1rem;
            opacity: 0.9;
            max-width: 800px;
            margin: 20px auto;
        }

        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 30px;
            color: var(--primary);
            position: relative;
        }

        h2::after {
            content: '';
            width: 50px;
            height: 4px;
            background: var(--accent);
            display: block;
            margin: 10px auto;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: var(--white);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: all .3s ease;
            border-top: 5px solid var(--secondary);
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        .card strong {
            display: block;
            color: var(--primary);
            font-size: 1.1rem;
            margin-bottom: 10px;
        }

        .pub-list { list-style: none; padding: 0; }
        .pub-list li {
            background: white;
            margin-bottom: 15px;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid var(--accent);
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .project-link {
            display: inline-block;
            background: var(--secondary);
            color: white;
            padding: 10px 20px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
            margin-top: 10px;
        }

        .project-link:hover { background: var(--primary); }

        footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        .social-icons a {
            color: white;
            font-size: 1.8rem;
            margin: 0 15px;
        }
    </style>
</head>
<body>

    <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Experience</a>
        <a href="#grants">Grants & Awards</a>
        <a href="#certifications">Certifications</a>
        <a href="#publications">Publications</a>
        <a href="#contact">Contact</a>
    </nav>

    <header>
        <h1>Olalekan Oluwabunmi Olaleye 👋</h1>
        <p>Business Analyst | Economist | Researcher | PhD Candidate | Financial & Data Analyst</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p style="text-align: center; font-size: 1.1rem;">
            I am a focused, efficient, and result-oriented economist and researcher with excellent skills in teaching, data analytics, econometrics, financial analysis, policy evaluation, research design, and communication. I have a strong passion for contributing to impactful research initiatives that address real-world challenges through data-driven solutions.
        </p>
    </section>
<section id="education">
        <h2>📈 Education</h2>
        <div class="grid">
            <div class="card">
                <strong>DOCTOR OF PHILOSOPHY (PHD) IN ECONOMICS</strong>
                Universiti Putra Malaysia (2024-2027).
            </div>
            <div class="card">
                <strong>POSTGRADUATE DIPLOMA IN EDUCATION AND TEACHING</strong>
                Asian College of Teachers (2024-2025).
            </div>
            <div class="card">
                <strong>MASTER OF BUSINESS ADMINISTRATION (MBA)</strong>
                National Institute of Business Management (2024-2025).
            </div>
            <div class="card">
                <strong>MASTER OF SCIENCE IN ECONOMICS</strong>
                University of Abuja (2018-2021).
            </div>
            <div class="card">
                <strong>BACHELOR OF SCIENCE IN ECONOMICS </strong>
                University of Abuja (2012-2017).
            </div>
        </div>
    </section>
    <section id="skills">
        <h2>🛠 Technical Skills</h2>
        <div class="grid">
            <div class="card">
                <strong>Econometrics</strong>
                Stata, SPSS, Eviews, SmartPLS, Panel Data Analysis.
            </div>
            <div class="card">
                <strong>Data Analytics</strong>
                Data Cleaning, Trend Analysis, Descriptive & Inferential Statistics.
            </div>
            <div class="card">
                <strong>Financial Analysis</strong>
                Portfolio and Risk Analysis.
            </div>
            <div class="card">
                <strong>Tools</strong>
                Advanced Excel Dashboarding (Pivot/Power Query), GitHub for Research.
            </div>
        </div>
    </section>

    <section id="grants">
        <h2>🏆 Honours, Awards & Grants</h2>
        <div class="grid">
            <div class="card" style="border-top-color: var(--accent);">
                <i class="fas fa-award" style="color: var(--accent); margin-bottom: 10px;"></i>
                <strong>PTDF Scholarship (2023/2024)</strong>
                Postgraduate Scholarship (Doctorate Level) awarded by the Petroleum Technology Development Fund.
            </div>
            <div class="card" style="border-top-color: var(--accent);">
                <i class="fas fa-hand-holding-usd" style="color: var(--accent); margin-bottom: 10px;"></i>
                <strong>TETFund Research Grant (2023-2024)</strong>
                Co-Researcher: "The Economic Efficiency of Android Phone-Enabled Modems vs Standard Modems in Nigeria."
            </div>
        </div>
    </section>

    <section id="experience">
        <h2>Professional Experience</h2>
        <div class="card" style="margin-bottom: 20px;">
            <strong>Adjunct Economics Lecturer | University of Abuja (2019 – 2024)</strong>
            <p>Supervised macroeconomics and environmental research, Delivered lectures on econometrics, international finance, and economic systems, Guided use of STATA/SPSS, improving research quality by 15%.</p>
        </div>
        <div class="card">
            <strong>Research Fellow | Epitome Resources Consulting Network Ltd. (2016 – Present)</strong>
            <p>Conducting applied research, designing econometric forecasting models, and producing high-level data visualisations.</p>
        </div>
    </section>
    <section id="certifications">
    <h2>Certifications</h2>
    <div class="certifications">
      <ul>
        <li><strong>Project Management Professional (PMP)</strong> – British Project Academy, UK (2017)</li>
        <li><strong>CFA Institute</strong> – Financial Analysis Fundamentals & Modelling Series (2022)</li>
        <li><strong>Managing Successful Field Research</strong> – World Bank Group (2024)</li>
        <li><strong>Certificate in Data Analytics</strong> – Orbal Digital Academy (2025)</li>
        <li><strong>ACCA</strong> – In Progress</li>
      </ul>
      </div>

    <section id="publications">
        <h2>Selected Publications</h2>
        <ul class="pub-list">
            <li>Olaleye, O.O., Rosland, A., Alao, R.O., & Issa, S.O. (2025). Asymmetric Responses of Industrial Output to Oil Price Volatility: A GARCH Approach in East Asia-Pacific Developing Countries.https://doi.org/10.55493/5049.v12i2.5495. <em>Energy Economics Letters</em>.</li>
        <li>Olasode, T., Eke, C. I & Olaleye, O. O (2022), Has economic growth reduced poverty in Nigeria? A critical analysis of the last two decades. https://doi.org/10.20414/jed.v4i2.5506. <em>Journal of Enterprise and Development (JED) Vol. 4, No.2, December 2022</em>.</li>
        <li>OLALEYE, O. O. (2022). Impact of Foreign Capital Inflow on a Selected Macroeconomic Variable in Nigeria 1990-2021.https://doi.org/10.5281/zenodo.6947149. <em>Indiana Journal of Humanities & Social Sciences, 3(7), 25–33.</em>.</li>
        <li>Olaleye, O.O. et al. (2021). Impact of Fiscal Policy on Economic Performance in Nigeria. <em>Abuja Journal of Economics</em>.</li>
        <li>Olaleye, O.O. et al. (2023). Public Domestic Debts & Private Investments in Nigeria. <em>IJEBER</em>.</li>
        </ul>

        <div class="card" style="margin-top: 40px; border-top: 5px solid var(--accent); text-align: center;">
            <h3>📈 Featured Research Project</h3>
            <p><strong>Health-Expectancy-Macro-Analysis:</strong> Replication study on HALE and Oil Consumption using robust panel data diagnostics.</p>
            <a href="https://github.com/olamilekan2552/Health-Expectancy-Macro-Analysis" class="project-link">View Project on GitHub</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <div style="text-align: center;">
            <p><i class="fas fa-envelope"></i> lekinzino@gmail.com</p>
            <p><i class="fas fa-phone"></i> +601117940546 | +2347039124372</p>
            <div class="social-icons" style="margin-top: 20px;">
                <a href="https://www.linkedin.com/in/olalekan-olaleye-b85651a7/"><i class="fab fa-linkedin" style="color:#0077b5"></i></a>
                <a href="https://github.com/olamilekan2552"><i class="fab fa-github" style="color:#333"></i></a>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 Olalekan Oluwabunmi Olaleye </p>
    </footer>

</body>
</html>
