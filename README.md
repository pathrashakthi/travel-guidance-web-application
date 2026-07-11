Travel Guidance Web Application
A Flask-based web application that helps users plan trips to unfamiliar locations by providing hotel recommendations, tourist attractions, and transportation guidance based on a selected destination. The application is designed for users traveling for examinations, internships, business meetings, or short visits.
Features
    • User Registration 
    • Travel Planning 
    • Dynamic State and District Selection 
    • Center Location Selection 
    • Hotel Recommendations 
    • Tourist Place Suggestions 
    • Bus, Train, and Car Route Guidance 
    • Travel Summary 
    • MySQL Database Integration 
    • Responsive User Interface 


Technology Stack
Frontend
    • HTML5 
    • CSS3 
Backend
    • Python 
Framework
    • Flask 
Database
    • MySQL 


Project Structure

Travel-Guidance-System/
│
├── static/
│   ├── css/
│   ├── images/
│   └── js/
│
├── templates/
│   ├── index.html
│   ├── register.html
│   ├── travel_plan.html
│   ├── hotels.html
│   ├── tourist_places.html
│   └── summary.html
│
├── app.py
├── database.sql
├── requirements.txt
├── README.md
└── LICENSE

System Workflow

User Registration
        │
        ▼
Travel Planning
        │
        ▼
Select State
        │
        ▼
Select District
        │
        ▼
Choose Center Location
        │
        ▼
Hotel Recommendation
        │
        ▼
Tourist Place Recommendation
        │
        ▼
Route Guidance
        │
        ▼
Travel Summary
        │
        ▼
Store Data in MySQL

Database Tables
    • user_information 
    • travel_plan 
    • states 
    • districts 
    • exam_centers 
    • hotels 
    • tourist_places 
    • district_state 
    • hotel_center 

Installation
1. Clone the repository
git clone https://github.com/pathrashakthi/Travel-Guidance-System.git
2. Navigate to the project directory
cd Travel-Guidance-System
3. Create a virtual environment (Optional)
python -m venv venv
4. Activate the virtual environment
Windows
venv\Scripts\activate
Linux/macOS
source venv/bin/activate
5. Install the required dependencies
pip install -r requirements.txt
6. Configure the MySQL Database
    • Create a MySQL database. 
    • Import the database.sql file. 
    • Update the database credentials in app.py. 
7. Run the application
python app.py
Open your browser and visit:
http://127.0.0.1:5000/

 
Future Enhancements
    • Google Maps Integration 
    • Live GPS Navigation 
    • Online Hotel Booking 
    • Weather Forecast Integration 
    • AI-Based Travel Recommendations 
    • User Authentication 
    • Payment Gateway Integration 
    • Email Notifications 
    • Mobile Application (Android & iOS) 
    • Real-Time Transport Tracking 

Learning Outcomes
    • Flask Web Development 
    • CRUD Operations with MySQL 
    • Relational Database Design 
    • Dynamic Form Handling 
    • Backend Development with Python 
    • Responsive Web Design 
    • Database Connectivity 
    • User-Centric Application Design
