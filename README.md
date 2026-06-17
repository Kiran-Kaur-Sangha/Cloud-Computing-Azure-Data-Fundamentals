# Cloud-Computing-and-Azure-Data-Fundamentals

## Overview

Week 5 took me beyond analysing data and into the world of cloud infrastructure, where I explored how organisations store, manage, secure, and scale data using Microsoft Azure.

From comparing cloud service models and deployment strategies to provisioning Azure databases and querying cloud-hosted data, this week helped me understand what happens behind the scenes before data ever reaches a dashboard or report.

One thing quickly became clear: modern data isn't just stored somewhere — it's constantly moving through cloud services, databases, security layers, and analytics platforms that all need to work together seamlessly.

---

# 🌩️ Cloud Computing Fundamentals

### Topics Explored

* Cloud Computing vs On-Premises Infrastructure
* Scalability & Elasticity
* Cloud Cost Management
* Data Storage & Accessibility
* Availability & Reliability

### Key Takeaway

Cloud computing allows organisations to access storage, databases, applications, and computing power on demand without investing heavily in physical infrastructure. Instead of buying servers, businesses can scale resources up or down as needed and only pay for what they use.

---

# 🏗️ Azure Service Models

One of the most useful exercises was learning how different organisations choose different cloud services depending on their requirements.

## Infrastructure as a Service (IaaS)

**Think:** "Give me the building materials and I'll build the house."

### Example

* Azure Virtual Machines
* Azure Storage

### Why Use It?

Provides maximum flexibility and control over operating systems, databases, networking, and storage.

### Workbook Scenario

For **DataCore Enterprises**, I recommended IaaS because the organisation wanted complete control over database servers and infrastructure whilst still benefiting from cloud scalability.

---

## Platform as a Service (PaaS)

**Think:** "The house is built — I just need to decorate it."

### Example

* Azure SQL Database
* Azure App Service

### Why Use It?

Developers can focus on applications and data rather than maintaining servers and infrastructure.

---

## Software as a Service (SaaS)

**Think:** "The hotel is already built — just check in and use it."

### Examples

* Microsoft 365
* Google Workspace

### Why Use It?

No installation, maintenance, or infrastructure management required.

---

# 🌍 Cloud Deployment Models

| Model              | Best For                                   |
| ------------------ | ------------------------------------------ |
| ☁️ Public Cloud    | Cost-effective and scalable solutions      |
| 🔒 Private Cloud   | Sensitive or regulated data                |
| ⚖️ Hybrid Cloud    | Security and flexibility combined          |
| 🤝 Community Cloud | Shared infrastructure across organisations |

### Real-World Example

A hospital may use a **Hybrid Cloud** approach by keeping patient records private while using public cloud services for appointment systems.

---

# 💰 Azure Cost Planning

Using the Azure Pricing Calculator, I explored the cost of designing an Enterprise Business Intelligence solution involving cloud databases, data pipelines, and reporting services.

### Estimated Costs

* Monthly: **£5,811.87**
* Annual: **£69,742.40**

### Why This Matters

Cloud platforms are highly scalable, but understanding cloud costs is just as important as understanding the technology itself. Good planning helps organisations avoid unnecessary spending while maintaining performance.

---

# 🗄️ Azure Databases

This week introduced me to cloud-hosted relational databases and how organisations manage structured data within Azure.

## Azure SQL Database

### What I Did

* Provisioned Azure SQL resources
* Explored relational database structures
* Connected to cloud-hosted data
* Investigated database management and security

### Why Organisations Use It

* Automated backups
* High availability
* Built-in security
* Reduced infrastructure management

---

## Azure Database for PostgreSQL

### What I Did

* Provisioned PostgreSQL resources
* Explored cloud-hosted relational databases
* Investigated scalable open-source database solutions

### Why It Matters

Provides flexible, cloud-based database management without the complexity of maintaining physical servers.

---

# 🔍 SQL in Azure

One of my favourite parts of the workbook was applying SQL skills inside Azure environments. These exercises simulated real business scenarios rather than simply retrieving data.

## Example 1: Customer Segmentation

```sql
SELECT *
FROM Customer
WHERE LastName LIKE 'A%';
```

### What It Does

Returns customers whose surname begins with the letter **A**.

### Why It Was Used

A marketing team may use this type of query to quickly identify and segment customers for targeted campaigns.

---

## Example 2: Customer Personalisation

```sql
SELECT CustomerID,
       FirstName,
       LastName,
       EmailAddress
FROM SalesLT.Customer
WHERE FirstName LIKE 'A%'
AND LastName LIKE '%A';
```

### What It Does

Returns customers whose first name begins with **A** and whose surname ends with **A**.

### Why It Was Used

Demonstrates how businesses can create highly specific customer groups for personalised communication and engagement strategies.

### Skills Demonstrated

* SELECT
* FROM
* WHERE
* LIKE
* Wildcards (%)
* AND Logic
* Data Filtering
* Customer Segmentation

---

# 🔐 Security, Governance & Compliance

Cloud technology isn't just about storage and speed — it also requires responsible data management.

### Topics Covered

* GDPR Principles
* Data Protection Act 2018
* Computer Misuse Act 1990
* Copyright & Intellectual Property
* Data Privacy & Retention
* Cybersecurity Risks

### Key Takeaway

One thing I found particularly interesting was how technical decisions often have legal and ethical consequences attached to them. As a Data Technician, handling data responsibly is just as important as analysing it.

---

# 🛠 Technologies Used

* Microsoft Azure
* Azure SQL Database
* Azure Database for PostgreSQL
* Azure Pricing Calculator
* SQL
* Microsoft Learn
* XtremeLabs

---

# 🚀 Skills Developed

✅ Cloud Computing Fundamentals

✅ Azure Data Fundamentals

✅ Azure Portal Navigation

✅ Cloud Service Models (IaaS, PaaS, SaaS)

✅ Cloud Deployment Models

✅ Database Provisioning

✅ SQL Querying in Azure

✅ Data Filtering & Segmentation

✅ Cloud Cost Planning

✅ Data Governance & GDPR

✅ Cybersecurity Awareness

✅ Relational Database Management

---

# Reflection

This week felt like stepping into the control room of modern data systems.

Up until now I had focused on analysing, cleaning, and visualising data. This module helped me understand where that data actually lives, how it's protected, and how cloud platforms like Azure make large-scale analytics possible.

The highlight for me was combining SQL with Azure databases because it felt like connecting everything I'd learned so far. Instead of querying local datasets, I was working with cloud-hosted resources in an environment similar to those used by organisations every day.

For the first time, I could clearly see how cloud infrastructure, databases, security, governance, and analytics all fit together as part of one connected data ecosystem.
