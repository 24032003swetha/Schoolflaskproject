This project is a web application developed using Flask, a micro web framework for Python. The application is designed to simple school web application.

****Technical Requirements****
To run this application, you need to have the following installed:
Python (version 3.x)
Flask (version 2.x)
Gunicorn (version 20.x)
Flask-Session (version 0.4.x)
****Installation and Setup****
Clone the repository using git clone <repository_url>
Install the required dependencies using pip install -r requirements.txt
Create a virtual environment using python -m venv venv (optional but recommended)
Activate the virtual environment using source venv/bin/activate (on Linux/Mac) or venv\Scripts\activate (on Windows)
Run the application using gunicorn -w 4 app:app (replace app with your application name)
Application Structure
**The application is structured as follows:**
app.py: The main application file that defines the Flask app and routes
templates/: Directory containing HTML templates for the application
static/: Directory containing static assets (CSS, JavaScript, images, etc.)
requirements.txt: File listing the dependencies required to run the application
**
