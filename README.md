# exam-access-control_python-code
A simple Python script that verifies user access to an exam portal using a 3-attempt PIN authentication system. Locks access after failed attempts.

This Python script simulates a PIN authentication system for an exam portal. The user is given three chances to input the correct PIN ( ). If the correct PIN is entered within these attempts, the system displays “Access Granted to Exam Portal” and exits. If the user enters the wrong PIN, it notifies them of the remaining attempts. After three failed attempts, the system displays “Exam Access Locked”, preventing further access.

The code uses a for loop to count down the attempts and simple if-else conditions to handle success and failure cases.
