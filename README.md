# Payroll-sender
=====================================
Webmail.exe (Paysender)

DESCRIPTION:
Webmail.exe (Paysender) is an automated email-sending tool that allows you to send bulk emails using SMTP. It reads recipient details from a leads file and customizes messages using predefined templates.


SYSTEM REQUIREMENTS:

Windows OS

Python 3.11+ (if running the script manually)

Internet connection

Valid SMTP credentials


FILES INCLUDED:

# webmail.exe - Main executable for sending emails.

# smtp_config.ini - Stores SMTP server settings.

# leads.txt - Contains recipient details.

# subject.txt - List of email subjects.

# message.txt - Email message templates.

# readme.txt - Instructions for using the software.


HOW TO USE:

#.Place webmail.exe and required files in the same directory.

#.Edit smtp_config.ini with your SMTP credentials.

#.Add recipient details in leads.txt (Format: Manager Name, Email, Worker Name, Position).

#.Update subject.txt with subject lines.

#.Edit message.txt with message templates (Use placeholders: {{FirstName}}, {{FullName}}, {{Position}}).

#.Double-click webmail.exe to run the program.

#.Press Enter to connect to SMTP and start sending emails.

#>Review the status messages displayed on the screen.


FEATURES:

*Reads email recipients from leads.txt.

*Uses randomized subjects from subject.txt.

*Customizes messages with placeholders.

*Supports bulk email sending with a 2-second delay per email.

*Displays success and failure reports in color-coded format.

*Logs errors for invalid email addresses.


TROUBLESHOOTING:

*SMTP Login Fails: Check your credentials in smtp_config.ini.

*Emails Not Sending: Ensure leads.txt, subject.txt, and message.txt are properly formatted.

*App Closes Immediately: Run the script from the command prompt (cmd) to view error messages.

*Invalid Email Format: Review leads.txt and correct email addresses.


SUPPORT:

For issues or improvements, contact: hidat@thomhost.com

=====================================
END OF FILE
