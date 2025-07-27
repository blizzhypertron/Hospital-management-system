Authors: Camron Hylton

Date Created: July 24, 2025

Course: ITT103
 
GitHub Public URL to Code: https://github.com/blizzhypertron/Hospital-management-system


🩺 Hospital Management System - README

📌 Purpose of the Program:
This hospital management system is a Python-based CLI (Command-Line Interface) application designed to simulate a real-world hospital environment. It manages new and returning patients & doctors, appointments, billing, and login features.

✅ Features:
- New users can register as patients or doctors.
- Returning users can log in using their unique IDs.
- Patients can:
    • Book appointments
    • Cancel appointments
    • Edit appointments
    • Pay medical bills (Cash, Card, Apple/Google Pay)
- Doctors can:
    • View their daily appointment schedule
    • View notifications
- Receipts, ID cards, and feedback options included.
- Specialty-based login with doctor ID formats (e.g., `D-Card-xxxx` for Cardiologists).

🚀 How to Run the Program:

1. Make sure **Python 3** is installed on your computer.
2. Open your terminal or command prompt.
3. Navigate to the folder where your `.py` file is located:

   - **Windows Example:**
     ```
     cd Downloads/HospitalSystemTest
     python hospital_management_system.py
     ```

   - **Mac/Linux Example:**
     ```
     cd ~/Downloads/HospitalSystemTest
     python3 hospital_management_system.py
     ```

⚙️ Required Modifications:

- 📦 You must have the **`pygame`** module installed IF your project includes hospital music.
  - Install it using:
    ```
    pip install pygame
    ```

- 💾 **Data Persistence**: Ensure the system saves patient and appointment data to a file (or database) so data is not lost when the program exits.

- 🖥️ *Optional*: Create a GUI (Graphical User Interface) version using Tkinter, PyQt, etc., for better usability.

🧠 Assumptions & Limitations:

- The program **uses in-memory data only** unless file saving is implemented.
- IDs are assumed to be unique and must be entered manually during login.
- Gender input is limited to **Male** or **Female** (case-insensitive, accepts full words or letters).
- The payment system is simulated — no real transactions occur.
- Receipt prints with tax, subtotal, extra services, card brand (if applicable), and currency (USD, JMD, CAD).
- Specialty IDs must follow correct format (e.g., D-Psy-XXXX for Psychiatry).

🎉 Bonus Features (Optional):
- 🪪 Printable Patient ID Card
- 🔔 Notifications for Doctors
- 📊 Doctor Dashboard
- 🗣️ Feedback system (can be linked to a Google Form)

