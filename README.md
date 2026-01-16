# Hospital Management System Database

This project is a **Hospital Management System Database** designed using **MySQL / SQL**.  
It manages hospital operations such as patients, doctors, rooms, lab tests, and billing.

---

## 📁 Project Files

- `Hospital Management System Database.txt`  
  → Contains all SQL queries (`CREATE TABLE` statements) for the database schema.

- `README.md`  
  → Project documentation.

---

## 🏥 Database Description

The database is designed to handle:
- Patient records
- Doctor information
- Room allocation
- Lab tests and reports
- Billing and payment details

It uses **primary keys and foreign keys** to maintain relationships between tables.

---

## 🗂 Tables Included

1. **Doctor**
   - doctor_id (Primary Key)
   - name, age, gender

2. **Patient**
   - patient_id (Primary Key)
   - name, age, gender, address, disease
   - doctor_id (Foreign Key)

3. **Room**
   - room_no (Primary Key)
   - room_type, status

4. **Patient Admission**
   - patient_id
   - room_no
   - date_of_admission
   - date_of_discharge
   - lab_no

5. **Lab**
   - lab_no (Primary Key)
   - patient_id
   - doctor_id
   - date
   - amount

6. **Lab Test**
   - patient_id
   - date
   - lab_no

7. **Billing**
   - bill_no (Primary Key)
   - doctor_charge
   - room_charge
   - no_of_days
   - lab_charge
   - total_amount
   - patient_id

---

## 🛠 Technologies Used

- SQL
- MySQL

---

## 🚀 How to Use This Project

1. Open MySQL Workbench or any SQL editor
2. Create a database (optional)
3. Open the file  
   `Hospital Management System Database.txt`
4. Run the SQL queries
5. Tables will be created successfully

---

## 🎯 Purpose of the Project

- Academic / college mini project
- Learning database design
- Understanding table relationships
- Practice with SQL constraints

---

## 👨‍💻 Author

**Pranjal**

---

## ⭐ Note

This project is for learning and academic purposes.  
Feel free to modify or extend it.

