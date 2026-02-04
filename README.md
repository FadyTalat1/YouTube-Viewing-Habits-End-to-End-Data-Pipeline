# 📊 YouTube Viewing Habits: End-to-End Data Pipeline

![Dashboard Screenshot](link_to_your_image_here.png) 

## 📝 Project Overview
This project is a comprehensive analysis of my personal YouTube viewing history (16,000+ records). The goal was to transform raw, unstructured HTML data into a high-fidelity interactive dashboard to uncover behavioral patterns and consumption habits.

## 🚀 Technical Stack
* **Data Engineering:** Python (BeautifulSoup) for Web Scraping & Data Parsing.
* **Data Visualization:** Power BI (DAX & Power Query).
* **Design:** Figma (Custom UI/UX Backgrounds).
* **Project Management:** Trello (Agile Methodology).

## 🛠️ Data Pipeline Steps

### 1. Extraction (Python)
- Exported raw data from Google Takeout in HTML format.
- Developed a **Python script** to parse the HTML tags and extract: `Video Title`, `Channel Name`, `Timestamp`, and `Video Link`.
- Cleaned the data and exported it to a structured **CSV** file.

### 2. UI/UX Design (Figma)
- Designed a custom **Figma background** to ensure a professional and non-distracting user interface.
- Focused on visual hierarchy to highlight Key Performance Indicators (KPIs).

### 3. Analysis & Modeling (Power BI)
- Imported the CSV and performed data transformation in **Power Query**.
- Created a **Calendar Table** to analyze trends by hour, day, and month.
- Developed **DAX measures** to calculate:
    - Total Videos Watched.
    - Average Videos per Day.
    - Year-over-Year (YoY) Growth in consumption.

## 📈 Key Insights
* **Volume:** Analyzed **16.7K** total videos watched.
* **Daily Habit:** Average of **51 videos** per day.
* **Peak Hours:** Viewing activity peaks between **8:00 PM and 11:00 PM**.
* **Top Categories:** (Mention your top 3 categories here, e.g., Education, Tech, Podcasts).

## 📂 Repository Structure
* `/scripts`: Python scraping script.
* `/data`: Sample data (make sure to anonymize or use a small sample).
* `/design`: Figma exported assets.
* `/report`: Power BI (.pbix) file.
