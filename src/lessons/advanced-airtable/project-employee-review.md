# Project: Six Months Employee Review

Here is the product requirement document (PRD) for this task.

> ## Six Months Employee Review Automation
>
> ### Background
>
>Every six months, team managers at Kibo carry out employee performance reviews. When it's time for an employee to be reviewed, the team manager sends a notification via email, which includes a self-evaluation document. However, this manual process is inefficient and time-consuming.
>
>The Six Months Employee Performance Review Automation project aims to develop a system that streamlines the process and eliminates the current manual process. The system will send notifications to employees and their managers every six months for a performance review.
>
>### Project Objectives
> 
> - Streamline the review process, reduce time and effort.
> - Develop a system that sends notifications for performance reviews every six months.
> 
>
>### Requirements
>
> - Employees and Managers tables - include necessary fields.
> - Automation to send email to employees and their manager every 6 months.
> - Employee self-evaluation document.
> 
>### Workflow
>
> When difference between employee's last review date and today is equal to 6 months:
> 
> - Send email notification to employee's work email address.
> - Send email notification to employee's manager's email address.
> - Update last review date to "today"(date when email notifications were sent out).
>
>### Email Template
>
> | from: | {{employee's manager email}} |
> | ----- | ----- |
> | to: | {{employee's email}} |
> | subject: | Performance Review |
> | body: | Dear {{employee's first name}},
> | | It's been 6 months since our last performance conversation, so I'd like to schedule some time to discuss your performance since then. |
> | | Ahead of the conversation, I would love to get your perspective on how things went. Could you please complete this {{self-performance review template}}, and send it to me.|
> | | We'll plan to have a feedback conversation the first week we return to the office in August.|
> | | Thank you!|
> | | {{employee's manager name}}
>
>**Deliverables**
>
>- Video demo of how your implementation works.
>- Airtable base of your implementation.
>
>**Submission:**
>
>- Complete this [form](https://airtable.com/appdi1dZ5NJo3ryDG/paggqRXhFJM4LFH1y/form) to submit your project.