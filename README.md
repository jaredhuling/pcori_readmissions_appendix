# Appendix Supplement — PCORI Methods Award ME-2022C1-26326

Online supplement to the Final Research Report for PCORI methods award **ME-2022C1-26326**,
"Data-adaptive readmissions models for heterogeneous and longitudinal data" (PI: Jared Huling,
University of Minnesota). This repository hosts the appendix components that cannot be included
in the report's single appendix file: interactive visualizations and software archives.

## Interactive nomograms (Appendix C)

Self-contained interactive visualizations of the fitted readmission risk model's covariate
effects, developed with stakeholder input. View them directly in a browser:

- **Overall covariate effects:**
  <https://jaredhuling.github.io/pcori_readmissions_appendix/nomograms/Saved_Plotly_Coefficients_final_model.html>
- **Subgroup-specific (MDC/DRG) covariate effects:**
  <https://jaredhuling.github.io/pcori_readmissions_appendix/nomograms/Saved_Plotly_SubgroupEffect_final_model.html>

The HTML files in `nomograms/` are fully self-contained (no external resources) and can also be
downloaded and opened locally in any browser.

## Software (Appendix C)

Archival source snapshots of the two open-source R packages exactly as described in the report:

- `software/hierNest_1.0.4.tar.gz` — Aim 1: hierarchical nested re-parameterization and
  structured regularization for subgroup-heterogeneous risk models.
- `software/swjm_0.1.3.tar.gz` — Aim 2: stagewise variable selection for joint semi-competing
  risks models of recurrent readmission and death.

Installation instructions are in [INSTALL.md](INSTALL.md). The packages are actively maintained
in their own repositories, which are the authoritative sources for current versions:

| Package | Development repository | Documentation website |
|---|---|---|
| hierNest | <https://github.com/ZirenJiang/hierNest> | <https://zirenjiang.github.io/hierNest/> |
| swjm | <https://github.com/jaredhuling/swjm> | <https://jaredhuling.org/swjm/> |

## About the project

The project developed two complementary methodological frameworks for hospital readmission risk
modeling from electronic health records linked with Medicare claims: (Aim 1) hierarchical,
diagnosis-adapted risk models that borrow strength across related patient subgroups, and (Aim 2)
penalized variable selection for joint models of recurrent readmissions and death. The Final
Research Report will be available in the PCORI literature database following peer review.
