# 🏥 MedTrack: Smart Healthcare Management System

MedTrack is a comprehensive and user-friendly healthcare web application designed to streamline patient-doctor interactions. It offers features for appointment booking, diagnosis management, report uploading, doctor search, and much more — all integrated into a secure and easy-to-use platform.

## 🚀 Features

### 🔐 Authentication
- User Signup & Login (Patients & Doctors)
- Session-based access control

### 👨‍⚕️ Doctor Role
- View all registered patients
- Add and view patient diagnoses
- Accept/Reject and manage appointments
- Download complete health reports in PDF format
- View uploaded reports from patients

### 🧑‍⚕️ Patient Role
- Book appointments with doctors
- View upcoming and past appointments
- Add and track medicines
- Upload medical reports
- Search for doctors by specialty
- View profile details

### 📂 Additional Features
- PDF report generation using `xhtml2pdf`
- Secure file upload support
- Dynamic UI with Bootstrap + custom CSS
- Flash message support for actions (success/failure)
- SQLite3 + SQLAlchemy for backend data storage

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Bootstrap 5, Jinja2
- **Backend**: Flask (Python)
- **Database**: SQLite3 with SQLAlchemy ORM
- **File Handling**: Secure Uploads, Report Management
- **Email Support** *(Optional)*: SMTP integration for diagnosis reports

## 📁 Folder Structure
## 🧑‍💻 How to Run Locally

1. **Clone this repository**:
   bash
   git clone https://github.com/Meenakumari609/MedTrack.git
   cd medtrack
   pip install flask flask_sqlalchemy xhtml2pdf
   python app.py
### 📄 Documents
- [Project Report]([docs/Project_Report.pdf](https://drive.google.com/file/d/1n-Hwwn5YMN9_Ezx7hDksmABa__UbrGj-/view?usp=drivesdk))
- ## 📄 Project Report (PDF)

[Click here to view/download the report](https://drive.google.com/file/d/1n-Hwwn5YMN9_Ezx7hDksmABa__UbrGj-/view?usp=drivesdk)

- [Presentation Slides](docs/Presentation.pptx)

### 🎥 Demo Video
- [Watch on Google Drive](https://drive.google.com/file/d/1mz-YNsXVdbEcknFR3HO141HQXCtSyFlb/view?usp=drivesdk)
