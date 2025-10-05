# Uber Ride Analytics: Cancellation & Availability Deep Dive

📌 **Overview**

Beginner-level data analysis project exploring ride-sharing data to uncover insights on ride cancellations, driver availability, and operational efficiency. This project uses **R** and the **Tidyverse** suite, run entirely in **Kaggle Notebooks**, to practice data manipulation and visualization while addressing business-critical questions.

📦 **Data Source**

The analysis utilizes the [Uber Ride Analytics Dashboard dataset](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard) sourced from Kaggle. The dataset contains detailed ride-sharing data, including booking patterns, vehicle types, cancellation reasons, and operational metrics.

🛠️ **Tools & Technologies**

- **Platform:** Kaggle Notebooks  
- **Language:** R  
- **Libraries (Tidyverse):**
  - `readr` – Data loading
  - `dplyr` – Data manipulation
  - `ggplot2` – Data visualization
  - `lubridate` – Date/time handling

🎯 **Business Questions**

- What is the overall ride completion rate, and how do specific cancellation types (customer, driver, no driver found) affect it?
- Are there starting or ending locations with high cancellation rates or where drivers are frequently unavailable?
- Do certain vehicle types experience higher cancellation rates?
- How does waiting time (Avg VTAT/CTAT) impact the likelihood of ride cancellation?

📊 **Key Insights & Recommendations**

1. Driver-initiated cancellations are the primary factor affecting customer wait times and subsequent cancellations.
2. Certain locations and vehicle types show consistently higher cancellation rates.

**Business Recommendations:**
1. Reduce driver cancellations through incentives and operational strategies.
2. Offer targeted bonuses for drivers maintaining low cancellation rates, especially in high-issue zones.
3. Implement localized solutions tailored to high-cancellation areas and vehicle types.

🚀 **How to Use**

- Open the Kaggle Notebook [`uber-ride-analytics-beginner-project.ipynb`](notebooks/uber-ride-analytics-beginner-project.ipynb) on Kaggle.
- The project runs entirely in **R**, so no additional setup is required if using Kaggle’s R kernel.
- To run locally in RStudio or Jupyter with R, install the Tidyverse libraries:
  ```R
  install.packages("tidyverse")
