## Schema of Hospital Management System

**Hosital Schema**
<img width="859" height="676" alt="image" src="https://github.com/user-attachments/assets/97c52b37-0b63-4427-8ef8-be9cbd114f67" />

**
Patients table **
patient_id	INT

first_name	TEXT

last_name	TEXT

gender	CHAR(1)

birth_date	DATE

city	TEXT

primary key icon	province_id	CHAR(2)

allergies	TEXT

height	INT

weight	INT


**Admissions table **

	patient_id	INT
	
admission_date	DATE

discharge_date	DATE

diagnosis	TEXT

primary key icon	attending_doctor_id	INT



**doctors table **
	doctor_id	INT
	
first_name	TEXT

last_name	TEXT

specialty	TEXT



