# Customer Support Analytics Dashboard

**Power BI + Python (NLP) | End-to-End Customer Support Insights**

This project combines **interactive data visualization using Power BI** with **Natural Language Processing (NLP)** in Python to deliver a robust analytics solution focused on customer support performance, satisfaction, and sentiment trends.

---

##  Project Objective

The goal of this project is to help businesses gain a 360° view of their customer support operations by analyzing structured and unstructured data (ticket descriptions). It empowers support managers to track key KPIs, identify high-priority issues, understand sentiment behind tickets, and improve decision-making.

---

##  Key Components

###  Power BI Dashboard

The dashboard is designed with multiple views and interactive features:

- **Executive Metrics**  
  → Total Tickets, Average Satisfaction, First Contact Resolution %, Response Rate

- **Issue & Priority Insights**  
  → Ticket distribution by issue type, priority level, and subject

- **Channel Performance**  
  → Average resolution days across Email, Chat, Phone, and Social Media

- **Customer Demographics**  
  → Drilldowns by Customer Age, Gender, Product Purchased, Ticket Status

- **Dynamic Filtering & Navigation**  
  → Responsive slicers for segmentation by ticket status, channel, priority, and customer

###  Python + NLP (Sentiment Analysis)

To enrich the dashboard with textual insights:

- Utilized **VADER Sentiment Analyzer** from the **NLTK** library
- Analyzed ticket descriptions and classified each one as:
  -  Positive
  -  Neutral
  -  Negative
- Output dataset with sentiment labels and scores was merged into the main data model
- Results visualized in Power BI to correlate with resolution and satisfaction metrics

---

## 🛠️ Tools & Technologies

| Technology | Purpose |
|------------|---------|
| **Power BI** | Dashboard development and data visualization |
| **DAX** | Calculated columns, KPIs, custom logic |
| **Python (NLTK)** | Sentiment analysis on text data |
| **VADER** | Rule-based sentiment scoring |
| **Pandas** | Data preprocessing |
| **CSV/Excel** | Raw dataset and output integration |

---



