for my portfolio project alx project we 
# DRF Teleafya

Teleafya is a healthcare management system that allows patients to register, book appointments, make payments, and manage chronic diseases through a simple and secure platform.

## Key Features

- **Patient Registration:** Register patients and assign unique identifiers.
- **Appointment Booking:** Schedule appointments with healthcare providers.
- **Payment Processing:** Handle payments for medical services.
- **Chronic Disease Management:** Tools for managing chronic conditions.

## API Overview

### Main Endpoints

- `POST /api/patient/register/` - Register a new patient.
- `POST /api/patient/register/verifyotp` - Verify patient via OTP.
- `POST /api/patient/login` - Authenticate user.
- `POST /api/patient/book-appointment` - Book a medical appointment.
- `GET /api/patient/view-appointment` - View scheduled appointments.

## Challenges

- **Technical:** Integration of React frontend with Django backend, handling CORS issues, and implementing secure authentication.
- **Non-technical:** Communication and internet disruptions due to protests in Kenya.

## Quick Start

### Backend

1. Clone the repo: `git clone https://github.com/ronaldkinyuru/drf-teleafya.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run migrations: `python manage.py migrate`
4. Start server: `python manage.py runserver`

### Frontend

1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`
3. Start the frontend: `npm start`

## License

This project is licensed under the MIT License.

