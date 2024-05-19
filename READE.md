 Regal Point Apartments Rent Payment System

Welcome to the Regal Point Apartments Rent Payment System! This web-based application simplifies the process of managing and making rent payments for tenants of Regal Point Apartments.

## Features

- *Tenant Registration*: Register new tenants by providing basic information such as name, email, and apartment number.
- *Rent Management*: Set rent amount and due date for each tenant.
- *Payment Processing*: Accept rent payments through various payment methods such as M-Pesa, credit/debit cards, etc.
- *Payment History*: Maintain a record of all rent payments made by each tenant.
- *Admin Dashboard*: Provide administrative features for managing tenant information, viewing payment history, and generating reports.
- *User Authentication*: Secure login system to authenticate users and restrict access to authorized users only.

## Technologies Used

PYTHON Backend logic and scripting.
- *Flask*: Web framework for building the application.
- *SQLite*: Database for storing tenant information and payment history.
- *HTML/CSS/JavaScript*: Frontend development for user interface and interaction.
- *M-Pesa API*: Integration for processing M-Pesa payments.
- *QR Code Generator*: Library for generating QR codes for payment purposes.

## Installation

1. Clone the repository:

    bash
    git clone https://github.com/your_username/regal-point-apartments-rent-payment.git
    

2. Install dependencies:

    bash
    pip install -r requirements.txt
    

3. Configure environment variables:

    - Rename .env.example to .env.
    - Set up necessary environment variables such as database connection details, API keys, etc.

4. Run the application:

    bash
    python app.py
    

5. Access the application in your web browser:

    
    http://localhost:5000
    
 License

This project is licensed under the [MIT License](LICENSE).
