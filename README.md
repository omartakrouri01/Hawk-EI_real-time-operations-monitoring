# Hawk Eye KNE – Operations Monitoring & Analytics System

Hawk Eye KNE is a real-time operations monitoring and analytics platform designed to improve visibility, efficiency, and decision-making for maintenance field engineers.

The system combines **live operational data**, **automation workflows**, and **daily KPI analytics** to support supervisors and management teams in monitoring workload distribution, productivity, and resource utilization.

---

## 🚀 Business Problem

Maintenance supervisors lacked:
- Real-time visibility into engineer availability and workload
- Clear KPIs to measure daily productivity and utilization
- Reliable tracking of dashboard usage and operational engagement
- Automated daily performance reporting

This resulted in delayed decisions, underutilized resources, and limited performance transparency.

---

## ✅ Solution Overview

Hawk Eye KNE provides:
- A **real-time dashboard** showing engineer locations, ticket status, and availability
- **Automated analytics tracking** for dashboard usage and interactions
- **Daily KPI calculations** combining product usage and field performance metrics
- A scalable, automation-first architecture using modern BI and workflow tools

---

## 🧩 Key Features

- 🗺️ **Live Engineer Map**
  - Interactive map with workload-based color coding
  - Real-time ticket and site visibility

- 👷 **Engineer Availability Panel**
  - Shows available engineers, scheduled tickets, and last completed tasks
  - Supports better assignment and dispatch decisions

- 📊 **Dual KPI Framework**
  - **Product KPIs:** dashboard usage, clicks, active users
  - **Operations KPIs:** resolved tickets, blocked tickets, utilization

- 🔄 **Fully Automated KPI Pipeline**
  - Real-time event tracking
  - Nightly KPI aggregation and storage
  - Zero manual reporting

---

## 🏗️ System Architecture
 React Dashboard
↓
n8n Webhooks (Automation & Tracking)
↓
MySQL (ERP Data) + Excel Online (Analytics Storage)
↓
Automated Daily KPI Calculation

## 🧠 KPIs Implemented

### Product (Dashboard Usage)
- Daily Refresh Clicks
- Engineer Detail Clicks (Map vs Sidebar)
- Daily Active Users

### Operations (Field Performance)
- Average Resolved Tickets per Engineer
- Average Blocked Tickets per Engineer
- Total Available Engineers per Day

Each KPI includes **threshold-based status indicators** (Blue / Orange / Red) to simplify management decisions.

---

## 🛠️ Technology Stack

| Layer | Tools |
|-----|------|
| Frontend | React, TypeScript, TailwindCSS, Leaflet |
| Automation | n8n (Webhooks, Scheduled Workflows) |
| Database | MySQL (ERP – Read-only) |
| Analytics | Excel Online (Microsoft Graph API) |
| Auth | Supabase |
| Deployment | Lovable.app |

---

## 📈 Business Impact

- Improved real-time visibility of engineer utilization
- Reduced manual reporting through full automation
- Enabled data-driven dispatch and capacity planning
- Created a scalable analytics foundation for future BI and AI use cases

---

## 🔄 Automation Highlights

- Real-time tracking of dashboard interactions
- Scheduled nightly KPI calculation workflows
- Automated data validation and formatting
- Centralized analytics storage for historical analysis
