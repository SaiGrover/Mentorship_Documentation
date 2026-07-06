# Human Skill Extinction Predictor (HSEP)

## Current State of the Project (July 2026)

The Human Skill Extinction Predictor (HSEP) has evolved from a basic Skill Extinction Score (SES) ranking system into **SkillLens AI**, a Workforce Intelligence, Skill Forecasting, Industry Analytics, Recommendation, and Career Intelligence Platform.

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
* Feedback Collection
* Dataset Validation
* Graph Explainability
* Mentor-Driven Product Refinement

Following mentor feedback and multiple rounds of frontend review, the project expanded beyond simple skill ranking and moved toward a user-facing platform that helps users understand which skills are future-proof, growing, stable, risky, or becoming less relevant.

The latest phase of development focused on validating dashboard data, improving KPIs and graphs, fixing UI issues, and adding interpretations to analytical visualizations throughout the website.

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

These signals form the foundation for skill scoring, clustering, forecasting, industry analytics, and recommendation intelligence.

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

These archetypes provide an interpretable workforce segmentation layer and help explain the position of each skill in the changing technology market.

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
Future Interest
Growth Rate
Current Usage
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
High-Risk    → 0.30
```

SES outputs include:

```text
SES Score
SES Tier
Skill Rankings
Risk Level
```

Risk categories include:

```text
Very Safe
Safe
Moderate
Risky
Extinction Risk
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

This helps users understand not only which skills are strong, but also which technology domains show stronger future potential.

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

The goal is to make HSEP capable of supporting questions such as:

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

This provides the foundation for a future AI Career Advisor that can answer using project intelligence instead of generic AI knowledge.

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
* Personalized Guidance

This approach is intended to improve explainability and reduce generic or hallucinated responses.

---

## 13. SkillLens AI Frontend Development

The project moved from research into frontend product development under the name:

```text
SkillLens AI
```

SkillLens AI is the user-facing platform built on top of the HSEP intelligence system.

Current frontend modules include:

* Dashboard
* Skill Explorer
* Forecasts
* Industries
* Recommendation
* Career Advisor
* Reports
* Methodology
* Feedback

The frontend converts HSEP outputs into an interactive and understandable workforce intelligence dashboard.

---

## 14. UI/UX Review and Product Refinement

The frontend was reviewed and refined to improve usability, layout, clarity, and overall product experience.

Focus areas included:

* Cleaner Dashboard Metrics
* Better Skill Explorer Tables
* Improved Forecast Formatting
* Clearer Industry Cards
* Recommendation Page Design
* Career Advisor Interface Improvement
* Reports Page Planning
* Methodology Page Improvement
* Better Explainability for SES, Forecasts, and Risk

The goal was to make SkillLens AI feel like a polished product rather than only a research dashboard.

---

## 15. Architecture Documentation and Visual Refinement

Project methodology and system flow were documented visually to make the technical work easier to understand.

Visual documentation included:

* HSEP Pipeline Overview
* Detailed Pipeline Flowchart
* SES Formula Explanation
* Methodology Visuals
* Frontend UI Concepts

These assets improved communication of the technical methodology during mentor review and project documentation.

---

## 16. Feedback Section Addition

A dedicated Feedback section was added to SkillLens AI.

The purpose of the section is to allow users, mentors, and reviewers to provide suggestions about:

* Dashboard usability
* Skill Explorer experience
* Forecast clarity
* Industry insights
* Recommendation usefulness
* Career Advisor experience
* Methodology explanation
* Overall UI/UX

The Feedback section makes the platform more review-friendly and supports future improvement based on actual user responses.

---

## 17. Mentor Dashboard Review

A detailed mentor meeting was conducted to critically review the Dashboard page.

The mentor analyzed:

* KPI Cards
* Graph Selection
* Chart Readability
* Graph Purpose
* Data Presentation
* Dashboard Flow
* Visual Clarity
* User Understanding

For every graph, the core questions discussed were:

```text
What does this graph show?

Why is this graph useful?

What should the user understand from it?

Does it support the purpose of the platform?
```

The mentor also appreciated the **Methodology page**, particularly its clear explanation of the project workflow and data-driven approach.

The review resulted in a structured list of dashboard improvements and bug fixes.

---

## 18. Dataset Sanity Check and Data Validation

Following the mentor review, the core datasets were checked for consistency and realistic interpretation.

Datasets reviewed included:

```text
industry_analytics.csv
canonical_skill_demand_history.csv
ses_rankings.csv
forecast_results.csv
```

The review focused on:

* KPI Validity
* Skill Ranking Logic
* Forecast Value Interpretation
* SES Score Distribution
* Graph Scaling
* Current Skill Relevance
* Industry-Level Patterns
* Historical Trend Consistency

This step was important because dashboard visuals should not only look good but must also be supported by meaningful data.

---

## 19. Dashboard KPI and Graph Refinement

Based on mentor feedback and dataset validation, several dashboard improvements were applied.

Work included:

* KPI Label Refinement
* KPI Value Formatting
* Graph Title Improvements
* Axis Label Improvements
* Forecast Value Presentation
* Graph Scaling Corrections
* Chart Spacing Improvements
* Removal of Unclear Visual Elements
* Better Dashboard Flow

The goal was to make every Dashboard element easier to understand for a first-time user.

---

## 20. UI Bug Fixes and Graph Explainability

Remaining UI bugs were fixed across SkillLens AI and interpretations were added to analytical graphs throughout the website.

UI improvements focused on:

* Section Spacing
* Card Alignment
* Text Readability
* Chart Positioning
* Responsive Behaviour
* Visual Consistency
* Outdated Text Removal
* Overall Layout Polish

Graph interpretation sections were added to help users understand:

* What the graph represents
* What trend or pattern is visible
* Why the graph is important
* What conclusion can be drawn from it

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

This significantly improved the explainability of SkillLens AI.

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

## Dashboard Explainability

One major product challenge was ensuring that charts and KPIs were understandable to users.

Initial dashboard visuals required improvement in:

* Graph Purpose
* Titles
* Labels
* Scaling
* KPI Names
* Value Formatting
* Interpretation

This was improved through mentor review, dataset validation, graph refinement, and interpretation sections.

---

## Product Alignment

As the project evolved into SkillLens AI, the frontend and documentation had to remain aligned with the actual product direction.

This required:

* Replacing Roadmaps with Recommendation
* Improving Dashboard Clarity
* Updating Methodology Explanations
* Connecting Frontend Pages with HSEP Outputs
* Adding Feedback Collection
* Improving Explainability
* Making the Platform More User-Friendly

---

# Current Architecture

<img width="1448" height="1086" alt="HSEP Architecture" src="https://github.com/user-attachments/assets/85b951b4-5a0c-4913-9f27-c610347e29f1" />

---

# Current SkillLens AI Modules

## Dashboard

Provides a high-level overview of tracked skills, industries, forecast insights, risk signals, salary indicators, and workforce intelligence summaries.

The Dashboard was critically reviewed with the mentor and later refined through KPI updates, graph improvements, bug fixes, and interpretation additions.

## Skill Explorer

Allows users to search, filter, inspect, and understand individual skills using SES, demand, salary, forecast, archetype, and risk signals.

## Forecasts

Displays future skill demand predictions using Holt's Trend Forecasting, Exponential Smoothing, and Feature-Based Projection.

Forecast results include trend direction and confidence information to improve interpretation.

## Industries

Shows domain-level workforce insights across AI/ML, Data Science, Data Analytics, Data Engineering, Software Engineering, Cloud & DevOps, Cybersecurity, and Systems Engineering.

## Recommendation

Provides skill suggestions using current skills, career goals, SES score, forecast trend, industry relevance, demand signals, and risk level.

The Recommendation module replaced the earlier Roadmaps direction to better match the career intelligence focus of the project.

## Career Advisor

Represents the AI-powered career guidance direction of SkillLens AI.

The current work includes:

* LLM Research
* Career Recommendation Research
* AI Career Advisor Architecture Research
* Knowledge Base Design
* RAG Retrieval Research
* Frontend Interface Planning

Full RAG and backend implementation remain future extensions.

## Reports

Designed to summarize and export insights such as:

* Skill Rankings
* Forecast Reports
* Industry Analytics
* High-Risk Skill Insights
* Recommendation Summaries

## Methodology

Explains the complete HSEP methodology, including:

* Datasets
* Skill Universe Expansion
* Feature Engineering
* Temporal Intelligence
* Clustering
* Forecasting
* SES Computation
* Industry Analytics
* Recommendation Logic
* AI Advisor Research Direction

The Methodology page received positive feedback during mentor review.

## Feedback

Provides a dedicated space for mentors, reviewers, and users to share suggestions about the platform.

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

✅ Feedback Section Addition

✅ Mentor Dashboard Review

✅ Dataset Sanity Check

✅ Dashboard Data Validation

✅ KPI Refinement

✅ Graph Refinement

✅ Forecast Display Improvements

✅ UI Bug Fixes

✅ Website-Wide Graph Interpretations

✅ Frontend Explainability Improvements

✅ Frontend Deployment

---

## In Progress

🟡 Final Website Testing

🟡 Final Documentation Cleanup

🟡 Final UI Consistency Checks

🟡 Final Project Review Preparation

---

## Future Scope

🔲 Backend API Integration

🔲 RAG Pipeline Implementation

🔲 AI Career Advisor Full Implementation

🔲 Advanced Recommendation Logic

🔲 Automated Report Generation

🔲 User Profiles and Personalization

🔲 Continuous Data Update Pipeline

🔲 Model and Forecast Monitoring

---

# Progress Estimate

```text
Research & Data Layer         ██████████ 100%
Feature Engineering           ██████████ 100%
Skill Intelligence            ██████████ 100%
Temporal Intelligence         ██████████ 100%
Archetype Discovery           ██████████ 100%
Forecasting                   ██████████ 100%
SES Engine                    ██████████ 100%
Industry Analytics            ██████████ 100%
Career Intelligence Research  ██████████ 100%
Knowledge Base Research       ██████████ 100%
RAG Research                  ██████████ 100%
Frontend Dashboard            ██████████ 100%
UI/UX Refinement              ██████████ 100%
Dashboard Validation          ██████████ 100%
Graph Explainability          ██████████ 100%
Feedback System               ██████████ 100%
Recommendation Experience     ███████░░░ 70%
Career Advisor Implementation ███░░░░░░░ 30%
Backend                       ░░░░░░░░░░ 0%
```

Overall Current-Scope Completion:

```text
~98%
```

The remaining advanced backend, full RAG implementation, and production-level AI Career Advisor are considered future extensions beyond the completed research and frontend scope.

---

# Final Summary

HSEP has progressed from a skill-risk prediction idea into **SkillLens AI**, an AI-powered workforce intelligence and career guidance platform.

The project now includes:

* Large-Scale Workforce Data Analysis
* Skill Universe Expansion
* Technical Skill Classification
* Historical Skill Intelligence
* Skill Archetype Discovery
* Hybrid Forecasting
* SES Computation
* Industry Analytics
* Career Recommendation Research
* RAG-Based AI Advisor Planning
* Frontend Dashboard Development
* Feedback Collection
* Mentor-Driven Review
* Dataset Sanity Validation
* KPI and Graph Refinement
* UI Bug Fixes
* Graph Interpretation and Explainability
* Product and Documentation Refinement

The latest phase focused on making the platform more reliable, understandable, and explainable.

Mentor feedback directly influenced dashboard improvements, while dataset validation ensured that displayed insights were checked before final refinement.

The addition of graph interpretations means SkillLens AI now not only displays analytical results but also helps users understand their meaning and relevance.

The current project phase is focused on final testing, documentation cleanup, and closing the current project development cycle.

---

**Last Updated:** 06 July 2026

**Project:** Human Skill Extinction Predictor (HSEP) / SkillLens AI

**Current Phase:** Final UI Stabilization, Explainability & Project Review

**Status:** Near Completion / Final Review Stage
