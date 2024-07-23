# RFID based Lock System using Arduino UNO
The RFID-based Lock System is a security application that leverages Radio Frequency Identification (RFID) technology for access control. The system utilizes an Arduino UNO microcontroller, an LCD display, LEDs, a buzzer, and an RFID reader to verify user credentials and grant or deny access.


## Project Demonstration

https://github.com/user-attachments/assets/460f1188-284e-4e29-ba54-98c06cbc199c

## Introduction:
Security is a critical aspect in various domains, including homes, offices, and restricted areas. Traditional locks and keys are prone to duplication and unauthorized access. The RFID-based Lock System addresses these issues by providing a more secure and convenient solution. RFID technology allows for contactless identification, making the system robust and user-friendly.

## Objective:
The main objective of this project is to design and implement a lock system that uses RFID technology to authenticate users and control access. The system will display the status on an LCD and provide visual and audio feedback using LEDs and a buzzer.

## Components Used:
1. Arduino UNO: The microcontroller that serves as the brain of the system.
2. RFID Reader and Tags: For reading unique RFID tag IDs.
3. Liquid Crystal Display (LCD): To display messages and status.
4. LEDs (Red and Green): Indicate valid and invalid access attempts.
5. Buzzer: Provides audio feedback for invalid access attempts.
6. Connecting Wires and Breadboard: For assembling the circuit.

## Working Principle:

When the system starts, it initializes the LCD and prompts the user to scan their RFID card.
The RFID reader reads the card's unique ID and sends it to the Arduino.
The Arduino compares the read ID with a predefined list of valid IDs.
If the ID matches, the system activates the green LED and displays a welcome message with the user's name on the LCD.
If the ID does not match, the system activates the red LED, sounds the buzzer, and displays an "Invalid Card" message on the LCD.

## Circuit Diagram
![RFID project Circuit](https://github.com/user-attachments/assets/e987c642-9a6e-47e2-833d-57d887d0f153)

## Applications:

* Home Security: Can be used to secure doors and prevent unauthorized entry.
* Office Access Control: Manage access to restricted areas in an office environment.
* Event Management: Control access to events, ensuring only authorized personnel can enter.

## Conclusion:
The RFID-based Lock System using Arduino UNO is an effective solution for enhancing security in various settings. It combines RFID technology with a microcontroller to provide a reliable and user-friendly access control system. This project demonstrates the potential of integrating RFID with Arduino for practical applications in security systems.

---

[Swaroop Kumar Yadav](https://www.linkedin.com/in/swaroop2sky)
