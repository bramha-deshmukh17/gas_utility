### Gas Utility Service

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Create a virtual environment](#create-a-virtual-environment)
  - [Activate the virtual environment](#activate-the-virtual-environment)
  - [Install the required packages](#install-the-required-packages)
  - [Clone the repository](#clone-the-repository)
  - [Apply migrations](#apply-migrations)
  - [Create a superuser](#create-a-superuser)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Credentials](#credentials)
- [Screenshots](#screenshots)

## Overview
The Gas Utility Service is a web application designed to streamline the process of service requests, account management, and tracking. Users can submit service requests, track their status, and manage their accounts efficiently.

## Prerequisites
Before you begin, ensure you have the following installed:
- [Python](https://www.python.org/downloads/) (version 3.10 or above)
- [Django](https://www.djangoproject.com/download/) (latest)
## Installation
Follow these steps to set up the project:

1. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```
   ```bash
   cd venv
   ```

2. **Activate the virtual environment**:
   - On Windows:
     ```bash
     Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source bin/activate
     ```

3. **Install the required packages**:
   ```bash
   pip install django
   ```

4. **Clone the repository**:
   ```bash
   git clone https://github.com/bramha-deshmukh17/gas_utility.git
   ```
   ```bash
   cd gas_utility
   ```

5. **Apply migrations**:
   ```bash
   python manage.py makemigrations
   ```
   ```bash
   python manage.py migrate
   ```

7. **Create a superuser** (optional, for admin access):
   ```bash
   python manage.py createsuperuser
   ```

## Running the Application
To start the development server, run:
```bash
python manage.py runserver
```
You can access the application by navigating to [here](http://127.0.0.1:8000/) in your web browser.

## Usage
- Users can register and log in to submit service requests.
- The application provides a tracking feature to monitor the status of submitted requests.
- Admins can manage users and service requests through the admin panel [here](http://127.0.0.1:8000/admin/).

## Credentials
1. Admin
 - Username
   ```bash
   hp
   ```
 - Password
   ```bash
   hp
   ```
    
    
##Screenshots
- Index Page
![Screenshot 2024-10-13 140927](https://github.com/user-attachments/assets/040300a4-65e9-4ce1-9c25-cce34b63beaa)
- Login Page
![Screenshot 2024-10-13 140933](https://github.com/user-attachments/assets/7f40de24-0f2b-470c-abb7-1697922a22b8)
- Register Page
![Screenshot 2024-10-13 140941](https://github.com/user-attachments/assets/7fc7ccd7-9262-4c4e-b979-9cfbad80876e)
- Home Page
![Screenshot 2024-10-13 141003](https://github.com/user-attachments/assets/dda799fb-423d-4df0-98c3-ed8d837ddd00)
- Account Page
![Screenshot 2024-10-13 141011](https://github.com/user-attachments/assets/d62b66c3-8ad1-40d4-ac34-34ff3c3cfba3)
- Submit Service Request
![Screenshot 2024-10-13 141018](https://github.com/user-attachments/assets/57419ac8-2634-4247-a561-1afbf64d4c8c)
- Track request
![Screenshot 2024-10-13 143025](https://github.com/user-attachments/assets/cec3dfa5-1caf-447c-9cd6-d0c21a2286da)
