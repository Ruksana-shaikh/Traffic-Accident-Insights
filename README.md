# Road Accident Analysis

## 📌 Problem Statement

Road accidents are a major public safety concern worldwide. Identifying accident patterns based on **time, weather, road conditions, and locations** can help policymakers, law enforcement, and city planners design safer roads and implement effective safety measures.

This project explores accident data through **Exploratory Data Analysis (EDA)** and **visualizations** to uncover key trends, contributing factors, and accident hotspots.

---

## 📂 Dataset

* **File Used:** `accident_data.csv`
* **Rows:** 147 (sample dataset for analysis)
* **Columns:**

  * `Date`, `Time` – accident date & time
  * `Latitude`, `Longitude` – accident location
  * `Location Description` – road type (Highway, Street, Intersection)
  * `Weather Conditions` – Clear, Rainy, Foggy, etc.
  * `Road Conditions` – Wet, Dry, etc.
  * `Visibility` – Clear or Poor
  * `Accident Type` – Collision, Rollover, etc.
  * `Injury Severity` – Minor, Moderate, Severe
  * `Contributing Factors` – Speeding, Drunk Driving, Weather, etc.
  * `Vehicle Type`, `Vehicle Speed`, `No of Vehicles`
  * `Day of Week`, `Month`, `Year`

---

## 🔎 Steps Performed

1. **Data Cleaning & Preparation**

   * Converted date and time into proper datetime format
   * Extracted additional features like `Hour` of the accident

2. **Exploratory Data Analysis (EDA)**

   * Accident frequency trends over the years
   * Accidents by **road conditions**
   * Accidents by **weather conditions**
   * Accidents by **time of day**

3. **Spatial Analysis**

   * Accident hotspots using latitude/longitude scatter plots

4. **Visualizations**

   * Line plots, bar plots, and scatter plots with Seaborn & Matplotlib

---

## 📊 Results & Insights

<img width="886" height="606" alt="image" src="https://github.com/user-attachments/assets/12b5d050-e3b4-4a1d-aaeb-f3db9a3e00d5" />
<img width="519" height="433" alt="image" src="https://github.com/user-attachments/assets/6114562a-77e7-4188-a972-6020eca1703e" />
<img width="724" height="712" alt="image" src="https://github.com/user-attachments/assets/1a96f57f-2ec8-42bb-abc3-bc3a70e91a27" />

* Accidents were more frequent in **poor weather and wet road conditions**
* **Evening hours** showed higher accident counts compared to mornings
* Highways recorded more **severe accidents**, while streets saw more minor/moderate ones
* **Hotspot visualization** revealed clusters in urban centers (New York, Chicago, San Francisco, Los Angeles)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas, NumPy
* Matplotlib, Seaborn

---

## 📌 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/Ruksana-shaikh/road-accident-analysis.git
   cd road-accident-analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   Jupyter Notebook accident_analysis.ipynb
   ```

---

## 📈 Future Work

* Use **machine learning models** to predict injury severity or accident likelihood
* Apply **geospatial visualization tools** (Folium, Plotly maps) for advanced hotspot analysis
* Integrate external datasets (traffic density, weather APIs) for deeper insights

---

## 📬 Contact

* **Author:** Ruksana Shaikh
* **Linkedin** (https://www.linkedin.com/in/ruksana-ks)
* **GitHub:** (https://github.com/Ruksana-shaikh)
* **Email:** (mail to: shaikhruksana.k@gmail.com)
---

✨ *If you like this project, don’t forget to ⭐ the repo!*
