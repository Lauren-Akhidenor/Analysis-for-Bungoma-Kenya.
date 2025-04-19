# Socio-Economic Characteristics, Farming Practices, and Productivity of Maize Farmers in Kenya Bungoma County.

## 📌 Introduction

Kenya is a geographically diverse country with many agroecological zones (AEZs). Maize (*Zea mays* L.) is a staple food for millions of people in Kenya. The total land area under maize production is approximately 1.5 million hectares, with an average annual output of around 3 million metric tons, yielding a national mean of 2 metric tons per hectare. In the high-potential highlands of Kenya, yields typically range from 4 to 8 T/Ha, representing only 50% (or less) of the genetic potential of hybrid varieties.

Maize production faces numerous constraints, including drought, low soil fertility, pests, and diseases. Foliar and stalk/ear rot diseases, as well as stem borers, significantly impact production in Kenya’s humid transitional and highland regions. Despite breeding advancements, production has not kept pace with population growth. While chemical control methods can help, **host-plant resistance** remains the most economical and sustainable strategy.

This project analyzes survey data from four sub-counties in Bungoma County: **Chwele, Sirisia, Tongaren, and Webuye West**. It aims to understand farming practices, output, training access, and socio-economic characteristics affecting maize production.

![Map of Bungoma County](https://github.com/your-username/your-repo-name/raw/main/2.jpg)


---

## 🎯 Objectives

1. **Assess the socio-economic characteristics of maize farmers**
2. **Evaluate maize farming practices in the region**
3. **Assess the level of access to agricultural training**
4. **Analyze productivity and output of maize farms**

---

## 🧪 Methodology

- **Participants:** 59 farmers
- **Tools Used:**
  - Microsoft Excel: cleaning, coding, averages, visualization
  - SPSS: descriptive analysis and charts
  - Microsoft Power BI: dashboard and data visualization

---

## 📊 Analysis

### 🔹 Microsoft Excel

#### a) Data Cleaning
- Removed duplicates
- Standardized entries

#### b) Data Coding
- Gender: Male = 1, Female = 0  
- Response: Yes = 1, No = 0  
- Fertilizer: Both = 1, Inorganic = 0

#### c) Summary Statistics
- **Avg. Age of HH head:** 51.9 years  
- **Avg. Household Size:** 6.3  
- **Avg. Land Available:** 3.46 acres  
- **Avg. Maize Plot Size:** 2.41 acres  
- **Avg. Maize Land (total):** 1.97 acres  
- **Avg. Main Plot Size:** 1.63 acres  
- **Avg. Years of Farming:** 20.83  
- **Avg. Maize Output:** 22.02 units

#### d) Statistical Analysis

##### i) Trendline Analysis

- **Household Size vs Output**


Equation: y = 0.7747x + 1.1996, R² = 0.6185


Where,
- m = 0.7747x and, b = 1.1996
- y dependent variable is the estimated output
- x is the independent variable is the household size


Interpretation: 
- For each additional household member, the estimated maize output is expected to increase by 0.7747 units.
- The R² value of 0.6185 suggests a moderate positive correlation.
- The estimated output of maize is 1.1996 when the household size is 0.
 

- **Land Size vs Output**  


Equation: y = 20.317x — 16.015, R² = 0.9865


Where,


- m = 20.317 and, b = -16.015
- y dependent variable is the estimated output
- x is the independent variable is the total size of land available to the household in acres


Interpretation: 
- For each additional acre of land, maize output is expected to increase by 20.317 units.
- The R² value of 0.9865 indicates a very strong positive correlation.
- The estimated output of maize is -16.015 when the total size of land available to the household in acres is 0.

- **Main Plot Size vs Output**

  
  Equation: y = 13.5x — 0.375, R² = 0.125


Where,
- m = 13.5 and, b = -0.375
- y dependent variable is the estimated output
- x is the independent variable is the size of the main/ major plot in acres


Interpretation: 
- Each additional acre in the main maize plot is expected to increase output by 13.5 units.
- The R² value of 0.125 suggests that other factors not captured by the model significantly affect maize output.
- The estimated output of maize is -0.375 when the size of the main/ major plot in acres 0. This relatively means there won’t be any form of production or output.
  

##### ii) Regression

- **Years of Farming vs Output:**


**Conclusion:**
The regression analysis indicates a weak relationship between years of farming and maize output. The number of years farming maize is a  weak predictor of output.


- **Total Land Size vs Output:** 


**Conclusion:**
The regression analysis shows a highly significant and strong positive relationship between land size and maize output, explaining 94.71% of the variation in maize output.


##### iii) Correlation

- **Land Size vs Output:**  


**Conclusion**:
A strong positive correlation (approximately 0.97) exists between the total size of land and maize output, indicating that larger land sizes are associated with higher maize yields.

##### iv) T-Test

- Mean land = 1.97 acres
- mean output = 22.02 units  
- t = -2.1425, p = 0.0342

   
**Conclusion:**
Significant relationship, smaller land sizes can produce higher output

-----------

### 🔹 SPSS Analysis

Frequency distributions of:
  
-  Table 2.1: Frequencies and statistics showing the Sex of household heads including their valid and missing values




- Table 2.2: Frequencies showing Sex of household head, age, size of all land, and estimated output including valid and missing values including their Sub-counties



- Table 2.3: Frequencies based on type of land ownership




- Table 2.4: Frequency table showing the total size of all land under maize production in acres.




- Table 2.5: Frequencies showing the estimated output of maize.




- Table 2.6: Frequencies based on the use of fertilizer on maize plot.




- 




- Charts included:
  - Fertilizer usage types
  - Age distribution
  - Land ownership
  - Training frequency

---

### 🔹 Power BI Dashboard

- Data cleaned and transformed
- Interactive visualizations:
  - Farmer demographics
  - Output by sub-county
  - Fertilizer and protection method use
  - Training source breakdown

---

## 🔍 Key Insights

### Socio-Economic Characteristics
- **Avg. age:** 51.9  
- **Mostly male-headed households**  
- **Education:** Mostly primary and secondary  
- **30** participants have **title deeds**

### Farming Practices
- **57** farmers use **plowing**  
- **All** use fertilizer (33 use both types)  
- **Hand-weeding** is dominant  
- **43** use crop protection measures

### Training and Advice
- **40** received training  
- Sources: Extension agents, agro-dealers, NGOs, research institutions

---

## ✅ Conclusion

- **Strong relationship between land size and output**
- **Years of experience not a reliable predictor**
- **Smallholder efficiency may drive high yields per acre**
- **Land size is a major economic variable in planning**

### 📌 Recommendations
- Promote **input efficiency** and training for smallholders
- Incorporate **non-linear models** in future analysis
- Explore more variables (e.g., rainfall, seed type)

---

## ⚠️ Limitations

- T-tests assume equal variance
- Models may oversimplify production complexity
- Future research should include more diverse variables

---

> _This analysis contributes to better policy-making and resource allocation for maize production in Kenya._

