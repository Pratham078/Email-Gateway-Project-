# College Event Organizer Project

## Project Overview
This project is designed to streamline the process of organizing college events within a university. It provides a structured platform for students to submit event details for approval and ensures effective communication of approved events to all students and professors. 

## Project Ideation

The goal is to create a user-friendly system where any student wishing to organize an event can easily do so by filling out a form. The following features are included in the event submission and approval process:

1. **Event Submission Form**:
   - A form is provided for students to submit essential event details, which includes:
     - **Event Date**: The date on which the event is planned to be held.
     - **Event Details**: A brief description of the event including the agenda, speakers, or any special activities.
     - **Area of Interest**: The category or type of event, such as cultural, technical, sports, etc.
     - **Event Poster**: A poster designed for the event, which needs to be uploaded by the organizer.

2. **Form Submission**:
   - Once the event details are filled out, the form is submitted by the student.
   
3. **Authorization by Authorities**:
   - The submitted form goes through an approval process where university authorities review the event details and either authorize or decline the request.
   
4. **Email Notification System**:
   - Upon authorization, an automated email is sent to the college email addresses of all students and professors.
   - The email contains:
     - Event details
     - Event date
     - The event poster
   
   This ensures that the entire college community is informed about the upcoming event.

5. **Technologies Used**:
   - Dynamo DB for storage
   - AWS Lambda
   - AWS Simple Email Service
   - AWS API Gateway

## Benefits
- **Simplified Event Organization**: Makes it easier for students to propose and organize events.
- **Efficient Approval Process**: Streamlines the approval process for authorities.
- **University-Wide Communication**: Ensures timely communication about authorized events to all students and faculty members.

## Future Enhancements
- Integrating event reminders and notifications.
- Adding an event calendar where students can see all upcoming events.
- Event feedback form for participants to review the event after completion.
   
