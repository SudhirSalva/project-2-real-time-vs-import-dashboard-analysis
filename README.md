# 📊 PROJECT 2: Dashboard Automation through Direct Query Mode  

---

## 📌 Difference Between Last Project and This Project  

In my last project, I worked on different datasets like:  
- Streaming Dataset  
- Semantic Model  

I understood their advantages and differences.  

In this project, the focus is different.  
Here I am focusing on how data is invoked in dashboards, such as:  

- Whether we store and refresh data  
- Or we call the data every time from the database  

---

## 🔄 Methods of Data Invocation  

In Power BI, there are mainly two methods:  

- Import Mode → Data is stored inside Power BI and refreshed periodically  
- Direct Query Mode → Dashboard asks data from the database every time   

---

## 🔁 What is Page Refresh?  

![Page Refresh](screenshots/Page%20Refresh.png)

Page refresh is mainly used in Direct Query Mode.  

- It refreshes the dashboard automatically  
- Can refresh every second or based on time set by the user  
- Helps to make the dashboard live  

---

## ⚡ Direct Query Mode vs Import Mode  

![Direct Query Mode](screenshots/Direct%20Query%20Mode.png)  
![Import Mode](screenshots/Import%20Mode.png)

### 🔹 Import Mode  
- Data is copied into Power BI  
- Stored inside the dashboard  
- Needs refresh  

### 🔹 Direct Query Mode  
- Data is stored in SQL database  
- Power BI does NOT store data  
- It queries the database every time using SQL  

---

## 🧠 What is SQL and Database?  

![Database](screenshots/Database%20Image.png)

- SQL (Structured Query Language)  
  - Used to communicate with the database  

- Database  
  - Collection of tables connected using keys  

---

## 🔑 Types of Keys  

- Primary Key → Main identifier of a table  
- Foreign Key → Refers to data in another table  

---

## 🔄 How Automation Works  

- In Direct Query Mode → Dashboard asks data from database every time  
- Page Refresh → Automatically refreshes the dashboard  

👉 Together they create a live automated dashboard  

---

## 🛠️ Tools Used  

### 1. Google Sheets  
![Google Sheets](screenshots/Google%20Sheets.png)  

### 2. SQL Server (SSMS)  
![SSMS](screenshots/SSMS.png)  
- Used to store data locally  
- Data imported into database  

### 3. Power BI  
![Power BI](screenshots/Power%20BI.png)  
- Used to create dashboard and analysis  

---

## ⚖️ Which is Better?  

### ✅ Pros of Direct Query Mode  
- Full visualization available  
- DAX measures and modelling available  
- Dashboard is live  
- Page refresh control  

### ❌ Cons  
- Depends completely on the database  
- Data is not stored in Power BI  
- Requires database connection  

---

## 📊 Dashboard Comparison   

### Direct Query Dashboard  
![Direct Query Dashboard](screenshots/Dashboard%20(Direct%20Query%20Mode).png)

### Import Mode Dashboard  
![Import Dashboard](screenshots/Dashboard%20(import%20mode).png)

> ⚠️ Note: The dashboard UI and structure were intentionally kept the same in both versions to ensure a clear and fair comparison of data automation between Import Mode and Direct Query Mode.

---


## 🔄 Workflow  

### Existing Workflow  
![Existing Workflow](screenshots/Existing%20Workflow.png)

### Final Workflow  
![Final Workflow](screenshots/Final%20Workflow.png)

### Updated Workflow (Power BI Service)  
![Updated Workflow](screenshots/Updated%20Schema.png)

---

## 📈 Dataset  

- 5000 rows of Credit Card Transactions  
- Objective: Fraud Analysis  

---

## 📸 Screenshots  

[screenshots](screenshots/)

---

## 📁 Resources  

[resources](resources/)
---

## 🔗 Previous Project  

https://github.com/SudhirSalva/PROJECT-1-Dashboard-Automation-Through-Google-Sheets.git  

---
