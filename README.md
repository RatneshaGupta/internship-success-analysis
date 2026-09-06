# Internship Success Analysis

> A Data Science project exploring factors that may influence internship
> opportunities and outcomes among engineering students.

---

## 📌 Project Overview

This project is part of my B.Tech CSE coursework in Fundamentals of
Data Science.

The aim is to collect and analyze student data to understand how factors
such as CGPA, DSA preparation, projects, GitHub activity, networking,
interview preparation and internship applications relate to internship
outcomes.

The project is currently in the **dataset design stage**. The present
dataset contains dummy/simulated data and will later be replaced or
extended with real responses collected through a Google Form.

---

## 🔎 Defining Data Analytics

Data Analytics is the process of examining and interpreting data to
identify patterns, relationships and useful insights that can support
better understanding and decision-making.

This project focuses on four types of analytics:

| Type | Question | Purpose |
|---|---|---|
| **Descriptive** | What happened? | Summarize the data |
| **Diagnostic** | Why did it happen? | Explore relationships and possible causes |
| **Predictive** | What might happen? | Identify patterns that may help predict outcomes |
| **Prescriptive** | What could be done? | Suggest possible actions based on findings |

---

## 🧪 Dataset Development

### Draft 1 — Initial Dataset

- **20 dummy student records**
- **22 attributes**
- Included academic, technical, preparation and internship-related
  information.

| Analytics Type | Draft 1 Rating |
|---|---|
| Descriptive | 🟢 Good |
| Diagnostic | 🟡 Fair |
| Predictive | 🔴 Limited |
| Prescriptive | 🟡 Fair |

**Observation:** Draft 1 was suitable for basic descriptive analysis,
but some variables were too broad and did not provide enough measurable
information for deeper analysis.

---

### Draft 2 — Improved Dataset

Draft 2 was redesigned to make the dataset more focused and useful
across all four types of analytics.

The dataset was reduced to **17 attributes**:

`Student_ID, Academic_Year, Gender, CGPA, DSA_Practice_Hours_Per_Week,
DSA_Problems_Solved, Relevant_Projects, GitHub_Usage,
Hackathons_Participated, Networking_Frequency, Referral_Received,
Interview_Preparation, Applications_Submitted, Interviews_Received,
Internship_Offers, Internship_Obtained, Internship_Type`

### Improvements

- Replaced **CGPA ranges with numerical CGPA**
- Replaced DSA practice frequency with **weekly DSA hours**
- Kept important internship-related outcome variables
- Removed unnecessary/redundant attributes
- Added **Gender** as a demographic variable
- Increased the number of measurable numerical variables
- Kept the dataset compact and focused

| Analytics Type | Draft 1 | Draft 2 |
|---|---|---|
| Descriptive | 🟢 Good | 🟢 Good |
| Diagnostic | 🟡 Fair | 🟢 Good |
| Predictive | 🔴 Limited | 🟢 Good* |
| Prescriptive | 🟡 Fair | 🟢 Good |

\*The current dataset is still dummy data with only 20 records.
A larger real dataset will be collected before attempting reliable
predictive analysis.

---

## 📊 Current Dataset Status

**Data Type:** Dummy / Simulated  
**Records:** 20  
**Attributes:** 17  
**Current Stage:** Dataset Design

The next stage is to finalize the variables and create a Google Form
for real data collection.

---

## 🚧 Project Progress

- [x] Project topic selected
- [x] Dummy dataset created
- [x] GitHub repository created
- [x] Draft 1 evaluated
- [x] Draft 2 created
- [ ] Finalize dataset
- [ ] Create Google Form
- [ ] Collect real data
- [ ] Clean and preprocess data
- [ ] Exploratory Data Analysis
- [ ] Descriptive Analytics
- [ ] Diagnostic Analytics
- [ ] Predictive Analytics
- [ ] Prescriptive Analytics
- [ ] Create infographic
- [ ] Final report

---

## 👤 Author

**Ratnesha Gupta**  
B.Tech CSE | Fundamentals of Data Science | Semester 3

---

*This repository will be updated regularly as the project progresses.*
