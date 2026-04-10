# Sex-Related Differences in Toxicities from Advanced Melanoma Treatment

> Systematic review · meta-analysis · biostatistics · immunotherapy · published in *British Journal of Cancer*

A systematic review and meta-analysis investigating whether biological sex influences the risk of adverse events (AEs) in patients receiving immunotherapy or targeted therapy for advanced melanoma. The study is **peer-reviewed and published** — [British Journal of Cancer, 2025](https://doi.org/10.1038/s41416-025-03266-0).

---

## Clinical Background

Immunotherapy and targeted therapy have transformed the prognosis of advanced melanoma, but both are associated with toxicities that affect treatment adherence and patient quality of life. Prior evidence from cytotoxic therapy suggested female patients may experience higher rates of AEs — this study systematically tests whether the same pattern holds for modern treatment regimens.

---

## Methods

**Literature search:** PubMed and Embase, all independent studies published up to April 2024 reporting sex-specific toxicity data in melanoma as the primary disease.

**Inclusion criteria:** studies providing sufficient data to estimate Odds Ratios (ORs) with 95% Confidence Intervals, or raw male/female counts with and without AEs.

**AE categories analysed:** dermatologic, thyroid-related, and grade III–IV toxicities — chosen due to limited availability of general AE data across studies.

**Statistical framework:**

| Component | Approach |
|-----------|----------|
| Effect size | Summary Odds Ratios (sORs) with 95% CIs |
| Pooling model | Random-effects meta-analysis |
| Heterogeneity | I² statistic |
| Publication bias | Egger's and Begg's tests |
| Sensitivity analysis | Leave-one-out method to identify heterogeneity sources |

All analyses performed in **R**.

---

## Key Findings

Female patients showed consistently higher risk of specific AE categories:

| Adverse Event Category | Finding |
|------------------------|---------|
| Thyroid-related AEs | Significantly higher risk in females; low heterogeneity (I² = 29.39%) |
| Dermatologic AEs | sOR = 1.31 (95% CI: 1.06–1.61) — significantly greater risk in females; moderate heterogeneity |
| Grade III–IV AEs | Higher occurrence in female patients |

No significant publication bias detected across analysed AE categories.

---

## Significance

This is one of the first studies to systematically examine sex-based toxicity differences specifically for **modern melanoma therapies** — immunotherapy and targeted agents — rather than traditional cytotoxic regimens. The findings provide quantitative evidence supporting sex-stratified monitoring protocols and inform clinical decision-making around treatment adherence and supportive care.

---

## Limitations

- **Retrospective design** — analysis is constrained by what primary studies reported; prospective sex-stratified trials would provide stronger causal evidence
- **Restricted AE scope** — limited availability of general AE data across studies prevented a broader toxicity analysis; findings are specific to the categories where sufficient data existed
- **Confounding** — differences in treatment dosing, adherence, or comorbidity profiles by sex could not be fully controlled across heterogeneous study populations

---

## Stack

`R` `meta-analysis` `random-effects models` `systematic review` `biostatistics` `oncology` `PRISMA` `epidemiology`
