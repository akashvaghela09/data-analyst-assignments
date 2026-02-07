**ACT AS:** A Senior Data Analytics Instructor and Career Coach.

**INPUT:** I am providing you with a Kaggle Dataset link:  
👉 **[INSERT KAGGLE DATASET LINK HERE]** *(Optional: Paste the dataset title and column description here if the link is not accessible)*

**YOUR GOAL:** Create a comprehensive, "Job-Ready" Data Analyst Portfolio Project Assignment based on this specific dataset.

**CRITICAL INSTRUCTION:**
1.  **Analyze the Data Type:** Determine if this is a Time-Series, Geospatial, Categorical, or NLP dataset.
2.  **Adapt the Tasks:** While you MUST follow the "Project Structure" below, you must customize the specific tasks within each phase to fit the data type (e.g., if it's Time-Series, ask for Rolling Averages; if it's Retail, ask for RFM Analysis).
3.  **Business Context:** Invent a realistic business scenario (e.g., "You are an analyst at [Company Type] looking to optimize [Metric]").

**STRICT OUTPUT FORMAT:** Return the response in a clean, structured **Markdown** file following the EXACT template below.

---

# 📝 Project: [Insert Catchy Project Title]

## 1. Project Overview
**Role:** [Define a specific role, e.g., "Supply Chain Analyst", "Marketing Strategist"]  
**Objective:** [Write a 2-sentence business problem. What is the specific business value? e.g., "Analyze customer churn to save $1M in revenue."]

---

## 2. Resources & Links
* **Dataset Source:** [Insert Link Provided]
* **Target Files:** [Identify which specific files from the dataset are most relevant]
* **Documentation/Tools:** * [Suggest 1 specific Python library relevant to this data type]
    * [Link to a relevant documentation page]

---

## 3. Detailed Task Instructions

### Phase 1: Ingestion & Data Quality Audit (The Foundation)
* **Task 1.1:** [Instruction on loading data, specifically mentioning likely file formats like CSV, JSON, or Excel]
* **Task 1.2:** [Identify the specific "dirty data" risk for this dataset. e.g., "Check for negative values in the Price column" or "Standardize date formats"]
* **Task 1.3:** [Instruction to handle duplicates or null values based on the likely dataset size]

### Phase 2: Feature Engineering (The Senior Analyst Step)
* **Task 2.1:** Create at least 3 new columns from existing data that add business value.
    * [Suggestion 1: e.g., Extract 'Month' from Date]
    * [Suggestion 2: e.g., Calculate 'Total_Revenue' = Price * Qty]
    * [Suggestion 3: e.g., Categorize 'Age' into 'Age_Groups']

### Phase 3: Exploratory Data Analysis (The "What" and "When")
* **Task 3.1 (Univariate):** [Instruction to visualize the distribution of the main variable using the most appropriate chart, e.g., Histogram or Box Plot]
* **Task 3.2 (Time/Trend):** [Instruction to visualize trends over time using the appropriate aggregation, e.g., Monthly or Weekly]
* **Task 3.3 (Categorical):** [Instruction to compare groups, e.g., "Compare Sales by Region" using a Bar Chart]

### Phase 4: Advanced Analysis (The "Why" - Correlations & Patterns)
* **Task 4.1:** [Design a specific advanced analysis relevant to this data type. Options: Correlation Heatmap, Geospatial Map, Sentiment Analysis, or Hypothesis Test]
    * *Goal:* [Specific insight to look for]
* **Task 4.2:** [Design a segmentation or grouping task. e.g., "Identify the Top 10% of customers" or "Find underperforming products"]

---

## 4. Expected Deliverables & Output
Your final Jupyter Notebook must contain:
1.  **Executive Summary:** A 3-point bulleted list of your biggest findings at the very top of the file.
2.  **Clean Visualizations:** Every chart must have a `title`, `xlabel`, and `ylabel`. 
3.  **Business Logic:** Below each chart, add a Markdown cell answering: *"So what? How does this help the business?"*
4.  **Final Recommendation:** A clear "Strategy Insight" based on the data.

---

## 💡 Pro-Tips & Suggestions
* **Performance:** [Tip on handling data size or efficiency for this specific dataset]
* **Aesthetics:** [Tip on styling charts for this specific domain]
* **The "Analyst Mindset":** [Specific advice on how to interpret this specific type of data]

---