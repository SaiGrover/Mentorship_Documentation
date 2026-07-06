# SkillLens AI – Mentorship Research Repository

This repository documents my mentorship journey while building **SkillLens AI**, an AI-powered Workforce Intelligence and Career Intelligence Platform.

SkillLens AI is built on the **Human Skill Extinction Predictor (HSEP)** framework and combines workforce analytics, historical skill intelligence, forecasting, industry analytics, recommendation research, explainability, and AI-assisted career guidance.

The project started as a skill-risk prediction system and gradually evolved into a user-facing platform for understanding the changing relevance of technical skills.

---

# Current SkillLens AI Architecture

<img width="1491" height="1055" alt="image" src="https://github.com/user-attachments/assets/bc8b8e64-8779-4611-9e0e-8ffdc7a09073" />

---

# Project Focus

The Human Skill Extinction Predictor analyzes technical skills to identify:

* Future-Proof Skills
* Growing Skills
* Stable Skills
* High-Risk Skills
* Emerging Technologies
* Potentially Obsolete Skills

The system uses:

* Workforce Demand
* Salary Signals
* Current Usage
* Future Interest
* Global Adoption
* Historical Trends
* Skill Clustering
* Hybrid Forecasting
* Industry Analytics

The analytical outputs are presented through the **SkillLens AI** frontend.

---

# Repository Timeline

| Date        | Topic                                        |
| ----------- | -------------------------------------------- |
| 28 May 2026 | Project Ideation & Problem Definition        |
| 29 May 2026 | Feasibility Study & Dataset Evaluation       |
| 01 Jun 2026 | HSEP Research & Planning                     |
| 02 Jun 2026 | System Architecture Design                   |
| 03 Jun 2026 | Dataset Acquisition & EDA                    |
| 04 Jun 2026 | Feature Engineering & NLP Intelligence       |
| 05 Jun 2026 | Global Adoption Intelligence                 |
| 08 Jun 2026 | Temporal Intelligence & Skill Expansion      |
| 09 Jun 2026 | Skill Classification & SES Redesign          |
| 10 Jun 2026 | Feature Recalculation & Forecasting Research |
| 11 Jun 2026 | Forecasting Research                         |
| 12 Jun 2026 | Hybrid Forecasting Implementation            |
| 15 Jun 2026 | Industry Analytics                           |
| 16 Jun 2026 | Career Intelligence Research                 |
| 17 Jun 2026 | Recommendation System Research               |
| 18 Jun 2026 | AI Career Advisor Research                   |
| 19 Jun 2026 | Knowledge Base Design                        |
| 22 Jun 2026 | RAG Retrieval Pipeline Research              |
| 23 Jun 2026 | SkillLens Frontend Development               |
| 24 Jun 2026 | UI/UX Review                                 |
| 25 Jun 2026 | Documentation & Visual Refinement            |
| 26 Jun 2026 | Product Alignment & Frontend Refinement      |
| 29 Jun 2026 | Feedback Section Addition                    |
| 30 Jun 2026 | Mentor Dashboard Review                      |
| 01 Jul 2026 | Dataset Sanity Check                         |
| 02 Jul 2026 | KPI & Graph Refinement                       |
| 03 Jul 2026 | Website Review                               |
| 06 Jul 2026 | UI Bug Fixes & Graph Interpretations         |

---

# Processed Data Scale

```text
120,000+ Job Postings
213,000+ Job-Skill Relationships
40,000+ Salary Records
2.7M+ Workforce Skill Mentions
39,004 Extracted Skills
114 Curated Technical Skills
1,209 Skill-Year Observations
3M+ Total Observations
```

---

# Core Research Components

## Workforce Intelligence

Six major workforce intelligence signals were developed:

```text
LinkedIn Demand
Salary Premium
Current Usage
Future Interest
Global Adoption Score
Growth Rate
```

These signals support skill scoring, clustering, forecasting, industry analytics, and recommendation research.

---

## Temporal Skill Intelligence

Historical skill intelligence was reconstructed using multi-year Stack Overflow Developer Survey data.

This work includes:

* Historical Skill Reconstruction
* Skill Classification
* NLP-Based Skill Taxonomy
* Emerging Skill Recovery
* Longitudinal Trend Analysis
* Technology Adoption Tracking

---

## Skill Archetype Discovery

K-Means clustering was used to group skills into four interpretable archetypes:

```text
Future-Proof
Growing
Stable
High-Risk
```

The clustering process uses workforce demand, salary, current usage, future interest, global adoption, and growth signals.

---

## Hybrid Forecasting

The forecasting system selects a method according to historical depth:

```text
≥ 10 Years
→ Holt's Trend Forecasting

7–9 Years
→ Exponential Smoothing

< 7 Years
→ Feature-Based Projection
```

Forecast outputs include:

```text
1-Year Forecast
2-Year Forecast
3-Year Forecast
Forecast Score
Confidence
Forecast Trend
```

---

## Skill Extinction Score

The final SES combines:

```text
SES =
0.40 × Feature Intelligence
+
0.35 × Forecast Intelligence
+
0.25 × Cluster Intelligence
```

The score is used to generate skill rankings, risk levels, and safety categories.

---

## Industry Intelligence

Industry-level analytics were developed for:

```text
AI & Machine Learning
Data Science
Data Analytics
Data Engineering
Software Engineering
Cloud & DevOps
Cybersecurity
Systems Engineering
```

Insights include:

* Top Skills by Industry
* SES Patterns
* Forecast Trends
* Demand Signals
* Archetype Distribution
* Industry-Level Comparisons

---

## Career Intelligence Research

Research was conducted on:

* Recommendation Systems
* Skill Gap Analysis
* Career Transition Guidance
* Large Language Models
* Retrieval-Augmented Generation
* Knowledge Base Design
* Explainable Recommendations
* AI Career Advisor Architecture

This research explores how HSEP outputs can support grounded and personalized career guidance.

---

# SkillLens AI Platform

SkillLens AI presents HSEP research through an interactive frontend.

## Dashboard

Provides a summary of workforce intelligence through:

* KPIs
* Skill Trends
* Risk Signals
* Forecast Insights
* Salary Indicators
* Industry-Level Summaries

The Dashboard was critically reviewed during mentor feedback sessions and later refined through KPI updates, graph improvements, dataset validation, and UI fixes.

## Skill Explorer

Allows users to search and inspect individual skills using:

* SES Score
* Risk Level
* Demand
* Salary Signal
* Forecast Trend
* Skill Archetype

## Forecasts

Displays:

* 1-Year Forecast
* 2-Year Forecast
* 3-Year Forecast
* Forecast Trend
* Forecast Confidence
* Forecasting Method

## Industries

Provides domain-level workforce intelligence and comparison across major technology industries.

## Recommendation

Provides skill suggestions using:

* Current Skills
* Career Goals
* SES Score
* Forecast Trend
* Industry Relevance
* Demand Signals
* Risk Level

## Career Advisor

Represents the AI-assisted career guidance direction of the project.

Research for this module includes:

* Recommendation System Research
* AI Career Advisor Architecture
* Knowledge Base Design
* RAG Retrieval Research
* Explainable Response Design

## Reports

Designed to summarize:

* Skill Rankings
* Forecast Results
* Industry Analytics
* High-Risk Skills
* Growing Skills
* Recommendation Insights

## Methodology

Explains the complete HSEP research process, including:

* Data Sources
* Skill Universe Expansion
* Feature Engineering
* Temporal Intelligence
* Skill Classification
* Archetype Discovery
* Hybrid Forecasting
* SES Computation
* Industry Analytics
* Recommendation Research
* Career Advisor Research

The Methodology page received positive feedback during mentor review for clearly explaining the depth and workflow of the project.

## Feedback

A dedicated Feedback section allows mentors, reviewers, and users to provide suggestions related to the platform and overall user experience.

---

# Mentor Review and Validation

A mentor review session was conducted for the Dashboard page.

The review focused on:

* KPI Purpose
* KPI Naming
* Graph Selection
* Graph Purpose
* Chart Readability
* Data Presentation
* User Understanding

A major takeaway from the review was:

```text
Every graph should clearly answer:

What does it show?
Why is it useful?
What should the user understand from it?
```

Following the review:

* Dashboard KPIs were refined
* Graph titles and labels were improved
* Forecast values were reviewed
* Dataset sanity checks were performed
* UI bugs were fixed
* Graph interpretations were added throughout the website

---

# Graph Explainability

Interpretations were added to analytical graphs across SkillLens AI.

The explanation approach follows:

```text
Graph
   ↓
Visible Pattern
   ↓
Interpretation
   ↓
Practical Insight
```

The purpose is to make analytical outputs understandable even for users without a technical data analysis background.

Interpretations focus on explaining the meaning and usefulness of the visualization rather than repeating the values already visible in the graph.

---

# Repository Contents

## Documentation

The repository contains dated mentorship documentation covering:

* Research and planning
* Dataset evaluation
* EDA
* Feature engineering
* Temporal intelligence
* Skill clustering
* Forecasting
* SES computation
* Industry analytics
* Career intelligence research
* Recommendation research
* RAG research
* Frontend development
* Mentor feedback
* Dataset validation
* UI refinement
* Graph explainability

## Core Notebooks

```text
01_Dataset_Inventory.ipynb
02_EDA_LinkedIn.ipynb
03_EDA_StackOverflow.ipynb
04_SES_Feature_Engineering.ipynb
04C_NLP_Skill_Extraction.ipynb
04D_SkillNER_Extraction.ipynb
05_Global_Adoption.ipynb
06_Growth_Rate_Feature_Engineering.ipynb
08A_Build_Skill_Demand_History.ipynb
08B_Skill_History_Normalization.ipynb
08C_Skill_Universe_Expansion.ipynb
08D_Skill_Classification.ipynb
08E_Longitudinal_History_Rebuilder.ipynb
09_Feature_Recalculation.ipynb
10_Skill_Archetype_Clustering.ipynb
11_Hybrid_Forecasting.ipynb
12_SES_Computation.ipynb
13_Industry_Analytics.ipynb
14_Career_Advisor_Research.ipynb
```

## Generated Datasets

```text
expanded_skill_master.csv
skill_demand_history.csv
skill_demand_history_clean.csv
skill_clusters.csv
forecast_results.csv
ses_rankings.csv
industry_analytics.csv
industry_summary.csv
top_skills_by_category.csv
global_adoption.csv
```

---

# Project Evolution

SkillLens AI progressed through five major stages:

```text
Research & Ideation
        ↓
Workforce Intelligence Development
        ↓
Forecasting & Skill Intelligence
        ↓
Career Intelligence Research
        ↓
SkillLens AI Product Development
```

The final platform combines technical research with an interactive product experience.

---

# Summary

SkillLens AI began as a project focused on predicting whether technical skills could become less relevant over time.

During the mentorship, it evolved into a broader workforce intelligence platform combining:

* Workforce Data Analysis
* Historical Skill Intelligence
* NLP-Based Skill Classification
* Skill Archetype Discovery
* Hybrid Forecasting
* SES Computation
* Industry Analytics
* Recommendation Research
* RAG-Based Career Advisor Research
* Frontend Dashboard Development
* Mentor-Driven Refinement
* Dataset Validation
* Feedback Collection
* Graph Interpretation
* Explainable Workforce Insights

This repository documents the complete journey from project ideation and research to forecasting, career intelligence, frontend development, mentor review, and final product refinement.
