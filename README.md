#  Clinic Management Software (ClinicMS)

A **web-based Clinic Management System** with appointment scheduling, developed to digitalize clinic functions and streamline operations for **Admins, Doctors, and Patients**.

---

##  Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Team Members](#-team-members)
- [Future Scope](#-future-scope)
- [License](#-license)

---

## 📖 About the Project
The **ClinicMS** software provides an efficient platform for managing:
- Patient registration
- Appointment booking
- Doctor consultations
- Prescription handling
- Billing and invoicing  

It ensures **role-based access** with three different portals:
-  Doctor  
-  Admin  
-  Patient  

---

##  Key Features
-  **Role-Based Login**: Separate dashboards for Admin, Doctor, and Patient  
-  **Appointment Scheduling**: Book, reschedule, or cancel appointments  
-  **Medical History**: Secure patient records and treatment history  
-  **Prescription Module**: Doctors can add and edit prescriptions  
-  **Billing System**: Auto-generated invoices and payment history  
-  **Admin Dashboard**: Manage users, view system metrics, and analytics  

---

##  Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Django)  
- **Database:** SQLite / MySQL  
- **Version Control:** Git & GitHub  
- **Collaboration Tools:** Google Meet, WhatsApp  
- **Documentation:** Google Docs, Notion, LaTeX  

---

##  Screenshots
  
- **Login Page**

![Login Page]()  

- **Admin Dashboard**

![Admin Dashboard]()  


### Prerequisites

- Python 3.8+
- pip package manager
- Virtual environment (recommended)  

---
### Steps

1. **Clone the repository**
 
2. **Create and activate virtual environment**
 
3. **Install dependencies**

 4. **Apply migrations**

    
     - python manage.py migrate

 5. **Create a superuser (Admin)**
    
    - python manage.py createsuperuser
    
6. **Run the development server**
   
    -  python manage.py runserver

---
##  Access Control
- **Admin:** Full access to all modules (appointments, doctors, patients, billing, prescriptions, analytics).  
- **Doctor:** Restricted access – can only manage appointments, view patient history, and add/edit prescriptions.  
- **Patient:** Limited access – can only book appointments, view their own records, and check billing.  

---
## Project Structure
clinicms/

│── manage.py

│── requirements.txt

│── README.md

│── clinicms/         # Main project settings

│── appointments/     # Appointment module

│── patients/         # Patient management

│── doctors/          # Doctor module

│── prescriptions/    # Prescriptions

│── billing/          # Billing & invoices

│── templates/        # HTML templates

│── static/           # CSS, JS, Images

---
## **Future Scope**

- Integration with online payments

- SMS/Email notifications

- AI-based health analytics

- Cloud deployment

