# 📚 Library Management System (Python + MySQL)

A simple CLI-based Library Management System built using **Python** and **MySQL**.

## 🎯 Features
- Add new books  
- Issue and return books  
- View all issued books  
- Delete book info  

## 🪜 Setup Instructions

1. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Set up MySQL and import the database:**
   ```bash
   mysql -u root -p < database.sql
   ```

3. **Set environment variables (recommended):**
   On Windows (Command Prompt):
   ```cmd
   set MYSQL_USER=root
   set MYSQL_PASSWORD=your_mysql_password
   set MYSQL_DATABASE=library
   ```
   On Linux/Mac:
   ```bash
   export MYSQL_USER=root
   export MYSQL_PASSWORD=your_mysql_password
   export MYSQL_DATABASE=library
   ```

4. **Run the program:**
   ```bash
   python library.py
   ```
