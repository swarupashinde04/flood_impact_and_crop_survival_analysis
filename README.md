# Flood Crop Survival Analysis System

**Author:** Swarupa Shinde
**Level:** Undergraduate (1st Year, B.Tech)  
**Domain:** Disaster Impact Analysis | Agriculture | Decision Support Systems  

---

## 📌 Problem Statement

Floods are one of the most frequent natural disasters in India and often result in severe agricultural losses.  
Farmers usually do not have quick, data-based guidance to understand:

- Whether a specific crop can survive a flood  
- How risky the situation is  
- What immediate action should be taken  

This lack of structured information increases crop damage and economic loss.

---

## 💡 Proposed Solution

This project presents a **rule-based analytical system** that estimates crop survival during floods using:

- Crop-specific flood survival capacity (in days)  
- Actual flood duration provided by the user  

The system calculates a **survival probability (%)**, classifies the **risk level**, and provides **clear recommendations** to support decision-making.

---

## ⚙️ Methodology

1. A predefined dataset maps crops to their maximum flood survival duration.  
2. User inputs:
   - Crop name  
   - Flood duration (in days)  
3. The system:
   - Validates input  
   - Computes survival probability  
   - Categorizes risk into:
     - SAFE  
     - LOW RISK  
     - MEDIUM RISK  
     - HIGH RISK  
4. Action-oriented recommendations are generated based on the risk level.

---

## 🧠 Core Logic

- If flood duration ≤ crop survival capacity → **Crop is SAFE**  
- Else, survival probability is calculated using:
survival_probability = (survival_days / flood_days) × 100
Copy code

### Risk Thresholds

- ≤ 40% → **High Risk**  
- 41% – 70% → **Medium Risk**  
- > 70% → **Low Risk**  

---

## 📊 Output

The system provides:

- Survival percentage  
- Risk category  
- Practical recommendation for farmers  

### Example Output
--- Crop Survival Assessment Report --- Crop Name            : Rice Flood Duration       : 10 days Survival Capacity    : 12 days Survival Probability : 100% Risk Category        : SAFE Recommendation       : Crop is SAFE.


---

## 🛠️ Technology Used

- Python  
- CSV (Crop survival data is loaded dynamically from a CSV file, allowing easy extension without modifying code.)
- Conditional logic  
- Console-based input/output  

---

## 🎯 Significance of the Project

- Addresses a real-world agricultural problem  
- Demonstrates logical thinking and problem modeling  
- Designed as a **foundation-level research prototype**  

Suitable for extension into:

- Data-driven models  
- Regional datasets  
- Machine learning-based prediction systems  

---

## ⚠️ Limitations

- Uses static crop survival values  
- Does not account for soil type, water depth, or weather variations  
- Assumes uniform flood impact  

---

## 🚀 Future Scope

- Integration with real flood datasets  
- Region-specific crop analysis  
- Visualization of risk levels  
- ML-based prediction using historical data  
- Multilingual farmer interface  

---

## 📚 Academic Relevance

This project reflects:

- Research-oriented thinking at an early academic stage  
- Application of programming to societal problems  
- Readiness for undergraduate research internships
