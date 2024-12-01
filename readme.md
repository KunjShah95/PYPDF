PDF Reader with Text-to-Speech
📖 Overview
The PDF Reader with Text-to-Speech is a Python-based application that allows users to open and read PDF files, display their content, and listen to the text read aloud using text-to-speech (TTS) functionality. The application provides a user-friendly graphical interface, built using Tkinter, and uses PyPDF2 for PDF parsing and pyttsx3 for TTS.

🚀 Features
Open PDF Files: Load any PDF file to display its content.
Text-to-Speech Playback:
Listen to the content of the PDF read aloud.
Adjust speech rate and volume dynamically.
Play, Pause, and Stop Controls:
Start, pause, or stop text-to-speech playback with intuitive buttons.
Scrollable Content Viewer:
View the entire content of the PDF in a scrollable text area.
Dynamic and Responsive GUI:
A clean and responsive graphical user interface for easy navigation.
🛠️ Technologies Used
Python: Core programming language.
Tkinter: For the graphical user interface.
PyPDF2: For parsing and extracting text from PDF files.
pyttsx3: For text-to-speech functionality.
🎯 How to Use
Prerequisites:
Python 3.8 or later installed on your system.
Required Python libraries: pyttsx3, PyPDF2, and tkinter (bundled with Python).
Installation:
Clone this repository:
git clone https://github.com/KunjShah95/PYPDF.git

cd PYPDF
Install the dependencies:
pip install pyttsx3 PyPDF2
Running the Application:
Launch the application:
python PYPDF.py
Use the Open PDF button to load a PDF file.
Click Play to start text-to-speech playback.
Use Pause or Stop to control playback.
🖼️ Screenshots
Main Window

🧩 Code Structure
pdf_reader_tts.py: Main application file containing the GUI logic, PDF handling, and TTS implementation.
🤝 Contribution
Contributions are welcome! If you'd like to improve this project:

Fork this repository.
Create a new branch: git checkout -b feature-new-feature.
Commit your changes: git commit -m "Add some feature".
Push to the branch: git push origin feature-new-feature.
Open a pull request.
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🌟 Acknowledgments
Inspired by the need for accessible solutions for reading PDFs.
Built using Python and open-source libraries.