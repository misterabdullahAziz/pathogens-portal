---
title: SARS-CoV-2 serology tests by the SciLifeLab Autoimmunity and Serology Profiling unit
description: The dashboard displays the SARS-CoV-2 serology tests completed over time at the at SciLifeLab Autoimmunology and Serology Profiling unit. The number of tests in total and the amount of positive/negative tests over time are shown.
banner: /dashboard_thumbs/auto_sero.jpg
toc: false
menu:
  main:
    identifier: serology-statistics
    parent: health_data
    weight: 10
  dashboard_menu:
    identifier: serology
    name: Serology tests for SARS-CoV-2 at SciLifeLab
aliases:
  - /data_types/health_data/serology-statistics/
dashboards_topics: [COVID-19, Infectious diseases]
---

<div class="alert alert-info">
  <i class="bi bi-exclamation-triangle-fill"></i>
  <span>The data on this page are largely historic, though they may be updated occasionally. The Autoimmunity and Serology Profiling unit has now expanded their pandemic preparedness efforts to include tests for multiple other viruses. Information about that work can be found on the <a href="/dashboards/serology_multidisease/"> Multiplex and high-throughput multi-disease serology dashboard</a>.</span>
</div>

Serology tests involve testing bodily fluids for the presence of antibodies or other substances. Since the beginning of the pandemic, the SciLifeLab Autoimmunity and Serology Profiling unit has conducted serology tests for antibodies targetting SARS-CoV-2 proteins. The unit has continuously provided the latest data to the Swedish Pathogens Portal. In each of the below sections, we show the numbers of samples that were **positive**, **negative** or **research and development (R&D)**.

- **Positive tests**: Serology tests indicating the _presence_ of immunoglobulin G (IgG) antibodies targetting SARS-CoV-2 proteins.
- **Negative tests**: Serology tests indicating the _absence_ of immunoglobulin G (IgG) antibodies targetting SARS-CoV-2 proteins.
- **R&D tests**: All of the remaining serum, plasma, and saliva samples that were completed to test the levels IgG, IgM, or IgA antibodies targeting SARS-CoV-2 proteins. This includes all of the positive and negative controls, all replicated and re-ran samples and assays, all samples analysed during the continuous development and optimisation of the tests, technically failed samples, and all research associated projects.

<div class="alert alert-info">Data last updated: {{% serology_date_modified %}}.</div>

## Number of serology tests completed

The below plot shows the total number (sum total) of serology tests related to SARS-CoV-2 completed by the SciLifeLab Autoimmunity and Serology Profiling unit since the beginning of the pandemic. The proportion of tests that indicated an infection with SARS-CoV-2 (proportion positive) is also shown. The plot shows the total number of positive, negative, and research & development (R&D) tests completed over time.

<br>

<div class="d-lg-none alert alert-info">
  Scroll the plot sideways to view all of the data.
</div>

<div class="plot_wrapper">
  <div class="w-100" id="total-number"></div>
</div>

## Weekly serology tests

The number of SARS-CoV-2 serology tests completed by the SciLifeLab Autoimmunity and Serology Profiling unit each week, divided according to whether tests were positive, negative, or research & development (R&D).

<div class="d-lg-none alert alert-info">
  Scroll the plot sideways to view all of the data.
</div>

<div class="plot_wrapper">
  <div class="w-100" id="bar-chart"></div>
</div>

## Cumulative serology tests

The cumulative number of positive, negative, and research & development (R&D) SARS-CoV-2 serology tests completed over time at the SciLifeLab Autoimmunity and Serology Profiling unit.

<div class="d-lg-none alert alert-info">
  Scroll the plot sideways to view all of the data.
</div>

<div class="plot_wrapper">
  <div class="w-100" id="cumulative-plot"></div>
</div>

#### About serology testing at the Autoimmunity and Serology Profiling unit

Early in the COVID-19 pandemic, work was initiated to [develop a serological assay](https://www.scilifelab.se/covid-19/kaw-program/serology/) for large scale testing of plasma and serum samples for antibodies against SARS-CoV-2. The work was undertaken by three research groups at [KTH Royal Institute of Technology (KTH)](https://www.kth.se) and the [Autoimmunity and Serology Profiling unit](https://www.scilifelab.se/facilities/autoimmunity-profiling/) at [SciLifeLab](https://www.scilifelab.se). The development of the assay has been funded by Knut and Alice Wallenberg Foundation, Erling-Persson Family Foundation, SciLifeLab, KTH, Region Stockholm, Atlas Copco, Mercodia, Family Christian and Jennifer Dahlberg, and Family Birgitta Klasén.

By comparing and combining a large number of variants of SARS-CoV-2 proteins as antigens, a highly sensitive and specific multiplex bead-based assay was established. The high-throughput assay can be used to process up to 8000 samples per week. The vast majority of samples analysed to date originated from healthcare personnel, population-based studies, personnel in the pharmaceutical and biotechnology industry, and from within multiple research collaborations. Collaborators and sample providers include Danderyd University Hospital ([see news involving a follow-up study at Danderyd University Hospital](https://www.scilifelab.se/news/four-out-of-five-still-have-antibodies-against-sars-cov-2)), Karolinska University Hospital, Uppsala University Hospital, Skåne University Hospital, Örebro University Hospital, Sophiahemmet Hospital, Public Health Agency of Sweden, RISE (Research Institutes of Sweden), AstraZeneca, Cytiva, SVPH, Karolinska Institutet, KTH, Uppsala University, and Lund University.

Check out the [Autoimmunity and Serology Profiling unit page](https://www.scilifelab.se/units/autoimmunity-profiling/) on the SciLifeLab website to find out more about the unit itself. Publications produced by studies making use of the unit are available in the [SciLifeLab Infrastructure Publications database](https://publications.scilifelab.se/label/Autoimmunity%20and%20Serology%20Profiling).

<script src="https://cdn.jsdelivr.net/npm/vega@5.12.1"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-lite@4.12.2"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-embed@6.8.0"></script>

<script src="https://datagraphics.dc.scilifelab.se/graphic/e5c031600d334d889f33080d3f0ac0dd.js?id=bar-chart"></script>
<script src="https://datagraphics.dc.scilifelab.se/graphic/4c635b2679e648e384d952dd3e506ff1.js?id=cumulative-plot"></script>
<script src="https://datagraphics.dc.scilifelab.se/graphic/63d9201aee8747c9b37c17ebb6b01c35.js?id=total-number"></script>
