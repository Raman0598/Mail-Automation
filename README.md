# Mail-Automation in UiPath
Scenario :- Fetch the top 10 Sender email address from mails inbox with condition where Subject in the mail Inbox is "Bill" and store the recipetent information in File and get the attachments in the created folder afterward send recipient information to recruiter with dedicated subject line to address the conern. 

Mail Automation with help of Robotic Process Automation in UiPath this automation process is build to capture the sender address and the subject of the mail it can be used when you get a lot of bills and you need to report the bills information with your seniors.

**Before starting the email integration follow the following steps:**
**Enabling Gmail for Email Activities**
To configure your gmail account for IMAP/POP3 protocols in Gmail and be able to use your Gmail account in creating automations, you must follow these steps:

Enable POP3/IMAP from Gmail.
Generate and use a Google app password (optional).
Enabling POP3/IMAP from Gmail
Go to https://mail.google.com and log in with the email you want to use in your automation.

Click Settings > Settings. The Settings page is opened.
In the Forwarding and POP/IMAP tab, select the Enable POP and Enable IMAP check boxes.
Generate and Use an App Password from Google
NOTE: This only works if you have 2-step verification enabled for your email account.
Go to https://security.google.com/settings/security/apppasswords.
From the Select app drop-down select Other (Custom Name). A text box (Custom Name) is displayed.
Fill in the text box with a custom app name, such as UiPath®, and click Generate. A 16-character password is generated that can be used in UiPath Studio instead of the original password.
NOTE: The password is only displayed once. This method makes your automation more secure, and keeps your Gmail account protected.
For more information on how to work with POP3 and IMAP email messages in Studio, see the Get POP3 Mail Message and Get IMAP Mail Messages activities.
