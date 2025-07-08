# Educational Organisation Using ServiceNow

This project presents an Educational Management System (EMS) built on the ServiceNow platform. It aims to streamline student admissions, academic progress tracking, and administrative operations for educational institutions.

---

## Table of Contents

- Project Overview
- Setup Instructions
- Core Tables
- Form Configuration
- Automation Features
- Results
- Advantages and Disadvantages
- Future Scope
- Demo
- GitHub Repository

---

## Project Overview

The Educational Management System (EMS) is designed to:
- Manage student and admission records
- Simplify the admission process
- Track academic progress
- Automate workflows and form interactions
- Improve operational efficiency using a centralized and customizable platform

---

## Setup Instructions

### 1. Create a ServiceNow Developer Account
- Visit the ServiceNow Developer Portal at [https://developer.servicenow.com](https://developer.servicenow.com)
- Sign up and create an account

### 2. Request and Access a Developer Instance
- Navigate to "Manage > Instance" and request an instance
- Use the credentials sent via email to log in

### 3. Create an Update Set
- Go to "All > Local Update Sets"
- Create a new set named "Educational Organisation"
- Click "Make Current" to activate it

---

## Core Tables

### Salesforce Table
This table stores student details, including:
- Admin Number (auto-generated)
- Grade (configured as a choice field)

### Admission Table
This table extends the Salesforce table and manages student admissions. It includes:
- Admission Number
- Grade
- School
- Pincode
- Admin Status, Purpose of Join, and School Area (configured as choice fields)

---

## Form Configuration

Form Designer is used to configure table forms:
- Salesforce Table Form: Add and arrange fields for a clear user experience
- Admission Table Form: Similar configuration for the Admission data
- Student Progress Table Form: Designed to track academic records

---

## Automation Features

The EMS includes client-side automation such as:
- Auto-population of fields based on selected admission number
- Pincode-based updates for Mandal, City, and District
- Disabling manual entry for specific calculated fields
- Automatic total calculation of subject marks

These features improve form usability and reduce manual errors.

---

## Results

The EMS delivers:
- Centralized and organized student data
- Automated workflows for better accuracy
- Easier tracking of admissions and academic progress
- Improved efficiency and decision-making for educational institutions

Recommended screenshots to include:
- Table configuration views
- Admission and Progress records
- Form behavior during data entry

---

## Advantages and Disadvantages

### Advantages
- Cloud-based access from any location
- Highly customizable to suit different educational setups
- Secure access based on user roles

### Disadvantages
- Requires familiarity with ServiceNow
- Licensing costs may apply for enterprise-level use
- Customization can be time-consuming

---

## Future Scope

This system can be extended to include:
- Integration with analytics tools such as Power BI or Tableau
- Teacher scheduling and performance tracking modules
- Mobile application support using ServiceNow Mobile Studio
- AI-driven performance monitoring and predictions

---

## Demo

Watch the working demo on YouTube:  
[https://www.youtube.com/watch?v=uequsynYkUA](https://www.youtube.com/watch?v=uequsynYkUA)

---

## GitHub Repository

[]()

---

**Developed using the ServiceNow platform to support modern educational workflows.**
