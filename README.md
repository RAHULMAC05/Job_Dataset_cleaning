# 🗂️ Job Dataset Cleaning & Processing Project

This repository contains the data cleaning and preparation process for a large **Job Posting Dataset** project.  
It focuses on organizing, cleaning, mapping, and preparing job-related data for further analysis and machine learning tasks.

---

## 📌 Project Structure

```text
job_desc/
 ├── allCountries/
 │    └── allCountries.txt (removed from repo due to size, linked below)
 ├── companies/
 │    ├── companies.csv
 │    ├── company_industry.csv
 │    ├── company_speciality.csv
 │    └── employee_count.csv
 ├── jobs/
 │    ├── benefits.csv
 │    ├── job_industry.csv
 │    ├── job_skill.csv
 │    └── salaries.csv
 ├── mappings/
 │    ├── skills.csv
 │    └── industries.csv
 ├── main/
 │    └── cleaned_data.dbc (Databricks notebook)
 ├── postings.csv (removed from repo due to size, linked below)
 └── ER-ENTITY.drawio (ER diagram of the dataset)
```

---

## 📊 Dataset Sources  

- **Job Posting Dataset (Kaggle)**  
  📥 [Download from Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)

- **External All Countries Dataset for City/State/Zip Validation**  
  This dataset was used to handle missing country, state, and city information based on zip code.  
  📥 [Download allCountries.txt](http://download.geonames.org/export/zip/allCountries.zip)

---

## 📖 Data Cleaning & Processing Steps

- Removed null values from critical columns  
- Standardized inconsistent entries (cities, states, countries)  
- Mapped skills, industries, and benefits to consistent formats using lookup files  
- Removed outlier salary values and job postings with missing titles  
- Handled missing zip codes using the **allCountries.txt** reference file  
- Removed excessively large files (>100MB) from the repository history using a history cleaning utility  

---

## 📐 Entity Relationship Diagram

The **ER diagram** representing relationships between the different entities in this project is included as:

- 📄 `ER-ENTITY.drawio`  
*(You can open it using [draw.io](https://app.diagrams.net/))*

---

## 📎 Notes

- Large files like the original **postings.csv (~500MB)** and **allCountries.txt (134MB)** have been removed to comply with hosting limits.
- Cleaned and trimmed datasets are included for easier handling and analysis.
- The repo is structured for easy access to processed and mapping datasets.

---

## 📬 Contact  

Feel free to fork, clone, or suggest improvements!  

📧 rahulmac05@gmail.com  

---

## 📄 License  

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/)

---
