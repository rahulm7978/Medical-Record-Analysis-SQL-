# Medical Record Analysis (SQL) - MySQL Server  

## Overview  
This project analyzes medical records using **MySQL Server**, extracting insights into patient demographics, disease trends, hospital performance, and billing data through SQL queries. The SQL file provided contains schema definitions, sample data, and analytical queries to extract meaningful insights.  

## Features  
✔ Patient demographics analysis (age, gender, location)  
✔ Common diagnosis and treatment trends  
✔ Readmission rate calculation  
✔ Hospital performance metrics  
✔ Medical billing and insurance insights  

## Technologies Used  
- **Database:** MySQL Server  
- **Query Language:** SQL  

## Database Schema  
The database consists of multiple tables, including:  
- `patients` – Stores patient details (ID, name, gender, age, etc.)  
- `admissions` – Records hospital admissions (admission date, discharge date, diagnosis)  
- `treatments` – Contains procedures and medications given to patients  
- `billing` – Stores financial details (total bill, insurance provider)  

## Installation & Setup  
1. **Install MySQL Server** (if not installed).  
2. Clone this repository:  
   ```sh
   git clone https://github.com/yourusername/Medical-Record-Analysis.git
   cd Medical-Record-Analysis
