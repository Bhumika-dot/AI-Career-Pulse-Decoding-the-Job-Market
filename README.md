# AI-Career-Pulse-Decoding-the-Job-Market
# 🌍 AI Career Pulse: Decoding the Job Market

> An interactive, data-driven project that analyzes global hiring trends, salary bands, and demand patterns across the rapidly evolving Artificial Intelligence job landscape using Business Intelligence tools and web technologies.

![Tableau](https://img.shields.io/badge/TABLEAU-VISUALIZATION-orange?style=for-the-badge&logo=tableau)
![Python](https://img.shields.io/badge/PYTHON-FLASK-blue?style=for-the-badge&logo=python)
![HTML5](https://img.shields.io/badge/HTML5-FRONTEND-e34f26?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-STYLING-1572B6?style=for-the-badge&logo=css3)

---

## 📖 Project Overview

The AI job market is one of the fastest-growing sectors in today's economy. As artificial intelligence continues to transform industries—from healthcare to finance, automotive to government—the demand for skilled AI professionals is accelerating at an unprecedented pace.

This project analyzes global AI job market data from **2025 to 2026**, extracting actionable insights through interactive dashboards developed in **Tableau Desktop Public Edition**. The dataset covers a wide range of AI roles, salary tiers, company sizes, industries, required education levels, and experience levels.

To make the findings accessible and user-friendly, the Tableau dashboards and story points are integrated into a responsive web interface built with **Flask**, **HTML5**, and **CSS3**.

---

## 🎯 Objectives & Career Scenarios

To extract meaningful insights, the analytical framework addresses three real-world career perspectives:

* **Scenario 1 — Fresher Candidate Perspective:** Assists new graduates in identifying beginner-friendly entry-level salary bands ($100k tier), industries with frequent junior hiring (such as Healthcare, Government, and IT services), and organizations offering learning-oriented environments.
* **Scenario 2 — Mid-Level Professional Perspective:** Guides analytics and software professionals in transitioning to AI without losing domain expertise by highlighting salary progression, high-growth AI roles, and necessary upskilling paths in ML and Cloud architectures.
* **Scenario 3 — Senior Professional Perspective:** Helps experienced leaders mitigate automation risks by focusing on enterprise hiring trends, AI strategy, governance, architecture, and innovation leadership roles.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **Tableau Desktop** | Visual Analytics & Dashboard Creation |
| **Tableau Public** | Dashboard Hosting & Cloud Publishing |
| **Flask** | Web Application Framework |
| **HTML5** | Frontend Page Structure & Embeds |
| **CSS3** | Interface Styling & Layout |
| **VS Code** | Code Editor & Development Environment |

---

## 📊 Dashboards & Analytics

### Interactive Visualizations Included
* **Key Performance Indicators (KPIs):** Instant summary of Avg. Annual Salary ($123K), Avg. Max Salary ($261K), Avg. Min Salary ($122.5K), and Min Required Experience (3 Years).
* **Job Category VS Annual Salary:** Treemap showing compensation scale across AI Engineering, Infrastructure, Security, Research, Data Engineering, Product, and Business roles.
* **Job Title VS Avg Annual Salary:** Ranked bar chart illustrating average pay for specialized roles like Multimodal AI Engineer, NLP Engineer, and AI Security Engineer.
* **Company Size VS Annual Salary:** Comparative analysis across Startups (1–50), Mid-size (501–5000), and Enterprise (5000+) organizations.
* **Industry VS Salary Tier:** Breakdown of entry (<$100k) and mid-level ($100k–$150k) roles across Finance, Government, Healthcare, and Retail sectors.
* **Job Demand & Postings:** Volume of posted jobs and YoY demand growth tracking from 2025 to 2026.

---

## 📈 Key Insights

* **Surging YoY Growth:** AI job postings showed a significant multi-fold increase from 2025 to 2026.
* **Specialization Premium:** Specialized roles like Multimodal AI Engineering and NLP Engineering command the highest average annual salaries.
* **Enterprise Scaling:** Enterprise organizations (5000+ employees) provide the highest cumulative salary budgets for AI teams.
* **Domain Diversity:** Healthcare and Government offer substantial entry-level opportunities, making them ideal starting sectors for freshers.

---

## 🖥️ Flask Web Application

The repository includes a lightweight Flask application that embeds the Tableau Public dashboards and story into a single web application interface for easy navigation and interactive exploration.

> **Note:** GitHub Pages cannot host Flask applications because it only supports static websites.

### 📂 Project Structure

```text
ai-job-market-analysis/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── dashboard.html
│   └── story.html
│
└── static/
    ├── css/
    │   └── style.css
    └── js/
