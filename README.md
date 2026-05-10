# 🌾 Food Security Monitoring Dashboard — Benin (2020–2023)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![CSV](https://img.shields.io/badge/Data-CSV-green?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

> An interactive Power BI dashboard tracking food insecurity, malnutrition, and agricultural production across the 12 departments of Benin — built to support evidence-based decision-making for NGOs, public health organizations, and development agencies.

---

## 📊 Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

---

## 🎯 Project Objective

Food insecurity remains a critical challenge in West Africa. This project provides a **clear, visual, and interactive monitoring tool** that allows decision-makers to:

- Track food insecurity rates by department and season
- Compare the North (more vulnerable) vs. South/Centre regions
- Analyze the relationship between agricultural production and food insecurity
- Monitor malnutrition trends from 2020 to 2023

---

## 🔍 Key Findings

| Indicator | Value |
|---|---|
| Average food insecurity rate | **~27%** |
| Average malnutrition rate | **~16%** |
| Total households surveyed | **~2.5 million** |
| Most affected region | **North (Atacora, Alibori, Donga)** |
| Trend | North remains stable at ~36% — urgent intervention needed |

**Main insight:** Departments with higher agricultural production (>1,400 kt) consistently show lower food insecurity rates — confirming that supporting local agriculture directly reduces vulnerability.

---

## 🛠️ Tools & Methodology

| Step | Tool |
|---|---|
| Data simulation | Python (random, csv) |
| Data cleaning & transformation | Power Query (Power BI) |
| Data modeling | DAX measures |
| Visualization | Power BI Desktop |

**Data source:** Simulated dataset modeled after FAO/WFP methodology for food security assessments in West Africa. Dataset structure mirrors real-world IPC (Integrated Food Security Phase Classification) surveys.

---

## 📁 Repository Structure

```
├── securite_alimentaire_benin.csv   # Dataset (96 rows, 9 variables)
├── dashboard_preview.png            # Dashboard screenshot
└── README.md                        # Project documentation
```

---

## 📌 Variables in the Dataset

| Column | Description |
|---|---|
| `Département` | One of 12 administrative departments |
| `Année` | Year (2020–2023) |
| `Saison` | Season: Dry (Sèche) or Rainy (Pluies) |
| `Taux_insécurité_alim_%` | Food insecurity rate (%) |
| `Taux_malnutrition_%` | Malnutrition rate (%) |
| `Production_agricole_kt` | Agricultural production (kilotons) |
| `Ménages_enquêtés` | Number of households surveyed |
| `Aide_alimentaire_reçue_%` | Food aid coverage rate (%) |
| `Zone` | Region: North or South/Centre |

---

## 👤 About the Author

**Patrick Alloumon Gbeho**
Webmaster & Junior Data Analyst — Cotonou, Benin 🇧🇯

I help organizations across West Africa turn raw data into clear, actionable insights — combining web expertise with data visualization to support better decisions.

- 🌍 Open to remote collaboration worldwide
- 📧 Contact me via [LinkedIn](https://linkedin.com/in/) 
- 💼 Available for freelance projects, NGO partnerships, and data consulting

---

## 📜 License

This project is open source under the [MIT License](LICENSE).  
Feel free to fork, adapt, and build upon this work — credit appreciated.

---

*Built with 💛 from Cotonou, Benin*
