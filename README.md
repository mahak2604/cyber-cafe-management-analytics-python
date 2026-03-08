# Smart Cyber Café Management & Analytics System

A Python-based desktop application designed to automate cyber café operations including user authentication, billing, transaction management, and business analytics. The system replaces manual record keeping with a secure and data-driven digital solution.

---

## Project Overview

This project was developed using Python to create a complete cyber café management system with both user and administrator functionalities. It automates registration, session billing, and invoice generation while also providing data analytics and forecasting features for business insights.

---

## Key Features

- User registration and login system
- OTP-based email verification for secure authentication
- Automated billing system with PDF invoice generation
- Transaction storage using CSV files
- Admin dashboard with real-time analytics
- Revenue and user activity insights
- Peak-hour usage analysis
- Revenue forecasting using linear regression

---

## Technologies Used

- **Python**
- **Tkinter** – GUI development
- **Pandas** – Data analysis
- **NumPy** – Numerical computation
- **Matplotlib** – Data visualization
- **ReportLab** – PDF bill generation
- **SMTP (smtplib)** – Email-based OTP verification

---

## System Modules

### 1. User Management
- User registration and login functionality
- Secure credential storage using binary files

### 2. Authentication System
- Email-based OTP verification
- Prevents unauthorized access and ensures user identity validation

### 3. Billing and Invoice Generation
- Calculates billing based on session duration
- Automatically generates and emails PDF invoices

### 4. Transaction Management
- Stores all transactions in CSV format
- Enables historical tracking and analysis

### 5. Admin Dashboard
- Displays operational insights including:
  - Daily revenue summary
  - Most active users
  - Peak usage hours
  - Session duration distribution

### 6. Predictive Analytics
- Implements **linear regression** to forecast next-day revenue
- Helps support data-driven decision making

---

## Project Structure

```
cyber-cafe-management-system
│
├── main.py
├── README.md
├── requirements.txt
│
├── screenshots
│   ├── login_page.png
│   ├── billing_page.png
│   ├── otp_verification.png
│   ├── admin_dashboard.png
│
├── sample_output
│   └── sample_bill.pdf
│
└── documentation
    └── project_report.pdf
```

---

## Installation

Clone the repository:

```
git clone https://github.com/yourusername/cyber-cafe-management-system.git
```

Install required dependencies:

```
pip install -r requirements.txt
```

Run the application:

```
python main.py
```

---

## Screenshots

Add screenshots of the application interface:

- Login & Registration Page
- Billing Interface
- OTP Verification
- Admin Dashboard
- Analytics Graphs

---

## Future Improvements

- Cloud database integration (AWS / Firebase)
- Web-based application using Flask or Django
- Mobile application support
- Online payment gateway integration
- Advanced machine learning forecasting models
- Enhanced security features (2FA, encryption)

---

## Author

**Mahak Wadhawan**  
B.Tech Computer Science Engineering (Data Science)  
MPSTME, NMIMS University

---

## License

This project is developed for academic and educational purposes.
