# Squad Cup Automation

> ## Product Requirement Document (PRD): Automated Squad Cup Automation
>
>
> **Introduction**
>
> The Student Success Team organizes an annual "Squad Cup" for first-year students, fostering teamwork and engagement through a competition where students form squads, participate in various activities, and earn points. The goal of this project is to reduce the time required to manage the Squad Cup by implementing an Airtable-based automated system. You can read more about the Squad Cup [here](https://docs.google.com/document/d/19h66geGSBo09XpeNDs-6JBr3iAG1ANElQeYQzNP2b0Y/edit)
>
>**Objectives**
>
>The primary objectives of the Automated Squad Cup Management System are:
>
>- Streamline the submission process for student activities.
>- Facilitate efficient approval or rejection of submissions with optional comments.
>- Provide real-time communication with students regarding submission status.
>- Generate a dynamic leaderboard showcasing squad performance.
>
>**Features**
>
>*1. Submission Form:*
>
>- Create an Airtable form for students to submit their completed activities.
>- Include fields for choosing an activity, who made the submission, what squad is the submitter a part of, and a link serving as "evidence."
>- Store submissions in the `submissions` table.
>
>*2. Approval Workflow:*
>
>- Implement a system for the Student Experience Team to mark submissions as "approved" or "not approved."
>- Allow optional comments for feedback.
>
>*3. Automated Emails:*
>
>- Send emails to students (and copy the Student Experience Team) regardingtheir submission status and any comments.
>
>*4. Leaderboard:*
>
>- Design a dynamic leaderboard within Airtable.
>- Ensure the leaderboard is accessible through a shareable link for transparency.
>
>**Implementation**
>
>*1. Tables:*
>
>- Create necessary tables for `students`, `submissions`, and `leaderboard` data.
>- Establish relationships between tables for data consistency.
>
>*2. Formulas:*
>
>- Implement basic formulas for calculating points earned per squad and updating the leaderboard.
>
>*3. Automations:*
>
>- Trigger email notifications based on submission status.
>
>*4. Interfaces:*
>
>- Use Airtable interfaces to display the leaderboard in an easily accessible format.
>
>**Testing**
>
>- Conduct thorough testing to ensure the system's functionality, including form submission, approval process, email notifications, and leaderboard updates.
>- To confirm your email automation works, you may want to update one of the student emails to your email, e.g., “youremail+studentdemo@emailprovider.com”
>
>**Tools and Resources**
>
>- Refer to [This spreadsheet](https://docs.google.com/spreadsheets/d/1nEYMBlQDPu8UIeR8t8W1X8FOXJJHkuvJ1M-miOWsOGE/copy) containing sample squads and activities for testing purposes.
>
>**Timeline**
>
>- This product should be made available to the Students' Experience Team on or before June 14, 2024.
>
>**Deliverables**
>
>- A video explaining how your base works, and showing the workflow from a student submitting an entry to the cup to a students' experience team member evaluating it, and the student receiving email feedback. The video is intended to help the student experience team understand how to use the base
>- A google docs writeup documenting the technical design of the base. This writeup should help another member of the team understand how the base is built, and how to make improvements.
>
>**Submission**
>
>- Complete this [form](https://airtable.com/appdi1dZ5NJo3ryDG/pagjz2N1hypDDzYve/form) to submit your project.
>