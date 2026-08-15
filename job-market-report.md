# Job Market Report — Prathamesh Deshmukh (@Ped20)

**Scope:** Jobs, internships, and project/fellowship applications worldwide + India that accept a **master's degree in any field** and require **R programming + research/statistical skills**.

**Date of research:** 15 August 2026
**Profile analysed from:** `github.com/Ped20` (public profile + 5 project repos)

---

## 1. What your profile currently says to a recruiter

| Signal | What a recruiter sees |
|---|---|
| Domain | Plant breeding / genetics — **Abiotic Stress Breeder, Trait Selection, Reproducible Pipelines** (self-described) |
| Tools | R, RStudio, tidyverse, ggplot2, agricolae, factoextra, Shiny, Git/GitHub, Markdown, LaTeX, command line |
| Methods | EDA → ANOVA + Duncan post-hoc → linear regression → K-Means clustering + PCA → Shiny dashboard |
| Projects | **5 repos that are actually ONE project** (100 plant genotypes) split into 5 "steps" |
| Location | Pune, India |

**The honest read (this is the single biggest thing to fix):** your GitHub shows a *good statistical toolkit* (EDA, ANOVA, regression, clustering/PCA, interactive dashboard) applied to a *relevant domain* (plant breeding) — which is genuinely a niche and hireable combination. But the portfolio is **under-presented**:

1. **One dataset, one workflow, five repos.** An employer sees "5 projects" but they are one analysis pipeline re-branded 5 times. That's thinner than it looks.
2. **The actual `.R` code is buried in `results/` subfolders**, not at the repo root. Most hiring managers only look at the repo landing page — they currently see a README and a `results` folder, not code.
3. **No reproducibility files** — no data file, no `renv.lock`/`sessionInfo`, no run instructions, no LICENSE, no `.Rproj`.
4. **No live dashboard.** The Shiny app exists only as a PNG screenshot. A clickable deployed app is a 10× stronger signal.

This is all **fixable in a weekend** and matters more than adding new skills. Details in §5.

---

## 2. Where your exact skill set is in demand (market map)

Your combination of **R + statistics + plant-breeding domain** sits at the intersection of four hiring markets. Ranked by fit:

### A. Plant breeding / quantitative genetics — India & global (BEST fit)
This is your home turf. R is the dominant tool, and "M.Sc. + statistical software" is the standard entry credential.

- **CGIAR research institutes** (the global agricultural research network):
  - **ICRISAT** (Patancheru, Hyderabad) — regularly posts *Associate Scientist (Data/Analytical Support)* and *Data Scientist* roles asking for R, SAS, ASReml-R, experimental design, mixed models, MET analysis. Note: "Associate Scientist" often asks PhD, but **Research Assistant / Research Associate / Scientific Officer / data-support roles take M.Sc.**
  - **CIMMYT** (Mexico + Africa) — *Assistant Research Associate* explicitly lists **"Masters' Degree in Plant Breeding or Crop Science"** and wants statistics + experimental design + statistical software (SAS, META-R, AGD-R, ADEL-R).
  - **IRRI** (Philippines, + India/ISARC Varanasi), **ICARDA**, **CIP**, **IFPRI** (New Delhi office) — data/research analyst roles.
- **Seed companies**: Bayer CropScience, Corteva (now spinning off its seed business as "Vylor"), Syngenta, Limagrain, Sakata, **Mahyco**, Advanta (Hyderabad — okra breeding), Nuziveedu, Kaveri. Entry roles: *Research Associate, Junior Breeder/Associate Breeder, Data Analyst, Trial Data Analyst*.
- **ICAR institutes & agricultural universities (India)** — **JRF/SRF** positions (₹37,000–42,000/month + HRA) explicitly accept **Master's degree** and list "statistical analysis" as desirable. Examples active in 2026: ICAR-IARI, ICAR-CIRCOT (Mumbai), ICAR-IVRI. This is the single highest-probability *paid* route for you right now.

### B. Biostatistics / statistical programming — pharma & CRO (STRONG, needs SAS add-on)
Master's degree is the standard entry credential; R is heavily listed. The catch: **SAS is usually mandatory alongside R**.

- **India**: ICON (Bengaluru — "Junior Statistician / Biostatistician I", lists M.Sc Statistics/Biostatistics + R), CPVIA (Hyderabad — Statistical Programmer/Biostatistician, 0–12 yrs), **ClinChoice** (Bengaluru — *Intern Statistical Programmer/Analyst*, freshers, ₹2.5–4 LPA), Parexel, IQVIA, Cytel, Novartis/Syneos.
- **Global/remote**: pharmaceutical biostatistics internships (Pfizer, Novartis, J&J, Eli Lilly — note many **internships are PhD-only**), CROs (Everest, BeiGene). Remote bioinformatics/biostat roles exist but skew senior or US-citizen.

### C. General data science / analytics — India & global (WEAKEST fit, needs Python/SQL)
Large hiring volume (23k+ data-science jobs in India) but the **gatekeeper stack is Python + SQL + ML**, not R-only. Examples: Honeywell, Citi, American Express, United Airlines, Amgen (Hyderabad — *Associate Data Science*, lists R **and** Git/SQL/ML). Your R helps; you won't clear the bar without Python/SQL/ML.

### D. Research / policy / international development — global (MODERATE, needs econometrics)
Organisations that hire master's-level "Research Analyst / Research Assistant" with R/Stata: **IFPRI, World Bank, ECB (Research Analysts), RAND Europe, Brattle Group, CGD Europe, ICRISAT/ILRI**. These value your statistical rigour but expect **Stata/econometrics** and often survey-data experience (NFHS/NSSO/DHS).

---

## 3. Where to actually apply (concrete portals + live leads)

**Job boards to check weekly (no scraping needed — these aggregate everything):**
- CGIAR careers hub — `cgiar.org/news-events/vacancy` (filters all 14 centres)
- `seedquest.com/career` — global seed-industry jobs (free, niche)
- ICAR institutes' individual "News/Recruitment" pages — `icar.org.in`
- `impactpool.org` — UN/CGIAR/development sector
- `r-users.com/job-category/` — R-specific jobs
- India: Naukri, LinkedIn, `freejobalert.com` (ICAR/CRO postings), `pharmabharat.com` / `pharmastuff.org` (CRO biostat)
- US/global: Indeed, ZipRecruiter, `compbiojobs.com` (bioinformatics/biostat), USAJobs (Research Geneticist — note most USDA needs US citizenship)

**Live leads found during research (Aug 2026):**
| Role | Organisation | Location | Type | Fit |
|---|---|---|---|---|
| Junior Statistician / Biostatistician I | ICON plc | Bengaluru | Job | High (needs SAS too) |
| Intern – Statistical Programmer/Analyst | ClinChoice | Bengaluru | Internship | High (fresher, R/SAS) |
| Statistical Programmer / Biostatistician | CPVIA | Hyderabad | Job (0–12 yr) | High |
| Associate Scientist – Data/Analytical Support | ICRISAT | Hyderabad | Job | High (PhD preferred → target RA tier) |
| Assistant Research Associate (M.Sc. Plant Breeding) | CIMMYT | Kenya/Africa | Job | High (domain match) |
| ICAR-IARI / CIRCOT / IVRI JRF | ICAR | Mumbai/Delhi | Fellowship | **Highest-probability paid** (M.Sc., ₹37–42k/mo) |
| ICRISAT Study-cum-Research Program | ICRISAT | Hyderabad | Internship (93 slots) | High (M.Sc. eligible) |
| ICAR internship | ICAR institutes | India | Internship | High (M.Sc. any semester) |
| CBRAIN internship (biostat/bioinfo) | IISc Bengaluru | Bengaluru | Internship | Moderate (M.Sc. final yr, R/Python) |
| Research Assistant | IFPRI | New Delhi | Job | Moderate (wants Stata) |
| Data analyst & crop modeller | Univ. of Missouri | USA | Job | Moderate (R, but US-based) |
| Research Analyst | ECB / Brattle / RAND Europe | EU/UK | Job | Moderate (econometrics, work-permit) |

> **Reality check on "worldwide":** most *global* R/research roles require either a PhD, several years' experience, or **work-authorisation in the host country** (US/EU). Your realistic worldwide entries today are (1) **CGIAR/development roles** (which sponsor visas for nationals of member countries) and (2) **remote internships/fellowships**. In India, you face no such barrier — prioritise India first.

---

## 4. Probability of getting hired — an honest, calibrated estimate

These are directional estimates (not guarantees), based on your *current* portfolio vs. what postings actually ask for. Base rate in every technical market is low (a few % per application); these numbers assume **targeted, well-presented applications**.

| Role category | Region | Probability (90 days, active applying) | Key driver |
|---|---|---|---|
| **ICAR JRF / SRF** (statistical analysis, plant breeding projects) | India | **Moderate-High (35–50%)** | M.Sc. eligibility + domain match + R; low competition vs. generic roles |
| **Agricultural research assistant / data analyst** (seed cos, CGIAR RA tier) | India | **Moderate (25–40%)** | Strong domain fit; thin portfolio is the drag |
| **CRO statistical programmer / biostat I** (fresher) | India | **Moderate (20–35%)** *if you add SAS*; ~10% without | SAS is the gatekeeper |
| **Research internship / study program** (ICRISAT ISRP, ICAR, ClinChoice) | India | **High (40–60%)** | Designed for M.Sc. students; lower bar |
| **General data scientist / analyst** | India | **Low (<10%)** | Needs Python + SQL + ML |
| **Global research analyst (CGIAR, dev sector)** | Worldwide | **Low-Moderate (10–20%)** | Visa + competition + Stata/econometrics |
| **US/EU biostat / pharma internship** | Worldwide | **Low (<10%)** | Many are PhD-only or need local work rights |

**Overall honest verdict:** you are **hireable today for agricultural-statistics and ICAR-track roles in India** — that's a real, achievable niche with decent probability. You are **not yet competitive** for general data-science or global pharma roles, and the gap is *not* your statistics — it's the presentation of the portfolio plus missing complementary tools (Python/SQL/SAS).

---

## 5. What's lacking — mapped to practical, company-facing use cases

Each gap below is tied to a *real use case* a company will test you on.

### 🔴 Critical (fix first — highest ROI)

1. **Visible, reproducible code.** Companies don't hire a README; they hire code they can inspect. Currently your `.R` files live in `results/` and there's no data file or run instructions.
   - *Use case:* "Show me your code and how to reproduce a result" — the #1 interview request for research roles.
   - *Fix:* move scripts to repo root, add the `.csv`/`.xlsx` data, a `README` with `install.packages(...)` + run steps, `sessionInfo()` output, a `LICENSE`, and a `results/` folder for outputs only.

2. **Python (pandas, scikit-learn) + SQL.** The universal gatekeeper for any non-agri data role and increasingly for agri-tech (Bayer's postings now mention "advanced analytics, AI-enabled decision making").
   - *Use case:* pull data from a database, clean it, fit a model, score it — the standard analyst take-home test.
   - *Fix:* one end-to-end project: SQL query → pandas → model → report. ~2–3 weeks.

3. **Mixed models & multi-environment trial (MET) analysis — ASReml-R / lme4 / META-R.** This is the **single most hireable "practical" skill in plant breeding statistics** — BLUP/BLUE, variance components, heritability, G×E, genetic gain. CGIAR/seed-company postings name it explicitly.
   - *Use case:* "Estimate heritability and BLUPs from this multi-location trial data." You currently show only ANOVA (fixed effects); breeding programs use mixed models.
   - *Fix:* extend your genotype project with `lme4`/`sommer`/`asreml` — a natural, high-value Project 6.

### 🟠 High value

4. **SAS (Base/STAT) + CDISC basics** — mandatory for pharma/CRO biostat roles in India (ICON, CPVIA, ClinChoice all list it). Even a 30-day SAS + `TFL` familiarity unlocks the entire CRO tier.

5. **Experimental design** (RCBD, alpha-lattice, augmented, spatial correction) — the other half of "design + analysis" that CGIAR/ICRISAT postings ask for. You have the analysis half; show the design half.

6. **Machine learning beyond K-means/PCA** — supervised models (regression/classification trees, random forest, cross-validation, train/test discipline). Even "interpretable ML" is named in ICRISAT postings.

7. **A live, deployed Shiny dashboard.** Convert your Project 5 screenshot into a real link (`shinyapps.io` free tier or Posit Connect). A hiring manager clicking your live app is worth 10 screenshots.
   - *Use case:* "We want stakeholders to explore trial data without touching R" — literally the agri-industry's #1 internal tool.

### 🟡 Differentiators (do after the above)

8. **Statistical genetics/genomics** — GWAS, genomic selection (`rrBLUP`, `rTASSEL`, PLINK). This is where "R + genetics" jobs cluster globally and pay best.
9. **R package development** (roxygen2, testthat, `R CMD check`) — a published/CRAN package instantly separates you from 95% of M.Sc. candidates.
10. **Quarto/R Markdown reports** — most of your PDFs exist; publish a polished Quarto report that a PI could skim.
11. **One publication or conference poster** (ISAP, Indian Society of Agricultural Statistics, a plant-breeding congress, or an arXiv preprint) — signals "research skills" more than any GitHub repo.
12. **Survey/econometrics exposure (Stata)** — only if you want the IFPRI/World Bank/ECB route.

---

## 6. How to present your existing 5 projects (turn 1 project into a portfolio)

Stop presenting them as 5 separate repos. Reframe as **"one reproducible end-to-end plant-breeding analytics pipeline"** with 5 modules:

> *"End-to-end phenotypic analysis of 100 plant genotypes: from exploratory analysis and ANOVA/post-hoc ranking, through linear regression and clustering/PCA for selection, to an interactive Shiny dashboard for breeder decisions."*

One-line repositioning for each module, tied to a company outcome:
- **P1 EDA** → "data quality + trait summaries before modeling" (shows you don't skip the boring-but-critical step)
- **P2 ANOVA + Duncan** → "ranking genotypes for selection decisions" (directly maps to breeder language)
- **P3 Regression** → "predicting a hard-to-measure trait (height) from an easy one" (cost-saving use case)
- **P4 Clustering + PCA** → "grouping germplasm to reduce trial redundancy" (genetic-resource management)
- **P5 Shiny** → "a no-code tool so field teams can explore data" (stakeholder delivery)

Then add the gaps from §5 as Projects 6–8 (mixed models → ML → Python/SQL). That's how 1 thin repo becomes a compelling, hireable story.

---

## 7. Suggested 30 / 60 / 90-day plan

- **Days 0–7:** Restructure the 5 repos (code to root, data file, README run-instructions, `sessionInfo`, LICENSE). Deploy the Shiny app to shinyapps.io. Update your GitHub profile README to the "one pipeline" story.
- **Days 7–30:** Build Project 6 — **mixed-model + heritability + BLUP** on your genotype data (`lme4`/`sommer`). Start applying to ICAR JRF/SRF walk-ins and ICRISAT ISRP internship.
- **Days 30–60:** Python + SQL foundations → one pandas/scikit-learn project. Start SAS Base/STAT (free academic via SAS OnDemand for Academics). Apply to CRO statistical-programmer fresher roles (ClinChoice, CPVIA, ICON).
- **Days 60–90:** Machine-learning project (supervised + CV). Apply broadly to CGIAR RA tier + seed-company trial data roles. Target one conference poster or preprint.

---

## 8. Bottom line

- **You are not lacking statistics or R.** You are lacking (a) **portfolio presentation/reproducibility**, (b) **mixed models** (the #1 practical breeding-stats skill), and (c) **Python/SQL/SAS** (the gates to non-agri and pharma markets).
- **Highest-probability paid outcome right now:** ICAR JRF/SRF or a seed-company/CGIAR research-assistant role in India (**~35–50% within 90 days** of targeted applying).
- **Fastest "on-paper" wins:** restructure the repos, deploy the live Shiny app, add the mixed-model project, and learn SAS — together these plausibly **double** your hit rate on the CRO tier.

*All figures are my calibrated estimates from the postings reviewed on 15 Aug 2026, not a promise. Job market details change quickly — verify every posting on the employer's own site before applying.*
