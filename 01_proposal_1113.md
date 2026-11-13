ICE ICE Baby: The Analysis of ICE Misconduct from 2016 and Beyond
================
Athena Li (al4922), Qixuan Cao (qc2385), Diego Antonio Quintana Licona
(daq2107) Sania Sheifuddin (sm5975), Nina Knitowski (nck2132)
2026-11-13

## Group Members

| Name                          | UNI     |
|-------------------------------|---------|
| Athena Li                     | al4922  |
| Qixuan Cao                    | qc2385  |
| Diego Antonio Quintana Licona | daq2107 |
| Sania Sheifuddin              | sm5975  |
| Nina Knitowski                | nck2132 |

## Motivation

Under the recent administration, there has been a clear trend: a massive
increase in criminalization surrounding US immigration with a 214%
increase in arrests comparing Term 2 to 1 (East et a.l, 2026). We wanted
to look at the data to summarize ICE reports quantitatively and
qualitatively to see what the data says behind our current discussions
around immigration and the scope of ICE’s authority. This data will help
us answer How has reported misconduct changed since 2016 and How long do
investigations take, and does this vary by category or outcome? As
enforcement activity expands, so does the potential for misconduct, yet
these records are rarely examined systematically.

## Final Products

The products we intend to create are an ICE misconduct search engine
(input a location, misconduct category, case status, and characteristics
of misconduct) and an interactive map of misconduct incidents across the
US.

## Data Sources

This dataset covers incident rates from 2016 onwards. Key variables
include a free-text case summary; primary and secondary reasons for the
case; incident, reported, created, and close dates; case type, class
code, and resolution; case status; incident location, subject office,
and facility; subject type (e.g., employee or contractor); whether the
case falls under the Prison Rape Elimination Act (PREA); and the
database allegedly misused. We intend to utilize database records Dhruv
Mehrota obtained via a Freedom of Information Act request:
<https://airtable.com/appxK2tDF0YAZMSOX/shrodU77cgvD2e8dc/tblwELYkSA0fNXgKF>.

## Analysis

We plan to begin by cleaning and tidying, check that each column value
makes sense, and standardize missing values in the dataset (convert to
NA if needed). Plots intended to include incident misconduct over time,
bar graphs of misconduct by state, bar plots for length of investigation
(from reported date to closed date), and visualizations to illuminate
trends of misconduct over time and geographic locations that we decide
to highlight in the final project. In these visualizations, we would
consider how the search engine itself should be formatted (a search bar
or search bar for key terms or another format).

Challenges in this process may come from merging datasets that have info
scraped from a variety of sources and from collaborating on the coding
analysis via github. Primary and secondary case reasons, case type,
class code, resolution, and the “database misused” field may contain
inconsistent labels that need to be collapsed into analytic categories;
cases with a secondary reason will also need to be handled so they
aren’t double-counted in summaries.

## Planned Timeline

| Date | Task |
|----|----|
| Nov 13 (by 1:00 pm) | Submit proposal via Canvas and team UNI form |
| Nov 13 - Nov 18 | Data feasibility assessment: import data, perform preliminary cleaning and descriptive statistics, evaluate whether the data can support our research questions, and prepare a backup project idea |
| Nov 19 - Nov 20 | Project review meeting with teaching team. Decide whether to proceed with the current dataset or switch to the backup project |
| Nov 21 - Nov 26 | Complete data cleaning (standardize formats, remove duplicates, derive new variables such as case processing time) |
| Nov 27 - Dec 2 | Exploratory analysis and visualizations |
| Dec 3 - Dec 6 | Build project website, write report, and conduct internal code review |
| Dec 7 - Dec 10 | Produce 2 minute screencast: write script, record, edit, upload, and embed in website |
| Dec 11 - Dec 12 | Final review of website, code reproducibility, and screencast length, complete peer assessments, submit all deliverables by Dec 12, 11:59 pm |
| Dec 17 | In-class project discussion |

## Citations

East, C. N., Patler, C., & Cox, E. (2026). ICE arrests, 2015–2026:
Variation in targeting, method, and geography. Proceedings of the
National Academy of Sciences, 123(31), e2618096123.
<https://doi.org/10.1073/pnas.2618096123>
