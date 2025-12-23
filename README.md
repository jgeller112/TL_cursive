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
│   │   └── read_data.qmd
│   │
│   ├── 02-Data_preprocessing/
│   │   └── data_preprocessing.qmd
│   │
│   ├── 03-RT_Preprocessing/
│   │   └── rt_preprocessing.qmd
│   │
│   ├── 04-RT_analysis/
│   │   └── rt_analysis.qmd
│   │
│   ├── 05-acc_preprocessing/
│   │   └── acc_preprocessing.qmd
│   │
│   ├── 06-acc_analysis/
│   │   └── acc_analysis.qmd
│   │
│   ├── 07-probe/
│   │   └── probe_analysis.qmd
│   │
│   └── 08-Figures/
│       └── figures.qmd
│
├── Raw_files/
│   ├── *.csv          # Pavlovia behavioral output (one file per participant)
│   ├── *.log.gz       # Pavlovia log files
│   └── README.md
│
├── .gitignore
├── README.md
└── LICENSE

