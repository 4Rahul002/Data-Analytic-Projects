### **Exploratory Data Analysis (EDA) Summary**  

#### **1. Introduction**  
Exploratory Data Analysis (EDA) is a fundamental step in understanding the dataset before applying predictive models. This project focuses on **predicting machine failures** based on operational parameters collected from industrial machines. The dataset consists of **136,429 records** with **14 features**, including various sensor readings, machine failure types, and product specifications.

---

#### **2. Dataset Overview**  
The dataset contains the following key features:  
- **Operational Parameters:**  
  - Air temperature [K]  
  - Process temperature [K]  
  - Rotational speed [rpm]  
  - Torque [Nm]  
  - Tool wear [min]  
- **Failure Types:**  
  - **TWF** (Tool Wear Failure)  
  - **HDF** (Heat Dissipation Failure)  
  - **PWF** (Power Failure)  
  - **OSF** (Overstrain Failure)  
  - **RNF** (Random Failure)  
- **Target Variable:**  
  - **Machine Failure** (Binary: 1 = Failure, 0 = No Failure)  
- **Product ID & Type:** Identifies the machine and its category (e.g., L, M, H).  

The dataset is complete with no missing values.

---

#### **3. Data Distribution & Statistical Insights**  
- **Air & Process Temperature:** Both features are **normally distributed** within a certain range, with process temperature slightly higher than air temperature.  
- **Rotational Speed & Torque:** These parameters show significant variation across different machine types.  
- **Tool Wear:** Machines with higher tool wear values are more likely to fail.  
- **Machine Failure Rate:**  
  - Failures occur in **a small percentage of the total data**, indicating an **imbalanced dataset**, which might require resampling techniques (e.g., SMOTE) for machine learning models.  
  - Most failures are associated with **specific failure types**, suggesting the importance of feature selection.  

---

#### **4. Correlation Analysis**  
A **correlation heatmap** was used to identify relationships between numerical features. Key findings:  
- **High correlation between air and process temperature**, indicating redundancy.  
- **Torque is inversely correlated with rotational speed**, which aligns with physical principles.  
- **Tool wear shows a positive correlation with failures**, reinforcing its importance as a predictor.  

---

#### **5. Failure Analysis & Trends**  
- **Failure Rate by Product Type:**  
  - Different machine types (L, M, H) show **varying failure rates**, with **some machine types being more prone to failures**.  
- **Failure Trends Over Time:**  
  - Failure rates **increase with tool wear** and extreme temperature values.  
- **Rotational Speed & Torque Influence:**  
  - Machines with very high or very low rotational speeds **experience more failures**, likely due to operational inefficiencies.  

---

#### **6. Key Insights from EDA**  
1. **Failures are rare** but follow specific trends related to temperature, rotational speed, and tool wear.  
2. **Certain machine types are more prone to failures**, making it essential to incorporate machine type in predictive models.  
3. **Tool wear is a critical factor in machine failure prediction**, emphasizing the need for proactive maintenance.  
4. **Air and process temperature are highly correlated**, indicating that one can be dropped without significant information loss.  
5. **Rotational speed and torque exhibit patterns that impact failures**, providing crucial insights for predictive modeling.  

---


