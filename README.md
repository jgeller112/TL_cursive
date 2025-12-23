# TL_cursive

**Transposed-Letter Effects in Print vs. Cursive Script**

This repository contains data and Quarto-based analyses for a lexical decision
experiment examining how **orthographic confusability**
(Transposed Letters vs. Replaced Letters) interacts with **script**
(print vs. cursive) across reaction time, accuracy, and probe memory measures.

All analyses are written in **Quarto (`.qmd`)** and organized as a
stepwise, reproducible pipeline.

---

## 📁 Repository Structure

```text
TL_cursive/
├── Analysis/
│   ├── 01-Read_Data/
│   ├── 02-Data_preprocessing/
│   ├── 03-RT_Preprocessing/
│   ├── 04-RT_analysis/
│   ├── 05-acc_preprocessing/
│   ├── 06-acc_analysis/
│   ├── 07-probe/
│   └── 08-Figures/
│
├── Raw_files/
│   ├── 27851_HW_LDT_1_2025-10-20_11h42.34.556.csv
│   ├── 27851_HW_LDT_1_2025-10-20_11h42.34.556.log.gz
│   ├── 28003_HW_LDT_1_2025-11-08_21h31.47.875.csv
│   ├── 28003_HW_LDT_1_2025-11-08_21h31.47.875.log.gz
│   ├── 28348_HW_LDT_1_2025-10-16_10h38.39.242.csv
│   ├── 28348_HW_LDT_1_2025-10-16_10h38.39.242.log.gz
│   ├── 29278_HW_LDT_1_2025-10-15_18h18.58.000.csv
│   ├── 29278_HW_LDT_1_2025-10-15_18h18.58.000.log.gz
│   ├── 29493_HW_LDT_1_2025-10-16_13h44.20.014.csv
│   └── ... (additional participant data)
│
├── .gitignore
├── README.md
└── LICENSE


