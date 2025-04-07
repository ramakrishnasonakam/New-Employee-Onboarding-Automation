# New-Employee-Onboarding-Automation
This project automates and streamlines the employee onboarding process using Microsoft Power Platform. It integrates MS Forms, Excel Online, and Power Automate to collect employee information, manage onboarding tasks, and automate communication between HR and new hires.

**Tools & Technologies**
Microsoft Forms – Captures new hire preferences (e.g., desk setup, equipment, dietary needs)
Excel Online (Office 365) – Serves as the central checklist and data repository
Power Automate – Automates onboarding workflows and HR notifications

**Workflow Summary**

New Hire Form (MS Forms)
Collects personal information and preferences
Submits responses directly to an Excel Online workbook

Onboarding Checklist (Excel Online)
Maintains task completion status
Tracks each new hire’s onboarding journey

Automation (Power Automate)
Sends onboarding steps via email
Notifies HR upon task completion and updates checklist entries

**Screenshots**

Form Input Preview- 
<img width="927" alt="image" src="https://github.com/user-attachments/assets/5c679cab-bf0b-4af2-a41c-bc583860e534" />

Excel Tracker Structure-
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/1f86cfe1-5180-423b-b2f6-062407765983" />


Power Automate Flow Diagram-

1. Trigger action: Update excel after a new response is submitted through Forms
<img width="1208" alt="image" src="https://github.com/user-attachments/assets/a493c1ee-966c-4e93-a608-add149cd6b8b" />

2. Trigger action: Notify HR when status of a task is updated to 'Completed'
   <img width="1352" alt="image" src="https://github.com/user-attachments/assets/4337c94f-3a4b-4a44-b255-e38fab04b28f" />

 
