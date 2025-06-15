
SIMPLE BILLING SYSTEM – PF 

Overview

This project is a simple Inventory and Billing System developed in C language. It allows users to manage inventory items and generate customer invoices with ease. The system is designed for small-scale businesses or academic learning purposes.


**👩‍💻 Group Members**

Shanza Shafiq   BITF24M008        
Aswah Rani      BITF24M016        
Tehreem Fatima  BITF24M029     

> *Department*: BS Information Technology  
> *Campus*: PUCIT – Old Campus, Lahore

**🌟 Features**

- 🔐 *Login System* (3 attempts, password protected)
- 📦 Add / View / Edit / Delete Inventory
- 🧾 Generate Invoices with Auto-Stock Updates
- 💸 Optional Discount Handling
- 📝 All data stored in text files (inventory.txt, invoices.txt)
- 🌐 Cross-platform clearScreen (Linux/Windows compatible)
- ✅ Input validation for quantity, price, phone number
- 📆 Shows real-time date and time in the menu
- 🧠 Built using pure C with <stdio.h>, <stdlib.h>, <string.h>, <time.h>, and <ctype.h>


**📁 File Structure**

 📄 File Name         📌 Purpose                             
   main.c              Full source code of the application     
  inventory.txt       Stores all inventory items              
  invoices.txt       Stores invoice history for customers    
  temp.txt           Used for intermediate edits/deletions   


## 🔓 Login Credentials
- 🔑 *Password*: admin123
(You get 3 attempts to login)


**🧾 Sample Invoice (Output Preview)**
----- Invoice -----
Customer: Aswah 
Phone: 03001234567

+-----------------+------------+------------+
| Item            | Qty        | Price      |
+-----------------+------------+------------+
| egg        | 2          | 35.00      |
+-----------------+------------+------------+
Final Total: 70.00
------------------------------

