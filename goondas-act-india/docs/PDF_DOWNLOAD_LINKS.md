# NCRB Report PDF Links — Direct Download

All links below are direct PDF URLs. Click or paste into browser to download.
NCRB blocks automated downloads but these URLs work manually in a browser.
Internet Archive mirrors are freely accessible without any login.

---

## NCRB Official Site (ncrb.gov.in)

> Note: NCRB blocks robots but direct PDF links work in a browser.
> If a link fails, use the Internet Archive mirrors below — they are identical files.

### Crime in India (CII) — Volume III contains Preventive Detention chapter

| Year | Direct PDF URL | Notes |
|------|---------------|-------|
| 2023 | https://www.ncrb.gov.in/uploads/files/1CrimeinIndia2023PartI.pdf | Part I only published so far |
| 2022 Vol I | https://www.ncrb.gov.in/uploads/nationalcrimerecordsbureau/custom/1701607577CrimeinIndia2022Book1.pdf | Vol I |
| 2022 Snapshots | https://www.ncrb.gov.in/uploads/nationalcrimerecordsbureau/custom/ciiyearwise2022/17016097489aCII2022Snapshots-StateandUTs.pdf | State/UT summary |
| 2020 Vol III | https://www.ncrb.gov.in/uploads/nationalcrimerecordsbureau/custom/1653724294_CII2020%20Volume%203.pdf | **Has preventive detention data** |

### Prison Statistics India (PSI) — Has detenus data by state and demographics

| Year | Direct PDF URL |
|------|---------------|
| 2022 | https://www.ncrb.gov.in/uploads/nationalcrimerecordsbureau/custom/psiyearwise2022/1701613297PSI2022ason01122023.pdf |

---

## Internet Archive Mirrors (Free, No Login Required)

These are the same NCRB reports hosted on archive.org — no login, no blocking.

### Crime in India — Full Collection
https://archive.org/details/CrimeInIndia-ncrb
*(Collection page — contains multiple years)*

### Crime in India 2022

| Volume | Internet Archive URL |
|--------|---------------------|
| Volume I | https://archive.org/details/PARI.crime-in-india-2022-volume-i |
| Volume II | https://archive.org/details/PARI.crime-in-india-2022-volume-ii |

### CII 2019 Volume III (Scribd — free to view)
https://www.scribd.com/document/487163722/CII-2019-Volume-3

---

## People's Archive of Rural India (PARI) — ruralindiaonline.org

PARI has mirrored all NCRB reports and they download cleanly.

| Report | URL |
|--------|-----|
| Crime in India 2022 Vol I | https://ruralindiaonline.org/en/library/resource/crime-in-india-2022-volume-i/ |
| Crime in India 2022 Vol II | https://ruralindiaonline.org/en/library/resource/crime-in-india-2022-volume-ii/ |

---

## Thakur Foundation Report (Most Useful — Pre-compiled Data)

**This PDF contains the actual data tables you need:**
- TN detenus 2016–2020 (age, education, caste, religion)
- District-wise TN Goondas Act detentions (RTI data)
- Category-wise breakdown (goonda / bootlegger / drug offender)

Direct PDF: https://www.thakur-foundation.org/upload/judgements/1649834297_Akila%20RS,%20Preventive%20Detentions%20under%20Tamil%20Nadu%20Goondas%20Act%20(1).pdf

---

## End Now Foundation (CII 2021 mirror)

Full Crime in India 2021 report (compressed):
https://endnowfoundation.org/wp-content/uploads/2023/04/Crime-in-India-2021-NCRB-1_compressed.pdf

---

## Bar & Bench (CII 2022 mirror)

https://images.assettype.com/barandbench/2023-12/dc0ba053-a1f0-4e6a-a5f8-e7668ddd2249/NCRB_STATS.pdf

---

## How to Find the Preventive Detention Table in Each PDF

Once you open any CII PDF, the preventive detention data is in:
- **CII reports**: Search for "Table 17A" or "Preventive Detention" or "Chapter 17"
- **PSI reports**: Search for "detenus" or "Table 7" — shows state-wise detenus in prison on 31 Dec
- **The Goondas Act (State and Central)** row = the specific number you want

---

## Data to Manually Fill Into CSV

When you open the PDFs, fill these rows into `data/national_preventive_detention_trend.csv`:

| Year | Look for in PDF | Table name |
|------|----------------|------------|
| 2017 | CII 2017, Chapter 17 | Table 17A — Preventive Detentions |
| 2018 | CII 2018, Chapter 17 | Table 17A |
| 2019 | CII 2019 Vol III | Table 17A |
| 2020 | CII 2020 Vol III (link above works) | Table 17A |
| 2021 | CII 2021 (End Now Foundation link above) | Table 17A |
| 2022 | CII 2022 Vol III | Table 17A |

And for `data/statewise_detenus_snapshot.csv`:
- Open PSI for each year → search "detenus" → Table showing state-wise count on 31 Dec
