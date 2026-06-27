# Human Skill Extinction Predictor (HSEP)

## Current State of the Project (June 2026)

The Human Skill Extinction Predictor (HSEP) has evolved from a basic Skill Extinction Score (SES) ranking system into **SkillLens AI**, a complete Workforce Intelligence, Skill Forecasting, Industry Analytics, Recommendation, and Career Intelligence Platform.

The project now combines:

* Workforce Intelligence
* Skill Forecasting
* Temporal Skill Analysis
* NLP-Based Skill Taxonomy
* Skill Archetype Discovery
* Hybrid Forecasting
* Industry Analytics
* Recommendation Intelligence
* RAG-Based Career Advisor Research
* Frontend Dashboard Development
* UI/UX Refinement
* Architecture Documentation

Following mentor feedback, the project expanded beyond simple skill ranking and moved toward a product-ready platform that helps users understand which skills are future-proof, growing, stable, risky, or becoming less relevant.

---

# Major Achievements

## 1. Skill Universe Expansion

### Original Coverage

```text
35 technical skills
```

### Expanded Coverage

```text
114 curated technical skills
```

Built from:

```text
2.7M+ workforce skill mentions
39,004 extracted skills
```

Coverage includes:

* Programming Languages
* AI & Machine Learning
* Cloud Computing
* DevOps
* Databases
* Data Engineering
* Data Analytics
* Cybersecurity
* Software Engineering

This expansion made the project more realistic and reduced the limitations of the original small skill list.

---

## 2. Workforce Intelligence Features

HSEP generates six major workforce intelligence signals:

```text
LinkedIn Demand
Salary Premium
Current Usage
Future Interest
Global Adoption Score
Growth Rate
```

These features represent:

* Hiring Demand
* Compensation Advantage
* Developer Adoption
* Future Learning Interest
* Global Technology Penetration
* Workforce Momentum

These signals form the foundation for skill scoring, clustering, forecasting, and recommendation intelligence.

---

## 3. Longitudinal Workforce Intelligence

A historical reconstruction pipeline was developed using Stack Overflow Developer Survey data.

Coverage:

```text
2013–2025
```

Final Dataset:

```text
114 workforce-aligned technical skills
1,209 skill-year observations
```

Coverage Statistics:

```text
Mean History Length     : 10.6 years
Median History Length   : 12 years
Maximum History Length  : 13 years
```

Examples:

```text
Python          13 years
Java            13 years
JavaScript      13 years
SQL             13 years
AWS             13 years
Docker          11 years
```

This introduced:

* Historical Skill Reconstruction
* Technology Lifecycle Analysis
* Adoption Trend Tracking
* Longitudinal Workforce Intelligence
* Technology Evolution Modeling

---

## 4. NLP-Driven Skill Intelligence

NLP techniques were introduced to improve skill understanding and filtering.

Used for:

* Skill Classification
* Skill Taxonomy Construction
* Technical Skill Filtering
* Noise Removal
* Workforce Knowledge Organization

Skill domains include:

```text
Programming
AI/ML
Cloud
DevOps
Databases
Cybersecurity
Data Engineering
Data Analytics
Software Engineering
```

This helped separate useful technical skills from soft skills, certifications, generic workforce terms, and noisy extracted phrases.

---

## 5. Emerging Skill Recovery

Several strategically important modern technologies were manually recovered and added back into the skill universe:

```text
LangChain
LLM
RAG
Power BI
Tableau
```

These skills were important because they represent current AI, analytics, and career-relevant trends that automated extraction did not fully capture.

---

## 6. Skill Archetype Discovery

Instead of depending only on manually designed SES assumptions, HSEP introduced unsupervised learning for skill segmentation.

### Features Used

```text
linkedin_demand
salary_premium
current_usage
future_interest
global_adoption_score
growth_rate
```

### Method

```text
StandardScaler
      ↓
K-Means Clustering
      ↓
Skill Archetype Discovery
```

### Validation

| K | Silhouette Score |
| - | ---------------: |
| 2 |            0.470 |
| 3 |            0.387 |
| 4 |            0.455 |
| 5 |            0.350 |

Selected:

```text
K = 4
```

Resulting Archetypes:

```text
Future-Proof
Growing
Stable
High-Risk
```

These archetypes provide an interpretable workforce segmentation layer and help explain the role of each skill in the future job market.

---

## 7. Hybrid Forecasting Intelligence

A hybrid forecasting framework was implemented to estimate future workforce demand across the skill universe.

### Forecasting Strategy

```text
≥ 10 Years History
→ Holt's Trend Forecasting

7–9 Years History
→ Exponential Smoothing

< 7 Years History
→ Feature-Based Projection
```

Feature-Based Projection uses:

```text
LinkedIn Demand
Current Usage
Future Interest
Growth Rate
Global Adoption Score
```

### Forecast Outputs

```text
forecast_1y
forecast_2y
forecast_3y
forecast_score
confidence
forecast_trend
```

Trend Categories:

```text
Explosive
Growing
Stable
Declining
```

This allows HSEP to forecast both mature technologies and emerging skills with limited historical data.

---

## 8. Skill Extinction Score (SES)

The SES framework was redesigned to combine current workforce strength, future forecasting behaviour, and skill archetype intelligence.

Current SES logic:

```text
SES =
0.40 × Feature Intelligence
+
0.35 × Forecast Intelligence
+
0.25 × Cluster Intelligence
```

### Feature Intelligence

```text
Feature Intelligence =
0.25 × LinkedIn Demand
+
0.20 × Salary Premium
+
0.20 × Current Usage
+
0.20 × Future Interest
+
0.10 × Global Adoption Score
+
0.05 × Growth Rate
```

### Forecast Intelligence

```text
Forecast Intelligence =
Confidence × Forecast Score
+
(1 - Confidence) × 0.50
```

### Forecast Score

```text
Forecast Score =
0.25 × Forecast Score 1Y
+
0.35 × Forecast Score 2Y
+
0.40 × Forecast Score 3Y
```

### Cluster Intelligence

```text
Future-Proof → 0.90
Growing      → 0.70
Stable       → 0.50
High-Risk    → 0.25
```

SES outputs include:

```text
SES Score
SES Tier
Skill Rankings
Risk Level
```

Categories:

```text
Very Safe
Safe
Moderate
Risky
```

This makes the SES more balanced, interpretable, and connected to real workforce signals.

---

## 9. Industry Analytics

A dedicated Industry Analytics layer was introduced to convert skill-level intelligence into domain-level workforce insights.

Industries analyzed:

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

Generated insights include:

* Industry Rankings
* Top Skills by Industry
* Industry SES Analysis
* Industry Forecast Analysis
* Workforce Trend Analysis
* Archetype Composition Analysis
* Industry-Level Demand Signals

This helps users understand not only which skills are strong, but also which career domains are expected to remain valuable.

---

## 10. Career Intelligence Research

Career intelligence research was introduced to move HSEP beyond analytics and toward personalized guidance.

Research areas include:

* Large Language Models
* Prompt Engineering
* Retrieval-Augmented Generation
* Knowledge Base Design
* Explainable Recommendation Systems
* Skill Gap Analysis
* Career Path Recommendation
* AI-Powered Career Guidance

The goal is to make HSEP capable of answering questions such as:

```text
What should I learn after SQL?

Is Python future-proof?

Which skills are risky in Data Analytics?

How do I move from Data Analyst to Data Scientist?

Which industry has better future growth?
```

---

## 11. HSEP Knowledge Base Design

A knowledge base design was researched to organize HSEP outputs for retrieval.

Knowledge sources include:

```text
ses_rankings.csv
forecast_results.csv
skill_clusters.csv
industry_analytics.csv
industry_summary.csv
top_skills_by_category.csv
expanded_skill_master.csv
```

The knowledge base is planned to contain:

* Skill Profiles
* Industry Profiles
* Forecast Information
* SES Scores
* Skill Archetypes
* Risk Levels
* Related Skills
* Recommendation Signals

This will allow the future AI Career Advisor to answer using HSEP project data instead of generic AI knowledge.

---

## 12. RAG Retrieval Pipeline Research

A RAG retrieval pipeline was researched for the AI Career Advisor.

Basic workflow:

```text
User Query
      ↓
Query Understanding
      ↓
Retrieve Relevant HSEP Knowledge
      ↓
Build Context
      ↓
Send Context to LLM
      ↓
Generate Grounded Career Response
```

Supported query types include:

* Skill Evaluation
* Skill Comparison
* Skill Recommendation
* Industry Guidance
* Career Transition
* Roadmap Generation

This improves explainability and reduces generic or hallucinated responses.

---

## 13. SkillLens AI Frontend Development

The project moved from research into frontend product development under the name:

```text
SkillLens AI
```

SkillLens AI is the user-facing platform built on top of the HSEP intelligence system.

Initial frontend modules include:

* Dashboard
* Skill Explorer
* Forecasts
* Industries
* Recommendation
* Career Advisor
* Reports
* Methodology

The frontend aims to convert HSEP outputs into an interactive and understandable workforce intelligence dashboard.

---

## 14. UI/UX Review and Product Refinement

The frontend was reviewed and refined to improve usability, layout, clarity, and overall product experience.

Focus areas included:

* Cleaner Dashboard Metrics
* Better Skill Explorer Tables
* Improved Forecast Formatting
* Clearer Industry Cards
* Recommendation Page Design
* Career Advisor Chat Layout
* Reports Page Planning
* Methodology Page Improvement
* Better Explainability for SES, Forecasts, and Risk

The goal was to make SkillLens AI feel like a polished product rather than only a research dashboard.

---

## 15. Architecture Documentation and Visual Refinement

The architecture and methodology were updated to reflect the current project direction.

Updated architecture includes:

* Data Foundation
* Skill Universe Expansion
* Skill Classification
* Feature Recalculation
* Temporal Intelligence
* Archetype Discovery
* Hybrid Forecasting
* SES Computation
* Industry Analytics
* Recommendation Intelligence
* Knowledge Base Design
* RAG Retrieval Pipeline
* AI Career Advisor
* SkillLens Frontend

This helped make the project easier to understand for mentors, reviewers, and future users.

---

# Key Challenges

## Historical Data Fragmentation

Stack Overflow survey schemas changed significantly between 2011 and 2025.

This required:

* Schema Normalization
* Alias Mapping
* Historical Harmonization
* Skill Name Standardization
* Cross-Year Reconstruction

---

## Skill Vocabulary Mismatch

LinkedIn data is workforce-oriented, while Stack Overflow data is technology-oriented.

This created mismatches between:

```text
Workforce Skills
vs
Developer Technologies
```

The issue was handled through skill normalization, curated mapping, and technical skill filtering.

---

## Forecasting Constraints

Many emerging technologies have limited historical data.

Examples:

```text
LangChain
LLM
RAG
```

Traditional forecasting is unreliable for such skills, so the project introduced a hybrid forecasting framework that selects the forecasting method based on historical depth.

---

## SES Redesign

The original SES design depended too much on manually engineered assumptions.

The project moved toward:

```text
Feature Intelligence
+
Forecast Intelligence
+
Cluster Intelligence
```

This improved objectivity, interpretability, and robustness.

---

## Product Alignment

As the project evolved into SkillLens AI, the frontend and documentation had to be aligned with the current direction.

This required:

* Renaming Roadmaps to Recommendation
* Improving dashboard clarity
* Updating methodology explanations
* Connecting frontend pages with actual HSEP outputs
* Making the platform more user-friendly and explainable

---

# Current Architecture

<img width="1448" height="1086" alt="image" src="https://github.com/user-attachments/assets/85b951b4-5a0c-4913-9f27-c610347e29f1" />

---

# Current SkillLens AI Modules

## Dashboard

Provides a high-level overview of tracked skills, industries, forecast insights, risk signals, salary indicators, and workforce intelligence summaries.

## Skill Explorer

Allows users to search, filter, inspect, and understand individual skills using SES, demand, salary, forecast, archetype, and risk signals.

## Forecasts

Displays future skill demand predictions using Holt's Trend Forecasting, Exponential Smoothing, and Feature-Based Projection.

## Industries

Shows domain-level workforce insights across AI/ML, Data Science, Data Analytics, Data Engineering, Software Engineering, Cloud & DevOps, Cybersecurity, and Systems Engineering.

## Recommendation

Provides personalized skill suggestions based on current skills, career goals, SES score, forecast trend, industry relevance, demand signals, and risk level.

## Career Advisor

Planned as an AI-powered assistant that uses HSEP data, RAG retrieval, and LLMs to generate explainable career guidance.

## Reports

Designed to summarize and export insights such as skill rankings, forecast reports, industry analytics, high-risk skills, and recommendation summaries.

## Methodology

Explains the complete HSEP pipeline, including datasets, feature engineering, clustering, forecasting, SES computation, industry analytics, recommendation logic, and AI advisor architecture.

---

# Current Status

## Completed

✅ Dataset Collection

✅ Workforce EDA

✅ Workforce Intelligence Features

✅ Skill Universe Expansion

✅ Technical Skill Classification

✅ Historical Intelligence

✅ Longitudinal History Reconstruction

✅ Emerging Skill Recovery

✅ Archetype Discovery

✅ Cluster Validation

✅ Hybrid Forecasting Design

✅ Hybrid Forecasting Implementation

✅ Forecast Intelligence Layer

✅ SES Computation

✅ Skill Ranking Framework

✅ Industry Analytics

✅ Career Intelligence Research

✅ Recommendation System Research

✅ AI Career Advisor Architecture Research

✅ HSEP Knowledge Base Design Research

✅ RAG Retrieval Pipeline Research

✅ SkillLens AI Frontend Dashboard Development

✅ UI/UX Review and Frontend Refinement

✅ Architecture Documentation and Visual Refinement

✅ Product Alignment and Documentation Cleanup

---

## In Progress

🟡 SkillLens Frontend Refinement

🟡 Recommendation Page Improvement

🟡 Career Advisor Interface Planning

🟡 Methodology Page Improvement

🟡 Explainability Improvements

🟡 Product-Level Documentation

---

## Upcoming

🔲 Backend Integration

🔲 RAG Pipeline Implementation

🔲 AI Career Advisor Implementation

🔲 Recommendation Logic Implementation

🔲 Report Generation System

🔲 Full Dashboard Deployment

🔲 Final Testing and Evaluation

---

# Progress Estimate

```text
Research & Data Layer        ██████████ 100%
Feature Engineering          ██████████ 100%
Skill Intelligence           ██████████ 100%
Temporal Intelligence        ██████████ 100%
Archetype Discovery          ██████████ 100%
Forecasting                  ██████████ 100%
SES Engine                   ██████████ 100%
Industry Analytics           ██████████ 100%
Career Intelligence Research ██████████ 100%
Knowledge Base Research      ██████████ 100%
RAG Research                 ██████████ 100%
Frontend Dashboard           ███████░░░ 70%
UI/UX Refinement             ███████░░░ 70%
Recommendation Layer         ████░░░░░░ 40%
Career Advisor               ███░░░░░░░ 30%
Backend                      ░░░░░░░░░░ 0%
Deployment                   ░░░░░░░░░░ 0%
```

Overall Project Completion:

```text
~92%
```

---

# Final Summary

HSEP has progressed from a skill-risk prediction idea into **SkillLens AI**, a complete AI-powered workforce intelligence and career guidance platform.

The project now includes:

* Large-scale workforce data analysis
* Skill universe expansion
* Technical skill classification
* Historical skill intelligence
* Skill archetype discovery
* Hybrid forecasting
* SES computation
* Industry analytics
* Career recommendation research
* RAG-based AI advisor planning
* Frontend dashboard development
* UI/UX and product refinement
* Architecture and methodology documentation

The current focus is on refining the SkillLens AI product experience and preparing the platform for backend integration, recommendation logic, and AI Career Advisor implementation.

---

**Last Updated:** 26 June 2026

**Project:** Human Skill Extinction Predictor (HSEP) / SkillLens AI

**Current Phase:** SkillLens AI Product Development, Frontend Refinement & Documentation

**Status:** Active Development
