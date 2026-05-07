# 📊 KSR Datavizon Hackathon: Event Management Challenge

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-123456?style=for-the-badge&logo=data&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview
This repository contains my submission for the **KSR Datavizon Hackathon: Event Management Challenge**. The objective of this project is to leverage **Power BI** to explore, analyze, and visualize a comprehensive collection of datasets covering various aspects of event management.

The final output is an interactive dashboard that transforms raw event data into a compelling narrative, uncovering valuable insights regarding event organization, attendee engagement, geographic performance, and profitability.

---

## 🎯 Problem Statement
Event organizers face challenges in understanding which categories, locations, and pricing strategies yield the highest attendance and profitability. The challenge required analyzing historical event data to:
1. Identify key trends in event categories and formats.
2. Analyze geographic performance (Cities and States).
3. Evaluate organizer efficiency and venue popularity.
4. Provide actionable insights to improve future event planning and ROI.

---

## 📂 Dataset Details
The data provided for this hackathon follows a standard Star Schema architecture.

* **Fact Table:**
  * `Events_Data_fct.csv`: Contains detailed records of events (dates, locations, organizers, pricing, registrations, attendance, and profitability metrics).
* **Dimension Tables:**
  * `Category_dim.csv`: Classifies events into thematic domains (e.g., Technology, Sports, Business).
  * `City_dim.csv`: Lists cities where events were held for geographic analysis.
  * `State_dim.csv`: Provides state-level categorization.
  * `Organizer_dim.csv`: Captures details about the event organizers.
  * `Venue_dim.csv`: Includes information on event venues.

---

## 🛠️ Tools & Technologies Used
* **Data Visualization & Modeling:** Power BI (DAX, Power Query)
* **Data Preparation/Cleaning:** [Mention if you used Python, Pandas, Excel, or just Power Query]
* **Design & UI:** [Mention if you used Figma or Canva for background design]

---

## ⚙️ Data Modeling & Architecture
*(Add a screenshot of your Power BI Model View here)*
![Data Model Screenshot](link-to-your-image.png)

* **Relationships:** Built a Star Schema connecting the `Events_Data_fct` table to the various dimension tables using one-to-many relationships.
* **Data Cleaning:** Handled missing values, formatted dates correctly, and created custom calculated columns using Power Query.
* **DAX Measures:** Created complex measures to calculate KPIs such as Total Profit Margin, Attendance Rate, YoY Growth, and Average Ticket Revenue.

---

## 📊 Key Insights & Dashboard Pages

### 1. Executive Summary
* **Total Events Hosted:** [Enter number]
* **Total Revenue Generated:** $[Enter number]
* **Top Performing Category:** [Enter Category]
* **Insight:** [Briefly describe the biggest takeaway from the summary page]

### 2. Geographic Analysis
* **Top City/State:** [Enter City/State] generated the highest attendee footfall.
* **Insight:** [Explain a geographic trend you found]

### 3. Organizer & Venue Performance
* **Top Organizer:** [Enter Organizer Name]
* **Insight:** [Explain how venue capacity correlates with event profitability]

*(Add screenshots of your Power BI Dashboard pages here)*
![Dashboard Screenshot 1](link-to-your-image-1.png)
![Dashboard Screenshot 2](link-to-your-image-2.png)

---

## 🚀 How to View the Project

### Option 1: Live Interactive Dashboard
You can view the fully interactive Power BI dashboard published on the web here:
**👉 [Link to your published Power BI Web Dashboard]**

### Option 2: Download the `.pbix` file
1. Clone this repository: 
   ```bash
   git clone [[https://github.com/yourusername/ksr-datavizon-hackathon.git](https://github.com/yourusername/ksr-datavizon-hackathon.git)](https://github.com/saikumarpadhi/Event-Management-Analytics-/blob/main/HACKATHON.pbix)
