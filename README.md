# Aviation Accident Safety Analysis

## Project Overview
This project provides a data-driven evaluation of commercial and passenger airplane safety to assist an airline/airplane insurer in underwriting risk. Analyzing aviation accident data from 1983 to 2023, this study identifies professional-build aircraft makes and models with low rates of total destruction and minimal fatal or serious passenger injuries.

## Key Visualizations & Analysis Summary

> **Note:** To render the visualizations, save the charts generated in Jupyter Notebook to an `images` folder in your repository and ensure the file paths below match your saved files.

### 1. Large Commercial Aircraft (> 20 Passengers)
![Large Aircraft Safety](images/large_planes_safety.png)

* **Recommended Makes:** Boeing, Airbus, Embraer.
* **Top Models:** Boeing 737 series, Airbus A320 family.
* **Analysis:** Large commercial jet transports exhibit near-zero median injury fractions in recorded accident incidents. Structural integrity in high-capacity aircraft significantly limits hull destruction during non-catastrophic events.

### 2. Small Aircraft (<= 20 Passengers)
![Small Aircraft Safety](images/small_planes_safety.png)

* **Recommended Makes:** Cessna, Piper, Beech.
* **Top Models:** Cessna 172, Piper PA-28, Beech King Air series.
* **Analysis:** Small general aviation aircraft carry a higher baseline risk of passenger injury than commercial airliners. However, certified, non-amateur builds from established manufacturers show consistently lower destruction rates across decades of operational data.

---

## Factors Affecting Injury and Damage Outcomes

### Factor 1: Weather Conditions (VMC vs. IMC)
![Weather Impact on Safety](images/weather_impact.png)

* **Visual Meteorological Conditions (VMC):** Associated with lower severity and destruction rates. Most incidents involve minor localized airframe damage during taxiing or landing.
* **Instrument Meteorological Conditions (IMC):** Incidents occurring under low-visibility and adverse weather conditions show a significantly higher rate of severe injuries and complete hull destruction, largely driven by Controlled Flight Into Terrain (CFIT).

### Factor 2: Phase of Flight
![Phase of Flight Impact](images/phase_of_flight.png)

* **Analysis:** Takeoff and Landing account for the highest frequency of recorded incidents but result in lower rates of passenger fatality due to lower speeds and proximity to the ground. Conversely, accidents occurring during the **Cruise** and **Maneuvering** phases exhibit the highest rates of complete aircraft destruction and passenger fatality due to high-energy impacts.

---

## Repository Structure
* `Aviation_Accident_Cleaning.ipynb`: Data ingestion, imputation, feature engineering, and filtering.
* `Aviation_Accident_Data_Analysis.ipynb`: EDA, aggregation, statistical modeling, and visualizations.
* `AviationData.csv`: Raw dataset downloaded from Kaggle.
* `cleaned_aviation_data.csv`: Exported clean dataset used for EDA.
* `images/`: Directory containing exported visualizations.

## GitHub Repository
The complete project repository, including code and data, can be accessed here:
**[https://github.com/Osesi/Airsafety/](https://github.com/Osesi/Airsafety/)**