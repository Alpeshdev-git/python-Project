Voice-Based Email System for Visually Challenged People 
A Python-based email system that leverages voice commands to assist visually challenged users in sending and receiving emails using speech recognition and Flask. 
Make sure you have the following installed on your system: 
•	Python 3.7 or higher 
•	Git 
•	pip (Python package installer) 
 
Step 1:-Create a Virtual Environment python -m venv venv # Activate the environment 
# On Windows: 
venv\Scripts\activate # On macOS/Linux: 
source venv/bin/activate 
 
Step 2:- Install Required Python Libraries pip install -r requirements.txt 
If you don’t have a requirements.txt file, you can create one with: 
pip install Flask SpeechRecognition pyttsx3 smtplib email pip freeze > requirements.txt 
 
Step 3:- Running the Project 
Once everything is set up, run the main file: 
python app.py 
Notes 
•	Ensure your system has a working microphone. 
•	Internet connection is required for speech recognition (Google API). 
•	You may need to enable "less secure app access" in Gmail if using it for SMTP. 
Sample Folder Structure 
 
•	CopyEdit 
•	voice-based-email-system/ 
•	├── app.py 
•	├── templates/ 
•	├── static/ 
•	├── venv/ (optional) 
•	├── requirements.txt 
•	└── README.md 
