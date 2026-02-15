# export-credit-risk-lab
This repository documents an ongoing analytical project that revisits my undergraduate thesis in Economics on export credit insurance claims.

The goal is not to build a production model, but to explore a more mature data science approach to export credit risk: explicit data engineering, transparent assumptions, probabilistic record linkage, and interpretable machine learning.

The project combines insurance claims data with public information on BNDES export financing, treating financing contracts as a proxy for exposure and explicitly acknowledging data bias and institutional limitations.

This is an open laboratory for experimenting with ETL design, fuzzy matching with confidence scores, exploratory analysis, and risk-oriented modeling — with an emphasis on methodological clarity over predictive performance.

## Project Roadmap

[✓] Phase 1 — Insurance Claims ETL  
- Clean and standardized ETL pipeline  
- Text normalization and entity handling  
- Explicit assumptions and reproducibility  

[✓] Phase 2 — BNDES Export Financing Data  
- Standardize entities, dates, and contract attributes
- Treat financing as exposure proxy  

[ ] Phase 3 — Probabilistic Record Linkage  
- Fuzzy matching between claims and financing datasets  
- Similarity scores and confidence thresholds  
- Explicit handling of unmatched records  

[ ] Phase 4 — Unified Analytical Dataset  
- Merge claims and financing into a single table  
- Preserve linkage uncertainty  
- Enable exploratory analysis  

[ ] Phase 5 — Exploratory Analysis & Modeling  
- Interpretable, risk-oriented models  
- Focus on patterns and ordering, not point prediction  
- Transparent discussion of limitations  
