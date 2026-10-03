# CLAUDE.md

`nchalohhwatersurvey` is an openwashdata R data package with the 2021
household and community survey from rural communities around Nchalo,
Malawi, collected with mWater.

## Package facts

- Raw data: `data-raw/Nchalo household survey 2021.csv`.
- Processing script: `data-raw/data_processing.R`. It writes
  `data/nchalohhwatersurvey.rda` and the CSV and XLSX exports in
  `inst/extdata/`. Its `read_csv()` call names
  `data-raw/usaid flood response malawi 2019.csv`, which is not in this
  repo.
- Data dictionary: `data-raw/dictionary.csv`.
- Branches: work and review PRs go to `dev`; `main` holds released
  versions.

## Reviews and releases

Reviews and releases follow the installed pkgreview skills.
`/review-package` starts a review, `/review-issue` works through one
review issue, `/create-release` makes a release and `/add-doi` adds the
Zenodo DOI. The skills hold the steps and the current standards, so this
file does not repeat them.
