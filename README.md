# UPI Digital Payments — Drop-Off & Failure Analytics

##  Overview
This project analyzes UPI transaction failures using data engineering, SQL analytics,
and dashboarding to identify operational bottlenecks across banks and PSPs.

---

##  Problem Statement
UPI transactions often fail due to bank downtime, PSP congestion, and network instability.
Goal: Improve success rates & user experience.

---

##  Solution Approach
### 1️ Synthetic Data Generation (10,000 records)
Replicated real UPI patterns:
- Timestamps
- PSPs (Google Pay, PhonePe, Paytm)
- Banks (SBI, HDFC, ICICI, etc.)
- Failure reasons

### 2️ Python Data Processing
- Refund delay calculation
- Drop-off analytics
- Peak-hour congestion indicators

### 3️ SQL Deep Dive
- Bank-wise & PSP-wise failure rates
- Hourly transaction performance
- Root cause segmentation

### 4️ Power BI Dashboard
- KPIs (success rate, peak-hour failures)
- Funnel visualization
- Heatmaps for hourly failures
- Bank performance comparison

---

##  Results
-  13.9% transactions failed
-  SBI + HDFC = **44% failures**
-  6–10 PM peak-hour failures spiked **32%**
-  Estimated daily loss: **₹2.3 Cr**
-  Recommendations improve success rate by **19%**

---

##  Tech Stack
Python · SQL · Power BI · KPI Design · Time-Series Analytics

---



