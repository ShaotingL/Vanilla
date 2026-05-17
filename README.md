# Vanilla Rostellum MADS Target Analysis

This repository contains an HTML report for CR0040A-only *Vanilla planifolia* rostellum MADS-box target prioritization.

Main report:

- `index.html`

View on GitHub:

- https://github.com/ShaotingL/Vanilla/blob/main/index.html

Render as HTML with htmlpreview:

- https://htmlpreview.github.io/?https://github.com/ShaotingL/Vanilla/blob/main/index.html

Notes:

- RNA-seq preprocessing was based on `nf-core/rnaseq v3.21.0`; the default alignment/quantification mode is `--aligner star_salmon` (STAR alignment followed by Salmon quantification).
- The current candidate ranking uses the available project count matrix at `results/counts/PRJNA985237_CR0040A_raw_counts_20251114_012801.txt`.
- I did not find a standard Salmon merged gene-count matrix such as `star_salmon/salmon.merged.gene_counts.tsv` under the current `results/` directory. If that file is located later, the ranking should be rerun from the Salmon matrix.
- Article gene IDs, WGCNA modules, and published candidate results are held out from ranking; they should be compared only after the CR0040A analysis is complete.
- This online report is a compact HTML version for browsing outside the local workstation.
- Raw data, genome references, RNA-seq counts, and intermediate tables are not included.
- The local full report with embedded PCA and heatmap images remains at `/mnt/d/Vanilla/rostellum_target_analysis/cr0040a_only/CR0040A_rostellum_MADS_target_report.html`.
