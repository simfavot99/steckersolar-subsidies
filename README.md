# Replication data and code

The Effect of Municipal Subsidy Programs on Balcony-PV Adoption in Germany
Master's thesis, University of Mannheim, 2026

One municipality is not included because its treatment dates come from a
confidential survey response. The panels therefore cover 50 municipalities
instead of the 51 used in the thesis, and the estimates differ slightly from
those reported.

Archived version: https://doi.org/10.5281/zenodo.22083534

## Files

    4_data.qmd                        Table 1, Sections 4.1 and 5.1
    6.1_dynamic.qmd                   Table 2, Figure 1
    6.2_effects_equal.qmd             Section 6.2, footnote 16
    appendix_A_all_horizons.qmd       Tables A.1, A.2
    appendix_B_carry-over.qmd         Tables B.1, B.2
    appendix_C_seasonality.qmd        Figure C.1, Table C.1
    appendix_D_static.qmd             Table D.1
    appendix_E_TWFE.qmd               Table E.1
    appendix_F_income_control.qmd     Table F.1
    appendix_G_monthly.qmd            Table G.1
    appendix_G_aggregation_rules.qmd  Alternative aggregation rules (Appendix G)

## Folders

    data/         The four panels used by the files above. data_quarterly is
                  the main one (a quarter is treated if at least one of its
                  months is). The _majority (at least 2 of 3 months) and
                  _all_months (all 3 months) versions are used only in
                  Appendix G.
    data/build/   Code that builds the panels from data/raw/. raw_data.qmd
                  makes data/raw/ from the full MaStR download of 16 June 2026
                  (564 MB, not included) and from the Destatis
                  Regionaldatenbank.
    data/raw/     Plug-in solar units in the 50 municipalities from the MaStR
                  download, and the Destatis population and income tables.
    not_reported/ Estimates that are not reported in the thesis.

## Data sources

Marktstammdatenregister (Bundesnetzagentur) and Regionaldatenbank Deutschland
(Statistische Ämter des Bundes und der Länder), both under the Data licence
Germany – attribution – version 2.0 (https://www.govdata.de/dl-de/by-2-0).
