# **Wildfire Analysis of the United States**

### **Contributors**
This project is a collaborative effort by Niket Pathak, Moulshree Guleria, Linda Mansour, and Saumya Chaudhary for CS 418 Introduction to Data Science. Each contributor played an equal role, working both independently and collaboratively to achieve the results presented in this analysis.

---

### **Objective**
The primary goals of this analysis are as follows:
1. **Classify wildfires by size** (e.g., small vs. large fires) using relevant features and machine learning models.
2. **Predict the cause of wildfires** into multiple categories (11 classes) using the available dataset and machine learning techniques.

---

### **Dataset**
The dataset utilized for this analysis is the **Inform Fire Dataset**. This dataset was obtained from [https://data-nifc.opendata.arcgis.com/datasets/nifc::inform-fire-occurrence-data-records/about]. It contains crucial information about wildfires, including features like:
- **Fuel type (vegetation type)**
- **Location data (latitude, longitude, state, etc.)**
- **Fire causes**
- **Incident size and other related attributes**

These features play a significant role in building models to classify fires and predict their causes.

The weather data was obtained from the **Open Meteo API** [https://open-meteo.com].

---

### **Workflow**
To achieve the project goals, the following steps were undertaken:

1. **Data Acquisition**
   - Collected the Inform Fire Dataset and weather data from the Open Meteo API.
   - Verified the integrity and consistency of the dataset.

2. **Data Cleaning and Exploratory Data Analysis (EDA)**
   - Handled missing data by filling NaN values where appropriate or removing irrelevant records.
   - Performed exploratory analysis to understand data distribution, detect outliers, and visualize key trends.
   - Identified essential features required for classification and prediction.

3. **Hypothesis Development**
   - Developed hypotheses to guide the classification and prediction models. These hypotheses include:
     - Fires with certain fuel types are more likely to grow large.
     - Specific weather or climate conditions increase the likelihood of larger fires.

4. **Data Visualization**
   - Created visualizations to provide insight into key patterns in the data.
   - Visualizations are:
     - **Response time** of fire occurrence across various states.
     - **Incident size variation** across various seasons for the last 3 decades.
     - **Number of fires** across various seasons based on the causes of these fires.

5. **Machine Learning Model Development**
   - **Classification of Fire Size**:
     - Built Random Forest to classify wildfires into "small" or "large" categories.
     - Used relevant features like fuel type, weather conditions, season, and GACC location for classification.
   - **Prediction of Fire Cause**:
     - Developed Random Forest models to predict the cause of the wildfire, selecting a multi-class classification approach.
     - Evaluated the performance of the models using accuracy, precision, recall, and F1-score metrics.

---

### **Conclusion**
The Wildfire Analysis of the United States provides a robust framework to classify wildfires by size and predict their causes. By leveraging the Inform Fire Dataset and weather data from Open Meteo API, this project contributes valuable insights that can aid in early intervention and wildfire prevention strategies. 




[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/eG6ocWkI)
