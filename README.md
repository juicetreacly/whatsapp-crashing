# whatsapp-crashing
# Disclaimer
This is for educational purposes only.

# Overview
This project utilizes Selenium to automate sending messages on WhatsApp. It allows users to send multiple messages to a specified phone number, making it useful for testing or demonstrating automated messaging scenarios that lead to bugging.

# Features
Sends repeated messages to a specified WhatsApp number.
Supports custom country codes and phone numbers.
Configurable message sending frequency.
User-friendly command-line interface with color-coded outputs.
# Prerequisites
Python 3.x installed on your machine.
Chrome browser and compatible ChromeDriver installed.
Required Python packages (selenium, colorama, and webdriver-manager).
# Installation
Clone the repository:

# bash
Copy code
git clone <repository-url>
cd <repository-directory>
Install the required packages:

# bash
Copy code
pip install selenium colorama webdriver-manager
# Usage
Run the script:

# bash
Copy code
python <script-name>.py
Follow the prompts in the terminal:

Enter the country code (without the +).
Enter the victim's phone number.
Specify the number of messages to send (maximum of 15 messages every 30 minutes).
Confirm the number before proceeding.
The script will launch a Chrome browser window and navigate to WhatsApp Web. Make sure to scan the QR code with your WhatsApp mobile app to log in.

The automation will start sending messages after a brief delay.

# Important Notes
Ethical Considerations: Use this tool responsibly and only with consent. Sending repeated messages without consent may violate privacy policies and can be considered harassment.
Limitations: WhatsApp may restrict accounts that send a high volume of messages in a short time. Ensure you adhere to the guidelines provided by WhatsApp.
# Troubleshooting
If you encounter issues with the ChromeDriver, ensure that the Chrome browser version matches the version of the ChromeDriver.
Make sure your internet connection is stable while running the script.
# License
This project is licensed under the MIT License.
