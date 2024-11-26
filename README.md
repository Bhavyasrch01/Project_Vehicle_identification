Vehicle Number Plate Recognition

A robust Django-based web application designed to detect and recognize vehicle number plates from both static images and dynamic videos. This tool also identifies the state to which the vehicle belongs, leveraging Optical Character Recognition (OCR) powered by Pytesseract. The interface is sleek and fully responsive, styled with Bootstrap.

🚀 Key Features
Home Page: A welcoming page with intuitive navigation.

User Authentication: Secure registration and login system.

Image Upload: Detects and recognizes number plates and vehicle states from uploaded images.

Video Upload: Performs real-time number plate recognition from video files.

Results Display: Extracted vehicle number plates and states are shown on a detailed results page.

Contact Page: Users can submit feedback or queries using a form.

Responsive Design: Optimized for compatibility across all devices using Bootstrap.

🛠 Technologies Used
Backend: Django Framework
OCR Tool: Pytesseract
Frontend: HTML, CSS, JavaScript, Bootstrap
Database: SQLite (db.sqlite3)

📂 Project Structure
plaintext
Copy code
vehiclerecognition/  
├── manage.py                # Django management script  
├── db.sqlite3               # SQLite database  
├── requirements.txt         # Python dependencies  
├── vehiclerecognition/      # Main application directory  
│   ├── settings.py          # Django project settings  
│   ├── urls.py              # URL routing configuration  
│   ├── views.py             # Core application logic  
│   ├── forms.py             # Form handling logic  
│   ├── utils.py             # OCR and plate recognition logic  
│   ├── templates/           # HTML templates for the website  
│   ├── static/              # Static files (CSS, JS, images)  
│   └── media/               # Uploaded images and videos  
⚙️ Installation and Setup
1. Clone the Repository
bash
Copy code
git clone https://github.com/your-username/vehicle-number-plate-recognition.git
cd vehicle-number-plate-recognition
2. Set Up a Virtual Environment
bash
Copy code
python -m venv venv
# Activate the environment:
# On macOS/Linux:
source venv/bin/activate
# On Windows:
.\venv\Scripts\activate
3. Install
Vehicle Number Plate Recognition
Overview
A powerful Django-based web application designed to identify vehicle number plates from both static images and dynamic videos. This tool utilizes Optical Character Recognition (OCR) with Pytesseract to extract plate details and map them to their respective states. The interface, styled with Bootstrap, ensures a seamless and responsive user experience.

Key Features
User-Friendly Home Page: Easy navigation and a modern look.
Secure User Authentication: Options to register and log in.
Image Upload: Detects and recognizes vehicle number plates from images.
Video Upload: Processes video files for dynamic recognition.
Detailed Results: Displays the recognized vehicle number plate and state information.
Contact Form: Enables users to submit feedback or queries.
Responsive Design: Optimized for compatibility with all device types.

Technology Stack
Backend: Django Framework for server-side operations.
OCR Tool: Pytesseract for text recognition from images and videos.
Frontend: Styled with HTML, CSS, JavaScript, and Bootstrap.
Database: SQLite for data storage.

Project Structure
Core Application: Centralized logic for processing requests, handling forms, and managing authentication.
Static Files: Includes CSS, JavaScript, and images to enhance frontend aesthetics.
Templates: Reusable HTML components for various pages.
Media Files: Repository for uploaded images and videos.
Utils Module: Handles OCR functionality and number plate recognition processes.

Setup Process
Clone the Repository: Download the project files from the GitHub repository.
Virtual Environment: Create and activate a Python virtual environment for dependency management.
Install Requirements: Use the provided requirements.txt file to install necessary libraries.
Pytesseract Configuration: Ensure Tesseract OCR is installed on your system and configure the executable path.
Database Migrations: Apply database migrations to initialize the application schema.
Run the Server: Start the Django server and access the application locally.

How It Works
Image Recognition: Upload an image, and the OCR extracts text from the number plate.
Video Processing: Upload a video to detect plates dynamically and display results.
State Mapping: Identifies the state associated with the extracted number plate.
Responsive Interface: Ensures a consistent user experience across all devices.

Testing and Usage
Supported File Formats:
Images: .jpg, .png, .jpeg
Videos: .mp4, .avi
Test the system with sample files for accurate results.

Acknowledgements
Special thanks to the tools and frameworks that make this project possible:

Pytesseract for OCR capabilities.
Django for backend development.
Bootstrap for responsive design.
Contact Information
Author: Bhavya Sri Chemitiganti
Email: bhavya.deekshu@gmail.com
GitHub: Bhavyasrch01
