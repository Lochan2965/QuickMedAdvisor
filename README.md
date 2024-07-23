# QuickMedAdvisor
QuickMed Advisor is a healthcare app connecting patients and doctors. It offers symptom checking via a machine learning model, secure report uploads, and video consultations. Built with Django, FastAPI, HTML, CSS, JavaScript, and SQLite, it ensures secure authentication and user-friendly interfaces.


# Project Description 
Key Features:

- **Symptom Checker**: Input symptoms and get a prognosis.
- **Upload Reports**: Securely upload medical reports.
- **Video Consultations**: Join virtual consultation rooms.
- **Doctor Interface**: View reports and send prescriptions.
- **Secure Authentication**: Robust user authentication.

Who It's For:

- **Patients/Users:** Seeking online medical advice and diagnosis.
- **Doctors:** Providing remote consultations and prescriptions.

## Appendix

Libraries and Technologies Used:
- Backend: Django, FastAPI, Python
- Frontend: HTML, CSS, JavaScript
- Machine Learning: Scikit-learn, Joblib
- Database: SQLite
- PDF Generation: ReportLab, xhtml2pdf
- Email: Django's EmailMessage
- Other Django Libraries:
  - django.http for handling HTTP responses
  - django.shortcuts for rendering templates and redirections
  - django.contrib.auth for user authentication and management
  - django.urls for URL routing
  - django.core.mail for sending emails
  - django.template.loader for loading templates
  - django.http.FileResponse for handling file responses
 
## Documentation

Setting Up the Project:
Clone the Repository
- git clone https://github.com/yourusername/quickmed-advisor.git
- cd quickmed-advisor

Install Dependencies:
pip install -r requirements.txt

Migrate the Database:
python manage.py migrate

Run the Development Server:
python manage.py runserver





