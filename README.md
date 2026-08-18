# India English-Speaking Population Claim Audit

An evidence-led audit of the statement: **“India is the world’s second-largest English-speaking country.”**

## Verdict

The statement is **plausible as qualified historical shorthand, but not verified as a current global ranking**.

India’s official Census 2011 C-17 workbook records:

| English reported as | Persons |
|---|---:|
| Mother tongue | 259,678 |
| First subsidiary language | 82,717,239 |
| Second subsidiary language | 45,562,173 |
| **Any of the three positions** | **128,539,090** |

The total is reproducible from the official workbook:

`259,678 + 82,717,239 + 45,562,173 = 128,539,090`

The United States is clearly larger under available official measures. Second place is not fully proved because countries use incompatible questions, population scopes, reference years, and proficiency thresholds.

## Recommended wording

> India’s 2011 Census recorded about 128.5 million people who named English as one of up to three languages known. That historical count is widely cited as the world’s second largest after the United States, although no current harmonized global census confirms the ranking.

## Evidence path

1. Define what the claim could mean: mother tongue, additional language, home language, or tested proficiency.
2. Recalculate the Indian total from the official Census 2011 C-17 workbook.
3. Compare the result with official national statistics where available.
4. Record definition, date, coverage, and comparability differences.
5. Search for evidence that could disprove the ranking.
6. Separate the verified count from the unresolved global rank.

## Repository guide

| File | Purpose |
|---|---|
| [`memo.md`](memo.md) | Full claim audit, competing evidence, and conclusion |
| [`Tripti_Research_Evidence_Memo.pdf`](Tripti_Research_Evidence_Memo.pdf) | Recruiter-friendly rendered memo |
| [`methodology.md`](methodology.md) | Scope, definitions, calculation, and limitations |
| [`sources.csv`](sources.csv) | Twenty-one-source register with provenance |
| [`search-log.csv`](search-log.csv) | Reproducible search and research trail |
| [`claim-evidence-table.csv`](claim-evidence-table.csv) | Claim-level support and confidence assessment |
| [`data/india_english_counts.csv`](data/india_english_counts.csv) | Reproduced calculation output |
| [`scripts/reproduce_india_count.py`](scripts/reproduce_india_count.py) | Workbook hash check and calculation script |
| [`VERIFICATION.md`](VERIFICATION.md) | Calculation, document, and integrity checks |
| [`AUTHORSHIP_CONFIRMATION.md`](AUTHORSHIP_CONFIRMATION.md) | Tripti’s review and approval record |

## Reproduce the Indian count

1. Download `DDW-C17-0000.XLSX` from the official Census of India C-17 catalog page identified as S01 in `sources.csv`.
2. Confirm its SHA-256 hash:

   `cd74f457dbd62017c919e763e8f4e956b4f8c46c0920500907d949828ccfe673`

3. Run:

```bash
python scripts/reproduce_india_count.py DDW-C17-0000.XLSX data/india_english_counts.csv
```

Expected total: `128,539,090`.

## What this project demonstrates

- Primary-source discovery and source hierarchy
- Definition, date, and coverage checks
- Disconfirming research and conflict analysis
- Reproducible calculation with a verified source hash
- Calibrated conclusions that distinguish evidence from inference

## Scope limit

The analysis uses evidence available through 18 August 2026. It does not convert incompatible national measures into a fabricated league table, and it does not treat a 2011 Indian count as a current 2026 measurement.
