# BrightTV_Viewership_Analytics_Project

**Project Overview**

This project analyzes user profile and session-level viewership data from BrightTV, a subscription-based streaming platform, to uncover trends and behavioral drivers behind content consumption. Using SQL (Databricks/PySpark) for data transformation and querying, alongside visualization tools for reporting, the project translates raw transactional data into actionable business insights for BrightTV's Customer Value Management (CVM) team.
The analysis covers user engagement patterns, time-based consumption trends, content/channel performance, and demographic influences on viewing behavior — culminating in data-backed recommendations to grow and retain BrightTV's subscriber base.

**Purpose**

## Purpose

BrightTV's CEO has set a strategic objective to grow the platform's subscription base this financial year.  

To achieve this, the CVM team needs a clear, evidence-based understanding of how subscribers currently engage with the platform — including:

- **Who is watching**
  - User demographics  
  - Customer segments  

- **What they are watching**
  - Channels  
  - Genres  
  - Content types  

- **When they are watching**
  - Time of day  
  - Day of week  
  - Peak vs. low periods  

- **Why consumption varies**
  - Package type  
  - Device used  
  - Customer tenure  
  - Region  

This project exists to close that knowledge gap by building a repeatable analytics pipeline that answers these questions and surfaces opportunities for content optimization, scheduling improvements, and subscriber growth initiatives.

**Objectives**

## Objectives

- Identify usage trends and patterns across:
  - Time  
  - Channels  
  - Content categories  

- Determine key factors influencing:
  - Viewership  
  - Engagement  

- Recommend content strategies to:
  - Boost consumption on low-performing days  

- Propose initiatives to:
  - Support subscriber base growth  

- Present findings in:
  - A clear, business-ready 20-minute presentation for leadership  

## Tools Used

| Tool        | Purpose |
|------------|--------|
| Databricks | Data processing, PySpark/Spark SQL querying, Unity Catalog, dashboards (Lakeview) |
| GitHub     | Version control and project documentation/hosting |
| Miro       | Project planning, workflow mapping, brainstorming insights/recommendations |
| Excel      | Supplementary data exploration, quick calculations, ad hoc validation |
| PowerPoint | Final 20-minute insights presentation for leadership |
| Lovable    | Rapid prototyping and building user-facing applications/demos for showcasing project outcomes |
| Gantt Chart| Project timeline planning, task tracking, milestone management, and ensuring delivery alignment |

**Dataset**

- **User profiles:** subscriber demographics, package type, signup date, region
- **Viewing sessions:** one record per session, including channel, genre, content title, start/end timestamps (UTC), device type
