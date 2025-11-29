# Incident-Management-Dashboard
SLA Tracking &amp; IT Incident Management Power BI Dashboard  Keep it Public

# IT Operations Dashboard

A Power BI dashboard showcasing IT Incident Management analytics, SLA tracking, and operational insights.

---

## **Overview**
This dashboard provides a comprehensive view of IT operations data, enabling insights into incident trends, SLA compliance, resolution efficiency, and priority-based analysis. The dashboard is built using Power BI with data sourced from ServiceNow/Excel datasets.

---

## **Key Features**
- **Incident Overview:** Total incidents, categorized by priority, type, and assigned group.  
- **SLA Compliance:** Gauge and trend analysis of SLA breaches versus SLA met.  
- **Resolution Efficiency:** Average MTTR (Mean Time to Resolution) and MTBF (Mean Time Between Failures).  
- **Trend Analysis:** Monthly and weekly incident trends, SLA breach patterns.  
- **Priority Analysis:** Breakdown of incidents by priority and resolution performance.  
- **Interactive Filters:** Filter dashboards by category, priority, assigned group, and time period.

---

## **Data Source**
- ServiceNow incident logs exported to CSV/Excel  
- Sample dataset included (500+ incidents)  
- Columns include: Incident ID, Opened Date, Resolved Date, Priority, Category, Assigned Group, SLA Breach, Time Taken  

---

## **Analysis & Insights**
- **SLA Breach Trends:** Identified recurring breaches in high-priority incidents, suggesting process bottlenecks.  
- **MTTR by Priority:** High-priority incidents resolved faster than low-priority, indicating prioritization is effective.  
- **Incident Volume:** Peak incident periods identified, useful for resource planning.  
- **Operational Improvements:** Visuals help highlight areas where process automation or additional training could reduce SLA breaches.  

---

## **Technologies Used**
- Power BI Desktop  
- DAX for calculations (Average MTTR, SLA %, etc.)  
- Excel / CSV for raw data handling  
- Conditional formatting & interactive slicers for visualization  
