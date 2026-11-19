<p align="center">
  <a href="https://github.com/wendy-160">
    <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=9791F1&fontSize=54&height=90&width=602&text=Hello!%20I'm%20Wendy" alt="Hello! I&#39;m Wendy" />
  </a>
</p>

Computer science graduate who builds data pipelines, SQL databases, and analysis for healthcare data. I'm interested in healthcare analytics, health IT, and data-focused roles where data quality, privacy, and compliance really matter.

⭐️ B.S. Computer Science, minor in Mathematics, [University of Houston]

## Featured projects 

#### [HIPAA Compliance Gap Analysis](https://github.com/wendy-160/HIPAA-Compliance-Gap-Analysis)
Analysis of 6,029 HHS OCR breaches (2013-2026) to find which HIPAA
safeguard failures put patients at greatest risk.
- **Technical safeguard failures caused ~60% of breaches but ~92% of
  all individuals affected**, making them the dominant source of impact.
- Hacking/IT incidents rose from 10% of breaches in 2013 to ~80% in
  2022-2024, while physical breaches (theft, loss) declined steadily.
- Breaches involving business associates had a larger median size
  (4,500 vs. 3,859 individuals, p < 0.001).
- Three-notebook pipeline: cleaning → feature engineering → analysis
- `Python` `pandas` `matplotlib` `SciPy` `Jupyter`

#### [Diabetes 130-US Hospitals Outcome Analysis](https://github.com/wendy-160/Hospital-Readmission-Analysis)
SQL- and BI-first reporting pipeline on 99,340 diabetic inpatient
encounters across 130 US hospitals (1999-2008), built to mirror how a
hospital quality team would track readmissions.
- **Discharge destination and prior-year utilization were the strongest
  readmission signals:** 30-day readmission ranged from 9.3% (discharged
  home) to 36.7% (psychiatric facility), and from 8.3% (no prior visits)
  to 26.0% (heavy prior utilization). Diagnosis mattered far less.
- A transparent, rule-based SQL risk score separated encounters into
  7.9% / 13.9% / 18.7% readmission tiers.
- Python ETL → normalized MySQL schema → SQL views (CTEs, window
  functions) → four-page Power BI dashboard
- `Python` `MySQL` `SQL` `Power BI`

#### [Full Stack Clinic Management System](https://github.com/wendy-160/Full-Stack-Clinic-Management-System)
Team project (5 people, Team lead): a full-stack web app and
relational database for a multi-office healthcare provider with patient,
doctor, and admin roles.
- Role-based access for three user types, covering appointments,
  referrals, prescriptions, medical tests, records, and billing
- **Business rules enforced in MySQL triggers:** max 3 active referrals
  per patient, 90-day referral expiration, and a 10-appointment daily
  cap per doctor
- Admin reports for clinic profitability, patient visit frequency, and
  doctor efficiency
- `React` `Node.js` `MySQL` `HTML` `CSS` `JavaScript`
