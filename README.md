# Udemy_Unlocked_Insights
📘 Dive deep into Udemy’s course universe! This project uncovers powerful insights about course pricing, popularity, subject trends, and learner engagement using Python and interactive visualizations.
# 📘 Udemy-Course-Explorer
![Udemy](https://img.shields.io/badge/Platform-Udemy-blueviolet)
![Python](https://img.shields.io/badge/Python-3.10+-green)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Last Update](https://img.shields.io/badge/Last_Update-May_2025-orange)

![Udemy Wallpaper](Udemy_poster.jpg)

## 🎓 Welcome to the Udemy Course Explorer Project!

This repository contains an end-to-end data analysis project focused on Udemy’s online courses. The project uses Python and Plotly to uncover key patterns in course pricing, ratings, popularity, and category trends to help learners and educators make informed decisions.

---

## 📑 Table of Contents

- [📌 Project Overview](#project-overview)
- [🧾 Dataset Information](#dataset-information)
- [📊 Key Highlights](#key-highlights)
- [📂 Visualizations](#visualizations)
- [🛠 Technologies Used](#technologies-used)
- [🚀 Installation and Usage](#installation-and-usage)
- [🧱 Project Structure](#project-structure)
- [🔮 Future Work](#future-work)
- [🤝 Contributions](#contributions)
- [📄 License](#license)

---

## Project Overview

The objective of this project is to derive actionable insights from Udemy course listings by analyzing various features such as:

- Course pricing trends across categories
- Relationship between course ratings and student enrollment
- Duration and content length impact on popularity
- Paid vs Free course performance
- Top instructors and subject domains

---

## Dataset Information

- Platform: Udemy
- Total Records: ~3,000+ courses
- Features:
  - course_title
  - category, subcategory
  - course_type (Free/Paid)
  - price
  - num_subscribers
  - num_reviews
  - content_duration
  - published_timestamp

### 📥 Source
The dataset was downloaded from [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/andrewmvd/udemy-courses)) and represents a snapshot of public Udemy course data.

---

## Key Highlights

### 1. Course Distribution

* Web Development and Business Finance dominate with \~1200 courses.
* Musical Instruments and Graphic Design offer growth potential.

### 2. Free vs Paid Courses

* 3368 Paid vs. 310 Free courses, suggesting a strong monetization focus.

### 3. Price Trends

* Most courses are priced at \$20 and \$50, with some premium options between \$100–\$200.

### 4. Course Levels

* "All Levels" is the most common, but Expert-level courses (58) are scarce.

### 5. Engagement

* Web Development leads with 470k+ reviews and 60,000 lectures.

### 6. Revenue Insights

* Web Development generates **71%** of total revenue (\$630M).

---

## 💰 Financial Insights

### 7. Total Revenue

* Estimated total revenue is \$884M.

### 8. Top Courses

* "Learn HTML5" and "The Web Developer Bootcamp" are top performers, with 100k+ subscribers each.

---

## 📈 Growth Insights

### 9. Course Creation & Subscribers

* Major growth from 2013-2016, peaking in 2016.
* Web Development leads subscriber growth every year.

---

## 🧾 Conclusion

> Udemy’s success lies in Web Development and premium pricing, with room for growth in expert-level and niche subjects. There are opportunities to expand free content and explore underserved categories.



---

## Visualizations

All visualizations are interactive and built using Plotly for better user engagement:

- 📊 Bar Plot: Course count per category
- 💰 Box Plot: Price distribution by subcategory
- 📈 Scatter Plot: Subscribers vs Ratings
- 🕒 Horizontal Bar: Duration comparison
- 🔥 Pie Chart: Free vs Paid course distribution
- 🧮 Count Plot: Courses by content length range

---

## Technologies Used

- Python 3.10+
- Pandas for data manipulation
- Plotly Express for visualization
- Jupyter Notebook for analysis presentation
- GitHub for version control and sharing

---

## Installation and Usage

### 1. Clone the Repository
git clone https://github.com/yourusername/Udemy-Course-Explorer.git
cd Udemy-Course-Explorer

### 2. Install Required Packages

pip install -r requirements.txt

### 3. Run the Notebook

Open the notebook using Jupyter:

jupyter notebook Udemy_Analysis.ipynb

> Tip: Export to PDF via File > Save As PDF (enable web-based export to retain visuals)

---

## Project Structure

Udemy-Course-Explorer/
│
├── data/
│   └── udemy_courses.csv             # Raw dataset
│
├── notebook/
│   └── Udemy_Analysis.ipynb          # Main analysis notebook
│
├── images/
│   └── *.png                         # Screenshots of charts (optional)
│
├── README.md                         # Project documentation
├── requirements.txt                  # Dependencies list

---

## Future Work

* Integrate machine learning models for course success prediction
* Add NLP analysis of course titles and descriptions
* Build a dashboard using Streamlit or Power BI

---

## Contributions

Contributions are welcome! Feel free to fork this repo and improve the visualizations, data insights, or add new features.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---
