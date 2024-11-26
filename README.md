# Spam Telegram

A Python script for executing SMS spamming using Telegram's API. This script allows users to select a country, input a phone number, and initiate a spam attack using various randomized user-agent configurations.

---

## Features

- **Country Selection**: Displays a table of country codes to select the desired target location.
- **Customizable Spam**: Takes a user-provided phone number and spams it using requests to Telegram's API.
- **Randomized User Agents**: Supports various user-agent types (Android, iOS, browser-specific) for obfuscation.
- **Retry Mechanism**: Includes error handling for failed spam attempts.

---

## Installation

1. Clone the repository or download the script:

   ```bash
   git clone https://github.com/your-username/spam-telegram.git
   cd spam-telegram
   
2. Install the required dependencies:

pip install -r requirements.txt

3. Run the script:
   
python SpamTelegram.py


## Usage

1. Select a Country: Upon execution, a list of countries with codes is displayed. Enter the number corresponding to the desired country.
2. Input Target Phone Number: Provide the phone number (without the country code).
3. Start Spamming: The script constructs the full phone number and sends spam requests to the target.


## Requirements
1. Python 3.x
2. Dependencies:
3. rich for console output
4. requests for HTTP requests
4. user_agent for generating randomized user agents

## Author

1. GitHub: sir-sv7
2. Instagram: sir.sv7
3. Discord: u_nt
