# CR0040A Vanilla Rostellum MADS Target Analysis

This repository contains the GitHub-facing entry pages for the CR0040A-only Vanilla rostellum MADS-box target prioritization analysis.

## 直接看網頁版

GitHub 的 `blob/main/*.html` 頁面會顯示 HTML 原始碼，不會直接像網頁一樣 render。請用下面其中一種方式開：

- [Main report rendered by htmlpreview](https://htmlpreview.github.io/?https://github.com/ShaotingL/Vanilla/blob/main/index.html)
- [Discussion summary rendered by htmlpreview](https://htmlpreview.github.io/?https://github.com/ShaotingL/Vanilla/blob/main/discussion_summary.html)
- [Main report via raw.githack](https://raw.githack.com/ShaotingL/Vanilla/main/index.html)
- [Discussion summary via raw.githack](https://raw.githack.com/ShaotingL/Vanilla/main/discussion_summary.html)

如果之後啟用 GitHub Pages，正式網址會是：

- https://shaotingl.github.io/Vanilla/

啟用位置：Repository `Settings` -> `Pages` -> `Build and deployment` -> `Deploy from a branch` -> `main` / `/root` -> `Save`.

## Files

- `index.html` - GitHub entry page for the CR0040A rostellum analysis
- `discussion_summary.html` - discussion and revision record
- `CR0040A_rostellum_experiment_logic_flowchart.md` - experiment logic flowchart
- `CR0040A_rostellum_analysis_summary.md` - compact analysis summary
- `build_cr0040a_html_report.py` - supporting report-generation script

Large raw data, genome reference files, RNA-seq counts, and intermediate tables are intentionally not included.
