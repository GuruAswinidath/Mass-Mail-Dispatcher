# Web-Based Mass-Mail Dispatcher

## Project Overview
The Web-Based Mass-Mail Dispatcher is an automated email-sending system that enables users to send bulk emails efficiently. 
Users can upload a CSV file containing email addresses, and the system validates and categorizes them as valid or invalid. 
The application is built using Django for the backend and supports SMTP for secure email dispatch.

## Features
- Bulk email sending via CSV file upload.
- Automated validation of email addresses.
- Segregation of valid and invalid emails.
- Secure email transmission using SMTP.
- Structured UI for managing email lists.
- Logging of sent, failed, and invalid emails.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Django (Python)
- **Database:** MySQL
- **Email Service:** SMTP
- **CSV Processing:** Python CSV module
- **Hosting (Optional):** AWS / DigitalOcean / Heroku

## Installation & Setup

### **1. Clone the Repository**
```sh
git clone https://github.com/GuruAswinidath/Mass-Mail-Dispatcher.git
cd mass-mail-dispatcher

## Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

## Install Dependencies
pip install -r requirements.txt

## Usage Instructions
- **Login/Register: Sign in to access the system.
- **Upload CSV File: Upload a file containing recipient email addresses.
- **Validation Process: The system verifies and segregates valid and invalid emails.
- **Send Emails: Choose the recipient list and send mass emails.
- **Track Status: View logs for sent, failed, and invalid emails.


## Future Enhancements
- **AI-powered spam detection and filtering.
- **Custom email templates with HTML support.
- **Advanced analytics and engagement tracking.
- **Integration with third-party email APIs.