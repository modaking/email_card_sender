## email_card_sender

This is a python script to send emails. It supports sending emails to multiple people. Also sends html cards in the email.

Requirements

-smtplib
-email
-os

This script first prompts user for their email address and password.
Note that if using gmail passwords you may need to enable allow unsecure apps from yor gmail account security settings(security risk) or enable 2-factor authentication(2-FA) then create app password for mail app under others where you will type python script. App password requires 2FA.  

Generate the 16 character password and copy it to use as email password. 

After this the script prompts for the number of recipients then prompts for the recipient addresses.

After this the user is prompted for the html file. Note the file should be in the same directory as the python file.

Error handling has been done for error situations.
