# Smoking Health Risk Analysis Dashboard

## Project Overview
This interactive Power BI dashboard analyzes a dataset of 529 patients to explore the relationship between smoking habits, demographics, and cardiovascular health risks. It serves as a tool for identifying patterns in smoking duration, intensity, and its subsequent impact on cholesterol and hypertension.

## Key Features
*   **Dynamic Health Slicing:** Toggle between "Damaged" and "Healthy" patient states to see how metrics shift.
*   **Multi-Organ Analysis:** (Conceptually) Sidebar navigation to focus on specific physiological impacts.
*   **Demographic Tracking:** Detailed breakdown of smoking status by age and gender.
*   **Health Risk Correlation:** Visualizes the distribution of high, low, and normal cholesterol/hypertension risks.
*   **Button Slicers (Top Right):** The Damaged vs. Healthy buttons act as global filters. They likely update the entire dashboard to show data specifically for patients with existing health issues versus those without.
*   **Navigation Icons (Far Left):** These vertical icons allow users to switch views between different organ systems (Heart, Lungs, Liver, Kidneys), though the current view is focused on the Heart.
*   **Central Image Effect:** The high-detail 3D heart model provides immediate visual context. When "Damaged" is selected, the image might change color or texture to represent physiological strain visually.


## Tech Stack & Skills
*   **Tool:** Microsoft Power BI Desktop
*   **Language:** DAX (Data Analysis Expressions) for calculated measures and KPIs.
*   **Design:** Custom UI/UX layout with integrated 3D medical assets.
*   **Analytical Skills:** Data cleaning, relationship modeling, and trend visualization.

## Data Points Analyzed
*   **Patient Demographics:** Age, Gender, BMI.
*   **Smoking Metrics:** Status (Current, Former, Never), Years of Smoking (YOS), Cigarettes Per Day (CPD).
*   **Health Indicators:** Cholesterol levels and Hypertension risk categories.

## Credits
Project inspired by and based on tutorials from **Isaac Emmanuel**.

## Preview
**Snapshots:**
1. https://github.com/Christopher-AR/Smoke-Health-Analysis-Dashboard/blob/main/Snapshot%20%5BHealthy%5D.png
2. https://github.com/Christopher-AR/Smoke-Health-Analysis-Dashboard/blob/main/Snapshot%20%5BDamaged%5D.png
