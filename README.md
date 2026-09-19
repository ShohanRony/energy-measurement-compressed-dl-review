# Energy Measurement of Compressed Deep Learning Models: A Literature Review

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22842954.svg)](https://doi.org/10.5281/zenodo.22842954)

Shohinur Pervez Shohan, September 2026. [paper.pdf](paper.pdf) · [Zenodo record (DOI)](https://doi.org/10.5281/zenodo.22842954)

A narrative literature review (not an original-measurement study) examining how the
energy of compressed deep learning models is measured, and whether model compression
reliably reduces energy in practice. Corpus of 53 works (2019-2026), assembled
purposively per the methodology in Section 1.4 of the paper.

## What's in this repo

The review's empirical content is the set of measurement results, tool errors, and
study characteristics it draws from the corpus. Those are extracted here as structured
data so every number in the paper's tables is checkable independently of the PDF.

| File | Paper reference | Rows |
|---|---|---|
| `data/table1_supplementary_search.csv` | Table 1 (Section 1.4) | 7 |
| `data/table2_measurement_tools.csv` | Table 2 (Section 2.3) | 15 |
| `data/table3_primary_studies.csv` | Table 3 (Section 2.4) | 21 |
| `data/table4_gap_evidence_matrix.csv` | Table 4 (Section 7.2) | 6 |
| `data/corpus_references.csv` | Full reference list (Section "References") | 53 |

Every row traces back to a numbered table or the reference list in `paper.pdf`; there
is no code because the review synthesizes measurements reported in prior publications
rather than running its own experiments.

## Scope note

This is a review, not a benchmark suite. "Data" here means the review's own
extracted evidence tables, not raw sensor logs — the underlying measurements were
collected by the cited papers, not by this project.
