---
description: "Chapter 24 — Household Capital Development Index for the Community Capital Development Project."
---

# Chapter 24: Household Capital Development Index

> **`[Original Framework]`** This chapter presents the Household Capital Development Index, an original composite measurement framework developed for the Community Capital Development Project.

---

## 24.1 Introduction

The Household Capital Development Index (HCDI) is a composite measure that aggregates household capital endowments across five dimensions into a single interpretable score. The Index is designed to:

- Provide a standardized measure of household capital position
- Enable comparison across households, communities, and regions
- Support the operationalization of the class categories established in Volume II
- Inform the assessment instruments developed in Volume III

The HCDI is an original framework developed by Anil Kumar Srivastava for the Community Capital Development Project. It is not an internationally standardised model produced by a multilateral institution. The Index is designed as an analytic and policy tool, not as a definitive measure of household well-being.

---

## 24.2 Index Architecture

The Index aggregates five sub-indexes, each corresponding to a capital dimension identified in the Household Socioeconomic Capital Framework (Chapter 16):

1. **Financial Capital Sub-Index (FCI)**
2. **Physical Capital Sub-Index (PCI)**
3. **Human Capital Sub-Index (HCI)**
4. **Social Capital Sub-Index (SCI)**
5. **Institutional Capital Sub-Index (ICI)**

### Composite Formula

[Original Framework]

```
HCDI = w_f × FCI + w_p × PCI + w_h × HCI + w_s × SCI + w_i × ICI
```

Where:
- `w_f, w_p, w_h, w_s, w_i` are dimension-specific weights
- Each sub-index is normalized to a common scale (0 to 100)
- The sum of weights equals 1.0 (w_f + w_p + w_h + w_s + w_i = 1.0)

### Normalization

Each sub-index is normalized to a scale of 0 to 100 using min-max normalization:

```
Sub-Index = [(Observed Value - Minimum Value) / (Maximum Value - Minimum Value)] × 100
```

The minimum and maximum values are determined empirically from household survey data (NFHS, NSSO, ASER) and represent the observed range of each indicator across Indian households.

### Weight Determination

Weights may be determined through:

- **Empirical factor analysis** of household-level data, using principal component analysis or factor analysis to identify the relative contribution of each dimension to overall household capital position
- **Delphi-based expert consensus**, engaging development economists, sociologists, statisticians, and policy practitioners to determine dimension weights through structured consultation
- **Community-informed participatory weighting**, engaging households and community members to determine the relative importance of each dimension through participatory methods
- **Context-specific calibration** for different regional settings, recognizing that the relative importance of capital dimensions may vary across regions, cultures, and historical periods

For initial calibration, the framework proposes equal weights (w_f = w_p = w_h = w_s = w_i = 0.20), with subsequent refinement based on empirical testing and expert consultation. Equal weights provide a transparent and defensible starting point, while allowing for context-specific adjustment as the framework is tested and refined.

---

## 24.3 Sub-Index Construction

### Financial Capital Sub-Index (FCI)

Indicators used in the FCI include:
- Monthly per capita consumption expenditure (MPCE) or income
- Savings balance and financial assets
- Access to formal credit (bank loans, microfinance)
- Ownership of financial instruments (insurance, pensions, mutual funds)
- Digital financial inclusion (bank account usage, UPI transactions, direct benefit transfers)

Data sources: NSSO Consumer Expenditure Survey, NFHS wealth index, PMJDY data, RBI financial inclusion statistics.

The FCI is normalized to a scale of 0 to 100, where 0 represents the lowest observed MPCE/savings/credit access across Indian households, and 100 represents the highest. The World Inequality Lab reports that the top 1 per cent of Indian households held 22.6 per cent of national income in 2022-23 (Bharti et al., 2024), representing the upper bound of the FCI scale.

### Physical Capital Sub-Index (PCI)

Indicators include:
- Housing quality (construction material, flooring, roofing)
- Ownership of durable goods (television, refrigerator, motorcycle, car)
- Land holdings (agricultural and non-agricultural)
- Access to electricity, improved water, and sanitation
- Ownership of productive equipment (tractors, tools, machinery)

Data sources: NFHS asset ownership data, Census of India housing data, PMAY-G beneficiary data, NSSO asset ownership data.

The PCI is normalized to a scale of 0 to 100, where 0 represents the lowest observed housing quality/asset ownership across Indian households, and 100 represents the highest. NFHS-5 data shows that car ownership ranges from 1 per cent (poorest quintile) to 30 per cent (richest quintile), and refrigerator ownership ranges from 10 per cent to 95 per cent (IIPS & ICF, 2021).

### Human Capital Sub-Index (HCI)

Indicators encompass:
- Educational attainment (years of schooling, highest qualification)
- Learning outcomes (reading ability, numeracy)
- Health status (height-for-age, BMI, anemia prevalence)
- Skill levels (vocational training, technical qualifications)
- Capability measures (decision-making autonomy, mobility)

Data sources: NFHS health and education data, ASER learning outcomes, NSSO education data, PLFS skill data.

The HCI is normalized to a scale of 0 to 100, where 0 represents the lowest observed educational attainment/health status across Indian households, and 100 represents the highest. NFHS-5 data shows that stunting rates range from 46 per cent (poorest quintile) to 23 per cent (richest quintile), and ASER 2024 finds that only 50.4 per cent of Standard V students can read Standard II level text (ASER Centre, 2024; IIPS & ICF, 2021).

### Social Capital Sub-Index (SCI)

Indicators include:
- Network density and diversity
- Membership in associations (self-help groups, cooperatives, religious organisations)
- Trust levels (interpersonal and institutional)
- Reciprocity and mutual support mechanisms
- Access to influential actors through social ties

Data sources: NFHS social network data, IHDS social capital indicators, qualitative fieldwork, SHG participation data.

The SCI is normalized to a scale of 0 to 100, where 0 represents the lowest observed network density/association membership across Indian households, and 100 represents the highest. Social capital is the most difficult dimension to measure quantitatively, and the framework acknowledges that qualitative fieldwork is essential for accurate assessment.

### Institutional Capital Sub-Index (ICI)

Indicators include:
- Access to government services (healthcare, education, social protection)
- Legal recognition (land titles, birth certificates, identity documents)
- Engagement with institutions (voting, participation in panchayats, grievance redressal)
- Relationship with financial institutions (bank account usage, credit history)
- Awareness of rights and entitlements

Data sources: Government scheme databases (MGNREGA, NFSA, PMJDY, PMAY-G), Census of India documentation data, qualitative fieldwork, e-governance usage statistics.

The ICI is normalized to a scale of 0 to 100, where 0 represents the lowest observed institutional access/recognition across Indian households, and 100 represents the highest. The Pradhan Mantri Jan Dhan Yojana has opened over 500 million bank accounts, with 55 per cent held by women (PIB, 2024), representing significant progress in institutional capital for Poor and Lower-Middle-Class households.

---

## 24.4 Weight Determination

Weights may be determined through multiple approaches, as described in Section 24.2. The framework proposes the following initial calibration:

| Approach | Financial | Physical | Human | Social | Institutional |
|----------|-----------|----------|-------|--------|---------------|
| Equal weights (initial) | 0.20 | 0.20 | 0.20 | 0.20 | 0.20 |
| Empirical factor analysis | To be determined | To be determined | To be determined | To be determined | To be determined |
| Delphi consensus | To be determined | To be determined | To be determined | To be determined | To be determined |
| Participatory weighting | To be determined | To be determined | To be determined | To be determined | To be determined |

The equal-weight approach provides a transparent and defensible starting point. Subsequent refinement through empirical factor analysis, expert consultation, and participatory methods will enable context-specific calibration.

---

## 24.5 Index Interpretation and Classification

The HCDI score is used to classify households into the categories established in this volume:

| HCDI Range | Classification | Approximate Percentile |
|------------|---------------|----------------------|
| 0 - 20 | Poor Households | Bottom 15-20% |
| 20 - 40 | Lower-Middle-Class Households | 15-40% |
| 40 - 60 | Middle-Class Households | 40-65% |
| 60 - 80 | Upper-Middle-Class Households | 65-85% |
| 80 - 90 | Neo-Rich Households | 85-95% |
| 90 - 100 | Elite Households | Top 5-10% |

> **Note:** Threshold values will be calibrated based on field testing and contextual norms. The ranges above are provisional and will be refined as the framework is tested and validated.

The HCDI classification is not a rigid boundary system. Households near category boundaries may exhibit characteristics of adjacent categories, and the framework acknowledges that household capital positions evolve over time. The HCDI is designed as a continuous measure, with category boundaries serving as analytical conveniences rather than absolute classifications.

---

## 24.6 Limitations and Cautions

The HCDI is designed as an analytic and policy tool, not as a definitive measure of household well-being. Users of the Index should understand:

- **The Index does not replace qualitative understanding of household circumstances.** The HCDI provides a quantitative summary of household capital endowments, but it cannot capture the full complexity of household life, including cultural practices, social relationships, and subjective well-being.

- **Threshold values are context-dependent and may vary by region.** The HCDI thresholds proposed in Section 24.5 are calibrated for the Indian context. They may need adjustment for other South Asian countries or for different regional settings within India.

- **The aggregation into a single number necessarily involves trade-offs.** The HCDI aggregates five dimensions into a single score, which means that households with different capital configurations may receive similar HCDI scores. The framework encourages users to examine sub-index scores in addition to the composite HCDI.

- **The Index should be used in conjunction with complementary qualitative data.** The HCDI is most useful when combined with qualitative fieldwork, case studies, and community-level assessment. The quantitative summary provided by the HCDI should be interpreted in light of qualitative understanding of household circumstances.

- **Social capital and institutional capital are difficult to measure quantitatively.** The SCI and ICI sub-indices rely on proxy indicators and may not fully capture the complexity of social networks and institutional relationships. Qualitative fieldwork is essential for accurate assessment of these dimensions.

---

## 24.7 Connection to Volume III

The HCDI architecture directly informs the assessment tools and scoring methodology developed in Volume III of this project. Volume III will provide:

- **Household survey instruments** for collecting data on all five capital dimensions
- **Scoring methodology** for calculating FCI, PCI, HCI, SCI, and ICI sub-indices
- **HCDI calculation procedures** for aggregating sub-indices into composite scores
- **Classification guidelines** for assigning households to category based on HCDI scores
- **Field testing protocols** for validating the framework in different regional and cultural contexts

The HCDI is designed to be iterative. As data is collected and analysed in Volume III, the framework may be refined — indicators may be adjusted, weights may be calibrated, and category boundaries may be sharpened. This iterative process is a feature, not a limitation, of the framework's design.

---

## 24.8 Conclusion

The Household Capital Development Index provides a standardized, multi-dimensional measure of household capital position. By aggregating financial, physical, human, social, and institutional capital into a single interpretable score, the HCDI enables comparison across households, communities, and regions.

The framework is designed as an original contribution to the theory and practice of community capital assessment. It is not an internationally standardised model produced by a multilateral institution. The HCDI is intended to inform policy, guide assessment, and support the operationalization of the household capital class framework developed in Volume II.

The next chapter presents a policy framework derived from the analytical findings developed throughout Volume II, translating the HCDI and comparative analysis into actionable policy recommendations.

---

## References for Chapter 24

Bharti, D., Chancel, L., Piketty, T., & Somanchi, K. (2024). *Income and wealth inequalities in India, 1922-2023: The rise of the billionaire raj*. World Inequality Lab Working Paper No. 2024/09. https://wid.world/www-site/uploads/2024/03/WorldInequalityLab_WP2024_09_Income-and-Wealth-Inequality-in-India-1922-2023_Final.pdf

ASER Centre. (2024). *Annual Status of Education Report (Rural) 2024*. Pratham Foundation. https://asercentre.org/aser-2024

International Institute for Population Sciences (IIPS) & ICF. (2021). *National Family Health Survey (NFHS-5), 2019–21: India*. IIPS.

Press Information Bureau (PIB). (2024). *PMJDY coverage data*. https://www.pib.gov.in/PressReleasePage.aspx?PRID=2049231

---

*Developed by Anil Kumar Srivastava | Community Capital Development Project*
