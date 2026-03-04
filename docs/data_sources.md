# Data Sources Reference

This document inventories repository data assets and records verifiable structure, coverage, and provenance signals based on direct file/header inspection.

## data

**Location**
data/BEA_BLS_industry_lp.csv, data/BEA_BLS_industry_tfp.csv, data/autoScores.csv, data/automation_gpt4_human_labels.tsv, data/bls_occupation_demographics_2022.xlsx, data/cpsaat11.xlsx, data/full_labelset.tsv, data/full_onet_data.tsv, data/national_May2021_dl.csv, data/nem-onet-to-soc-crosswalk.xlsx, data/occ_level.csv, data/occupation_2023_final.xlsx, data/occupations_onet_basic_skills.csv, data/occupations_onet_bls_matched.csv, data/occupations_onet_work_contexts.csv, data/occupations_projections_processed.csv

**Source**
US Bureau of Economic Analysis (BEA); Office for National Statistics (ONS)

**Description**
9 .csv file(s); sample schema from `data/BEA_BLS_industry_lp.csv`: Farms, 111CA, 51.624, 49.8, 54.679, 58.859, 60.525, 65.313, 65.318, 77.657, 73.164, 77.459; rows=62 4 spreadsheet file(s); sample sheets from `data/bls_occupation_demographics_2022.xlsx`: cpsaat11 3 .tsv file(s); sample schema from `data/automation_gpt4_human_labels.tsv`: gpt4_automation, O*NET-SOC Code, Task ID, Task, Task Type, Title, human_automation; rows=19265

**Coverage**
- Time: Filename years observed: 2021 to 2023
- Geography: Not explicit in inspected headers/keys.
- Unit of observation: Industry/occupation-coded observations appear present.

**Caveats**
No additional source-specific caveat identified beyond cross-cutting caveats.


## Cross-Cutting Caveats

- Source attribution can be incomplete when provider/publication metadata is absent from local files; confirm against acquisition logs, scripts, or citations before publication use.
- Coverage summaries rely on inspected headers, sheet names, keys, and filename date patterns; validate against canonical source documentation for final claims.
- Mixed file formats and vintages can introduce schema drift and crosswalk inconsistencies; validate joins and harmonization assumptions before pooled analysis.
- Descriptive and predictive associations in these datasets do not establish causal effects without explicit identification design.

