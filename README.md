
<img src="Visuals/360-customer-im1.webp" alt="Customer Support Banner" width="700" height="350">

# 📊 CUSTOMER_SUPPORT_DATA_ANALYSIS

## 📑 Table of Contents
- [Project Overview](#-project-overview)
- [Objective](#-objective)
- [Key Visuals](#-key-visuals)
- [Libraries Used](#libraries-used)
- [Key Insights](#-key-insights)
- [Dataset Description](#-dataset-description)
- [Subgroup Analysis](#-subgroup-analysis)
- [📁 Jump to Folder Links](#-jump-to-folder-links)


---

## 📌 Project Overview
This project focuses on analyzing customer support ticket data to understand the most common customer issues, how quickly they are resolved, and how we can improve the overall support experience.
We cleaned and explored the dataset, identified problem areas, and focused especially on elderly users, who often face more technical difficulties. We also analyzed ticket priorities, response delays, resolution time, and customer satisfaction trends.. 
The project is divided into three parts:  
1. Auto-closed tickets  
2. Open (unresolved) tickets  
3. Resolved tickets  

---

## 🔍 Objective
- Identify common ticket types and subjects  
- Analyze response and resolution times 
- Understand how age groups and support channels affect ticket handling 
- To suggest ways to make the support process faster and easier for customers
- Suggest practical solutions like chatbots and improved help sections  

---

## 📊 Key Visuals
The project includes simple and clear graphs like:

- Average Satisfaction Rating Across Age Groups for Resolved Tickets  
- Ticket Status Distribution 
- Customer Issues by Gender and Age Group  
- Types of Issues Reported by Different Age Groups 
- Status Distribution for Ticket Type Issue
- Ticket Priority Breakdown by Ticket Type 

---

##  Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly.express
- nltk  

---

## 📈 Key Insights
- Many tickets were closed automatically after 90 days without a reply from the customer. This helped clean the system.  
- Some tickets were left open with no reply from the support team. These need urgent attention.  
- Elderly users mostly faced technical and refund-related problems.  
- A chatbot and a better help section (FAQs) can help reduce the number of tickets.  
- Some high-priority tickets still got low ratings, showing that we need better support handling.  

---

## 📂 Dataset Description
The dataset includes:

- Customer info: age and gender  
- Ticket details: type, subject, status, priority, and channel  
- Time details: delay in response and total resolution time  
- Customer feedback: satisfaction rating and if the issue was solved  

---

## 📂 Subgroup Analysis

### 🔹 Auto-Closed Tickets  
We checked tickets that were closed automatically after 90 days of no reply from the customer. This helped reduce inactive tickets and made the system cleaner.

### 🔹 Open Tickets  
We found tickets that were open and never got any reply from support. We suggested checking these tickets often, setting high priority, and assigning them quickly to avoid unhappy customers.

### 🔹 Resolved Tickets  
We looked at tickets that were solved. Many elderly users had technical or refund issues. So, we suggested creating a chatbot and improving the help section with easy FAQs to reduce repeated questions.

---

## 📁 Jump to Folder Links
Click below to open each folder directly:

- [CUSTOMER_SUPPORT_DATA_ANALYSIS](./CUSTOMER_SUPPORT_DATA_ANALYSIS)
- [For_auto-closed_tickets](./For_auto-closed_tickets)
- [For_open_tickets](./For_open_tickets)
- [For_resolved_tickets](./For_resolved_tickets)

## 📊 Key Visuals

<table>
  <tr>
    <td><img src="CUSTOMER_SUPPORT_DATA_ANALYSIS/ticket_by_age.png" alt="Ticket by Age Group" width="400"/></td>
    <td><img src="For_auto-closed_tickets/ticket_subject_sunburst.png" alt="Ticket Subject Sunburst" width="400"/></td>
  </tr>
  <tr>
    <td><img src="For_open_tickets/ticket_type_bar.png" alt="Ticket Type Bar" width="400"/></td>
    <td><img src="For_resolved_tickets/response_time_channel.png" alt="Response Time by Channel" width="400"/></td>
  </tr>
</table>


