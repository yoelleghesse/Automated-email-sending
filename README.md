The Automated Email Sender is a Python script that sends emails at regular intervals using the yagmail library. It continuously sends emails to a specified recipient with a fixed subject and content.

Install the required dependencies:

``pip install yagmail``

Ensure you have set up environment variables for your email sender's credentials (PASSWORD).

Run the script:

``python automated_email_sender.py``

Features:

- Sends emails at regular intervals to a specified recipient.
- Uses the yagmail library for sending emails.
- Continuously sends emails until the script is stopped.

Config:

- Modify the sender, receiver, subject, and contents variables to customize the email's sender, recipient, subject, and content.
- Adjust the time interval in the time.sleep() function to change the frequency of email sending.
