# Asynchronous Module: Week 3, Class 1
**Course:** HES 3000-002: Sport Performance Analytics  
**Format:** Asynchronous / At-Home Online Learning  
**Topic:** Data Collection, Messy Spreadsheets, and Basic Data Hygiene  

---

## I. Welcome & Objectives
Welcome to your first asynchronous session of the semester! By now, your group project teams are formed, and you have started thinking about your core research questions. 

Today's objective is entirely practical: **Get your data in hand and ensure it is clean enough to work with in R.** 

By the end of this module, you should have a raw dataset downloaded, stored correctly in your project repository, and verified so that you are ready for next week's descriptive analytics labs.

---

## II. Step 1: Sourcing Your Data (The Hunt)
If your group hasn't finalized a dataset yet, today is the day to lock it down. Here are the primary places to look depending on your chosen domain:

1. **Public Sports Repositories & Open Data:**
   - **Kaggle:** Search for sport-specific datasets (e.g., tracking data, historical box scores, player tracking logs).
   - **GitHub Open Repositories:** Many sports analytics communities host clean CSV files ready for R import.
   - **League/Federation Stats:** Public CSV exports or historical archives.
2. **The "Checklist" for a Good Project Dataset:**
   - Does it have at least **several hundred rows** (observations) so you can run meaningful summaries?
   - Does it include a mix of **numeric variables** (e.g., speed, distance, points) and **categorical variables** (e.g., position, team, home/away)?
   - Is it actually downloadable as a `.csv` file? (Avoid data locked behind hard-to-scrape web pages for this project).

---

## III. Step 2: Understanding "Messy" Data
Real-world sports data is rarely clean. When you download your CSV file and open it, you will likely encounter common hygiene issues that break code in R:

* **Inconsistent Naming:** Column names with spaces (`Player Name`), special characters, or mixed capitalization (`GPS_Distance` vs `gps distance`).
* **Missing Values:** Blank cells, strange placeholder characters (like `-999` or `N/A`), or unformatted text mixed into numeric columns.
* **Untidy Structure:** Data where variables are spread across column headers instead of rows (we will talk more about tidy data principles soon).

---

## IV. Step 3: Practical Checklist & Deliverable
To complete today's asynchronous session, your group must accomplish the following milestones by our next in-class meeting:

1. [ ] **Download your raw dataset** as a `.csv` file.
2. [ ] **Create a `data/` folder** inside your project directory and place the raw CSV file inside it.
3. [ ] **Perform a quick sanity check:** Open the file in a spreadsheet viewer or RStudio to ensure columns load properly and headers are readable.
4. [ ] **Draft a 1-paragraph summary** of what your dataset contains, what variables you plan to analyze, and submit it to the course management system as your proof of completion.

---

## V. Looking Ahead
In our next class (**Week 3, Class 2**), we will meet back in person to discuss **Athlete Data Privacy, Consent, and the Ethics of Tracking Physical Fatigue**. 

Make sure your data is downloaded and organized before you arrive!