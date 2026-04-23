# Manufacturing-Downtime-Analysis-Project
Understanding Production Efficiency, Downtime Drivers & Operator Impact

<img width="666" height="1000" alt="Untitled design (1)" src="https://github.com/user-attachments/assets/6977119d-f801-44c3-9c9b-d8003c98f64b" />


### Project Overview

In manufacturing, downtime is often seen as unavoidable — but is it really?

This project analyzes a soda bottling production line to uncover:

* How efficiently the line is operating
* What is causing downtime
* Whether inefficiencies are driven by systems or operators

Using real-world production data, I built a 3-page interactive dashboard that breaks down performance, identifies bottlenecks, and highlights opportunities for improvement.

### Problem Statement

Production inefficiencies are often difficult to diagnose because:

* Downtime appears scattered
* Multiple factors contribute simultaneously
* It’s unclear whether issues are process-related or operator-driven

The goal of this project is to bring clarity by answering three key questions:

- Are we operating efficiently?
- What is causing downtime?
- Who is driving performance or delays?

### Dataset Description

The dataset consists of four tables:

* **Line Productivity** → Batch-level production data (start time, end time, operator, product)
* **Line Downtime** → Downtime duration across multiple factors per batch
* **Products** → Product details including minimum expected batch time
* **Downtime Factors** → Descriptions of downtime causes and whether they are operator-related

### Data Preparation

Before analysis, several transformations were carried out:

* Converted production time into minutes for accurate aggregation
* Reshaped downtime data by unpivoting multiple factor columns
* Cleaned and standardized date/time formats
* Built relationships between tables to enable cross-analysis

### Dashboard Structure

The final dashboard is divided into three key sections:

##### 1. Production Performance Overview

**Goal**: Understand overall efficiency

This page answers:

* Are we meeting expected production time?
* Which products are underperforming?

**Key Insights:**

* Some products consistently exceed expected production time
* Efficiency varies significantly across products
* Downtime contributes directly to performance gaps

<img width="522" height="279" alt="Page 1D" src="https://github.com/user-attachments/assets/6821a556-d3c6-445c-9bae-064b89344904" />


##### 2. Downtime Root Cause Analysis

**Goal:** Identify what is slowing production down

This page answers:

* What are the main causes of downtime?
* Are issues driven by operators or systems?

**Key Insights:**

* A large number of factors account for most downtime
* Downtime is not random; it follows clear patterns
* Operator errors contribute a noticeable share of inefficiencies

<img width="510" height="284" alt="Page 2D" src="https://github.com/user-attachments/assets/1f6ef075-8b1f-404f-9293-80ae37ebd8bf" />


##### 3. Operator Deep Dive

**Goal:** Evaluate individual operator performance

This page answers:

* Which operators are efficient or struggling?
* What specific issues affect each operator?

**Key Insights:**

* Operator performance varies significantly
* Some operators are more affected by specific downtime factors
* Not all downtime is operator-driven; system issues also play a role

<img width="508" height="284" alt="Page 3D" src="https://github.com/user-attachments/assets/e0f4701c-322a-428a-a383-01014326f87b" />


### Key Takeaways
* Downtime is concentrated, not random.
* Efficiency gaps exist across products and operators
* Operator errors contribute to downtime, but are not the sole cause
* Separating “what is happening” from “why it is happening” is critical for real insight

### Tools Used
* Microsoft Excel (Power Query & Power Pivot)
* DAX (for calculations and measures)
* Data Modeling (Star Schema approach)
* Data Visualization & Dashboard Design

### Final Thoughts

This project reinforced an important lesson:

 / *Data doesn’t just show problems — it helps you understand where to look and what to fix.*

By structuring the analysis into:

* Performance → Root Cause → Responsibility

…it becomes easier to move from observation to action.

### Let’s Connect

If you’re interested in data analytics, dashboard design, or solving real business problems with data, feel free to connect or share your thoughts!
