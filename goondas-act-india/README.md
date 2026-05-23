# Goondas Act in India — Data & Visualization

A data repository and interactive dashboard on preventive detentions under Goondas Acts across India, based on NCRB annual reports, TN SCRB Crime Review data, and civil society research.

## Live Dashboard

Open `index.html` in any browser, or deploy to GitHub Pages.

## Repository Structure

```
goondas-act-india/
├── index.html                          # Main interactive dashboard
├── README.md                           # This file
├── docs/
│   └── REFERENCES.md                   # Full citations and source URLs
└── data/
    ├── national_preventive_detention_trend.csv      # All-India totals 2017–2021
    ├── statewise_detenus_snapshot.csv               # State-wise prison snapshot (31 Dec each year)
    ├── tamil_nadu_goondas_act_details.csv           # TN-specific Goondas Act breakdowns
    ├── tn_detenu_age_profile.csv                    # Age distribution of TN detenus (2016–2020)
    └── tn_detenu_education_profile.csv              # Education profile of TN detenus (2016–2020)
```

## Key Findings

- India had **1,10,151** preventive detentions in 2021 — a 23.7% rise from 2020, highest since NCRB tracking began in 2017
- **Tamil Nadu alone accounted for 51.2%** of all preventive detenus in India (confirmed by Supreme Court and Madras High Court citing NCRB data)
- In TN, **89% of all preventive detentions** are under the Goondas Act (TN SCRB Crime Review 2021)
- **75% of TN detenus** had not completed Class X education (NCRB PSI 2020)
- **95% of habeas corpus petitions** in Madras HC over 22 years (2000–2022) related to the Goondas Act

## Data Sources

| Source | Type | Access |
|---|---|---|
| NCRB Crime in India (2017–2023) | National totals, state/UT-wise, act-wise | Free download — ncrb.gov.in |
| NCRB Prison Statistics India (1995–2022) | Detenus in prison; demographics | Free download — ncrb.gov.in |
| TN SCRB Crime Review | District-wise, category-wise TN data | scrb.tn.gov.in or RTI |
| Thakur Foundation Report (2022) | Compiled NCRB + SCRB + RTI data | Free PDF — thakur-foundation.org |
| data.gov.in | Machine-readable Crime in India tables | data.gov.in/catalog/crime-india-2022 |

See `docs/REFERENCES.md` for full URLs and citation formats.

## Data Gaps & Notes

- NCRB did not publish preventive detention data before 2017
- District-level breakdown for most states requires RTI filing
- Category-wise (goonda / bootlegger / drug offender) breakdown publicly available only for Tamil Nadu
- 2022 and 2023 NCRB reports are published but preventive detention chapters may be in Vol. III (not yet fully digitised on open platforms)

## How to Get More Data

1. **NCRB website**: ncrb.gov.in → Publications
2. **TN SCRB**: scrb.tn.gov.in (Crime Review PDFs)
3. **RTI**: File at rtionline.gov.in with State Home Department or District Collector
4. **Thakur Foundation Report**: Best single compiled source for TN — includes annexure with raw district-wise and category-wise data not available elsewhere

## Contributing

If you have access to newer NCRB data, district-level RTI responses, or data from other states, open a pull request to add rows to the CSV files.

## License

Data sourced from Government of India publications (open access). Visualization code is MIT licensed.
