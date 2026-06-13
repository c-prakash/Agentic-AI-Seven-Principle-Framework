# Appendix C. Bibliometric Descriptors

## C.1 Publication Venue and Publisher Distribution

The 25 included studies were distributed across three publisher families and 21 distinct publication venues. Table 18 presents the full publication venue breakdown.

**Table 18. Distribution of Included Studies by Publication Venue and Publisher (N = 25)**

| n | Venue | Publisher | Domain(s) |
|---:|---|---|---|
| **Publisher Group: IEEE (n = 11, 44.0%)** |  |  |  |
| 5 | IEEE Conference Proceedings (various) | IEEE/ieeexplore.ieee.org | CDS, Admin, Monitoring |
| 2 | IEEE Access (journal) | IEEE | Multi-domain, Cross-domain |
| 1 | IEEE Transactions (journal) | IEEE | Patient Monitoring |
| 1 | ACM/IEEE Joint Conference | IEEE | CDS – Radiology |
| 2 | IEEE Conference (Bioinformatics/Biomedical) | IEEE | CDS |
| **Publisher Group: Nature / Springer Nature (n = 7, 28.0%)** |  |  |  |
| 1 | Nature Medicine | Springer Nature | Regulatory / Safety |
| 1 | Nature Cancer | Springer Nature | CDS – Oncology |
| 1 | Nature | Springer Nature | CDS – Rare Disease |
| 2 | npj Digital Medicine | Springer Nature | CDS – Multi-Cancer; CDS – Patient Education |
| 1 | Nature Medicine | Springer Nature | CDS – Patient Interaction (CRAFT-MD) |
| 1 | Scientific Reports | Springer Nature | Monitoring – Ophthalmology |
| **Publisher Group: Elsevier (n = 7, 28.0%)** |  |  |  |
| 1 | European Journal of Radiology Artificial Intelligence | Elsevier | CDS – Radiology |
| 1 | Value in Health | Elsevier | CDS – Evidence Synthesis |
| 1 | Clinical Radiology | Elsevier | CDS – Oncology Imaging |
| 1 | American Journal of Medicine | Elsevier | CDS – E-Medicine |
| 1 | ESMO Real World Data and Evidence | Elsevier | CDS – Oncology |
| 1 | Heart Rhythm O2 | Elsevier | Admin – Cardiology Workflow |
| 1 | Parkinsonism and Related Disorders | Elsevier | Monitoring – Neurology |

*Note: Publisher group subtotals shown in italicized rows. The IEEE count of 11 includes both journals and conference proceedings published by IEEE.*

IEEE-affiliated publications represent the largest publisher group (n = 11; 44.0%), encompassing both peer-reviewed journal publications (IEEE Access, IEEE Transactions) and conference proceedings in biomedical engineering, bioinformatics, and ubiquitous computing. Nature/Springer Nature publications accounted for 7 included studies (28.0%), with representation across Nature, Nature Cancer, Nature Medicine, npj Digital Medicine, and Scientific Reports. Elsevier publications also accounted for 7 included studies (28.0%) and spanned domain-specific journals in radiology AI, health technology assessment, clinical oncology, cardiology, and neurology. Publication venue and publisher family were extracted only as descriptive metadata and were not used as indicators of methodological quality, clinical relevance, or evidentiary strength.

The publisher distribution reflects the interdisciplinary nature of agentic healthcare AI research, spanning computer science, biomedical engineering, clinical, and health informatics venues. Evidence maturity was assessed using study design, evaluation context, data source, comparator availability, outcome validity, limitations transparency, and quality-appraisal score rather than publisher family.

## C.2 Citation Analysis

Citation counts were extracted directly from the structured metadata of the source corpus. The 25 included studies accumulated a total of 500 citations at the time of corpus extraction (April 2026), with a mean of 20.0 citations per study (SD ≈ 45.1) and a median of 3 citations. The marked difference between the mean and median indicates a strongly right-skewed distribution, consistent with citation patterns in rapidly evolving fields, where a small number of high-impact publications account for the majority of citations. Citation counts ranged from 0 to 218. Five studies (20.0%) had received zero citations at the time of extraction, nine studies (36.0%) had accumulated 1–4 citations, four studies (16.0%) had 5–9 citations, and seven studies (28.0%) had 10 or more citations. Table 19 presents the full citation frequency distribution, and Table 20 identifies the five most cited studies in the corpus.

**Table 19. Citation Frequency Distribution of Included Studies (N = 25)**

| Citation Range | No. of Studies | Percentage (%) | Venue Predominance |
|---|---:|---:|---|
| 0 citations | 5 | 20.0% | IEEE Conference proceedings (n=4); IEEE Access (n=1) |
| 1–4 citations | 9 | 36.0% | Mixed: IEEE (n=5); Elsevier (n=3); Nature-family (n=1) |
| 5–9 citations | 4 | 16.0% | Elsevier (n=2); IEEE (n=1); Nature-family (n=1) |
| 10–49 citations | 5 | 20.0% | IEEE (n=2); Elsevier (n=1); Nature-family (n=2) |
| 50–99 citations | 0 | 0.0% | — |
| 100–199 citations | 1 | 4.0% | Nature Cancer (Ferber et al., 2025) |
| ≥ 200 citations | 1 | 4.0% | Nature Medicine (Johri et al., 2025) |
| **TOTAL** | **25** | **100.0%** | **Mean = 20.0; Median = 3; Range = 0–218** |

**Table 20. Five Most Cited Studies in the Included Corpus**

| First Author (Year) | Venue | Citations | Significance |
|---|---|---:|---|
| Johri et al. (2025) | Nature Medicine | 218 | CRAFT-MD: first standardized evaluation framework for clinical LLM reasoning in patient interaction tasks |
| Ferber et al. (2025) | Nature Cancer | 142 | First validation of an autonomous AI agent for multi-step oncology clinical decision-making |
| Zhao et al. (2026) | Nature | 43 | DeepRare: agentic rare disease diagnosis evaluated on MIMIC-IV-Rare benchmark |
| Freyer et al. (2025) | Nature Medicine | 21 | Authoritative taxonomy of regulatory barriers to healthcare AI agent deployment |
| Shimgekar et al. (2025) | IEEE Conference | 16 | End-to-end agentic clinical data inference pipeline across multiple dataset types |

The three most cited studies are all published in the Nature family, Nature Medicine (n=218), Nature Cancer (n=142), and Nature (n=43), consistent with the citation advantage that high-impact journals confer. Notably, the fifth-highest-cited study (Shimgekar et al. [43], n=16) is an IEEE conference paper, indicating that technically substantive IEEE contributions can achieve meaningful citation impact in this field. The Freyer et al. [37] regulatory analysis in Nature Medicine (n=21) is the most cited non-CDS publication, confirming that safety and regulatory considerations are an active area of scholarly engagement rather than peripheral concerns. The high proportion of studies with zero or low citations (5 with 0 citations; 9 with 1–4) is expected, given that many studies were published within 12 months of corpus extraction. Several of these studies are in IEEE conference proceedings, which typically accumulate citations more slowly than journal publications and are frequently updated by journal versions. Citation counts were highly skewed, with two studies accounting for a large share of citations.

## C.3 Authorship Characteristics

Author counts across the 25 included studies ranged from 1 to 8, with a mean of 4.2 (SD ≈ 1.8) and a median of 4. The majority of studies (n = 18; 72.0%) involved teams of 3–6 authors, consistent with the collaborative team science norms of applied AI and clinical research. Only one study was single-authored (Pai [29] - IEEE conference), and two studies had a maximum of 8 authors (Zhao et al. [7] - Nature; Liu et al.[13] - npj Digital Medicine). The Nature-family studies exhibited the highest mean author count (mean=5.6), reflecting the larger cross-institutional research consortia typically required for clinical validation studies suitable for high-impact venues. IEEE conference papers exhibited the lowest mean author count (mean = 3.1), consistent with their typically more circumscribed technical scope. Table 21 presents the author count distribution.

**Table 21. Authorship Distribution of Included Studies (N = 25)**

| Author Count | No. of Studies | Percentage (%) | Publisher Group (Predominant) |
|---|---:|---:|---|
| 1 author | 1 | 4.0% | IEEE Conference (n=1) |
| 2 authors | 2 | 8.0% | Elsevier (n=1); IEEE Conference (n=1) |
| 3 authors | 6 | 24.0% | IEEE (n=5); Elsevier (n=1) |
| 4 authors | 5 | 20.0% | Nature-family (n=2); IEEE (n=2); Elsevier (n=1) |
| 5 authors | 5 | 20.0% | Nature-family (n=3); IEEE (n=1); Elsevier (n=1) |
| 6 authors | 4 | 16.0% | Nature-family (n=1); IEEE (n=2); Elsevier (n=1) |
| 7 authors | 0 | 0.0% | — |
| 8 authors | 2 | 8.0% | Nature-family (n=2) |
| **TOTAL** | **25** | **100.0%** | **Mean = 4.2; Median = 4; Range = 1–8** |
