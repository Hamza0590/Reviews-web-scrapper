# 🍽️ Restaurant Feedback Analysis — PAI Project

This project is a complete end-to-end solution for analyzing customer feedback from restaurants using **web scraping**, **AI-driven text analysis**, and a **web-based dashboard**.

Developed as a solo semester project for the *Programming for AI* course, it demonstrates skills in **data extraction**, **prompt engineering**, **NLP**, and **visual analytics** using **Python**, **Selenium**, **LLMs**, and **Streamlit**.

---

## 📌 Project Components

### 🔍 Part 1: Web Scraping

- Scrapes restaurant reviews from **[OpenTable](https://www.opentable.com)** using `Selenium` and `BeautifulSoup`.
- Extracts:
  - Restaurant Name
  - Review Content
  - Ratings
  - Date
- Handles pagination (with some known edge cases at the last page).
- Stores results in a structured format (`CSV` or `JSON`).

### 💬 Part 2: Prompt Engineering

- Uses a **Large Language Model (LLM)** to:
  - Extract **food-related comments**
  - Extract **staff/service-related comments**
- Prevents **hallucinations** through precise prompt design.
- Excludes **personal identifiable information (PII)** in all output.
- Results are saved in a clean, categorized `.json` file.

### 🖥️ Part 3: Streamlit Dashboard

- Web GUI built using **Streamlit**:
  - Search and view categorized reviews
  - Food-related and staff/service content are **highlighted in different colors**
  - Clean, user-friendly layout mimics OpenTable-style review presentation

### 📊 Part 4: Competitor Analysis (25 Marks)

- Allows user to input a competitor's restaurant link
- Scrapes historical rating data (by date) for **both restaurants**
- Visualizes rating trends with a **time-series line graph**
- Bonus: Includes a **summary comparison and insights** section

---

## 💡 Features

- ✅ Multi-page review extraction
- ✅ Structured, categorized feedback
- ✅ Clean web dashboard (with filtering and highlighting)
- ✅ Competitor comparison graph
- ✅ Real-world use of LLMs for **text classification**

---

## 🛠 Technologies Used

- **Python**
- **Selenium** (for web scraping)
- **Prompt Engineering with LLM**
- **Streamlit** (for dashboard)
- **Matplotlib** (for graphs)
- **pandas**, **json**, etc.

---

## 🏁 Getting Started

### 🔧 Setup

1. Clone the repository:
   ```bash
  ---Dowload the zip folder and run the jupyter notebook in visual studio and then run the web.py on the terminal
