Authors: Camron Hylton

Date Created: July 20, 2025

Course: ITT103
 
GitHub Public URL to Code: https://github.com/blizzhypertron/Hospital-management-system


The Purpose of the Program:
This hospital management system is a Python-based CLI (Command-Line Interface) application
designed to simulate a real-world hospital environment. It manages new and returning patients 
& doctors, appointments, billing, and login features.

It allows:
- New users to register as patients or doctors 
- Returning users to log in with their unique IDs
- Patients to book/cancel appointments and pay bills
- Doctors to view their daily schedule 


How to Run it:
1. Make sure Python 3 is installed on your system.
2. Open your terminal or command prompt 
3. Navigate to the folder where your '.py' file is located.
4. Run the script using:

Windows:
   "cd Downloads/HospitalSystemTest" (or anywhere it might be)
   
 Then write:
 
   "python hospital_management_system.py" or "python 3 hospital_management_system.py"


Linux/MacOS:
   "cd ~/Downloads/HospitalSystemTest"
   
 Then write:
 
   "python 3 hospital_management_system.py


Required Modifications:

⦁	You must have the pygame module installed if your project includes music.
Use "pip install pygame" if needed 

⦁	Make sure the system saves the patient and appointment data to a file, 
   so the info doesn't disappear when you close the program.

⦁	Optional: Build a GUI (Graphical User Interface) for better usability


Assumptions & Limitations:

⦁	The program uses in-memory data only. All data is lost once the program is closed.
⦁	IDs are assumed to be unique and manually entered for login
⦁	Gender input is limited to "Male" or "Female".
⦁	No payment system is integrated - billing is simulated.
