# Age-Based Community Detection in Mental Health Symptom Networks  
### Using PHQ-9, GAD-7, and PSS-10

This repository contains all scripts, analysis code, and the accompanying AAAI-style report for a study investigating how mental health symptom networks differ across age groups.  
Using PHQ-9, GAD-7, and PSS-10 survey data, we construct correlation-based networks, perform Louvain community detection, and measure structural similarity across age groups using ARI and NMI.

---

## Overview

Mental health symptoms often co-occur in structured and interpretable ways. Network-based analysis makes it possible to model these relationships as graphs instead of treating disorders as isolated entities.

This project explores:

- How symptom communities differ across age groups  
- Whether depression, anxiety, and stress symptoms become more or less integrated with age  
- How similar or different symptom networks are between age demographics  

We find that younger adults display fragmented symptom clusters, while older adults show more integrated stress–anxiety–depression structures.

---

## Key Results

### Symptom Communities by Age Group
- **18–25 years:** 4 communities; highest fragmentation; PSS items split across multiple clusters.
- **26–35 years:** 4 communities; greater cohesion among PHQ and GAD items.
- **36–50 years:** 3 communities; anxiety and depression become more integrated.
- **51+ years:** 3 communities; strongest cross-domain merging (stress–anxiety–depression).

### ARI & NMI Scores

| Age Groups          | ARI   | NMI   |
|--------------------|--------|--------|
| 18–25 vs 26–35     | 0.853  | 0.837 |
| 18–25 vs 36–50     | 0.698  | 0.669 |
| 18–25 vs 51+       | 0.585  | 0.561 |
| 26–35 vs 36–50     | 0.846  | 0.798 |
| 26–35 vs 51+       | 0.574  | 0.557 |
| 36–50 vs 51+       | 0.574  | 0.557 |

Similarity decreases as age differences increase—suggesting structural shifts in how symptoms interact across the lifespan.

---

## Directory Structure

