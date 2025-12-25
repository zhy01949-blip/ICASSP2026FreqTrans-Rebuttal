# FreqTrans: Rebuttal and Supplementary Materials

This repository provides the revised manuscript, detailed responses to reviewers, and supplementary experimental materials for the paper:

**FreqTrans: Adaptive Frequency Feature Fusion for Robust Breast Ultrasound Image Analysis**

submitted to **ICASSP**.

The goal of this repository is to transparently document all revisions, additional experiments, and analyses conducted in response to reviewer comments.

---

## 1. Revised Manuscript

- `paper/ICASSP_2024_revised.pdf`  
  The revised version of the manuscript, addressing all reviewer comments, including:
  - Clarified method descriptions and notation
  - Improved figure resolution and annotations
  - Added recent medical and frequency-aware baseline methods
  - Refined experimental analysis and discussion

- `paper/ICASSP_2024_original.pdf`  
  The original submission (for reference).

---

## 2. Response to Reviewers

- `rebuttal/Response_to_Reviewers.pdf`  
  A point-by-point response to all reviewer comments, explicitly indicating:
  - Each reviewer concern
  - Corresponding revisions
  - Exact sections, tables, or figures where changes were made

- `rebuttal/Change_Log.md`  
  A concise summary of major changes between the original and revised versions.

---

## 3. Additional Experiments and Statistical Results

Due to page limitations, some robustness analyses are provided here:

- `experiments/stats_mean_std.txt`  
  Mean ± standard deviation results over multiple runs with different random seeds.

- `experiments/tables/`  
  Raw experimental results on the UDIAT and BUSI datasets in CSV format.

---

## 4. Model Interpretability and Visualization

To improve clinical interpretability, additional qualitative results are provided:

- `visualizations/GradCAM_UDIAT/`  
- `visualizations/GradCAM_BUSI/`  

These folders contain Grad-CAM visualizations comparing baseline models and FreqTrans, demonstrating improved lesion-focused attention.

---

## 5. Summary of Revisions

The revised manuscript includes the following key updates:

- Added comparisons with recent domain-specific and frequency-aware methods (e.g., HoVer-Trans, FABRF-Net)
- Reported robustness statistics (mean ± standard deviation) over multiple runs
- Included additional interpretability analysis via Grad-CAM visualizations
- Clarified frequency decomposition, fusion weights, and attention mechanisms
- Improved overall presentation, formatting, and citation consistency

---

## 6. Note on Supplementary Materials

Due to the strict page limit of ICASSP, some experimental details and visualizations are provided in this GitHub repository.  
All supplementary materials are consistent with the results reported in the revised manuscript.

---

## Contact

For any questions regarding the revisions or supplementary materials, please refer to the corresponding authors listed in the manuscript.
