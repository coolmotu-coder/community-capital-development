---
description: "Scoring Methodology for the Community Capital Development Project."
---

# Scoring Methodology

> **`[Proposed]`** This section presents the scoring methodology for the Community Capital Development Project. All scoring procedures are original frameworks developed by Anil Kumar Srivastava and have not been independently validated.

---

## 1. Introduction

This section presents the scoring methodology for aggregating questionnaire responses into composite capital indices and the Household Capital Development Index (HCDI) described in Volume II, Chapter 24. The methodology provides procedures for scoring each capital dimension, determining weights, aggregating sub-indices, and interpreting results.

The scoring methodology is designed to be transparent, reproducible, and adaptable to different contexts. It draws on established methods from the National Family Health Survey (NFHS) wealth index construction, the National Multidimensional Poverty Index (MPI) methodology developed by NITI Aayog, and the Community Capitals Framework assessment metrics developed by Flora and Flora (Flora & Flora, 2008; Emery & Flora, 2006).

The methodology is not intended as an official government scoring system. It is an original framework developed for the CCDP and should be calibrated and validated in the target context before deployment.

---

## 2. Sub-Index Construction

Each of the five capital dimensions (financial, physical, human, social, institutional) is scored as a sub-index on a scale of 0 to 100. The sub-index is constructed by aggregating individual indicators within each dimension using a weighted average.

### 2.1 Financial Capital Sub-Index (FCI)

**Indicators:**
1. Monthly per capita consumption expenditure (MPCE)
2. Savings and financial assets
3. Access to formal credit
4. Access to informal credit
5. Insurance coverage
6. Digital financial inclusion

**Scoring Procedure:**

**Indicator 1: MPCE**
- Convert MPCE to a 0-100 scale using min-max normalisation:
  ```
  FCI_1 = [(MPCE - MPCE_min) / (MPCE_max - MPCE_min)] × 100
  ```
- MPCE_min and MPCE_max are determined empirically from the survey data or from NSSO 75th round data (Rs. 526 rural, Rs. 5,293 urban) (NSSO, 2019)
- Values below MPCE_min are scored as 0; values above MPCE_max are scored as 100

**Indicator 2: Savings and Financial Assets**
- Score each asset type (bank accounts, fixed deposits, gold, livestock) as 1 (present) or 0 (absent)
- Aggregate across asset types: FCI_2 = (number of assets / total asset types) × 100

**Indicator 3: Access to Formal Credit**
- Score as 1 (has access) or 0 (no access)
- FCI_3 = 100 if access = 1; FCI_3 = 0 if access = 0

**Indicator 4: Access to Informal Credit**
- Score as 1 (has access) or 0 (no access)
- FCI_4 = 100 if access = 1; FCI_4 = 0 if access = 0

**Indicator 5: Insurance Coverage**
- Score each insurance type (health, life, crop, property) as 1 (present) or 0 (absent)
- Aggregate across insurance types: FCI_5 = (number of insurances / total insurance types) × 100

**Indicator 6: Digital Financial Inclusion**
- Score each digital finance indicator (mobile phone, UPI usage, DBT receipt) as 1 (present) or 0 (absent)
- Aggregate across indicators: FCI_6 = (number of indicators / total indicators) × 100

**Sub-Index Aggregation:**
```
FCI = w_1 × FCI_1 + w_2 × FCI_2 + w_3 × FCI_3 + w_4 × FCI_4 + w_5 × FCI_5 + w_6 × FCI_6
```
Where w_1 through w_6 are indicator weights that sum to 1.0.

**Default Weights (equal weighting):**
- w_1 = 0.30 (MPCE is the most significant financial indicator)
- w_2 = 0.20
- w_3 = 0.10
- w_4 = 0.05
- w_5 = 0.15
- w_6 = 0.20

These weights can be adjusted through empirical factor analysis or expert consultation.

### 2.2 Physical Capital Sub-Index (PCI)

**Indicators:**
1. Housing quality
2. Durable goods ownership
3. Land holdings
4. Access to utilities
5. Productive equipment

**Scoring Procedure:**

**Indicator 1: Housing Quality**
- Score wall material: mud/straw = 20, brick/concrete = 80, wood/bamboo = 40, other = 50
- Score roof material: mud/thatch = 20, tin/corrugated metal = 50, concrete/brick = 100, other = 40
- Score flooring: mud/earth = 20, cement/concrete = 80, tiles/marble = 100, other = 50
- Score number of rooms per member: < 0.5 = 20, 0.5-1.0 = 50, 1.0-1.5 = 70, > 1.5 = 100
- PCI_1 = average of wall, roof, flooring, and room scores

**Indicator 2: Durable Goods Ownership**
- Score each durable good (television, refrigerator, motorcycle, car, washing machine, air conditioner, microwave, computer, smartphone) as 1 (present) or 0 (absent)
- Aggregate across goods: PCI_2 = (number of goods / total goods) × 100

**Indicator 3: Land Holdings**
- Score agricultural land ownership: 0 acres = 0, < 1 acre = 30, 1-2 acres = 50, 2-5 acres = 70, > 5 acres = 100
- Score non-agricultural land ownership: 0 acres = 0, < 0.5 acre = 30, 0.5-1 acre = 50, > 1 acre = 100
- PCI_3 = average of agricultural and non-agricultural land scores

**Indicator 4: Access to Utilities**
- Score electricity: 24/7 = 100, 12-18 hours = 70, 6-12 hours = 40, < 6 hours = 20, none = 0
- Score drinking water: improved = 100, unimproved = 40, none = 0
- Score sanitation: improved private = 100, improved shared = 60, unimproved = 30, none = 0
- Score cooking fuel: clean (LPG/electricity) = 100, intermediate (kerosene) = 50, unclean (wood/charcoal) = 20
- PCI_4 = average of electricity, water, sanitation, and cooking fuel scores

**Indicator 5: Productive Equipment**
- Score each equipment type (tractor, irrigation pump, agricultural tools, non-agricultural equipment) as 1 (present) or 0 (absent)
- Aggregate across equipment: PCI_5 = (number of equipment / total equipment types) × 100

**Sub-Index Aggregation:**
```
PCI = w_1 × PCI_1 + w_2 × PCI_2 + w_3 × PCI_3 + w_4 × PCI_4 + w_5 × PCI_5
```
Where w_1 through w_5 are indicator weights that sum to 1.0.

**Default Weights (equal weighting):**
- w_1 = 0.30 (housing quality is the most significant physical capital indicator)
- w_2 = 0.25
- w_3 = 0.15
- w_4 = 0.20
- w_5 = 0.10

### 2.3 Human Capital Sub-Index (HCI)

**Indicators:**
1. Educational attainment (household head)
2. Educational attainment (spouse, if applicable)
3. Educational attainment (children)
4. Health status (household head)
5. Health status (children under 5)
6. Institutional delivery (mothers, if applicable)

**Scoring Procedure:**

**Indicator 1: Educational Attainment (Household Head)**
- Score education level: no formal schooling = 0, primary = 20, upper primary = 40, secondary = 60, higher secondary = 75, graduate = 90, postgraduate = 100
- Adjust for learning outcomes: if can read simple text, add 5 points; if can perform division, add 5 points
- HCI_1 = education score + learning adjustment (capped at 100)

**Indicator 2: Educational Attainment (Spouse)**
- Same scoring as Indicator 1
- HCI_2 = education score + learning adjustment (capped at 100)

**Indicator 3: Educational Attainment (Children)**
- Score number of children enrolled: 0 = 0, 1-50% = 30, 51-80% = 60, 81-100% = 100
- HCI_3 = enrollment score

**Indicator 4: Health Status (Household Head)**
- Score self-reported health: excellent = 100, good = 80, fair = 60, poor = 30, very poor = 10
- Adjust for chronic illness: subtract 10 points per chronic condition
- HCI_4 = health score - illness adjustment (capped at 0-100)

**Indicator 5: Health Status (Children under 5)**
- Score immunization: 0% = 0, 1-50% = 30, 51-80% = 60, 81-100% = 100
- Adjust for stunting: subtract 15 points if any child stunted
- Adjust for wasting: subtract 10 points if any child wasted
- HCI_5 = immunization score - stunting adjustment - wasting adjustment (capped at 0-100)

**Indicator 6: Institutional Delivery**
- Score institutional delivery rate: 0% = 0, 1-50% = 30, 51-80% = 60, 81-100% = 100
- HCI_6 = delivery score

**Sub-Index Aggregation:**
```
HCI = w_1 × HCI_1 + w_2 × HCI_2 + w_3 × HCI_3 + w_4 × HCI_4 + w_5 × HCI_5 + w_6 × HCI_6
```
Where w_1 through w_6 are indicator weights that sum to 1.0.

**Default Weights (equal weighting):**
- w_1 = 0.20 (household head education is most significant)
- w_2 = 0.15
- w_3 = 0.15
- w_4 = 0.20
- w_5 = 0.15
- w_6 = 0.15

### 2.4 Social Capital Sub-Index (SCI)

**Indicators:**
1. Membership in organisations
2. Trust and reciprocity
3. Collective action
4. Social network density

**Scoring Procedure:**

**Indicator 1: Membership in Organisations**
- Score each organisation type (SHG, cooperative, religious, caste/tribe, women's, youth, farmers', other) as 1 (member) or 0 (non-member)
- Aggregate across organisation types: SCI_1 = (number of memberships / total organisation types) × 100

**Indicator 2: Trust and Reciprocity**
- Score generalised trust (1-5 scale): convert to 0-100 scale (1 = 0, 2 = 25, 3 = 50, 4 = 75, 5 = 100)
- Score inter-group trust (1-5 scale): convert to 0-100 scale
- Score institutional trust (1-5 scale): convert to 0-100 scale
- Score mutual support (always = 100, often = 75, sometimes = 50, rarely = 25, never = 0)
- Score resource sharing (always = 100, often = 75, sometimes = 50, rarely = 25, never = 0)
- SCI_2 = average of trust and reciprocity scores

**Indicator 3: Collective Action**
- Score community collective action: yes = 100, no = 0
- Score frequency of collective actions in past 5 years: 0 = 0, 1-2 = 30, 3-5 = 60, > 5 = 100
- Score household participation in community work: yes = 100, no = 0
- SCI_3 = average of collective action scores

**Indicator 4: Social Network Density**
- Score number of people for financial help: 0 = 0, 1-2 = 30, 3-5 = 60, > 5 = 100
- Score number of people for advice: 0 = 0, 1-2 = 30, 3-5 = 60, > 5 = 100
- Score number of regular contacts: 0-5 = 20, 6-15 = 50, 16-30 = 70, > 30 = 100
- Score out-of-community connections: yes = 100, no = 0
- SCI_4 = average of network density scores

**Sub-Index Aggregation:**
```
SCI = w_1 × SCI_1 + w_2 × SCI_2 + w_3 × SCI_3 + w_4 × SCI_4
```
Where w_1 through w_4 are indicator weights that sum to 1.0.

**Default Weights (equal weighting):**
- w_1 = 0.25
- w_2 = 0.35 (trust and reciprocity are most significant social capital indicators)
- w_3 = 0.20
- w_4 = 0.20

### 2.5 Institutional Capital Sub-Index (ICI)

**Indicators:**
1. Awareness of entitlements
2. Access to government services
3. Engagement with institutions
4. Relationship with institutions

**Scoring Procedure:**

**Indicator 1: Awareness of Entitlements**
- Score awareness of each programme (NFSA, MGNREGA, Ayushman Bharat, PMAY, scholarships, pensions) as 1 (aware) or 0 (unaware)
- Aggregate across programmes: ICI_1 = (number aware / total programmes) × 100

**Indicator 2: Access to Government Services**
- Score documentation (Aadhaar, voter ID, ration card, land title, birth certificate) as 1 (present) or 0 (absent)
- Aggregate across documents: ICI_2 = (number of documents / total documents) × 100

**Indicator 3: Engagement with Institutions**
- Score panchayat meeting attendance: always = 100, usually = 75, sometimes = 50, rarely = 25, never = 0
- Score grievance filing: yes = 100, no = 0
- Score voting: always = 100, usually = 75, sometimes = 50, rarely = 25, never = 0
- ICI_3 = average of engagement scores

**Indicator 4: Relationship with Institutions**
- Score satisfaction with service delivery (1-5 scale): convert to 0-100 scale
- Score responsiveness of officials (1-5 scale): convert to 0-100 scale
- Score fairness of programme distribution (1-5 scale): convert to 0-100 scale
- ICI_4 = average of relationship scores

**Sub-Index Aggregation:**
```
ICI = w_1 × ICI_1 + w_2 × ICI_2 + w_3 × ICI_3 + w_4 × ICI_4
```
Where w_1 through w_4 are indicator weights that sum to 1.0.

**Default Weights (equal weighting):**
- w_1 = 0.20
- w_2 = 0.30 (documentation access is most significant institutional capital indicator)
- w_3 = 0.25
- w_4 = 0.25

---

## 3. Weight Determination

The weights for sub-index aggregation (w_1 through w_5 for the five capital dimensions) and indicator aggregation (w_1 through w_n within each sub-index) can be determined through multiple approaches.

### 3.1 Equal Weighting (Default)

The default approach uses equal weights for all dimensions and indicators. This provides a transparent and defensible starting point:
- All five capital dimensions receive equal weight (w_f = w_p = w_h = w_s = w_i = 0.20)
- All indicators within each sub-index receive equal weight (as specified in Sections 2.1-2.5)

### 3.2 Empirical Factor Analysis

Weights can be determined through principal component analysis (PCA) or factor analysis of household-level survey data. This approach identifies the relative contribution of each dimension to overall household capital position based on observed correlations.

**Procedure:**
1. Collect household-level data on all indicators
2. Perform PCA or factor analysis
3. Extract eigenvalues and eigenvectors
4. Use factor loadings to determine dimension weights
5. Use indicator loadings within each factor to determine indicator weights

**Advantages:** Data-driven, reflects actual variation in household capital endowments
**Limitations:** Requires large sample size; weights may vary across contexts

### 3.3 Delphi-Based Expert Consensus

Weights can be determined through structured consultation with development economists, sociologists, statisticians, and policy practitioners.

**Procedure:**
1. Assemble panel of 10-15 experts
2. Distribute initial weight proposals (equal weighting)
3. Collect anonymous feedback and justification
4. Revise weights based on feedback
5. Repeat for 2-3 rounds until consensus is reached

**Advantages:** Incorporates expert judgment; transparent process
**Limitations:** Subject to expert bias; time-intensive

### 3.4 Participatory Weighting

Weights can be determined through community consultation, engaging households and community members to determine the relative importance of each dimension.

**Procedure:**
1. Conduct focus group discussions with different community segments
2. Present the five capital dimensions and ask participants to rank their importance
3. Use pairwise comparison or point allocation methods to determine weights
4. Aggregate weights across groups

**Advantages:** Context-specific; builds community ownership
**Limitations:** May reflect local biases; difficult to compare across communities

### 3.5 Context-Specific Calibration

Weights can be calibrated for different regional settings based on local priorities and conditions. For example:
- In rural agricultural communities, natural capital (not included in the five-dimension framework but relevant in broader assessments) and physical capital may receive higher weights
- In urban communities, financial capital and institutional capital may receive higher weights
- In communities with strong social networks, social capital may receive higher weight

---

## 4. Composite Index Aggregation

The Household Capital Development Index (HCDI) is calculated as a weighted sum of the five sub-indices:

```
HCDI = w_f × FCI + w_p × PCI + w_h × HCI + w_s × SCI + w_i × ICI
```

Where:
- w_f, w_p, w_h, w_s, w_i are dimension-specific weights that sum to 1.0
- FCI, PCI, HCI, SCI, ICI are the financial, physical, human, social, and institutional capital sub-indices (each on a 0-100 scale)
- HCDI is on a 0-100 scale

### 4.1 Classification Thresholds

The HCDI score is used to classify households into the categories established in Volume II, Chapter 22:

| HCDI Range | Classification | Approximate Percentile |
|------------|---------------|----------------------|
| 0 - 20 | Poor Households | Bottom 15-20% |
| 20 - 40 | Lower-Middle-Class Households | 15-40% |
| 40 - 60 | Middle-Class Households | 40-65% |
| 60 - 80 | Upper-Middle-Class Households | 65-85% |
| 80 - 90 | Neo-Rich Households | 85-95% |
| 90 - 100 | Elite Households | Top 5-10% |

> **Note:** Threshold values are provisional and will be calibrated based on field testing and contextual norms. The ranges above are proposed starting points and should be adjusted based on the distribution of HCDI scores in the target population.

### 4.2 Interpretation

The HCDI provides a single interpretable score that summarises household capital endowments across all five dimensions. However, users should understand the following:

- **The HCDI does not replace qualitative understanding of household circumstances.** It provides a quantitative summary but cannot capture the full complexity of household life.
- **Threshold values are context-dependent.** The classification thresholds proposed above are calibrated for the Indian context. They may need adjustment for other South Asian countries or for different regional settings within India.
- **Aggregation involves trade-offs.** A household with high financial capital but low human capital may receive the same HCDI score as a household with low financial capital but high human capital. Users should examine sub-index scores in addition to the composite HCDI.
- **The Index should be used in conjunction with complementary qualitative data.** The HCDI is most useful when combined with qualitative fieldwork, case studies, and community-level assessment.

---

## 5. Missing Data Treatment

Missing data is a common challenge in household surveys. The following procedures should be followed:

### 5.1 Indicator-Level Missing Data

- If an indicator is missing for a household, impute the value using the median value of the same indicator across all households in the same stratum (e.g., same village, same wealth quintile)
- If the indicator is missing for all households in the stratum, use the national median
- If imputation is not possible, exclude the indicator from the sub-index calculation and adjust weights proportionally

### 5.2 Sub-Index-Level Missing Data

- If a sub-index cannot be calculated (e.g., too many missing indicators), classify the household as "Unclassified" and flag for follow-up
- Do not impute sub-index values

### 5.3 HCDI-Level Missing Data

- If the HCDI cannot be calculated (e.g., too many missing sub-indices), classify the household as "Unclassified" and flag for follow-up
- Do not impute HCDI values

### 5.4 Reporting

- Report the percentage of missing data at the indicator, sub-index, and HCDI levels
- Report the percentage of households classified as "Unclassified"
- Conduct sensitivity analysis to assess the impact of missing data on classification results

---

## 6. Sensitivity Analysis

Sensitivity analysis should be conducted to assess the robustness of HCDI classifications to changes in weights and thresholds.

### 6.1 Weight Sensitivity

- Test alternative weight schemes (equal weighting, factor analysis weights, expert consensus weights, participatory weights)
- Compare HCDI classifications across weight schemes
- Report the percentage of households whose classification changes across weight schemes

### 6.2 Threshold Sensitivity

- Test alternative classification thresholds (e.g., 0-25, 25-50, 50-75, 75-100 instead of the proposed thresholds)
- Compare household classifications across threshold schemes
- Report the percentage of households whose classification changes across threshold schemes

### 6.3 Interpretation

- If a large percentage of households change classification across weight or threshold schemes, the classification system is not robust and should be refined
- If a small percentage of households change classification, the classification system is robust

---

## 7. Limitations and Cautions

The scoring methodology presented in this section is an original framework developed for the Community Capital Development Project. It has not been independently validated. Users should understand the following limitations:

- **Not officially validated:** The scoring methodology has not undergone formal validation. It should be pilot-tested and validated in the target context before full deployment.
- **Context dependence:** The methodology is calibrated for the Indian context. It may need significant modification for other South Asian countries or for different regional settings within India.
- **Weight determination is value-laden:** The choice of weights reflects value judgments about the relative importance of different capital dimensions. Equal weighting provides a transparent starting point but may not reflect local priorities.
- **Thresholds are provisional:** The classification thresholds proposed above are starting points and should be calibrated based on the distribution of HCDI scores in the target population.
- **Social desirability bias:** Respondents may provide socially desirable answers, particularly on questions related to income, asset ownership, and institutional access. This can inflate sub-index scores and HCDI values.
- **Cross-sectional limitation:** The HCDI captures a snapshot of capital endowments at a point in time. It does not capture dynamics of capital accumulation, transformation, or intergenerational transmission without longitudinal follow-up.

---

## 8. Conclusion

The scoring methodology presented in this section provides procedures for aggregating questionnaire responses into composite capital indices and the Household Capital Development Index. It draws on established methods from NFHS, NITI Aayog's MPI, and the Community Capitals Framework while extending them to measure the five capital dimensions of the CCDP framework.

The methodology is designed to be transparent, reproducible, and adaptable. It should be pilot-tested, refined, and validated in the target context before full deployment. The methodology is an original framework developed by Anil Kumar Srivastava for the Community Capital Development Project and is not an official government scoring system.

The next section presents implementation guides for field deployment of the CCDP assessment tools, questionnaires, and scoring methodology.

---

## References for Scoring Methodology Section

Emery, M., & Flora, C. B. (2006). Spiraling-up: Mapping community transformation with community capitals framework. *Community Development, 37*(1), 19–35.

Flora, C. B., & Flora, J. L. (2008). *Rural communities: Legacy and change* (3rd ed.). Westview Press.

International Institute for Population Sciences (IIPS) & ICF. (2021). *National Family Health Survey (NFHS-5), 2019–21: India*. IIPS.

National Institution for Transforming India (NITI Aayog). (2023). *National Multidimensional Poverty Index: A Progress Review 2023*. Government of India. https://www.niti.gov.in/sites/default/files/2023-08/India-National-Multidimentional-Poverty-Index-2023.pdf

National Sample Survey Office (NSSO). (2019). *Key indicators of household consumer expenditure in India, 75th round (July 2017 – June 2018)*. Ministry of Statistics and Programme Implementation. https://mospi.gov.in/national-sample-survey-office

---

*Developed by Anil Kumar Srivastava | Community Capital Development Project*
