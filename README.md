# 🩺 Public Health Explorer

A data exploration and analysis project using a public health survey dataset to derive insights into patients' health conditions, sleeping troubles, doctor visits, and more — all through Python and visualization tools.

> 📊 Built by [Sonali Kumari](https://github.com/sonalee88) — AI & Data Engineer | ML • LangChain • Cloud | Exploring Human-Centered AI

---

## 📁 Project Structure

This project was developed using **Google Colab** and is organized in the following way:

- `public_health_explorer.ipynb` – Main analysis notebook
- `summary_report.txt` – Text file containing summary statistics

---

## 📌 Objective

Analyze a public health dataset to:

- Calculate average health, age, and doctor visit metrics
- Understand distribution of sleeping issues and their causes
- Explore relationships between age and health
- Segment patient demographics based on race and gender

---

## 🧪 Dataset Overview

The dataset contains **714** records with **15 columns**:

| Column Name                                      | Description                                  |
|--------------------------------------------------|----------------------------------------------|
| Number of Doctors Visited                        | Number of doctor visits                      |
| Age                                              | Age of the patient                           |
| Physical Health                                  | Self-reported physical health (numeric)      |
| Mental Health                                    | Self-reported mental health (numeric)        |
| Dental Health                                    | Self-reported dental health (numeric)        |
| Employment                                       | Employment status                            |
| Stress / Medication / Pain / Bathroom / Unknown  | Reasons keeping patient from sleeping        |
| Trouble Sleeping                                 | Whether the patient has trouble sleeping     |
| Prescription Sleep Medication                    | If they use prescription sleep aids          |
| Race                                             | Race category                                |
| Gender                                           | Gender category                              |

---

## 📊 Key Analyses

- ✅ Average health score, age, and number of doctors visited
- ✅ Patient count reporting trouble sleeping
- ✅ Sleep issues due to stress, medication, pain, etc.
- ✅ Scatter plot: Age vs Health Score
- ✅ Bar chart: Distribution of patients by race

---

## 📷 Visualizations

<img src="https://github.com/sonalee88/public-health-explorer/blob/main/assets/age_vs_health.png" width="500">
<img src="https://github.com/sonalee88/public-health-explorer/blob/main/assets/race_distribution.png" width="500">

*(Update this section with your actual image links if you add screenshots)*

---

## 🛠️ Technologies Used

- Python (pandas, matplotlib, seaborn)
- Google Colab
- Git & GitHub

---

## 📝 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/sonalee88/public-health-explorer.git
   cd public-health-explorer
