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
   * Extracted additional features like `Hour` of accident

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
   jupyter notebook accident_analysis.ipynb
   ```

---

## 📈 Future Work

* Use **machine learning models** to predict injury severity or accident likelihood
* Apply **geospatial visualization tools** (Folium, Plotly maps) for advanced hotspot analysis
* Integrate external datasets (traffic density, weather APIs) for deeper insights

---

## 👩‍💻 Author

**Ruksana Shaikh**

* 🌐 [GitHub](https://github.com/Ruksana-shaikh)
* 💼 [LinkedIn](#) *(add your link)*

---

✨ *If you like this project, don’t forget to ⭐ the repo!*

---

Would you like me to also generate a **`requirements.txt`** file (Pandas, Seaborn, Matplotlib) so anyone can run this repo smoothly?
