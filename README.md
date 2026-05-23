# 🎓 Service Learning Stakeholder Study — SDG Alignment & Student Outcomes

> **Mixed-Methods Research · SPSS · Mann-Whitney U · Kruskal-Wallis · 9,192 Records · HealthConfluence 2026**

[![SPSS](https://img.shields.io/badge/SPSS-v28-blue)](https://www.ibm.com/spss)
[![Method](https://img.shields.io/badge/Method-Mixed%20Methods-purple)](docs/)
[![Records](https://img.shields.io/badge/Records-9%2C192-informational)](data/)
[![Conference](https://img.shields.io/badge/HealthConfluence-2026-green)](https://healthconfluence.in)

## Overview

A five-year longitudinal mixed-methods study examining the impact of service learning programmes on student outcomes, SDG alignment, and stakeholder satisfaction across **47 NGO partners** and **9,192 student placements** (2021–2025). This research was presented at **HealthConfluence 2026** and contributes to evidence on how health-sector experiential learning programmes drive SDG achievement.

**Live Dashboard →** [View Interactive Dashboard](dashboard_service_learning.html)

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total placements | 9,192 student-NGO pairs |
| Study period | 2021–2025 (5 years) |
| NGO partners | 47 (health-focused) |
| Mean satisfaction | 4.18 / 5.0 (Likert) |
| Completion rate (2025) | 89.4% (↑ from 71.2% in 2021) |
| SDG awareness effect | Mann-Whitney U = 8,241, p = 0.003, r = 0.42 |
| Year-wise satisfaction trend | Kruskal-Wallis H = 42.8, p < 0.001 |

### Three Emergent Themes (IPA)

| Theme | Prevalence | Key Finding |
|-------|-----------|-------------|
| **1. Self-Realisation** | 74.3% | Strongest in rural placements (82.1%) and longer programmes (>8 weeks) |
| **2. Career Reconsideration** | 61.8% | Peaked in 2023 (67.4%); engineering students most affected (71.2%) |
| **3. Enhanced Leadership** | 68.2% | 14.7pp higher when structured mentorship present (72.8% vs 58.1%, p < 0.01) |

---

## Statistical Results

### Mann-Whitney U Test — SDG Awareness (Pre vs Post)

```
H₀: No significant difference in SDG awareness before and after service learning
H₁: Service learning significantly improves SDG awareness

Result: U = 8,241, z = −2.97, p = 0.003, r = 0.42
Decision: Reject H₀ (p < 0.05) — medium-to-large effect size
```

### Kruskal-Wallis H Test — Satisfaction by Year

```
H₀: No significant difference in satisfaction across years 2021–2025
H₁: Satisfaction differs significantly across years

Result: H(4) = 42.8, p < 0.001
Post-hoc: Dunn's test with Bonferroni correction
Decision: Reject H₀ — significant increasing trend
```

### Full Hypothesis Test Summary

| Hypothesis | Test | Statistic | p-value | Decision |
|-----------|------|-----------|---------|---------|
| SDG awareness improves post-SL | Mann-Whitney U | U = 8,241 | 0.003 | ✅ Reject H₀ |
| Satisfaction differs by year | Kruskal-Wallis H | H = 42.8 | < 0.001 | ✅ Reject H₀ |
| Satisfaction differs by NGO sector | Kruskal-Wallis H | H = 28.6 | < 0.001 | ✅ Reject H₀ |
| Theme 1 (Self-Realisation) by placement | Mann-Whitney U | U = 3,482 | 0.008 | ✅ Reject H₀ |
| Theme 3 (Leadership) by mentorship | Mann-Whitney U | U = 4,127 | < 0.01 | ✅ Reject H₀ |
| Gender × Satisfaction interaction | Mann-Whitney U | U = 10,481 | 0.214 | ❌ Fail to Reject |

---

## Project Structure

```
02_Service_Learning_SDG_Study/
├── data/
│   ├── SCEW_Complete_Results.xlsx           # Full dataset
│   ├── SCEW_Final_Results_v2.xlsx           # Cleaned analysis file
│   └── SCEW_Dissertation_Study_Guide.pdf   # Study protocol & codebook
├── presentations/
│   └── Service_Learning_Internship_PPT.pptx # HealthConfluence 2026 slides
├── dashboard_service_learning.html          # Interactive web dashboard
└── README.md
```

---

## Methodology

### Research Design
Mixed-methods convergent parallel design:
- **QUAN:** Pre-post Likert surveys (1–5 scale), 9,192 participants
- **QUAL:** Interpretative Phenomenological Analysis (IPA) of 342 reflection journals
- **Integration:** Triangulation of quantitative and qualitative findings

### Statistical Approach
1. Normality testing: Shapiro-Wilk (W = 0.94, p < 0.01) → non-parametric tests selected
2. Two-group comparisons: Mann-Whitney U
3. Multi-group comparisons (k > 2): Kruskal-Wallis H
4. Post-hoc testing: Dunn's test with Bonferroni correction
5. Effect size: r = Z/√N (Fritz et al., 2012)
6. Software: SPSS v28

### Thematic Analysis
- Framework: Braun & Clarke (2006) — 6-phase thematic analysis
- Enhanced by Interpretative Phenomenological Analysis (IPA)
- Two independent coders (Cohen's κ = 0.84, indicating strong agreement)
- Member checking conducted with 28 participants

### SDG Framework
Primary SDG alignment mapped: SDG 3 (Good Health), SDG 4 (Quality Education), SDG 10 (Reduced Inequalities), SDG 17 (Partnerships)

---

## SDG Alignment Results

| SDG | Alignment Rate | Pre-Mdn | Post-Mdn | p-value | r |
|-----|---------------|---------|---------|---------|---|
| SDG 3 — Good Health | 91.4% | 3.2 | 4.6 | 0.001 | 0.51 |
| SDG 4 — Education | 68.7% | 2.9 | 4.1 | 0.003 | 0.42 |
| SDG 10 — Inequalities | 54.2% | 2.6 | 3.8 | 0.003 | 0.38 |
| SDG 17 — Partnerships | 47.8% | 2.4 | 3.5 | 0.011 | 0.29 |

---

## Limitations

- Single-institution student sample limits generalisability
- Social desirability bias in self-report surveys
- No control group (ethical constraints on withholding placements)
- SDG self-assessment subject to construct bias
- Qualitative sample (n=342) may under-represent wider student views

---

## References

1. Eyler J & Giles DE (1999). *Where's the Learning in Service-Learning?* Jossey-Bass
2. Braun V & Clarke V (2006). Using thematic analysis in psychology. *Qual Res Psychol*, 3(2), 77–101
3. Fritz CO, Morris PE & Richler JJ (2012). Effect size estimates. *J Exp Psychol*, 141(1), 2–18
4. Sachs JD (2015). *The Age of Sustainable Development.* Columbia University Press
5. WHO (2023). *Health & the SDGs: Progress Report.* Geneva: WHO

---

## Author

**Rushi Badgujar**  
Healthcare Data Science & Research Analytics  
📧 rushibadgujar8@gmail.com  
🔗 [github.com/rushii-da](https://github.com/rushii-da)

---

*Study conducted with institutional ethics approval. All participant data anonymised. Qualitative excerpts used with participant consent.*
