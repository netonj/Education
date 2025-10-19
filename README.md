# Education Project

> This project explores how certain socioeconomic variables influence high school ACT score.

---

## Project Overview


- **Objective:** Explain how ACT score can be influenced by certain socioeconomic factors to identify disparity in test performance.
- **Domain:** Education
- **Key Techniques:** Statistical comparison and time-series.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** EdGap data: https://github.com/brian-fischer/DATA-5100/blob/main/EdGap_data.xlsx; Schools information data: https://www.dropbox.com/scl/fi/fkafjk8902sq8ptxh94r2/ccd_sch_029_1617_w_1a_11212017.csv?rlkey=gucrdz5f6e38bezz2y3yalxbw&e=1&dl=0
- **Description:** The raw data for EdGap had 7986 entries and 7 columns, containing the ACT average variable. The Schools information set had 102183 entries and 65 columns, containing the relevant socioeconomic data.
- **License:** NA

---

## Analysis

After cleaning and combining the two data sets, simple categorial analysis was conducted. The primary analyis, however, was done by regression modeling. Single variable regression, multiple variable regression, and comparisons of their results informed the conclusion.

---

## Results

Percentage of students on school lunch is the strongest predictor of average ACT score in this analysis. As percentage of students on free or reduced lunch increases, average ACT score decreases.

---

## Authors

- Jack Neton - [@netonj](https://github.com/netonj)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- NOAA, pandas,numpy, matplotlib, seaborn
- DATA 5100 at Seattle University taught by Brian Fischer.
