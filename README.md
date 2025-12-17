# Yelp Open Dataset

## 📌 About
The Yelp Open Dataset is a subset of Yelp data that is intended for educational use.  
It provides real-world data related to businesses including reviews, photos, check-ins, and attributes like hours, parking availability, and ambience.

---

# LA County Restaurant Inspections and Violations Dataset

## 📌 About
Restaurants and markets in Los Angeles County are regularly inspected for health code violations.  
The county makes these data publicly available, enabling a transparent look into this public health information.

---

## 📂 Content
The dataset includes two main files:

- **`inspections.csv`** → Health code inspection results  
- **`violations.csv`** → Health code violations  

Details about each file are provided below.

---

## 🚨 Violations
This dataset contains **Environmental Health Violations** for restaurants and markets in Los Angeles County.

- Covers all unincorporated areas and 85 of the 88 cities in the county  
- Excludes Pasadena, Long Beach, and Vernon (each has its own health department)  
- Each row represents one health code violation  
- Rows with the same **Activity Date**, **Record ID**, and **Serial Number** are part of the same violation  
- **Serial Number** is the primary key linking to the inspection grade (Inspection Results dataset)  

---

## 🧾 Inspections
This dataset contains **Environmental Health Inspection Results** for restaurants and markets in Los Angeles County.

- Covers inspections and enforcement activities for all unincorporated areas and 85 of the 88 cities  
- Excludes Pasadena, Long Beach, and Vernon  
- Each row represents one inspection result  
- **Activity Date**, **Record ID**, and **Serial Number** are the primary keys linking to the Violations dataset  

---

## 💡 Inspiration
Questions you might explore with this dataset:

- What are the most common health code violations?  
- What is the trend of health code violations over time?  
- Is there a geographic pattern to health code violations?  

---


## 🔗 Sources
- [LA County Restaurant Inspections and Violations (Kaggle)](https://www.kaggle.com/datasets/meganrisdal/la-county-restaurant-inspections-and-violations)  
- [Yelp Open Dataset](https://business.yelp.com/data/resources/open-dataset/)
