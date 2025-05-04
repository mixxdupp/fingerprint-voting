# fingerprint-voting
Fingerprint based Electronic Voting System

An Arduino-based biometric voting prototype that ensures secure, one-person-one-vote authentication using a fingerprint sensor. Designed to reduce voter fraud and improve accessibility in small-scale elections such as classrooms, clubs, or institutional polls.

🔧 Features
	
 •	✅ Biometric Authentication using optical fingerprint sensor (R305)

 •	✅ LCD Display (I2C) for real-time voter guidance and feedback

 •	✅ Duplicate Vote Prevention by storing and comparing voter IDs

 •	✅ Vote Count Simulation for three parties with admin-triggered result display

 •	✅ Compact Embedded Design using Arduino Uno and minimal components

🛠️ Hardware Used

 •	Arduino Uno

 •	R305 Fingerprint Sensor

 •	I2C 16x2 LCD Display

 •	Push Buttons

 •	Buzzer

 •	Breadboard and Jumper Wires

💻 Software & Libraries

 •	Arduino IDE

 •	Adafruit_Fingerprint library

 •	Wire.h for I2C communication

🚀 How It Works

 1.	User scans fingerprint → If matched and not already voted, proceeds to vote selection.

 2.	Vote is cast → Button press triggers buzzer confirmation and updates party count.

 3.	Repeat attempt by same user → Access denied via stored fingerprint ID.

 4.	Admin Mode (Fingerprint ID = 4) → Displays total vote count and announces winner.

📦 Applications

 •	Campus elections

 •	Club voting

 •	Prototype for scalable biometric voting solutions
