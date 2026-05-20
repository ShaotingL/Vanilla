# CR0040A-only rostellum key gene analysis

This analysis uses only the public sequencing runs remapped to the user's `CR0040_HaplotypeA` reference and the resulting featureCounts matrix. Article results, HPP92/KAG IDs, and WGCNA modules are intentionally held out from ranking and should be compared only after this analysis is complete.

## QC

- Excluded `SRR24981847` (`B_S2_A`) because assigned reads were 462 and STAR unique mapping was 0.06%.
- Analyzed samples: 38; genes: 26392.

## Local CR0040A MADS-like bait genes

- `VANPL_A_00001t031260` score=2.31 PF00319+PF01486: putative MADS-box protein SVP
- `VANPL_A_00001t004780` score=1.98 PF00319+PF01486: Floral homeotic protein AGAMOUS
- `VANPL_A_00003t009520` score=1.66 PF00319: Agamous-like MADS-box protein AGL62
- `VANPL_A_00010t006110` score=1.46 PF00319+PF01486: Floral homeotic protein AGAMOUS
- `VANPL_A_00009t012690` score=1.32 PF00319: putative Agamous-like MADS-box protein AGL11
- `VANPL_A_00012t007660` score=1.26 PF00319+PF01486: putative MADS-box transcription factor 32

## Top qPCR candidates

| gene | score | rost_idx | S3 | S4 | BGR/B | MADS corr | CArG | note |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| `VANPL_A_00001t017650` | 19.00 | 4.64 | 6.20 | 3.09 | 3.62 | 0.67 | 2 | Sugar transport protein MST3 |
| `VANPL_A_00012t008630` | 17.60 | 4.67 | 5.02 | 4.31 | 1.60 | 0.61 | 3 | aspartic proteinase CDR1-like |
| `VANPL_A_00004t004860` | 16.51 | 3.11 | 4.69 | 1.52 | 5.44 | 0.66 | 3 | Bidirectional sugar transporter SWEET4 |
| `VANPL_A_00009t008760` | 16.21 | 4.28 | 6.49 | 2.06 | 3.65 | 0.69 | 4 | hypothetical protein |
| `VANPL_A_00001t033180` | 15.37 | 3.24 | 4.72 | 1.77 | 4.31 | 0.85 | 2 | Invertase inhibitor |
| `VANPL_A_00001t028930` | 14.25 | 2.86 | 4.37 | 1.35 | 4.69 | 0.71 | 2 | Subtilisin-like protease SBT5.3 |
| `VANPL_A_00002t004950` | 13.31 | 2.49 | 2.08 | 2.89 | 3.41 | 0.86 | 2 | LOB domain-containing protein 11-like |
| `VANPL_A_00010t001660` | 13.26 | 2.66 | 4.65 | 0.66 | 4.83 | 0.74 | 3 | putative LOB domain-containing protein 20 |

## Recommended interpretation

Prioritize genes with consistent S3/S4 GR>G signal, local CR0040A MADS-like co-expression, promoter CArG motif, and functions compatible with local organ growth or cell-wall remodeling. Do not use article results for prioritization at this stage; compare against the article only after the CR0040A analysis is complete.
