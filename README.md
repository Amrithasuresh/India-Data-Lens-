# India Data Lens

Data visualizations built on Indian government data — NCRB, Census, NFHS, ECI — with a focus on state-level depth, especially Tamil Nadu.

## Live Site

Deployed via Vercel. Each folder is a self-contained project with its own `index.html` and `data/` folder.

## Structure

```
India-Data-Lens/
├── index.html                  ← Landing page
├── vercel.json                 ← Vercel routing config
├── README.md
└── goondas-act-india/          ← Project 1 (live)
    ├── index.html
    ├── data/
    │   ├── national_preventive_detention_trend.csv
    │   ├── statewise_detenus_snapshot.csv
    │   ├── tamil_nadu_goondas_act_details.csv
    │   ├── tn_detenu_age_profile.csv
    │   └── tn_detenu_education_profile.csv
    └── docs/
        ├── REFERENCES.md
        └── PDF_DOWNLOAD_LINKS.md
```

## Adding a New Project

1. Create a new folder: `mkdir my-new-project`
2. Add `index.html` + `data/` inside it
3. Add a card to the main `index.html` projects grid
4. Push — Vercel auto-deploys

## Data Sources

| Project | Source | Years |
|---|---|---|
| Goondas Act | NCRB Crime in India, PSI, TN SCRB | 2017–2021 |

## Deploying to Vercel

1. Push this repo to GitHub (private)
2. Go to vercel.com → New Project → Import from GitHub
3. Framework: Other (static HTML)
4. Root directory: `./` (leave default)
5. Deploy — done

No build step needed. Pure HTML/CSS/JS.
