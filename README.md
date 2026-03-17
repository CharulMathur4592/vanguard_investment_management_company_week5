# 📊 Vanguard Investment Company – Customer Experience Analysis

### 📌 Project Overview
This project was developed as part of the Data Analytics Bootcamp at Ironhack.

The objective of this project is to analyze customer behavior and evaluate the effectiveness of a new website design implemented by Vanguard Group.

Using A/B testing techniques and customer interaction data, we analyze whether the new digital interface improves the client experience and increases task completion rates.

### 🎯 Project Objectives

The main goals of this project are:

- Evaluate the effectiveness of the new Vanguard website design
- Analyze client interaction behavior
- Measure task completion rates
- Identify pain points in the customer journey
- Provide data-driven recommendations

### 📂 Dataset Description

The dataset contains information about customer sessions and interactions with Vanguard's online platform.

Key tables used in the analysis:

- client: Client demographic information
- digital: Online interaction data
- experiment: A/B test assignment
- final_demo: Combined dataset used for analysis

### 📊 Key Variables

- client_id: Unique identifier for each client
- age: Client age
- gender: Client gender
- tenure: Years as a Vanguard client
- balance: Account balance
- experiment_group: Control or Test group
- process_step: Step completed in the process
- date_time: Timestamp of user action

### 🧹 Data Cleaning

Several preprocessing steps were applied before performing the analysis.

Data Cleaning Steps:

- Removed duplicate records
- Standardized column names
- Converted date variables to datetime format
- Handled missing values
- Merged multiple datasets
- Filtered incomplete sessions

### 🔎 Exploratory Data Analysis (EDA)

The following analyses were performed:

#### Client Demographics

- Age distribution
- Gender breakdown
- Account balance distribution

#### User Behavior

- Steps completed per session
- Session duration
- Drop-off points in the process

#### Experiment Analysis

Comparison between:

- Control group (old design)
- Test group (new design)

Metrics analyzed:

- Task completion rate
- Time to completion
- Error rate
- Step abandonment

### 📈 A/B Testing

The experiment compares two website versions:

	Group			Description
- Control	Existing Vanguard interface
- Test		New redesigned interface

### 📊 Visualizations

Visualizations were created using:

- Matplotlib
- Seaborn
- Pandas

Examples include:
- Completion rate comparison
- Client age distribution
- Process step funnel
- Session duration analysis

### 🧠 Key Insights

Main insights from the analysis:

- The test interface improved task completion rates.
- Certain process steps show high drop-off rates, indicating usability issues.
- Older clients tend to take longer to complete digital processes.
- Clients with higher balances tend to complete more online transactions.

### 🛠 Tools & Technologies

The project was built using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Links:

#### 1. Presentation:
https://www.canva.com/design/DAG9wCVBJd4/hgaZO55rBdwTmyUlL1kVXw/edit?utm_content=DAG9wCVBJd4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

#### 2. Tableau Dashboard:
https://public.tableau.com/views/Tableau-Dashboard_17678712622560/Dashboard1?:language=fr-FR&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

#### 3. Trello Board:
https://trello.com/invite/b/69415c7edd885fdcf3b7e805/ATTI5a331276465a6caa86410f4213943ae48F58938D/vanguard-investment-management-company
