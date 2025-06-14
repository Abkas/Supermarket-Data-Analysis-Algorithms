# 🛒 Supermarket Data Analysis Using Algorithms

This project focuses on applying fundamental data structures and algorithms to analyze supermarket transactional data. The aim is to identify customer patterns, high-performing products, and underperforming items, using custom implementations of sorting, searching, and data processing logic.

## 📊 Project Overview

The dataset contains records of products, sales, and customers from a fictional supermarket. We perform analysis to:

- Identify the **top 5 most profitable products**
- Detect **high-value customers**
- Find **underperforming or low-selling items**
- Compare **algorithm performance (e.g., selection sort vs. merge sort)**

---

## 🧠 Algorithms Used

### ✅ Sorting Algorithms
- **Selection Sort**: Used to sort products by profit or frequency.
- **Merge Sort**: Applied to compare efficiency and correctness against selection sort.

### ✅ Searching Algorithms
- **Linear Search**: To find specific customer or product entries.
- **Binary Search** (if applicable): For fast lookups in sorted data.

### ✅ Custom Logic
- Profit calculation = `Selling Price - Cost Price`
- Frequency tracking using dictionaries/lists

---

## 🔍 Features

- Manual implementation of algorithms (no built-in sort functions)
- Efficiency comparison between algorithms (with time complexity analysis)
- Graphical visualization of sorted data (optional)
- Confusion matrix or binning logic (if classification is attempted)

---

## 📁 Folder Structure
```
Supermarket/
├── dataset/
│ └── supermarket_data.csv
├── code/
│ └── supermarkettt.ipynb
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Abkas/Supermarket-Data-Analysis-Algorithms.git
   
2. Navigate to the project
   cd Supermarket-Data-Analysis-Algorithms

3. Run the analysis
   python src/supermarkettt.ipynb

Make sure Python 3.x is installed and required libraries (if any) like matplotlib, pandas, or numpy are available.

📈 Performance Analysis
Algorithm	Time Complexity	Stability	Use Case
Selection Sort	O(n²)	No	Simple datasets
Merge Sort	O(n log n)	Yes	Large, performance-sensitive tasks

📌 Future Work
Add visualization (bar charts, pie charts)
Integrate a UI using Tkinter or web dashboard
Explore predictive models (e.g., using ML)

👨‍💻 Author
Abhishek Magar
Project for Data Structures & Algorithms (DSA) Course

