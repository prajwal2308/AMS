# Applicant Management System (AMS)
# Attendance Management System (AMS)

An automated Attendance Management System built using Flask, Python, SQL, and HTML/CSS to streamline attendance tracking for educational institutions or workplaces.

## Features

- User Authentication – Secure login/logout functionality for admins and users.  
- Attendance Tracking – Automated record-keeping of student or employee attendance.  
- Database Integration – Stores user and attendance data in a structured SQL database.  
- Dashboard and UI – Interactive and user-friendly web interface.  
- Export Data – Generate and download attendance reports.  

## Tech Stack

- Backend: Flask (Python), SQLAlchemy (Database ORM)  
- Frontend: HTML, CSS, JavaScript (Bootstrap for styling)  
- Database: SQLite / MySQL  
- Deployment: AWS (Optional: Docker for containerization)  

## Installation and Setup

### Clone the Repository  
```bash
git clone https://github.com/prajwal2308/AMS.git
cd AMS
```

### Create a Virtual Environment  
```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### Install Dependencies  
```bash
pip install -r requirements.txt
```

### Configure the Database  
```bash
python init_db.py  # Initializes the database
```

### Run the Application  
```bash
python app.py
```
The application will be available at http://127.0.0.1:5000/

## Screenshots  

(Add relevant screenshots here to showcase the UI and features.)  

## Future Enhancements  

- Facial Recognition Integration – Use AI for attendance via facial recognition.  
- Admin Panel Enhancements – More control over reports and user roles.  
- Email Notifications – Notify users about attendance via email alerts.  

## License  

This project is licensed under the MIT License.  

## Contributing  

Contributions are welcome. If you would like to enhance this project, feel free to fork the repository and submit a pull request.  

## Contact  

Email: prajwal.srinivas238@gmail.com  
LinkedIn: [linkedin.com/in/prajwalsrinivas238](https://linkedin.com/in/prajwalsrinivas238)  

Built with passion for automation and efficiency.
