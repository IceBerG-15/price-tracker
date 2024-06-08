# Price Tracker
A simple Python script for tracking the price of a product on Amazon and sending email notifications when the price drops below a certain threshold.

## Features
Scrapes the Amazon product page for the current price.
Sends an email notification if the price drops below a specified threshold.
Uses environment variables for email authentication to ensure security.

## Prerequisites
Before running the script, ensure you have the following installed:

- Python 3.x
- Required Python packages: requests, beautifulsoup4, smtplib, dotenv

## Usage
1. Clone the repository:

```bash
git clone https://github.com/IceBerG-15/price-tracker.git
```
2. Install the required packages:

```bash
pip install -r requirements.txt
```
3. Create a .env file in the project directory with the following variables:

```plaintext
EMAIL=your_email@gmail.com
PASS=your_email_password
```
Replace your_email@gmail.com with your email address and your_email_password with your email password.

Modify the URL variable in the script to the Amazon product page URL you want to track.

## Run the script:

```bash
python main.py
```
## Notes
- Ensure that you have allowed less secure apps in your Gmail account settings to allow sending emails via SMTP.
- Customize the user_price variable in the script to set your desired price threshold.
