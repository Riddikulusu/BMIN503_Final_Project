# Spatial Analysis of Hospital Accessibility and District-Level Mortality in Philadelphia

**Objective:**\
Assess whether spatial differences in hospital availability and accessibility are associated with district-level mortality in Philadelphia, accounting for demographic and socioeconomic factors.

**Method:**\
I calculate district-level hospital accessibility using tract-population–weighted distances to the nearest hospital and link these metrics with annual mortality data (2013–2022). After describing temporal patterns, I fit regression models—from unadjusted to fully adjusted SDOH models—to evaluate whether hospital count and accessibility predict mortality. Diagnostic checks, VIF assessment, and sensitivity analyses are used to test robustness.

**Materials:**

-   `final_project_template.qmd`: analysis code

-   `DOH_Hospitals202311`: hospital locations (PA)

-   `Planning_Districts`: district boundaries for accessibility calculation

-   `Vital_Mortality_PD.csv`: district-level mortality

-   `Vital_Social_Determinants_PD.csv`: SDOH indicators

**Expected Contribution:**\
Provide an initial assessment of whether disparities in healthcare access relate to differences in mortality across Philadelphia districts, supporting evidence-based planning and health equity efforts.
