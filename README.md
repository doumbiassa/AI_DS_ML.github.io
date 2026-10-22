# Messy Data Library

Synthetic practice datasets for learning to clean, scale and visualize data.
Curated by **Moussa Doumbia, Ph.D.**, Expert in AI, Machine Learning and Data Science,
Department of Mathematics, Howard University, Washington, DC.

All people, places, organizations and numbers in the data are invented.

**Website:** https://doumbiassa.github.io/AI_DS_ML.github.io/

Each dataset comes in two files:

- `data/<name>.csv`: raw version with planted data-quality problems (work on this one)
- `data/<name>_clean.csv`: cleaned reference version (check your results against it)

Load any file directly in Python:



| Record | Dataset | Subject | Rows | File |
|---|---|---|---|---|
| MDL-001 | Student Success & Study Habits | Education | 1,215 | `data/student-success.csv` |
| MDL-002 | Riverton 311 Service Requests | Government | 5,060 | `data/riverton-311.csv` |
| MDL-003 | Harbor City Short-Term Rentals | Business | 3,025 | `data/harbor-rentals.csv` |
| MDL-004 | Bean There Coffee Sales | Business | 8,050 | `data/bean-there-coffee.csv` |
| MDL-005 | Community Clinic Vitals | Health | 2,000 | `data/clinic-vitals.csv` |
| MDL-006 | Music Track Audio Features | Entertainment | 4,040 | `data/track-features.csv` |
| MDL-007 | Craft Beer Chemistry | Food & Drink | 1,500 | `data/craft-brew.csv` |
| MDL-008 | Maple County Home Sales | Real Estate | 2,520 | `data/maple-county-housing.csv` |
| MDL-009 | AirWatch Sensor Readings | Environment | 10,701 | `data/airwatch-sensors.csv` |
| MDL-010 | LinkUp Telecom Customer Churn | Business | 4,000 | `data/linkup-churn.csv` |
| MDL-011 | ShopNest Online Orders | Business | 6,045 | `data/shopnest-orders.csv` |
| MDL-012 | Glide Bike-Share Trips | Transportation | 7,000 | `data/glide-bikeshare.csv` |
| MDL-013 | Fictional Nations Indicators | Social Science | 728 | `data/nations-indicators.csv` |
| MDL-014 | Riverton Restaurant Inspections | Government | 3,500 | `data/riverton-inspections.csv` |
| MDL-015 | Summit Analytics Employee Records | Business | 1,800 | `data/summit-hr.csv` |
| MDL-016 | Metro Basketball League Stats | Sports | 681 | `data/metro-hoops.csv` |
| MDL-017 | Kalindra Malaria Surveillance | Health | 1,460 | `data/kalindra-malaria.csv` |
| MDL-018 | Tuberculosis Treatment Outcomes | Health | 3,000 | `data/tb-outcomes.csv` |
| MDL-019 | Memory & Aging Cohort | Health | 2,119 | `data/memory-cohort.csv` |
| MDL-020 | Heart Disease Risk Study | Health | 1,818 | `data/heart-disease.csv` |
| MDL-021 | COVID-19 County Daily Reports | Health | 12,296 | `data/covid19-counties.csv` |
| MDL-022 | Influenza-Like Illness Surveillance | Health | 3,234 | `data/flu-surveillance.csv` |
| MDL-023 | Common Cold Symptom Diary | Health | 2,500 | `data/common-cold-diary.csv` |
| MDL-024 | Riverton Crime Incidents | Public Safety | 9,070 | `data/riverton-crime.csv` |
| MDL-025 | Gun Violence Incidents | Public Safety | 2,249 | `data/gun-violence-incidents.csv` |
| MDL-026 | Regional Flight Delays | Transportation | 12,060 | `data/regional-flights.csv` |
| MDL-027 | Fuel & Crude Oil Prices | Energy | 2,749 | `data/fuel-prices.csv` |

`source/` holds the Python scripts that generated the data. Running `python source/generate.py`
rebuilds every file into `source/site/data/`.

**Headshot:** add a square photo named `headshot.jpg` next to `index.html` (about 400 × 400 pixels).
