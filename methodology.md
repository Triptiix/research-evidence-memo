# Methodology

## Research standard

The memo uses a claim-audit method rather than accepting the most repeated statistic. The test is whether the rank can be reproduced from current, nationally representative sources using a consistent definition of “English speaker.”

## Scope

- Cut-off date: 18 August 2026
- Unit of analysis: persons, not households or test scores
- Preferred evidence: national statistical offices, census tables, official methodology, and original datasets
- Secondary evidence: used to trace circulation of the claim, not to establish the ranking

## Operational definitions tested

1. **Mother tongue / first language** — too narrow for India; captures 259,678 people in Census 2011.
2. **English named among languages known** — India C-17 measure; includes mother tongue plus two subsidiary languages, without a published proficiency threshold in the table.
3. **English used at home** — used by the United States and Australia; excludes many people who speak English but use another language at home.
4. **Ability to conduct a conversation / self-rated proficiency** — used in Canada and England and Wales; closer to functional ability but still not identical across questionnaires.
5. **Standardized proficiency index** — useful for skill comparisons, but not a population headcount and not representative of the full population when test takers are self-selected.

## India calculation

Source: Census of India 2011, table C-17, all-India workbook, state code `00`.

- English mother tongue: column 5 where total-language name is English
- English first subsidiary language: sum of column 10 where first-subsidiary name is English
- English second subsidiary language: sum of column 15 where second-subsidiary name is English
- Total: the sum of those mutually positioned categories

Result:

| Category | Persons |
|---|---:|
| Mother tongue | 259,678 |
| First subsidiary language | 82,717,239 |
| Second subsidiary language | 45,562,173 |
| Total | **128,539,090** |

The local reproduction script refuses to run if the source workbook hash differs from the verified download.

## Comparator test

The United States is unambiguously above the Indian count even under a conservative measure: the 2024 ACS records 247,695,110 people age five or older who speak only English at home. The broader ACS category “English only or English very well” is 292,827,195. These measures are not identical to India’s, but either confirms the United States as larger.

Official measures for England and Wales, Canada, and Australia are far below 128.5 million, but use different universes and questions. Pakistan’s 2023 census publishes mother-tongue categories, not a national English-ability headcount. EF EPI reports comparable test scores for self-selected adult test takers, not population totals.

## Decision rule

The unqualified global rank is accepted only if:

1. India has a recent national count;
2. plausible comparator countries have equivalent national counts;
3. the counts use materially comparable age universes and thresholds; and
4. no unmeasured country could plausibly alter the ranking.

The evidence fails conditions 1–3. Therefore the unqualified current ranking is not verified.

## Known limitations

- India’s latest published language count remains Census 2011; Census 2027 results do not yet exist.
- The Indian table records up to three languages known and does not measure proficiency on a shared international scale.
- National questionnaires differ by age, household universe, language-at-home wording, and proficiency threshold.
- This review did not infer national totals from nonrepresentative online tests.
- Absence of a comparable official count is not evidence that a country has fewer English speakers.
