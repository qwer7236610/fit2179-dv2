# Two Paths to Later Life in Australia

FIT2179 Data Visualisation 2 — Mingqi He, May 2026.

A single-page data story comparing **home care** and **residential aged care** across
Australia, from the major cities to the most remote communities. The headline finding:
distance from a capital changes the *form* of aged care, not *whether* it reaches people.

**Live page:** [https://qwer7236610.github.io/fit-2179-DATA-VIS-II/](https://qwer7236610.github.io/fit2179-dv2/)


## Repository structure

```
index.html        The visualisation (open this / GitHub Pages serves it)
specs/            Vega-Lite v5 JSON for every chart and map (human-readable)
data/            Source data used by the charts
```

Each diagram and map is a Vega-Lite v5 specification in `specs/`, embedded in
`index.html` with `vega-embed`. The maps use a Mercator projection over SA3 boundaries.

## Data

Two open datasets, combined at SA3 (Statistical Area Level 3), both CC BY:

- **AIHW** — GEN "People using aged care by region" data tables, 2024–25.
  https://www.gen-agedcaredata.gov.au/resources/access-data/2026/february/gen-data-people-using-aged-care-by-region
- **ABS** — Regional population by age and sex, 2024.
  https://www.abs.gov.au/statistics/people/population/regional-population-age-and-sex/latest-release

Per-capita rates are derived as AIHW counts ÷ ABS population at SA3 level.

## Use of AI

Generative AI (Claude) was used to help interpret the data, refine the choice and design
of the charts, write and refine the Vega-Lite specifications, and draft and edit the
narrative text. See the "About this visualisation" section on the page for the full
acknowledgement.
