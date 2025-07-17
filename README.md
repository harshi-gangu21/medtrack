🏥 MedTrack - Cloud-Based Healthcare Management System
MedTrack is a cloud-powered healthcare management platform built with Flask, AWS DynamoDB, and Bootstrap, designed to streamline hospital operations for doctors, patients, and administrators. The system allows for secure user registration, appointment scheduling, diagnosis submission, and medical history tracking — all from a single intuitive web interface.

🚀 Features
👩‍⚕️ Role-Based Access – Separate flows for doctors and patients.

📅 Appointment Booking – Patients can schedule appointments with doctors.

📄 Diagnosis Submission – Doctors can upload and record patient diagnosis reports.

📁 File Uploads – Upload medical reports securely to the cloud.

📜 Medical History Viewer – Patients can view past reports and diagnoses.

☁️ Cloud Native – Uses AWS DynamoDB for fast, serverless data storage.

🧑‍💻 Tech Stack
Frontend: HTML, CSS, Bootstrap

Backend: Python, Flask

Database: AWS DynamoDB

Storage: Local (can be extended to AWS S3)

Authentication: Session-based with Flask

🌐 Deployment Ready
✅ AWS-compatible

✅ Upload folder auto-creation

✅ Can be Dockerized or deployed to EC2/Render

📸 Screenshots
(Add screenshots or gifs of dashboard, appointment page, etc.)

📦 Setup Instructions
Clone the repo

Set up AWS credentials and DynamoDB tables (Users, Appointments, Reports)

Run the Flask app:

bash
Copy
Edit
python app.py
📌 Future Scope
🔐 JWT Authentication

🌍 Integration with AWS S3 for file storage

📈 Admin Analytics Dashboard

📱 Responsive Mobile UI

FROM YOUR --HARSHITHA--
