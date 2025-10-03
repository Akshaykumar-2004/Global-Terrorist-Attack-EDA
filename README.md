# Exploratory Data Analysis of the Global Terrorism Database (GTD) 🕵️‍♂️

## 📌 Overview
This project presents an in-depth **exploratory data analysis (EDA)** of the **Global Terrorism Database (GTD)**, which documents over **180,000 terrorist attacks worldwide between 1970 and 2017**.  

The goal of this analysis is to uncover key **trends, patterns, and hotspots** in global terrorism to better understand its evolution and impact.  
This is not just a technical exercise, but an application of data science to a dataset with **major social and historical implications**.  

The entire analysis is documented in the Jupyter Notebook provided in this repository.  

---

## 🎯 Project Goals
- Identify trends in terrorist activities over time  
- Pinpoint geographical hotspots with the highest concentration of attacks  
- Analyze the most common methods of attack and types of weapons used  
- Identify the most active and impactful perpetrator groups  
- Tell a **data-driven story** of global terrorism over nearly five decades  

---

## 💾 Dataset
- **Source:** [Kaggle - Global Terrorism Database](https://www.kaggle.com/)  
- **Maintained by:** National Consortium for the Study of Terrorism and Responses to Terrorism (START)  
- **Content:** Information on more than **181,000 terrorist attacks**  
- **Time Period:** 1970 - 2017  
- **Columns:** Original dataset has 135 columns; analysis reduced this to 13 key features  

---

## 🛠️ Tools and Libraries
This project was conducted in a **Python 3.x** environment, using:  

- **Pandas** – data manipulation, cleaning, and preprocessing  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – visualizations  
- **Jupyter Notebook** – interactive environment  

---

## 🔄 Project Workflow
1. **Data Loading and Exploration**  
   - Loaded the dataset (181,691 rows × 135 columns)  
   - Handled encoding issues (`latin1`)  

2. **Data Cleaning and Preprocessing**  
   - Selected 13 relevant features  
   - Renamed columns for readability (e.g., `iyear` → `Year`)  
   - Filled missing values in `Killed` and `Wounded` columns with zeros  
   - Created new **Casualties** column (`Killed + Wounded`)  

3. **Data Analysis & Visualization**  
   - Trends over time  
   - Regional hotspots  
   - Attack methods and tactics  
   - Perpetrator groups  

---

## 📊 Key Findings
- **Dramatic Rise in Attacks** – Terrorist activities surged after 2004, peaking in 2014  
- **Geographical Concentration** – Most attacks occurred in the **Middle East & North Africa** and **South Asia**  
- **Dominant Tactics** – Bombings/Explosions were most common, followed by armed assaults  
- **Key Perpetrators** – Groups like the **Taliban** and **ISIL** were disproportionately responsible.  
- A significant **“Unknown”** category shows many attacks were unclaimed  

---

## 🚀 How to Use This Repository
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

   📌 Disclaimer

This project is for educational and research purposes only. The analysis is based on publicly available data and aims to promote understanding of global terrorism patterns through data science.


   cd your-repo-name

