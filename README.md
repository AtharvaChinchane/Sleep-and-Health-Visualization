
<h1>💤 Sleep & Health Visualization</h1>

An exploratory analysis project that combines multiple datasets to explore how sleep patterns relate to cognitive performance, lifestyle, and health indicators.

## 📚 Datasets

1. **Sleep Deprivation (detailed)**
   Columns include:

   * `Participant ID`, `Sleep Hours`, `Sleep Quality Score`
   * Cognitive measures: `Daytime Sleepiness`, `Stroop Task Reaction Time`, `N Back Accuracy`, `Emotion Regulation Score`, `PVT Reaction Time`, `Caffeine Intake`, `Physical Activity Level`, `Stress Level`

2. **Sleep Health & Lifestyle**
   Columns include:

   * `Participant ID`, `Gender`, `Age`, `Occupation`
   * `Sleep Hours`, `Sleep Quality Score`
   * Health indicators: `Physical Activity Level`, `Stress Level`, `BMI Category`, `Blood Pressure`, `Heart Rate`, `Daily Steps`, `Sleep Disorder`

3. **Sleep Analysis Lifestyle Survey**
   Columns include:

   * Demographics (`Age`, `Gender`)
   * `meals/day`, `physical illness`, `screen time`, `bluelight filter`, `sleep direction`, `exercise`, `smoke/drink`, `beverage`, and computed `sleep time`

---

## 🔗 Data Processing & Integration

* Renamed columns for consistency across all datasets:

  * Example: `Sleep Quality Score`, `Participant ID`, `Physical Activity Level`, `Stress Level`, etc.
* Converted quality scores to numeric and rescaled them to a 0–10 scale.
* Rounded `Sleep Hours` to nearest integer for easier analysis.

---

## 🔍 Analysis Highlights

* **Distribution visualizations** of sleep hours and sleep quality across participants.
* **Correlations** between sleep quality and:

  * Reaction time (`PVT`, `Stroop`)
  * Cognitive accuracy (`N Back`)
  * Emotion regulation
* **Lifestyle factors**:

  * BMI, stress, caffeine intake, physical activity
  * Sleep disorders — e.g., insomnia, sleep apnea
* **Survey insights**:

  * Effects of screen time, blue light, exercise frequency, smoking/drinking habits, and beverage type on sleep duration.

---

## 🛠️ How to Run

1. Clone the repo and navigate to the project directory:

   ```bash
   git clone https://github.com/AtharvaChinchane/Sleep-and-Health-Visualization.git
   cd Sleep-and-Health-Visualization
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

3. Open and run the notebook:

   ```bash
   jupyter notebook Sleep.ipynb
   ```

---

## 🎯 Usage

* **Extend Analysis**: Add further statistical modeling, e.g., regression of sleep quality.
* **Improve Visuals**: Create interactive dashboards (Plotly, Bokeh) for enhanced UI.
* **Clean Survey Data**: Normalize categorical variables and encode for deeper analysis.
* **Time-Series Tracking**: If you collect longitudinal sleep data, build trend tracking models.

---

## 🔗 Resources & Acknowledgements

* Datasets sourced from in‑house studies or public sleep research files.
* Cognitive tests included: **Stroop**, **PVT**, **N‑Back**.

---

## 🧑‍💻 Author

**Atharva Chinchane**
Explore the notebook here: [Sleep.ipynb on GitHub](https://github.com/AtharvaChinchane/Sleep-and-Health-Visualization/blob/main/Sleep.ipynb)
