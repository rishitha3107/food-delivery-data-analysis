# Innomatics Research Labs – Hackathon Project

## Food Delivery Data Analysis

## 📌 Project Summary

This repository contains my submission for the Innomatics Research Labs hackathon.
The project focuses on performing an end-to-end data analysis for a food delivery platform by integrating data from multiple heterogeneous sources and extracting meaningful insights.

The solution demonstrates a complete analytical workflow, from raw data ingestion to SQL-driven analysis, with a strong emphasis on accuracy and reproducibility.

---

## 📂 Data Sources

The analysis is based on three datasets provided as part of the hackathon:

* **orders.csv** – Contains order-level transactional information
* **users.json** – Stores customer details such as city and membership status
* **restaurants.sql** – Holds restaurant metadata including cuisine type and ratings

To maintain data integrity, all datasets were combined using **LEFT JOINs**, ensuring that every order record is preserved.

---

## 🧱 Unified Analytical Dataset

After integrating the three source datasets, a consolidated dataset was created:

* **final_food_delivery_dataset.csv**

This merged file serves as the **authoritative dataset** for all downstream analysis, including MCQs, numerical questions, and fill-in-the-blank responses.

---

## 🛠️ Tools and Technologies Used

* Python
* Pandas
* SQLite (in-memory database)
* Google Colab
* Jupyter Notebook

---

## 🗄️ SQL-Based Analysis in Google Colab

To enable SQL analysis within Google Colab:

* The final merged dataset is loaded into an **in-memory SQLite database**
* All analytical questions are answered using **SQL queries**
* Each query can be executed independently to reproduce the results

---

## 📊 Scope of Analysis

The notebook includes SQL queries to answer:

* Multiple Choice Questions (MCQs)
* Numerical response questions
* Fill-in-the-blank questions

All answers are derived strictly from the final merged dataset.


