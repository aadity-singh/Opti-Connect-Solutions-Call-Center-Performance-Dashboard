# OptiConnect Solutions – Call Center Performance Dashboard

## 📊 Project Overview
This project delivers an interactive **Power BI dashboard** to analyze the call center operations of **OptiConnect Solutions**. It converts raw call log data into actionable insights, focusing on **agent productivity, customer satisfaction, and departmental performance**.

---

## 🧹 Data Cleaning Summary
The dataset was processed to ensure accuracy and usability for analysis:

1. **Removed Metadata & Empty Rows**
   - Dropped irrelevant top rows and empty entries.

2. **Renamed Columns for Clarity**
   - Applied meaningful column headers for better readability.

3. **Handled Missing Values**
   - Filled unanswered/resolved fields with "No".
   - Imputed or left satisfaction ratings blank when unavailable.
   - Converted talk duration to seconds for better analysis.

4. **Standardized Data Formats**
   - Converted timestamps to `datetime`.
   - Unified Y/N fields to Yes/No.
   - Cleaned agent and department names.

---

## 📑 Dataset Columns
| Column Name         | Description                                      |
|----------------------|--------------------------------------------------|
| **Call_ID**          | Unique identifier for each call                  |
| **DateTime**         | Date and time of the call                        |
| **Agent_Name**       | Name of the call center agent                    |
| **Department**       | Department/product associated with the call      |
| **Answered**         | Whether the call was answered (Yes/No)           |
| **Resolved**         | Whether the issue was resolved (Yes/No)          |
| **Satisfaction_Rating** | Customer satisfaction score (1–5)             |
| **Talk_Duration**    | Duration of the call (hh:mm:ss)                  |
| **Call_Count**       | Number of calls handled by the agent             |
| **Avg_Talk_Duration**| Average talk duration (in seconds)               |

---

## ✨ Key Insights from Dashboard
- **Total Calls:** 1,000  
- **Answer Rate:** 100%  
- **Resolution Rate:** ~90%  
- **Average Speed of Answer (SOA):** ~67 seconds  
- **Average Talk Duration:** ~226 seconds  
- **Average Satisfaction Rating:** ~3.45 / 5  

---

## 🧑‍🤝‍🧑 Agent Performance
- Agents like *Becky, Greg, and Diane* achieved consistently high satisfaction scores.
- Resolution rates remained stable across most agents.
- Talk durations varied slightly, revealing potential process improvements.

---

## 🏢 Departmental Insights
- **Television & Toaster** handled the highest call volumes.
- **Air Conditioner & Fridge** had longer average handling times.
- **Washing Machine** department showed the highest customer satisfaction.

---

## 🗂 Project Structure

Call-Center-Dashboard/
│
├── data/
│ ├── Call_Centre_Dataset_Raw.xlsx # Original dataset
│ └── Call_Center_Dataset_Cleaned.xlsx # Cleaned dataset used in dashboard
│
├── dashboard/
│ └── OptiConnect_Call_Centre_Dashboard.pbix # Power BI dashboard file
│
├── images/
│ └── Call_Center_Dashboard_Preview.png # Dashboard screenshot
│
└── README.md # Project documentation

---

## 🛠 Tools & Technologies
- **Power BI** – Dashboard development & visualization  
- **Excel / Power Query** – Data cleaning & preprocessing  

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Call-Center-Dashboard.git


## 🗂 Project Structure
