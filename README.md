Drowsiness Detection System

📖 Project Overview

The Drowsiness Detection System is a computer vision–based project designed to enhance road safety by monitoring driver fatigue in real time. The system uses a webcam to track eye movements and triggers an alarm if drowsiness is detected. This helps prevent accidents caused by driver sleepiness, especially during long journeys.

✨ Features

--Real-time monitoring of driver’s eye state via webcam

--Detects eye closure duration to determine drowsiness

--Triggers an alarm sound when drowsiness is detected

--Helps reduce accidents caused by driver fatigue

--Lightweight and easy to run on any computer with a webcam

🛠 Technologies Used

-Programming Language: Python 3.x

--Libraries & Tools:

-OpenCV – image processing & video capture

-NumPy – numerical computations

-dlib / mediapipe – facial landmark detection

-pygame – sound alerts

⚙ Installation & Setup

🔹 1. Clone the Repository

git clone https://github.com/Sharvirala-Sai-Advika/Drowsiness-detection-system.git

cd Drowsiness-detection-system

🔹 2. Set Up Python Environment

python -m venv venv

source venv/bin/activate   # On macOS/Linux

venv\Scripts\activate      # On Windows

🔹 3. Install Dependencies

If requirements.txt is provided:

pip install -r requirements.txt


Or manually install key libraries:

pip install opencv-python numpy dlib playsound imutils

🔹 4. Run the System

python Drowsiness_Detection.py

🚀 How to Use

-Ensure your webcam is connected.

-Run the detection script.

-Keep your face clearly visible in front of the camera.

-If the system detects prolonged eye closure, it will play an alarm sound.


