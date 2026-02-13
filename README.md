Report on Building a Python Keylogger
AIM
To demonstrate how to build a basic keylogger in Python for educational and cybersecurity
awareness purposes.
INTRODUCTION
A keylogger is a monitoring tool that records every keystroke typed on a keyboard. There
are both legitimate uses—such as productivity analysis, parental control, and research—and
malicious uses by cybercriminals to steal sensitive information. We will know how keyloggers
function internally, thereby improving cybersecurity knowledge and awareness.
PROBLEM STATEMENT
Keyloggers are commonly used by attackers to steal information without a user’s knowledge.
Most learners and users do not understand how such tools operate, leaving them vulnerable to
attacks. Therefore, the problem addressed is:
How can a simple Python keylogger be built to understand its working mechanism, keystroke
capturing, periodic reporting, and security implications?
OBJECTIVE
The objectives are:
• To demonstrate how to build a simple Python keylogger.
• To explain keystroke capturing and logging.
• To show how logs can be saved or emailed.
• To implement reporting using timers.
• To highlight ethical and legal considerations when studying keyloggers.
1

METHODOLOGY
The methodology used is explained step-by-step as follows:
1. Prerequisites and Setup
Python installation, virtual environment setup, and installation of the keyboard module.
2. Importing Required Libraries
Modules such as keyboard, smtplib, threading.Timer, datetime, and email-handling
modules are imported.
3. Building the Keylogger Class
A Keylogger class is created to store logs, track time stamps, define the reporting interval,
and choose the reporting method (file or email).
4. Keystroke Capturing
A callback function records each key released. Special keys such as space, enter, or shift are
formatted into readable symbols.
5. Reporting Mechanism
Two methods of reporting are implemented:
• File Reporting: Saved as a text file.
• Email Reporting: Sent via SMTP after constructing an email message.
6. Scheduling Reports
A timer repeatedly calls the report() method at fixed time intervals to send or save logs.
7. Running the Keylogger
The final script initializes the keylogger and starts continuous keystroke monitoring.
2

RESULT
The final output is a fully functional Python keylogger capable of:
• Recording all keystrokes typed on the keyboard.
• Converting special keys into readable formats.
• Saving keystroke logs to a file or emailing them.
• Periodically reporting logs using timers.
The keylogger successfully demonstrates keystroke capturing, logging, and reporting mecha-
nisms.
CONCLUSION
We got a clear and educational walkthrough of how to build a basic Python keylogger. It in-
creases understanding of keylogging techniques, cybersecurity risks, and ethical considerations.
While the project is useful for learning, such tools must only be used legally and responsibly.
3
<img width="474" height="670" alt="image" src="https://github.com/user-attachments/assets/eb353d82-fa32-4fdf-96c0-e15e1d6d8b5a" />
