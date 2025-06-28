<div align="center">

# AI-HOTEL-MANAGEMENT-SYSTEM

*Transform Hospitality with Intelligent, Seamless Management*

![last commit](https://img.shields.io/github/last-commit/Muhammad-Ahmed-Rayyan/AI-Hotel-Management-System)
![Python](https://img.shields.io/badge/Python-90%25-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-10%25-4479A1?logo=mysql&logoColor=white)
![languages](https://img.shields.io/badge/languages-2-blue)

<br>

Built with the tools and technologies:

![Streamlit](https://img.shields.io/badge/Streamlit-red?logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-purple?logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

</div>

---

## Overview

AI-Hotel-Management-System is an all-in-one platform that simplifies hotel operations through integrated database management, interactive dashboards, and AI-powered demand forecasting. Built with Streamlit, it offers a user-friendly interface for booking, administration, and data analysis.

### Why AI-Hotel-Management-System?

This project aims to streamline hotel management workflows by combining data processing, visualization, and predictive analytics. The core features include:

- **🗄️ Database Management:** Efficiently create, update, and maintain core hotel data such as reservations, customers, and rooms.
- **🤖 AI Demand Forecasting:** Leverage historical data to predict future demand and optimize pricing strategies.
- **🖥️ Interactive User Interface:** Facilitate seamless booking, user management, and administrative controls.
- **🔐 Role-Based Access:** Ensure secure, role-specific access to sensitive data and management functions.
- **📝 SQL Query Interface:** Enable direct database queries for troubleshooting and data insights.
- **📊 Integrated Data Workflows:** Support end-to-end data handling, visualization, and forecasting within a single platform.

---

## 🚀 Installation & Setup

Follow these steps to set up and run the project locally:

To get started, make sure you have MySQL installed and running on your system.
Create a database named `hoteldatabase` and then execute the provided `commands_&_Data_Input.sql` file to create the necessary tables and insert initial data.

After setting up the database, update the database authentication details in the Python code wherever the MySQL connection is defined (such as in the `get_connection()` function). Replace the host, port, user, password, and database fields with your own MySQL credentials to ensure the application connects properly.

```bash
# Clone the repository
git clone https://github.com/Muhammad-Ahmed-Rayyan/AI-Hotel-Management-System.git

# Navigate to the project directory
cd AI-Hotel-Management-System

# (Optional) Create a virtual environment
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run Main_Page.py
