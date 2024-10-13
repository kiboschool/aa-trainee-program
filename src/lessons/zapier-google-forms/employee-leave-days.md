# Employee Time-off Automation

>## Product Requirement Document (PRD): Automated Employee Time-Off Management
>
>**Introduction**
>
>Every year, employees are entitled to 22 working days paid time off (PTO). The objective of this project is to implement an automated system for managing employees time-off processing within the organization. This system aims to streamline the application and approval of time-off requests, ensuring efficient communication between employees and their managers.
>
>**Objectives**
>
>The key objectives of this project are:
>
>- Utilize Airtable as the database to store and manage time-off requests, approval status, and leave days balances.
>- Automate the time-off request process.
>- Notify managers via email when employees apply for time-off.
>- Facilitate manager approval or rejection of time-off requests within Airtable.
>- Notify employees of the approval status via email.
>- Deduct approved time-off days from the employee's total allocated leave days, with updates reflected in Airtable and added in the email sent to the employee.
>
>**Features**
>
>*1. Time-Off Application:*
>
>- Create a form for employees to submit time-off requests.
>- Include fields for the number of days requested and any relevant notes.
>
>*2. Manager Notification:*
>
>- Send a notification to the respective manager when an employee applies for time-off.
>
>*3. Approval Workflow:*
>
>- Allow managers to approve or reject time-off requests.
>- Include optional comments for feedback.
>
>*4. Employee Notification:*
>
>- Set up email notification automation to inform employees of the approval status of their time-off requests.
>
>*5. Leave Deduction:*
>
>- Deduct approved time-off days from the employee's total leave balance.
>
>**Implementation**
>
>*1. Tables:*
>
>- Create necessary tables for `employees`, `managers` and `time-off requests`. Include only necessary fields required for this implementation.
>
>- Establish relationships between tables for data consistency.
>
>- Setup fields for approval status, and employee leave balances. Leave days should automatically reset to 22 days at the start of a new year.
>
>*2. Airtable Automation:*
>
>- Trigger email notification for manager's approval based on time-off request submission.
>
>- Trigger email notification to employee when manager completes time-off request review with approval status.
>
>*4. Leave Deduction Logic:*
>
>- Calculate and deduct approved time-off days from the employee's total leave balance.
>
>**Employee Leave Application Workflow**
>
>1. Create a Google Form for employees to complete to request for leave days (ensure proper validation)
>2. On form submission, transfer the request to Airtable
>3. Ensure all communication automations work as needed 
>
>**Testing**
>
>- Conduct comprehensive testing to validate the functionality of the system, including time-off request submission, manager approval, email notifications, and leave deduction.
>
>**Timeline**
>
>- This product should be made available to the HR manager on or before June 21, 2024.
>
>**Deliverables**
>
>- Video explaining how your implementation works, and showing the workflow from an employee submitting a leave request to a manager receiving the application notifications, approving or rejecting the request, and the employee receiving the manager's response. The video is intended to help the HR Manager understand how to use the base.
>- A google docs writeup documenting the technical design of the base. This writeup should help another member of the team understand how the base is built, and how to make improvements.
>
>**Submission**
>
>- Complete this [form](https://airtable.com/appdi1dZ5NJo3ryDG/pagT7uYNZ2htBFc2A/form) to submit your project.
>
