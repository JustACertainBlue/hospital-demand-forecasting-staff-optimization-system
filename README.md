# Hospital Demand Forecasting & Staff Optimization System
An end-to-end Business Analytics project that helps hospitals move from reactive operations to proactive, data-driven patient flow management.

## 📌 Overview
Hospitals often face peak-hour congestion, long patient waiting times, doctor overload, and inefficient staffing allocation. This project was developed to address those problems through a unified system that combines demand forecasting, staffing optimization, dashboard monitoring, a staff-facing web prototype, and a patient-support chatbot.

The project uses the Internal Medicine Department of Hanoi Medical University Hospital as a case study. The goal is to help hospital managers anticipate demand, identify overload risk early, allocate staff more effectively, and guide patients toward less crowded time slots.

## 🔗 Interactive Prototype
Check out our interactive prototype here:  
[Hospital Optimization Web Prototype](https://hospital-management-website-five.vercel.app/)

## 🚨 Business Problem
This project addresses four key operational issues:
- Patient demand is uneven and concentrated in peak hours
- Doctor allocation is often fixed rather than demand-based
- Managers have limited visibility into future overload risk
- Patients lack guidance on when to visit to avoid congestion

## 💡 Proposed Solution

The system includes four main components:

### 1. 📈 Demand Forecasting Engine
Forecasts shift-level patient demand using historical patterns and booking data.

### 2. 👨‍⚕️ Staff Optimization Logic
Compares forecasted demand with capacity to identify:
- overloaded shifts
- underutilized shifts
- staffing gaps
- recommended doctor adjustments

### 3. 📊 Analytical Dashboard
A Power BI dashboard that helps managers monitor:
- patient volume trends
- utilization
- overload levels
- forecasted demand
- staffing requirements

### 4. 🤖 Patient Support Chatbot
A chatbot workflow that:
- answers FAQ and hospital policy questions
- recommends less crowded appointment slots
- supports structured booking capture

## ✨ Key Features
- Patient demand forecasting
- Overload detection by shift
- Staffing recommendation logic
- Interactive dashboard for decision-making
- Staff-facing web prototype for shift management
- Chatbot for scheduling support and FAQ automation

## 🔄 Project Workflow
Data → Forecasting → Overload Detection → Staffing Recommendation → Dashboard / Web Tool / Chatbot

This flow turns analytical outputs into practical operational decisions.

## 🗂️ Repository Structure
- `[docs](https://github.com/JustACertainBlue/hospital-demand-forecasting-staff-optimization-system/tree/main/docs)/` – report, slides, screenshots, system architecture
- `data/` – raw, processed, and sample datasets
- `notebooks/` – exploratory analysis and modeling notebooks
- `src/` – reusable code for NLP, forecasting, and optimization
- `api/` – FastAPI service for model inference
- `chatbot/` – n8n workflow, FAQ logic, and scheduling rules
- `dashboard/` – Power BI dashboard file
- `web-app/` – hospital optimization web prototype
- `deployment/` – deployment notes and system flow
- `results/` – model outputs and staffing recommendations

## 🛠️ Tools & Technologies
- Python
- FastAPI
- Random Forest / forecasting models
- Power BI
- n8n
- HTML / CSS / JavaScript
- GitHub
- Render / Vercel
  
## 🙋 My Role
In this group project, my main contributions focused on turning analysis into a more usable product experience:
- Worked on the **Natural Language Processing module** to analyze patient reviews and surface operational pain points
- Built the **web-based hospital optimization prototype** to make forecasting and staffing insights easier for users to act on
- Shape how analytical outputs were translated into a clearer **decision-support workflow** for hospital staff
- Owned the **website/prototype** component in the final project demo
  
## 📈 Business Value
Expected impact of the solution:
- reduce patient waiting time
- reduce peak-hour overload
- improve doctor utilization
- improve patient guidance and scheduling experience
- support more proactive hospital operations

## 📝 Notes
- Some datasets are simulated or prototype-level due to limited access to internal hospital data
- This repository is intended to demonstrate business logic, analytical thinking, and product/system design
- Sensitive or real patient data should not be uploaded
